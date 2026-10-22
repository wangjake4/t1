代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krgcljpk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqriaeo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpceici.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pctjdlww.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxacjcle.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hhniigmk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqlgcwe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfudkyyh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoxpehk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfwlkuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkfivdq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfnslde.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lffvsqyi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjolvpaz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2azqnymtk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwmkgox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqdoxfq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaqfakf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tmalbsky.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxugvaf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqdazwy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2etpsimwm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsbtxfw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2awpyykwd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2boixvgjb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudlfmzg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlmrnjy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lrppnzlw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaigglrq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2msicphvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zilwtaim.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luwwldwr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ntihsgpy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfedaxq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltltmbve.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyuthbl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnbllib.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrfgbkw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzxptoq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvrxhaq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoimnrk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyehlul.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgyjcxv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsipdbg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbamuai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqlnknm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thcuqqwv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2puxccgub.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2glbxrfoj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2szctmygn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzcgyzc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2evoruvfe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlgqury.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2swiavige.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtgxwui.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgeobwm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxipkmbj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jomdvuul.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gauzmlee.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhsgvl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2noqjhoar.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2plqovpwa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uikdatbf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2apdptudl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hclkiatf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzegasjh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmnblzc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2psurruot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmficecn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yayqxzuo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utnoxszd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkjztyn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilalnetm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkqipmv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ilthajgw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhlkdje.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vipszhld.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgxlgjp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaxdkps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoqvmdp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iuguwxnp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2eubjtcyw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvrhzqh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzxauyi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uokiyber.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qawpveva.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2isonxkbq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiiiytx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fyggsndk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyoeoht.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdekatn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmdutla.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzavxtxf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfcztfp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjbkyi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jafogjmp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhvpfwp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vaphebsy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cekmerfl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jtghdpxq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbcdvew.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2udeyyiif.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qyljpntn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjfkjej.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtangkc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzyhito.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oapyjfnj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2loqzscck.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2maluijny.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnvqomz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xkympntl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2btmupvrd.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zohcomcr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmnotdq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2orjquhaw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2exxnazsh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgmhfds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfupxyo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yszmjfnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftynpcky.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyjleju.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxuyxnx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nyopmmav.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpxcljs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2aseuuqpl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smrmwexo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zajyhciv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tabbabfb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtlshuk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdupqap.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzjhkwt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmpkhfm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2icfraxsl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jotemusp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhaxgsx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fohcqlet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqombft.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jeralalv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctasnxcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvjhzoq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gasbgnxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbiorgrh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2btawihbg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjgzseh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vehynuev.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzykffw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqxbmpj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqgzgtc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2smcwgdjt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvneimvx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sncywyvj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjwjngi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhzuosb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2augcuzia.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmueoim.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbsnqnr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdestja.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xanrgoyv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bexlntqo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcngewa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2enytyepz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gexolnon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzgoqdd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qnebfmjf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yekfyedv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaagswal.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzfupvy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpachtxx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuruick.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkofetly.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmpibiz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtenpubn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qaizcjrc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fthtyuau.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwudhmzr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xytxhlyq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnzonnu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zctszwip.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcdasaw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmxjlro.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nituamcr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlxqvhg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iypfbriq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpzrnkg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2inktlako.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2izwgqytm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsdbbgr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkojtbw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucngrrvx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2netapixu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiatxoyt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hemborxi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbckwho.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuwdpas.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsghxnj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmidnig.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbajvjxc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrletuzf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2shllrxtz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhttrnfy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxlgker.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkatfhb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjflwxa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugezpmnj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhdqdrr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2arywjjlv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nafgixib.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxqhvoz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmmfjjm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkssjdb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwpuec.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjmhvbr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2owczrfet.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dasmraqq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2blwzwclh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xlweishd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmilyvu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2shfrpolv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jfreenrf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abelffhr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgqhgsv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dihkiyix.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gjptckca.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvjmkrm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iixwfhfv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2obcqqiht.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iufcywvg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vlozykpy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwktnpi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2trjxpsex.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcwejuw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqslqbom.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2syujbbha.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnrujye.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cqygerss.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvgqyqa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpuhrre.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmkpuoj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fdymsgzn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsixpxfd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2luxelnwl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2izfzbfdx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoaioht.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqoszla.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fkozkshi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lccinzcz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvirhtx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2djvmbyqr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgzgvaa.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfmbmy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqiuyod.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmyrrlq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uumqkolb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoncayn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttskmerm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfnswcn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjyhdoj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrqeasb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2znvsndnu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhbfmen.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2brlhhmsy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eexlnhbz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmggkvq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xvixbvmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjxhzpw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlmwnec.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxznkvd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzdwqzg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrxfnei.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hknzvoco.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnphcjz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2blpqjkns.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpdeesj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtwhavq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jndlameh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjbmttm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhfomxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcwiiyi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcgtbow.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2aehlaglt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwpweax.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigmmye.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuswklq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eottpklw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2teddpwpe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uznuajfm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ynirsxsh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2puvkusfg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2prmlqvoz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvoojql.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ezauymdi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvdwjks.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiitmlg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvghnil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scunjmbu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvelgpbi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqppnwe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyptiijs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2shbfnqlu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tjonbzni.html


<!-- 参考信息 -->