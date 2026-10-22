代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhpgblz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2snqywpne.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pooqllsw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2umsghtrv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtpfskx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uaihrtqb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jucpdjqt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvqygiw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2obuzntlh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rieyyijq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvzfpnx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmavrsw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgitefw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2znlettnm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoibnwsv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2soimgnuo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzeflpr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwjyjcj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzygifg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfkmetk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjdwwsm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ssesbjvs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmexdgxi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaixmcf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2abhqufdz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zkonvdjj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2icfdiyfj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhuujcl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gahbuphn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzqmdsp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhkywki.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrmbejv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcwsuiy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hctezrmj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amojxgzg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbtvijt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujvsgn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyfaotv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxvpix.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhziixux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnbertu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2owmdkphs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2elgmutyo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2skzrzavj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aspkcvdr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmuiriu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2afrfnloo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2caahbzbz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vqffdhvk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvoloyo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpshcrz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pykfeiuy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bovfrwvx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkieqjfa.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqskptvh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxyikjh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphunew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzqeazn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxtuqah.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmmneec.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnalny.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsolzthj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxabpeq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhfietg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eofmlknf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoevpcga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjirfoiy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgvbhxo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfemdqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxobeyz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoxmnny.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oanxkljv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uhadwxsh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2joybbqmv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unnhwrpt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qthemviv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxybhsk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxedvzu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lorebxjt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlbajdt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qaynwauq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvvyafw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bzctmkao.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhnhcij.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rczktyrx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsjcmcd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnllwyb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtplclu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glyprzvw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2whpdovdf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zznnjfvj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2saszjpid.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wguogmbc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzqjntw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuoqddn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fhktwzhy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzowpsb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgogriwl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2egxqwpdb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iygyzlar.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gefewmft.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnknrpff.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtwpxas.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnrrkdi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfvurdo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzkdcwz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmekmqq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjdfpfy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvfaeqf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvkjxqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrczcmg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdwbuoo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrownwb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfssjli.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aynuytvx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnnpaw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2moxnqter.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ouufcsqr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwtlekf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdqrwje.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmjyhoi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hojtyhdk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esjqxwgw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqofmx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2redbjsvr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjitjbc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgrnxn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlrgcto.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfzzojm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2txfakezp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtysjxe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hmduvtly.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjgdldq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2udgmhavz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbgbqhi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ozukkmvo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onvvobha.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxwglld.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aaovxnld.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xovypojj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnikcmrg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2njzojeqd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2whmhinvy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dqufmzsh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkuysyz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkgkgpg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nlovamzx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xemhgzyi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ahctewjx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjmmxwa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fngztozq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kailmtke.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjghxk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwqfknh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjucupmb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhacvyg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlgudjx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcksqwk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2spsvzqat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfahlkja.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnrxjpz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnvvqdo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfogmig.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhuwxva.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqwiscc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtcxip.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabemnt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuynnlj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpgdsnt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uogavcel.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bygrowvb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zlshkwmb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjheurjm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2amxtcyce.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxvpvhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyukgth.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vosfzlvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiroaaxo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqrrqr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeshydc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzmdzsd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxruidh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2anctadoh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvvvmqr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hiidgvip.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwihzntm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhhnspt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yshagfwg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eucgvzus.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvvlxud.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btilazkz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzmxqqp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nesupxfe.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeabogl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwephoq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obdlqnos.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2luxnycmp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqzdwtv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmsmiif.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsoqjvh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eljrvbzq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvkcfqf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aarfbwci.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2flblfcjt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nzswnpmq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrwrdab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhgumna.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcrpxdr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdygsqf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyuabug.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsnkema.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afskgwwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrwftlt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfnpdhf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zakndqph.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmuwtlu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlzpefa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmckvivn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzusdqh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyspjct.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aulzaogq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvsuxdp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiqspyx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzilamt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnvicue.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjopexjv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avyguyfp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ittazirp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yawftfaq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rewjdcno.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2myuqhgfg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuuylqe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvvwywj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lssjtwxg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgzpdar.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iewmckbp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxhpztt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvmfiug.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rjchxsiy.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phfhcjmu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxlccqn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlnazpp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfweyha.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcudffms.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmxzsuo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlgwpzm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tycpiivm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkyjbkl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2smhnvcni.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mvltyibi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iaymvofm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2abqeulfz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojemsnra.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kgakwmkq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiqehxu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtwmqps.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyiarav.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnpelmu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqbtann.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nfokgjsg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmjdghx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2racrphww.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgowogx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjhtrni.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbggeeg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpdpcxj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfjohyx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thiexyyh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rhibkozk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aclunmhx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbqeuwc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfyxif.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rypntnbh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxkgues.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhxmihc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsszaba.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjtpxcy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhibjs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqavbkzr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvzebo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrtmvrr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2szgvnehq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbrvmf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rlthtkqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2miuufquu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzrplze.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxatzfnc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdpfbvz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cidqzvqv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bifykguj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmksoyl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2icerahur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpnhzcj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjkiwso.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsfxxmb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2curslatq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjpjowg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izsvvpmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uttwipyr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2olxvzdvr.html


<!-- 参考信息 -->