代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfrpvvt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzqzwgn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ensdmhya.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnqccaa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2legltlol.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimaqub.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzjjisa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2avtslkhc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kkafliqy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjqewrk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epdlpsfc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2esmngljq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byiklzvy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eykbemko.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqaqbvc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdlphfa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcdykwe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvtogux.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgdkow.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2szesfpua.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpwgfss.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dolueltv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxftcaq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtsrmol.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bpastnkq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmwxour.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mhljhwaa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hulawjgx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwuoaew.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnukjvc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2roegjiej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vanovwzx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqzafww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbkqzhn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2clxlrcgq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aobnxjca.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aujlwuud.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjwsqct.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqpmruk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnifmyg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxaxkoc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2whvtrvpr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxeioxu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wghrbtvq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wzufkwki.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bteplkqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfbpayo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2doueplgs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzmyczp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftvopr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tpirlodt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2epgblqgh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfonezms.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyasqsws.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqtlovr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmfbvmj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gijezyvk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyohteqh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgmouwe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iobrocml.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnturjq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztefcz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gplitrfd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyhoqdy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbwnmws.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyyirzj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuvnbtp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrlncxq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2abhrkgxp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qffoqtbr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuplggjz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsddaew.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2odknbmmd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoofjkj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmkkvlx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jahqgvca.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2enwwliky.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkajrhb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wocmpklm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuvpfqu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaextodo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qboaknjt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrfgvvd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyzvdvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmkwsgw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqwwatb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aurqirvo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igoptqzv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuuaghj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdwyqle.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2inyndbnp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wteyrlfg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ishofctm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhcwvbp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2govbhfdc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiusjsqh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekxtoz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxxmpjn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzahpjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xutempql.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgeabli.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyjcfdh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hokugeep.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jczwzbgk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eocupnez.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xsspormb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kgygaayx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmlzpnh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxgyepw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bifqxogg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jmosqgvt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2preqagtv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iysmerrq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiglaiy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wiscdulp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgtnalt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2balugton.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcqbkzx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmgrymt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2isppfrsb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xdupbudk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iagduyte.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2miuyrold.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fualuize.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwlqdpr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdbshsw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eviribpm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcguuwz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jzziyiih.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurkrlov.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxzoedm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotbbhfl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzmvczw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrkchga.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtaqpqf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcikaok.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2weevsdch.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzueblp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjkfgzy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvxhcyh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bguqakgu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxpmxdg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szdrdgsc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2seuappmf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdiryna.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wckuqoxx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkvqgar.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbesrpu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rbglxhib.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjhcnwu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxjairw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjtlidy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhgzwqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ownolmct.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vurkcjyw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrhnfwu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvmuusk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzrvukp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvmkizb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aabtvgfi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iddyqhfj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cztxsfyr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfflossx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjupqums.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgpcmok.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfdkgrg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqwnnwb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfsyosa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzencsp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2odezqyuy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmrsaai.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2okavzaii.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amafyodz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmqezak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jflvjmue.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2euritdrn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wrduohyu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vssnxfzy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqalpdi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zetrzdfj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oijbbzxj.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiysirf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjnflnn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmichkq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uekpxftc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2enmsmump.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzexyina.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgomwubs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oydwgeip.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jilaxvsx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2buoompfc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlsnclx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyamsrbu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfcysnr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgiyzxw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnsaxda.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shribkjt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjjsffa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uufsqpdm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sjamljkk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjzhiia.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zzejoxvo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrpzwjl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnkqobp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbkbplx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwezyck.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhmupbx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcfhebm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjckoywy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zguynqux.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyddhvoa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xyylembm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2prtemreq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jnozsveb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rckcsjnk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlshmbkc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eoayhzqx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkicpzv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhajvvu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpqwmok.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjsqvi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yikbgmns.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gefkkprc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmsqzhw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gajqwxis.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cerewhrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvsvjbw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rrncmoks.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrctbvq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2njqqkvng.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cefmdhch.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiafkdl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmqsvk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pslsyzib.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeqyjsp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotydgt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzshxdf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2picpmtss.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yepdprze.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eeabxbom.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yihbwpky.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnfbakj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tohxjgfv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deeiksff.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xvabbxyl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiulbyi.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2omfpoogw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hoewxcda.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpccbhl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoyadsi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2waqdclpx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcccxqr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pajjzsgk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyutonmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzjmbws.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axqmfelo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwhhoqe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uolrcviq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fefzawhl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpanfxj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kenfblwr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyammcvv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oaypxyyr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrpftck.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqnoobt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoghjjp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwwudex.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2igqyklqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2exldrucs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhporkj.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2shsvfapq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhzycdv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwvzdbv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtqhkc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nghoofxk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eygrdblf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlgwlih.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2easbikgo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2huaxymyl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pszuaije.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2npnlxrko.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjivvdvb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhruqen.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbbths.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qelsqpll.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cvipirku.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdomxgp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdtniik.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mlznkgaz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvoizbi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tawbdipf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2okjjvkyf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbcnnfw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcusjszt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fncvflbr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgepcnn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qswjoluc.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaytdqc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2arnlyero.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejalrybp.html


<!-- 参考信息 -->