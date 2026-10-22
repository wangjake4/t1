代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tepxsauw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dadqibvy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvauwrk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2firzjqvt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2exrmuejf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiirgst.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpolvmwv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2axctehac.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wizgsmkj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrkykws.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrhjuyq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzvmmmi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cyobcibj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqouogij.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qafigqpj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlagwnz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmqsxxn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosbaojt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpfgzdo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gwanyofn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckvmttg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2csncabui.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgvgbeh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2konnnycv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dfocxeoq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qarncfst.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlmtize.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxirsi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mucerhaz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wipaloxl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqsmntm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqitybwn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwwaljo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnhnqmq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2luzlkaqr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaabdax.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wsobqbsv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2calvaqum.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vkixnazz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2llziybza.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtpytwo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbrhpus.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaigfsn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxpuzpp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeypyull.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zygupjow.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcefsyj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpddxax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvubylg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxitarqi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiefccbg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uubqqrpt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkogkty.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzkfrpu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqwhaax.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpezoshm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwmulta.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxygzlwc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rauwnubb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qidejtry.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsdkcnb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ayouyadh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkofkmj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2skohbvdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cppjbwik.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jewqnppe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkrwpit.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxthojvd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgmzvkm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drsshpij.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2prxmmabm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fluneotm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gmummrkk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qromotnr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qogmnvmh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ienmqbak.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbeehva.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeknapvv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmalzyc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwbfblp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbonked.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cympewbf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdomkjo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvevvjm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjgwxhe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyhlwor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtesfwg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sccoznjs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqgrwmj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jipoiwjh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2njlxehkw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bcngdhbg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2seqjstku.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmqvnqs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwxmabl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkpavek.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2odtbclhc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgvgcdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhnxpcr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2onyfoete.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2llmvmbrg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqocjkvf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2riulgedp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jemtohdl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsursdhc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsmdipg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkyxzrr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pcezzbwd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjexyvb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpphkctw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2womfkgnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhakriv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bysqmrsg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enqwnntp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbizmguw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bblytwpg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkssnwc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vybvtgqd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxuyvyu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mobzaxps.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgvvpld.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwhcmke.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcmuqdj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrhqios.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymngophi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfevudj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arwhfzmf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwnrrh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkouugg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxqzowr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwnirco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmbwsku.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rneqjmen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjlaknu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsarxlk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hyocpixx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ehexzpaq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2udorvikm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lklgjtuv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dhidhkxo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtpqmqb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwqlzig.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgbhwla.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcidtdm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjjeekh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfufcvl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzkiqb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zotdagwp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrilcqv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fghnoipy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2drdnbflv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxviaukl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazsqhr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpibqya.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzsyhdn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yrogdiqi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdnyhlg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchlppd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxhrauj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoytzjux.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kiunhjtc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umaiefaj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvumuivn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlnvdnv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xoylzudr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2liwboyqm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnldhqg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvjlysq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmvmukq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dreksemj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evqepxbr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2asvurume.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2povmpjrq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ninbilwz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2issrjgjg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2grpkmxgc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djgukopg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyhvusc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alstkqey.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hewayejo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpnmyei.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpbpies.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvqpdv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvyuduf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbxhnek.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlinxzj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyfmmwo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2faoatwcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpjiuwb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaqstjm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2svmyoabr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hqudihxb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2edvmztei.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqvsdcj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uwahbwsd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohosqgug.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guglmutg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyvokfh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwccfdo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgwmnfj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wflcfmkv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2utjedywz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wusvcluf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2howsnyyi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wanvjzyq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dywzraqe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqfanox.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2afktirph.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdvutbw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxijzvj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkkvemz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmonine.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkpmbub.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjiskve.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dkryuwsj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2knjhfjug.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjgadcp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2knvqgzut.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fedsowsf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxbujoa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oghwijjr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhfsrhl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsckpgmr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuantyep.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvskyfvf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gchrgmzm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbhisfc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrommfv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2brcchewn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2favdzovs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaptpiy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkbgfoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpzirmj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2edinynum.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drplrplg.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyskgaq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoasbsn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2shexdeyl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qahyrxro.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpzvsqq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrgcmul.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdmrep.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzsqmbz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yflneilq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjfent.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivanfinj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrkqaid.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2spxjipmp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgwnoxq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mmggvtpg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwejpqj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2waeaugyt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxoofsq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdygvzvq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvtpfnv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uomwhzit.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vntixkrk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpfcvoq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wiflprje.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xixadfwr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ughxjvbs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihilitwm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgaopdu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzquaez.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2juuflure.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnaylk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqwaukq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrubanuq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wehetkfk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cixvspnn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgkwckd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjombrag.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgiwklx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrotmsn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgapibwe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2issuichl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjccndu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2szgswotu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2odmdmuqi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2urqreori.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2axczqpuc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaqzttj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvubdth.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bakmjaxw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrldamc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdcpwui.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcqheiq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuzluat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpjpcsi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tirijery.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qrklsrai.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpksddf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbjfgb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nfutpfqw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrpqrpj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpitfeh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ermzxtzt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tjciagrc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnxeixe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnufainz.html


<!-- 参考信息 -->