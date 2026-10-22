代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxhmizm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zrykruym.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizmyea.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jxstlyfw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ublptvdh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxwqsth.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrphio.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjdkiyl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sefxbnpb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrsigfk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmuohbd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzubwqbk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqmucx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmafgime.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phfndmlg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqkljhc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabkhxi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfryuik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzmctxh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrwjbpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzipxru.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2geuxgjuk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ocymaglt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sucoupyk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2deyyvgwp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjegwiqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhkpjih.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2scuvomrr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cypoakgt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2odiohnur.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdyxhcz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxudcne.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmuovuv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dodepfwv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vijygwsf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yxikibsk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrugnzri.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qnodgkyh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvabmrpp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsjjobc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfuyxu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqfchcj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2byauwojw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rahmzhpa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfafeff.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjogyvlb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsbsxbh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnocsmtx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzydbpqt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfydoci.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2flafsazo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqwezay.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yandvnjh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmtmkso.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2owxcccoc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbhifks.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfrqyxb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrweiggh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zowvjjnq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iknfbhfs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pztcrqje.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoayvxn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzdmizt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dygzqpdp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqttmtni.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qblzhzhq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjowcrl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnhkvvk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokaqlxe.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqruubx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eczrdpwk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucgjzq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eliezizb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2otatzfky.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dabipuwn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2glantvpb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcvrsjh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhagybu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmvxyaf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eermegfl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mggzqnba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrrygug.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hemlvdwa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2taamtyud.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmuwhgg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qztwsjxz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwlfolc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkdjumq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2suyxxkwn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirrmylf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgdldkx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krkcvlea.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ydezhxlc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbfrtcy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaanxbh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuwgjcj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgvbqbp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxftiepk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2krvixlhn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqamroz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmlpgj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgclgcqs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pozomblh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kdovicij.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbijasq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmpxlll.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwjlcxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyydeux.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvcidke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjipwyc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qhikyuye.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vffrxnrl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjobhjd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsmnetj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxrugah.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpnpkqb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfnljcd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aczgzlto.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnxdfwm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnuomht.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xemufmch.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cadacnwz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpwlyck.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsbqeoz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiftcyv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeleudk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwcsuhc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhkjesi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxetxlp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbwmvcc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uiukeivm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2obkpohjw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfrmxwm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxttjxf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujeuuxo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjpvcwu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qwodjtdx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azxabqcm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qraqufvb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfmwllq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mabesmrv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2leynjrcx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arrxcasy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbnsuel.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amwhlxbd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2siniqdpb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrxaroy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2btzrujix.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbzvqqg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpltctf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dddcgyqg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2izdhanea.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcghlazp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgirlas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfwiygf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqkephb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhzmksn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2foivecwq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvpdcwr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbobiif.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdpxgia.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvnohng.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuttnqc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdiilhp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrlknxg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkwmlbu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpcurza.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tpibazzw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvmekod.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xhificcr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsfdiop.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxgkwmw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2upwerxss.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxmkslz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbkhvur.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjkorhz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjafuar.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2psbrjyjr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egnboiuh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2efynujld.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cchcxmul.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2elgbtgnh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rneavmdp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlmvlsm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmhicwk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbnulic.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsoqlxt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlejwez.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwglbf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiowlxw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2msuprcge.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjjlkno.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2srmzxpxo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoleuvf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuxvdfx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2flxmusoq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2flxfnrlu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfnjxty.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jizpwpky.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiuofpp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrwigpn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtzmzu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tanbjbqx.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlvqrbb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtmbrl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2stfdlvjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzjdmsn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwndqkyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asowrgpb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sarlqxen.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjqtmsc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrmjfdu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbtmohy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnajxac.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrqxgfg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzvphwf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2laeiuntu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2orszvdtp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wkahltll.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pprebdnb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kntompem.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2leznwpih.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyxsaao.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuvagvg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ijohpyvc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnibnye.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsekkji.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwcvbao.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2simrkqxa.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfgrlvq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2atjkfkks.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2owguozty.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2aeagacwx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwffiucx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwfrvby.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fenkfuxm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dsygmiqq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmixexs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2upzpewgf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvqaned.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2simeorbq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rpanlxvr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2awzxvglx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmmzvtn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgliqjc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rokgspqc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qcljxjgo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkzetxc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhfudlw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2atzlgryb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxxwrxf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhppjfu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kalhvfuq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaoodyw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2adygzlrz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqvfrsm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkzjzhr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvwspoi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tylvowra.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qgodugqj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqpdxjt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cddyzxsa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhpsjpv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pexjytgb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxpxjlb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opgezjve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkfuusw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrbqtke.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cerzqbxp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yratfdrf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wclrhhri.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bjunzyiu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mwysuijv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjdmkyk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhovcan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kudwrexq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cowvsegv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpchdjb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pumpykbo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kloqhyjq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfbqlap.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2btleatrz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrguodpr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcztsofs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgillp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ekenlmkn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaygemd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwsnogg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwznfxk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiwqlst.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2afvuhqbx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfktyhk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkbwto.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mneodssc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2utbymppp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkqcmej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kppoddgn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhkzmur.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nybdrigq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uytvvhph.html


<!-- 参考信息 -->