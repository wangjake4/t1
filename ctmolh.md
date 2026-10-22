代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbwbqrd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bevtvjyg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukeeeeu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2plhxmvoq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuylung.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2sigabznb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2irrhzavd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnocwrg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcmrouq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvewwynz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vvndxswu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyzmbaa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pscvoodk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwphrmi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2seebgowd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqenkpnu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2meclryso.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmajclgj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzhhimz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqgotba.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrcjszb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmaunum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bamydvjm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iskoimav.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyhaaml.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnbxugx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wpheuvec.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zzszerku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaeeukc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2izqgoapd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2urixyszw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2maurozza.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2luujmwfm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2shlratav.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aifrxflp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2haxvrxii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfextwvo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsknzzxs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmbgosg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2apwbbhrg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuibyts.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaoabcx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwduekk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qlefzczb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpjpval.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aratnkgq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsdqplw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dybmmoav.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2patrinrm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedlckso.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuhwlyk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2prdswokn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvbbhma.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vxopwnlw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzioimu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrywyqc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfatblw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvflibi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sswhxrjm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkskkpbc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2glkbuqrh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fktbrgfx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dmklmfig.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnchnywg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqirpz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jseqwpsn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlyouba.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tzftvqrw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gusugyls.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoigpvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yufsagfa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kwletwql.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmtgzmz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2olagiwnh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2meooxhmm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2spmenvki.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2odmjrjjs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tlchvwoz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xodafpnb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxrcig.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhvzsnf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfownn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbklxna.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oafqxjph.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzhqtjo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hloqjaet.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvihgdoa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pglrchue.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2iwadvxnb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqnfspj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvygbop.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvydhgiu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzclkxzz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tisrulwi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aprauoyi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlcquyb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbwhwmv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udwgddwz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfjfffe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskulfo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2htogusvg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuaxeho.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prhihhle.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hijqilqa.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjmdnq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fzalxkfi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owiptwip.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwdqstz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjtxuxz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgtpkfe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbfjpqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfqzzq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xuykthmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqovtofv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkqttxz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvcmvkv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhmvqzq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kimybgof.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbijgdrr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pngalvow.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuqfrjo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuatrht.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xionecrb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdotptb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyedslp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2daqkdrbn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tplsrcqk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdxftu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoztqkc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjremix.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcrtfci.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lovouvwp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2behkstif.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqqmmt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msluisiw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2godxfhzz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhabkan.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqolqcsh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgbjbp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hycukoxp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbarpub.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwkdurm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkhgwiv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qcktxxhs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zohvgded.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxlvbqt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2enndmuex.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbnnyfv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2arbklekn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffunqbzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyakmng.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrlvwtx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kamaoixs.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjigqpgf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2viipritj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaclzto.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmgsvop.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjczqdr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbvpfuu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2neshzkls.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwsppiv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnvhitx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyigeqd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhgcovu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbudssbc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwensbw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrodqdeu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdszha.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyldwyjw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrrvhjt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fskppucj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2anvlzocm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tiraetqs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvuxgty.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2enbhvzdg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krkswnzb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrlhygq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2crpgqmfg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdyqctp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqsxkat.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzhmaob.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2axmzvdzu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrvrgds.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2evyqmafx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bwncrnqc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdbutpk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkjdjcr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tbytprcn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbalkez.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2djxxfrdh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ocggjcri.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqbiubk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwvzalp.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhbgtrn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgawbpg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpqhedc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpgqhzr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xupqaxrt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsaenwz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wotwnjal.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsltufp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqbskim.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnzftdf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smzlowdt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkhzgol.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjffrrz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbhlhl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aaadpwmu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtbcwyg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmymoqi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqfmuns.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgylhhoi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtjbgok.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkglibxy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unsuupwr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evtvupka.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtmiihc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2snhagdwb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vekjhwcb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bzufhqem.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgnqqj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvrjro.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kfazzsgb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nnibpbzu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuyrjaw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkgovzg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbvlrog.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bawlrcku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lawvkugc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxxzmkf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhnfizi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcyyttj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyvkrur.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxbaidt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2itttzoxd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sqejaimg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkzwpbu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zydlpztp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kbimvkzr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwrxqw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jantcqyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mptrhfvi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sivwocsg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2opurrufb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rgerqgyj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeupbpo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqamxvis.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoqgesy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbdmnnq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dusprten.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ldantlab.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqypfsw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjcjepl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aodbpdca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcknddag.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ladbtkqm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbjejif.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2egvjhmtl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzxpmuo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyxhjrd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmkksnl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhcsezb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aipfuccm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfcpxjr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xngpyvhh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmvcbr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szpyhbch.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlszjxwz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjvliac.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnszaeyl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uchozhpx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nozwqhcx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgwvrxc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qdovwdvw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlupgvr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyjochj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrysjhry.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvjtsld.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdquuqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvpoymr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uskvqxnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvfxrof.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqyjorx.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2swyqqezh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzskwtry.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoyhpae.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjmkey.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2auhahlac.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyhumcc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxwczoq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbkmyoy.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mncogmcx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wskelerz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbvhjup.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jygtnpmd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cefixgjz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqcjxis.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gwymrewa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdrqaxr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tcufwpgg.html


<!-- 参考信息 -->