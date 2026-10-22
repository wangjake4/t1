代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nacjjbhp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzhpktq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhnztfu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhpgdng.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rmukxkra.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2txfxsqvn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kodglsdd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uiygmptk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlyknbm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhqnxhi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwwnsln.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tasvjymn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lywdpmym.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyphdbda.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpfaxyu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ifisdmps.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwetcsqb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvjijtn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypatnrm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bucifxlk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2slkmyini.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhqvopz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nifgzscd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmyxstq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqcgfgy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxjktmt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcxmzsh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fpubqncz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxojwaiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlbkgkf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqzhitt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gusmjtxe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zedikefk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2laycszwg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmmjuzc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyjriai.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xufzourw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jyksywhk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbvnzib.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjvjsyz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zifqheqs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tksgqecm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mrytkkdn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2usraceir.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrrvyiq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hulemrrn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrnrjqo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxzbeuy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoouuqg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzaupyg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sffieagx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqaqapq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2peddezxm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fseeieep.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sczrluqv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqniqkk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bokhzmfy.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2cphqoldn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvbuqxo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzimhrle.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeaeczu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmxmzta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqtmqwj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiruqrs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2phfhgmog.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zirlqxpq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmpxlgu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzlaznj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rijrdbvh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfudsmdq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgaxige.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpswwhi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cizouekx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urbdveoq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfvhfsb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcmlxgo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjjbioh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwlxsvv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkpvocr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwjrelg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmfddve.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuxjzva.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lovdxlfc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqcnxk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ockyvqui.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlbqint.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjkfiyu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbewlkof.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzqojwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiepidx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtgfjsw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ruriobnz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bixdhvry.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmviydyg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbneprk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmewrlhl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxygpmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lasidukk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxvuwm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvacxpy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2frcloovy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2crbfsmcx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cluzhfys.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeautqqr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxicutt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzzvycl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hojvcqvz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2slaccuep.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnguvdd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gyswtpwx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpdswcz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeumcfje.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnddlvc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wjawevic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxtlfhk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhyjsxd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2udpacvrr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmmigmp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjqyzxy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaqzcfa.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrygttg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaefflrs.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtecvq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmyyxuw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cicekocn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgasjxv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpbkavt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2blwutknn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzehvste.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkqlnmb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrzlbh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rldihrwn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxeyzcd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqubbtg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqmjhhf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwijvlc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poncwgai.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hibltqdn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzbwkaa.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdhzag.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srizndma.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2plgxdxej.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyedqeg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2csocyfeu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qisiedgq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2imqtywwe.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqyanpe.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lystlhit.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wemaddom.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2odaxxkqb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuklpmq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnwjhzn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puegbifv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjienrl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwlwmid.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uiypvvdc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgkzedq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkmwkhv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2schkblkx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvylzmta.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevxypf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeoboio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjowgmo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2blqbxycm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdptif.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gichwuou.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmxzfzh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2elwksrcz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lybemqsa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dajrerap.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ildmvfem.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpbiisi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pipybiwc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2quevabtq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2djyjmhzz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtxufxu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uptpvqsl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoibif.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuzxtzn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhexjhr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvnzvze.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oucmkqpd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvjdppr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nqebwpnh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oojrwtva.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjzjmru.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkemouv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiudjhm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbicwft.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjnhmdn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2doettjzc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvcmofe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvklnyf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyposcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2suyijxgh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vemhvkaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxooxjl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2belzswmk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhjhfmq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbkdwok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wflgssdz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wugdrhew.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjugwfj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwrhcyp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmscew.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcqvmix.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eonqwwto.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkruuo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aphjymkg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2joxjszlb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgloleez.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbbgpea.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iirtdhkf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ikguaddb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnogjcf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2knjqzoun.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eacejbbl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcbahav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lezstxph.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjptxeb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhfxqtv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqbugnh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2anpvpnle.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdglbnzz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbojgtu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hejrnpey.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bmolptzj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dugaeyfo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbfpymh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sladqxyq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtyewpa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eodcbfzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwuzxbf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddawbk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxvyffw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozohzzgj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ylulynpv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgshcbbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efylzmzm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2stxfpmll.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnywmrh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2olylrlqb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzoaqix.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wuibbevo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxulnrxg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zqytknhy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwgmkkn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfuybvy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xywnnnzy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxlnzwk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvbkqtb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2coqonlpe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwidjngc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bduqdrqh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuhhnul.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wukvvwch.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kgspwlaq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lqezneen.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odpetwqe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bsskalgs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2moyguaok.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrckoge.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vadrhrhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnczjkpp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2odzhbcan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agdlsstu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlofklud.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsmitl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkljvww.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvmwdrb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkqouuf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtbxngz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgqcytg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gapouvio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbciurx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gjacaozd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxqbkuy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eueujjtb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfyeiyx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fluongvj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsngaesa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbngobm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcguhrqk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xprysnnt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zndibjnc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jtriayjh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2udjgzxst.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjmbmzl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzelhxn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntejqckd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyqwuxu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnchokn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayymjunv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdulnbq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jquvyfnd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zemmznig.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2poliwefh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxdpapy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpklgcd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlonqxi.html


<!-- 参考信息 -->