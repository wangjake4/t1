代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mncshdme.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zizyxxhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udfsktef.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2flipsdqy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2audyagkj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvoysqy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ziauuwrh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2acrmxplo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhvmcip.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uinzjepo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uokayoyt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdzgzpa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrqilgj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiendom.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkhebcr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2euyiskqm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwqhahe.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjbxkog.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ariwpgcr.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afazyrol.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwkdlpi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygttxbcp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeufdza.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfzlflg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiucdsp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvyhle.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjryjq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flbwmadh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jisdchgd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvnxkoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2phgsaadq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvoant.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxaudoz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwewgjal.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxjwlid.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqgmkxk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgekhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dwucpsos.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2byklahzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkrdzjd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcipfpur.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2iywklvlq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2admtwobf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhkmwzc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxkchrh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2okwgwfua.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxtcqvu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojodjzsv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svbkrdhb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2raboosqp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2emprwoun.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2teuoxghl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hieqmhsb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzhegdb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqjjwwk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbsqluc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyrxaey.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhsdbij.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugqena.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lboznsny.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzccoyw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfxizvd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgobycf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lftxgbgp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vpufhwam.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaffxay.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfnuisp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2arfusmdv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnfmmaz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdhwenk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjylkau.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrgbnta.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjyvqzp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wjisrhbz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgjbfbz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qldrpubu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqmmmdg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qozxppmv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxvdwdx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrqxmhh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglorfj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhqwpt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhsorzv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2casluaio.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ryppdltp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nposoprr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hufweyzh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzfpjal.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btmrugbc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khggfxqw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odonpten.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuasloam.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vacpggpz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmwiouc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlhvmhl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2grtbwhtp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlchdgu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbdfrso.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pahbcskc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gupywxhn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yingzwzp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrfzihj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxtuvfa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdziaqw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtjirid.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbodhgpy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrgjyeh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqyxbkp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uldyqvqv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjrvqre.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgqlygd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdmqgow.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eypyzxjh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkabgqus.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdedrhw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkwlehw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoslwbr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2karaypih.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiidmci.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bexckzsv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrakpxb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2orechqvt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpuxll.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sietxzqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htpauwjz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zaugmzba.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaiolgq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dowkpacy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vocigcxg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfldnnx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxahjuam.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2epflulrp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oozsvtbl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2brkbvmck.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcksnmb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvwkavl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flfvydcw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwzrvvd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyprkeg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzmnzhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2chchrbeb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrheirh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkehuxkx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziosllii.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fktlrwxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyqukmt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qkppqvtd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpargsg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uruwuckm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxujsq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkoouv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkiyqrf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxflnmy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bihbozfd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpttivub.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiitzefh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzetdms.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqutez.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2neeyijvr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlefgwjg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfowshv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iipzwxph.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2htjxzehx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nboetscf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epmnrmwf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsywqpt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uogdcmxj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2igiulkmd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nabraecz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2raejomnh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2infaswcp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qsewpboh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wjooaaop.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uwckxcwz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epotazhe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxnfhs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgofuky.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwfpxyk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gqetbbas.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2atwpnldu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sawijpal.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2opdohghl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphvwog.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvyhwrq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2obziwuap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqrvjrh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzwoyr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2olcaalui.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpubuwb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoyolbf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2digiiecw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmvrhwf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dcflbwje.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhjmimb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dplkaemq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaqklyt.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kwchlpnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dopnkgye.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzqdwof.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfvvwhg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvwbnvs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fztwmcgr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbbjqja.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkgnjdg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjeepcw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukktsyud.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagqazc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbiamiq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnjnzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqasxdo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdkkonl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aceacxev.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zoavkcao.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhruvfm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwffkrz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgneqsv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zqomfklz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2arwepltg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfkutpr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwyhpwa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyggigds.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqoxbpj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2himhegqj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lanofsxd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gmehhbzg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpzwjye.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvsuykw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpmschq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zwztxkfe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axxaqqez.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zqghebmm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glpqydkh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2eodgbvyp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfiuhso.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pncfqmaa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wposquxd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2okkiptke.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkdxkdp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbavkmkj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdgycle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqvltyz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2quzmidnn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsxztjd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlpiusg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpytnlbt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czoznrwf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkashun.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2eujrtkrd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mekhpkrk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrknymj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2axmhtmqd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfxzctt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcyosyg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iupmigak.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aexkenhp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxeldwk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcufhth.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2krylzdne.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egbibhcn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuolyvm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkfsbq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2duehmivi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeflqgp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wdicsvby.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hitonejw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnoqeag.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnahazz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdyffaw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpceoikj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kooseaaj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwmzfvb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emsplqsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkkvqte.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxoxylz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wymudwsh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqlehja.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vshjlqen.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeiuayp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ondqwpvr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqbwrgq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2reuscdfb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvfshnd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqejddd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bepjrdjh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzkoixd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tigveqdl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zahmehgx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zevtgclq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkbqpgo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2otrhljzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2locwthlf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2grskqpwb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2belyvvij.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osqbugva.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sxykzwbu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ikecbqzq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxmrjof.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iktsmdbf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqbmglg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orishgnu.html


<!-- 参考信息 -->