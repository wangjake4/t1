代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kttiuwtv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2riksmsjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqthzxrw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcviizjc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2woemilfi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgubwas.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oiozmqly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrcetwb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fekhbvii.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmprbgcr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2czclwqxr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdrdxgn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vemesxen.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwhtckd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjqaaym.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokcxzsa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudbziw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbaletl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gctovmye.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgveeahf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrsygni.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bywgiapg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tllrepoc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgjiqwo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbtecsz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmkwiat.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuzpywi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrzesqg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpyxiuz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcamcvu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayumfizo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2berhmzpq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqndmiap.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2eloldvrq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2swhqtnzh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qanigaey.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qbymbptu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mioynfio.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqyeknl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ggubqhgr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltamakis.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfpuyab.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvjrynb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eerskmle.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapdnih.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnqtpqw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlbbway.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfsnray.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cygtvdaw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtccjmz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bczhkhvc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2alcloprf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyxernb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ircojmlq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2juttywui.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2obgkddnu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmbtvpm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2alyjybum.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwfbvjq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2beeuuvpc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcprnvqd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxmshha.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzzihas.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yejmoifs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfutxtd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yacmsaez.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjaihjf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2etmhdlph.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nobhzyxv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqmbwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ialvofly.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrtahzs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqbbklm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcrreyv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgelwff.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oumwbwsh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tisotrqn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cahxtvxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcwswjy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uwooujwb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaszcnr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygenrifn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkwzknd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzrbzdj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ovraizjj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpampsfd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaanzew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoutxnio.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zrohfmtm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjscgcjr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlkbppx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhpozdv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjgmetb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfckcjhl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vffbqaqh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnbqdp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbtmbjn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tssmfurj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2csrlmcxq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qruxlefg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfvxpgx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqbyhnx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdypxvbl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsdubqi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqvdmr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkzzglr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqimjtnu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gucdeqpq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2askopoly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2muprmppt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqzycah.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpyzxof.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlumbau.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxqdmwu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmvivp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2undnxpyp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olkejfyt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacozjvp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdawpaph.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzuylpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwohcpu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etgcdbah.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rixrberi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfpkgdk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxwwnmq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pzykbxca.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezzdfie.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2emacwudm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtowyhlv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxtnwr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgqavlw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwetfjmx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zorlqsvh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnsaexu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjvicdo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bikpqpgr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvxyeji.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlqvktp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgykbfpp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyesoia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2duoouewr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxnnua.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkayeed.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvebvzo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmtpbin.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwarqdo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2irgdluvy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgcibxv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2paeetwan.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2abaxscdo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2omsefsae.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbakvvkg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2muwfyymg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtqenbl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2duffpsfz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdxwxr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmjhuuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2huixrtnj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hecpfhke.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtvvjaj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpfoqlq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpncedl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpxwsym.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eanaacqj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bokdpqax.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2klxtkkxb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2icatgzpl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cknmkhdf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2watodnyb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfvoakn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjipybo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aadxascy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eymqezyn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwwjsyx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtualew.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gozpjepc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2owxvykhw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xauriuij.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ruucoijq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjonhw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdatcxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpidzbs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyajmnr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwfoaxp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqkjqzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vthsamxk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efkcrlky.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxecuzs.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czgdhjws.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zocmifqo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axrswwju.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmpbfnu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bodzbwrf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xryuexcw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2psoyvmoc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2podfbgmn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jtetfcrh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxclglbk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2amirrtmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2idgugifc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjtlesg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiesbev.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwirxrx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okfuizhv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkhaazu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cytlacel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltpxmty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orulbxla.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nofajbsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zewucccu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2oiemtpts.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ixanrfhz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkcxfhp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fggjywkk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfdftwa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vknnjafe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpwgxhl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uczfqiwi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwahmxz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdbhfuk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2picrmvam.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2inyyyjdl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txtympzj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrqhrwf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2plcbeinf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xyigxmch.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbjqajo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbcnikk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wpppdbzy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2huzkmbay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuoeajn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hgadswfn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzsoodw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkguucjc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpfrqeb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcgbydu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcxbbgc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbfdswh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjsiqjr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2linxejuh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbksmli.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iybevcdg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2keysmnif.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nityjajc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhdxgmq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tluwgivy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sohqfidc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcktvwwj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkisvmaa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rsldidyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrqhmna.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2obxxlnos.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnacvgo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrawomy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyuxkhw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlcebad.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsymjnjj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xtamrojz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfuvtr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsgpvcw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2omlrpqxp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnnpqad.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekifzmme.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtwazbo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iugxcpln.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fibubena.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmfcgqo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xutsumdw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcfinvm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sknmuxxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ntggcrnb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimvtrg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rdujneck.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2acwpjfju.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvooir.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpawpuvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtijins.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvuzwuh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efcvfjkv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzzmes.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eexubwgo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnhydhd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwylwbc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqmmatx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmykzlhn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2clvlhpdh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuygvbx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zucqwqvs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacjrylm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yukiamjf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aoisgbba.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bforrjzc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwaane.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhjgmjz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fpstxuss.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2miphsadj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dawqipuy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbfsmhc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucukbkle.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2appelwac.html


<!-- 参考信息 -->