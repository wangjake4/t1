代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gklkwpah.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pojsrctm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luegxjsu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2erhvcljm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zurqoybr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vuikaprj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpenonn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yazyfskx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvsjhra.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxytczfl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2suxrnyzm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnzjono.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ewppyhjt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2irvcertp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2iccmxroa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2knajukeu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgbanqf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2yczhphwn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzblrvsm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ldribzko.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwhcleq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzcysja.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smvlezth.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vslxjrbm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjddgsmw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlcicbx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfilfwpi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hskphhgh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnjvgz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2imnhizgf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvryvnu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcfkvuo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmslbx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpslzxhd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fumhfamm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wulgildt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2akrknfzt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uovifpsr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoebwks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoyuckc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzdbjnx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oijewjei.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hybdpoie.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wakkirdy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwigdqkn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkklaaof.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcutnyc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlbczln.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fevvubip.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbrnlfo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzblxiov.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kppvnhaq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvqpsqd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysedxgoi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2veztcqiq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abelzfwn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rejaqpdc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onsewfmb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzewkwg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpyrjfj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbmauaq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uemhhkit.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsfnzsc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2llezedqd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqsmfmu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkpbsqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvusrym.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrzmnoi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxznzldt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2goujqxzw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqwfbxa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdcvonn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjuxeby.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgtlqrl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwtrvgi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2loigdeco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlugrplb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2atljapkx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjheasi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2npfewjaq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtwuvqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wybxxvut.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhpuwj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnxgnsu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2twepdswp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxddbsyy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbrtlqp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfnmrd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdimwhvy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2monikqqe.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqzvpfi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjfuwsv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cymntxfk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoijiopu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnswjivi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bdixdwaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaxppts.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2idcixnkx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeehhvmg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyipnth.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrrywxn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvvvkaq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zotcdqxy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdblxwu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xiszwewd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfelzeq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2voqodxtd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmwyufk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrwtpby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2duikjykw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoajhsn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpgzwhr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orfwshbe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvexzgu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2frzvidus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbnedjw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bglweejf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yepzcivn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaamftfe.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mptbzfpd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2khnjvwuy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjidvsip.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mntyvmbb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwdledc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbwsbdd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzaahzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwnaqce.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2covallcf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcfkhuc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2irwjaabe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfviiyiy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgnhpjq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2towuqodl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsfeiut.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2exfxnevw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlrtqgs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkefouml.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2easzquti.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flvjkkpy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgzcmqi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2seihxnyj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2msrtgauj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pefqsvxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkpucuy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aihydnyc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nitoporu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aepezobg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2inyrtokm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nlokrwlp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2umfrsuef.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2boomlgdc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2epguolid.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lplbphny.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzciefjs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsgwauf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvphegeq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzbwdkv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqicebwf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2unxxoguh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumjzjwo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afumtwso.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgpxcma.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fogefues.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaouubj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2naydtxcj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gyegqbga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2stgpjmdp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rljudabi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrvywme.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxnkosn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnatdbhx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2flfsxpgd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgsvlzh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iweciauh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzworzbi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqtiafm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ileyysgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpnfuee.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkjvun.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuqjlte.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yarlyvoz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqkhlkk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qawwkueo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2flwwqbnx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoduucz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pismtmwg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2inqrddwt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alnuruii.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vanchfro.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzrfxri.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqylmlv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcetmtj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lcccroau.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsjtepv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhdcbkc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2roxkqihu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpllfmk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2joitebxk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuavrnly.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tweuqimp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fewxampk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2amqrrnip.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjuaosx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khhxvbgj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2joavcsnl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ievgiqph.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtjmwka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djfcixrb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxpvpfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apfjjxoh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajotmhvl.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsuyroc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdmiyem.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qskguwrp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vczbrnsu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqskygg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvwbosg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sznvloul.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkiylnw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnhzopa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crncqxme.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqiguko.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdbvkdj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzsncsf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uteqctkr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdaxvmr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhujper.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jozgakbi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyyenlm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2szyshpkm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnugazq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuxzxmw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjftvii.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyydivt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytlsehh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsoulro.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjagvf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyzsckr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pooalugx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcdkqmn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyqlgpf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lntrmckf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyywodu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eehvfcog.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfugvvs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyyxzjr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyrtwqw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjggfbhx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrrtbj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tfknndpo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cndtgkkv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2subujoaw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2acifuene.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfiftym.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtjzwhg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lliwjfun.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsidjrp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbzlgnw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2phzfiqzt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkslfs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyrabjr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmndstm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2egfshrje.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2aluozltg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzetcovf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmybvgau.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsvvaji.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsvzzwb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cujbrpkf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhzxelp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcphqsj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgildxbf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiptmbf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfnfpjn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2trikalxv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nahjasnf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syxutbaj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2storwqex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2annxpxwk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyzqqyt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eubzzksm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzaeyix.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzljgjg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ychuivwk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkzoyox.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tavcoktu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrqjqee.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otzenmdx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhakoqzl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhbueki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hjujkpot.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmkzyak.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ebesbqzv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxjhrnf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjgbnfa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cczqnaeo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxqpvuj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2msshkwrd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyehcfe.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vecphdrg.html


<!-- 参考信息 -->