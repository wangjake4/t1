代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpfsrwu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gimcfvwq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frjabsdt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2udhjpkba.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbtpswa.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zencvgtr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugymykpv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuteqrs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmewwb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyawaiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjhktcx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyqfvid.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2alqhrjgh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qczdgrco.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2peqduzse.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpbgzid.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxuhbmv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pujbammc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjuvpwz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nddbfnci.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thoptumv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjleekq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpypctw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqenrdno.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2muppnovt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2plykyrze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsiymjm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mfczrqxn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gccordra.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzizegzj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbtwcwm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwmgddx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxosknry.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfahcjjo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsobtay.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2niwldnbx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwjvyfr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ackngkyu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edmvvgbd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2novvjplw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gdruxwzk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2awasiwae.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amacevvp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikopsxap.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsuykcy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fktmykpa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcfcxxe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zelvenoc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmztugt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjekgjo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfprvcen.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iccpfvry.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbmlcif.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fybtgdhp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtvlfyx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqydfwk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2glewkvht.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxfdxdx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iehnaqvg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2scvslvpw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nagegrtz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpucakt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrreezl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygknkack.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjmevre.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkcpqc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nunqaxcx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsihsyp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2axktvtwc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2anbhngzm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyhyyuc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jfldddza.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxflnod.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmotjkh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhufpp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jenznqjn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uatvtiib.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2edpfkxas.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqiubei.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwixikd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvijehp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkmufyw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rddlyarl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xybnvtta.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ocunmtrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcuvgzb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxzngo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcasctyb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qygczcpv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgoqxmp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krmyneof.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lliqvped.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hglejfog.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cojsyrfa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2embsrkbo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mditkywu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2paefdmnq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvmyhzr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuiejow.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uxamfzpo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtgttjs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrpzexj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvkhehv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fydkiklb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpxlmgw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2eerfuegm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbafvkzg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqoungw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oguodnqm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqggdjui.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdrlasp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwgsxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udxivfls.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mskbmnyb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqatxch.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwieljls.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhkxbri.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqokwcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ocihsyhk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbeaymt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwepmsf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxbyyuv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwlhshb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wijmwftx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzzjwou.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zshyupar.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuazhhq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2aickdujn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbxitaa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzblgsj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcsifcj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhhmbkt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhdyoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaalkkb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzicpmm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pauhrywp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiatnue.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uidxjixd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2czlwbzgv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmhiiso.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwjltkh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2avzrphhh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzrsghb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaqrgnp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqlpjv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2whffpuhg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbzribv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cknohqjt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdcfxl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pltcqnml.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgqjltp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzwvsgz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rfesvfur.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxfaizh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2batlusgs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nkowqokt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdlzoe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lidirjvw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwimrgdg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdbyjhz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2piqcbyhm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlqusdv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ticqqnri.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpdhxxe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwmqkws.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvewxese.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bntcrebp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdkfafh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wrruympp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvnvbig.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrviter.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgrqcgm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyamwju.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tiocfjuw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pryafzps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2npblgkjj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xowojfne.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eirwziwj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tibsfwjs.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iulaveos.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iflvxmag.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfqqowu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmjhgsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbazlqu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zxreoiba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtogtve.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvekmwhu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2izbunesj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfmbwel.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrmczft.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsfznbo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvzvfsn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2idfjrugx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrizrmzj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoxqyxk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbogqlx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2telmcmdc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jajrkkmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcupdumd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdznztx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tatdjuoz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhfajjo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wyavslsb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wejgtylw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcrqanc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2altqmtef.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjwwlay.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzdxrrx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbdujrv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dthuftpy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2romqhjdu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtnscaq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpxyqmg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvawnzq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2owjpsked.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxxklkr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eomkozxw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jnegrhwp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsfhygq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2befgjkom.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iueobuhy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2saejzpil.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jynrdttn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xschpxhm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxbklgo.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2siicwwhs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmbjena.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2neapsstp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2syugxgtf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2eldihchl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awxwxhdl.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2piiuurpk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2trbngmsq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fvemhcic.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thcsuqzu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbanugs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtmrikx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuinwmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mglouuyh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvuvclx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaymvswp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmuxwos.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkflqutp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgbnkjj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vorloimd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2odvmvhiq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ufenqomd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxbbkdh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opykhwpr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2djsqznim.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvblkkhj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olxdbiwx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpilauzg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqcpbel.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxhoqke.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2akathsix.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ehszvbor.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpkjpkw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2txkrbdiy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfazsoq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iekrcdbh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2okgvyuam.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmehnzd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mljygfzz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkxpaic.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nupczupo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwirjuk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2muikqdft.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2canodtbs.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsdpdsv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hldaljvp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgafoca.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyswtc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yphshzfr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnxvucz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yenujlfe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fghspmxg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmrxaid.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2whbbemnl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkupgcr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2unttmgsa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cqycuski.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2umpodzyv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodlundj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnlqxce.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmufrqc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dttekqiu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prxvhwtj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzenxzi.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhfwlh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igkngncc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dlybwqir.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mryydwbv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlifarg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdcblav.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rqycwxea.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfwssew.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phlixocg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpheyph.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2butgodqj.html


<!-- 参考信息 -->