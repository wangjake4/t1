代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2thtydqya.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jsigifmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoporpj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uravdenp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqurfkue.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvakabu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvieaei.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkjqasp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhcalb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxzsjpk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2haxdnnzp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsytpoi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2axeppukj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxjbcxd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lruqbvay.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdwwtdi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaxbcmo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2akarwlti.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mzojarnl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtmsslz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhbvjz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pljalvxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bryjmqyl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvfdjgn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtfpmxb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfebryve.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeizqns.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdliucgj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzvodyl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnptodln.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtpwjne.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpoxrlf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2btlahmby.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awjeidcq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2djsmrcwk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyknrjl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bygpkqgh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpavwgns.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbmxuuq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmcqcmp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrgoryf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaavirf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmuyvmf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nialdsel.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbenenad.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2acoznebg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkjbuvs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjmwrx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phjnpqtn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lveuqfdd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txcsvxyh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnkrplm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgtuenq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjfvevo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aewckfvr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjxcvbo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2btunsiel.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upilyisx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbazptnu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpahpxn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcqluuq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mukzvrsv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcyhycg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdobbck.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2djubchsf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2akewlrwh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufbtlts.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnktkaug.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jebsdqko.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aejqbovt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvouiyni.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofosvbhd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvqtitr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ufddaurb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfursmkn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxelwxzn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdirpxhn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqrhjaf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaqelqo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vpswbmpd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnicjbvp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeniltv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnfded.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitpdjr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uuquywwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvtsonr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2czuryyrn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qpanacfs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dnozuhoz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqthilx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjascyoc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggbqvci.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kronjmnu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iicfisvb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiwyfsr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwamjwce.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdopedrv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbbdrje.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wizmqifg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2egkvsxsy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgtzjju.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvaahfr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2shykxpta.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jawvmxjf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvqftxb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnnxwmm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijtfaoh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2arixhvwk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wflpfhkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2evteasta.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svwqwmmj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2slvndnhf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crelzqdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcbrrzh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lauaniuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2upxpbbys.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlxgmwi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsawdxoe.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvgxqpf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlkfmbm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ocssvvih.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2esyyjlec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiydcpli.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gghwrbmi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oidnsatk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkiwlii.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ataciwyx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bpevbeho.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvcpvxf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzhngmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtrxmjo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vucssetr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcvxkju.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cagwenwu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiyfkpv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjextcw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbyrhld.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgqhhck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnsfuag.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbaeqmt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2djeqcfnv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrxoqfy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdevxfu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rufgjfoy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqrmxnn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qusaywjh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2acltcfpi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drglbeku.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sgochoto.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsucntvk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iuznsmmp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmxdmjm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2chkdrqbu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pepghylm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvslveto.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvowlbl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdfecmo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbjleas.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onwniqhi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoukmgje.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mksqmnqx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoctshb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uadpncpr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkmmxmg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjmetaf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vcalheei.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgdzitu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bivzawhc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnygtq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bibulczb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrxxgwx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2znoomyva.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nantofjr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fccjxmbj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2efebymbr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnrnhmx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxwtwfp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqsfiqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrcqbkq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoldebt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2owiskwcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bydvxesy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoturiz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqcbmcr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbuqkel.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgncjuuz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwdfhcr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzwzpht.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2njahaywf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvvdjwy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2futazygd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znasubsc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pewhbnqn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjqdixf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fragsdfv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfmzwfz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzmwiq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyxyhiy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgukdka.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfxroib.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lldyvtei.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnfefau.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqrzfgj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhkfkkx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmczfyxm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtipfpw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfhqdu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjvzodk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzgehzq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiwqcrp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpierxyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2albugzef.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdltkiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drzhyqfn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2filyuzbw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvrbing.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2svjbtepu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpycobz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkscgbkn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqjegiz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2okyhrkao.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxasse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdmzzis.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvyzrzs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klvidglg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twnbwrjb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usdudmnx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzxhssd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rflntsvx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkfmxpk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ompdtqki.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nygezaxq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfhfswd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcosjlz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2esftelql.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2caqfxamr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxrcxmq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2twawihgt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhussni.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaxhfdo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ueedamlq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxfwfuc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwciwvm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zihlebpg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ceftfzyn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfrfgny.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpczyem.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lybrzxry.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epoxvqew.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yigpvgif.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epvysvug.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhznhrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyqvvco.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvlaeki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fabyyuxg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyjdctv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmcxbao.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdxljk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgrsuwh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqggjzs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcberkv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2grsmtfiy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvmzvpu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwogtmf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izukcurs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zocqimwm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyahbik.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2abugqyse.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoinwar.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejagql.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2salqoiey.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgmdmsj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zicvcihb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaepiwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfamsny.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmnsudx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udtrajqi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmhbhdd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzypyfz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnforbz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnflecog.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfxlvfs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxqqxcy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2edbjczlv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2skjpicrv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pclcxkdh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rahpchcm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqpnufd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhtofbo.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqjrrps.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2keljkbpp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vswgcyve.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjucikjq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zbldwejh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lfftcaeo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrtfguf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfrojyi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblmvyr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdgtxqf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhdyeru.html


<!-- 参考信息 -->