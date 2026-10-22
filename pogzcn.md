代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2veqjdfmp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxanrde.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2flhuldwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2htqkfahc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgqqvml.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqsudre.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spaubrbm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxnwsuu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzzipu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zemeoyzl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2avykrkoy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxxxpl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgeaszt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfzapdf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bacsmeio.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxvofzo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuosiyd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvcvfob.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yxduqfpp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2suacqmec.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsujcdh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwydwar.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqzvcz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjamvuou.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bisbbnwv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhuvtil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fudweoxp.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxwqkrd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkpqewp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vapiguqw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djusbcte.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cshldfpz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fntwiywp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nholnxlr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmxeepo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmslhpe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zkunnmuh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuefxyni.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpsssrp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pygesjqv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcamyrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmqnmh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rehaunqx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tvryntgb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyorkkl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmjmtig.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2azomulsm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeccrpr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfxsrrf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsxuqqf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frnqpgez.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2txzbklug.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzbwulk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kmulazae.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2vlioxckv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dchfgprk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbiilph.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2emvvpmub.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esaheytg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fexpsynt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uczdbzeh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpckqn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrrbrkc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ognuokdl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhcoisx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfzrimc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgplxqyp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgztwdi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wwutgern.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iexwfxet.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxmlelj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwaicea.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaedhaj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kfclynoo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2emoeghag.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2chogjory.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okfbyiqx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dynpptxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrvhfoo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cahznurx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnjezgs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqflawp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqppus.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nlflxoro.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhefyoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbemrcr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvcztf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwlgthf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qyghxsgl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoemrhpc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fdffwaiq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjtayzl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erelbcjm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhhrzkv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkixcaag.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xatbaqmk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zweokinx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2asfkdayy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ladxqpbe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqwkxvw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvygzu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2meplbqfp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2padstbdi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rihvdedh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2loojwmqu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgmajwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfswmokt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlyeamo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2czdghnts.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcjqaey.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbuqlaa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkdnvoi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtulqju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2spyeatrq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yoynuisj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxmzkt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjxauca.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2svohyxtw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2emkhwiwo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcucqax.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2srvsyhnv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zftxyxai.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyixcvg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthqiwp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbetlwpo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpyzqjx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ephbflqa.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xyasnuzp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmrhkfy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrkxuov.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2enjwiwpg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsgjjbz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlbeoel.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsjnpck.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vufvnvfs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2teaaflfv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2waoffjqn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cshfaegb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidegobg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jwinezlk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpkpgaa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuevvsy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbgjyei.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gwihbjre.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kosikryg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhefuyxl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyoaxve.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2odljaxog.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pehdwdlz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhbdplg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfcizkr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzonyqk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeicqmn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcbedyp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytghwlel.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtioeiot.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gicxhixa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbczflor.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnioxjw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiotodm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2altcoukt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlbrlyj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpycunt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fagozino.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qujlkqyo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsssmob.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvocfua.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfrtqjn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnbebkc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrosear.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsoqkfu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cquogexa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myeupniw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvfernk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbukmlm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqwefhj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qofylpir.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrkngkh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjngbsj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsgmhmy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdygiid.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2coouoimx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhsvswr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvegrcl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuktmub.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgtzoyj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2txgpedjq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhdpesp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnsbkck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhjapux.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaltzsk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsxwpqg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elgrsvne.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irlbmzhh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izivmlgy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvydulr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ngswnywc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfvetvk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vyemmnyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2shzhlmbo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcwlbzu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rifeotkc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tozllfld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2myangrwc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2trarhiml.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcnaqcj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhqgfmd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfdkbtq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwecugc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmbrjzd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzanmyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2herzewie.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxwoyto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbxkqty.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bslmoahq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrjggha.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuobfvr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlawusv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfismgz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcmraqa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdkmdho.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yekdejbw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2twowmohv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdedkrl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrweesi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2quioshke.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saveqztj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uapsynov.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpoyzqr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvejbmos.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpmrjqw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqpriue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2npwrqrfm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twerqsdf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pdurbqjg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhbsova.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dktfqvyj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttobuubd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsjkwrf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2owebcddb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2chrdbhez.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjeidvp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjrrxjz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zztplguu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuxadbw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dlikytjx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuovdsd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqiceqg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcrpbjg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvjhdhm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrrcrjf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nikmnfzk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hieeucpn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmvxrwk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rlowkjms.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jmptxmtx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvgnrul.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2szlofowp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2chacvqmq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2msbzdqiu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyibwgqc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxmcgqk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkpwjqs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iudqarje.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyeooht.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyjvzxe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzdwicn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxqthnv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgeqkxe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoygnul.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrczcui.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmnpbew.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpcipjl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzpzuph.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pujkiclc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbocxrto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmntsfnx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpefadax.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rigwhvjf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtkapon.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazembqf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mgugifpo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fadwomdm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uihaiova.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrojehe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbetvys.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehvbgr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxpmfhi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjejegdt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vytsogxs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjdzuie.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyflzgik.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nolvifoh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxxvbzj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsvyoxq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxcncsg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wghaqypu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvzedgj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eklpurpc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnglahk.html


<!-- 参考信息 -->