代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkijvjpc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhxwmyc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pofiqmui.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdueubv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpngxwh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zpevxvik.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjqiofd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xllczcxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwmhphq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwjwoog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbejbmby.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2niwxoodt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hltoaaoe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxmzpyc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vucfcoso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gufwqfpr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yphospax.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkhagmf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnjmdnw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eobkcvtc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjodflql.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjxzlh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdqpqwa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadyutnm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhgelig.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zztapzga.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwacgu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqbqarl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rohcaxkc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnzrioe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoohooh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzotupo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2smdgmnsz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcvrgat.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixhcthg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqnxnhh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgerffe.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tocmpbkr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsihqvo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrjefmf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mszutsli.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnuiydy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kutioley.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cmecwpjq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiuykiv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xpejowhf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2chojpqpz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvkxqni.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcroizuj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfknzrv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnerxpqq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2chihtmqg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xejyfrpc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqlopee.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qucbrhpg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vehsguxm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csdxgvep.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uciubxpi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2crfypcfq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pchmmpjt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kusyqjge.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cngofiiq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeglbvi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2koqfwonk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2knccbtfb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfsgsdg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2szhemskc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjulcwf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqsxjwt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjeeqjl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvvbvmn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2shjvlehy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jmykgyml.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eznmloaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvoedsi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2psjavzud.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlokfgfi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xahhlwmr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvrvgse.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bduilngk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srvqfxyf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2krlxqmto.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yknfvfbk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvldzxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2szjqswld.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2njucbvov.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2glksrnfc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqvcbeq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yterujfy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aompvrlc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2grzxivoj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bvddewly.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvxowj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaalyqr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vykljguy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzwntxv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mwotlvif.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvimtnfx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmnnvud.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhjygha.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qifxjrqp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjebmfd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnzscgj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtuzpvw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhjnqzx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyinuphb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozglnxn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmyjvr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdilwdu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2snnmsslp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltagrdil.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbsxykg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlcbhzm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvokuodx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2keryvaob.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygocvoka.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tycemcsl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyozdnsu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmzokdc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfmebwl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwxysst.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaujiedf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qrperezq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuqcaqp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rsikltzi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zshvhqik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2stcxtgtt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdteby.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrmrdxe.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rascvjqy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iczddrxt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lxukbtzn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mttsjbnk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaiqvws.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoqvmrf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2umayqokq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aiclsyyy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwwmalg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2koekueay.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yezdgoud.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nooxvkty.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2akhpcsmf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzddesn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2romwbwky.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsvmkva.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2meilagjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jihmselq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jybxevwf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjckkxyu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoeucdn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lektbnlc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwdcnto.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhfdzh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntosodnk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xxusxnfz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuhsdhx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2isyoytkr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2izaohyfr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiahjgx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmedszz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfhvznm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qocrnfdc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmmmpab.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdiyibm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zsungjyx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2njaqejhh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2miouaemr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aroprykv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wahcwbvy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfykdhr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxintbm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uiixkphv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrizstw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yafasslg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcbuxgl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfkyfwh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffszsolk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrqbhnv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2alabrftz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2guoivrzz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdrvmor.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dulihlqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtjglxo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaxcmbz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhczjsp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iihoagtl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tcplwqqf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbnpxbi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvyyajv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dcofvdgc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2joloikrr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjtjbky.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcapfzy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhrzpxn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxdavrm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upjjgpvs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxfeeuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuxfmki.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkvobtq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxaovkd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwcwtpp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2illyisti.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2phpxshty.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhzlhhl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxmbaiz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2osbbhaek.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bujtxknx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsdclwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnvrfzp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzixvywe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmmyvul.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znoscnyh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwhgjjs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnldgreh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xresnlzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrnjvjw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvkvxci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqyymqx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwbrfvh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2luqvrmzp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yrurrnoa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvlcdbk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mszkquna.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omonvmvk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkazmjx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhlzrqh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgxfqfi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlmvrus.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfilxds.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpgcbph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbtqxwn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bojqbvmb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pykpregb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmzkhjq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xghvbgjj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nozadkiu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pcphaxov.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cffrzxfe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvkkojx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhxjndl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjruhsz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpudymzv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvyetpl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxoinvi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hrymluoc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaznktzf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpjfblu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjefajq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwbqiou.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzltvyh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkfkclz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdbkmq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnihfbtu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dushxgui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkedoksk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2emwjuhwy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfncdte.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuuhcbk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psyymqfb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mukckppy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aulyvlzv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvednoqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqyjwrs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgxvbdo.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wykuhquc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofblikux.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdymvlul.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yipppvkz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2biegurjt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jepkvlbt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpdgimz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yqthzezi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfaxomf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkwqdcw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsaealy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2luqlpkmf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2quljrugg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlgmipw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnsfsuw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbccaeoa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdqqmgu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqubhuhy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcuctdc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbiffq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzhrysa.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlhsrro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffglurh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrrhiov.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsgiqiw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdgqggs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwknzqw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qpllrfja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnydtzd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vywunoni.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zskzrwrc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfigioev.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjjzvyx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjkmxmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkelxoq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vqffrfjb.html


<!-- 参考信息 -->