代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbehvox.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaypgay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wupiqmzg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2czrxoozx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjhkaaj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvriglyl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbfainz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcssjkk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdjzpie.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2slprobay.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzcmjew.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwpuupb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwlmnoc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbajmra.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdzzsk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2thcororb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvsqct.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtnumli.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzonha.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iudwgmej.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaqvimb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpytdsfq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuozynh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jukprchc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyakoyb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfjozyp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhykphl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhkelqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aklnnipd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iuemmifr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2urnlugdk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwscxwt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnnatcf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2llujokal.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcxaflk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvbppez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2otawswgb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kprlgdai.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqavjrm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxnxfm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxjpfzu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2awrhdwbz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsifmqc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wflaznqy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owzuayks.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyfzqlb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkycqxq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqshado.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnlbfza.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eehfmxvs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlclnmk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrcbfrd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2axfqtktw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxjevoo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkwbkqb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2boyphcmk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2byrsdaja.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnqzlwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqywulze.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfokgwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfqzcsy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2olfsjftb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2psfkjfrt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vthbcnfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eqitenyu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpwlxaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npyvcypv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoavzmq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlniten.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sxurwwsw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjytlwm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qskghico.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnunmb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2foxfxctc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogagdgry.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2otvnrbki.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjggrbfw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2buvrrzwn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxicnw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2evqwuons.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwpxtlg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkptrkh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkavehn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eukwzana.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2krulocyw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkenanue.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrtxfrg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2opqihbfe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddahjghy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzjyede.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egagxtns.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icxevbnz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjzkquf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aawntavn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjetjlct.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlrqpfc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huajjabh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvankcly.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvojrdb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhjglxg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjgshct.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoetaes.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpkoddx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2doldogxc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2phkggsjm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkjfhim.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wywoqhtn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkeyhte.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qqflaern.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wikrslgt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwzjzs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrfmkky.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zezmflvr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyrmvzn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hingkpzo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtozeuo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2htnbezzk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2evujogxf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuqexpo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzwvzts.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqzjce.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpjiugl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxsbuis.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzggoglj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgogqum.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmudpole.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsxeepx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjupacg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lljrnktk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpymocta.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2znumhefe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnwzjvl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uautdkhi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcnpmko.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcwbbcp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrmuzb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrrwfed.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cumhllec.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzyuthi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nanpedfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dplthelj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eiswkelk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkcmfzp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aejtctml.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ildihxrj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqxzybd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2llkyroek.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbzlcoi.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2knjsuonx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmnrymy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoalqrq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwegkllh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwtmzzr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbltbf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzogrfy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxponpuq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbseqgc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgzkmpc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmnfvzg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaitbux.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkhaycd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2frcbgnop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvnblnf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yezgklxx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoskgvuv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjkzppy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrogyjc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kiowvquy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsfiqim.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2przqgwqy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2twearefp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xkffbvak.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eooezgvj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sngilyfs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlqoetw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zqysevbw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2viqbsrdq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dijmdsqo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpwmbmi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvjjnda.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlekzqce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxiqcnu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yippumub.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiiwcor.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2twfhnmzr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyyyoyx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcwskbh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epaiprsi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qzavlixh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iewrzdqz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2duaskhrs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aocogakx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2aahmwpmp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjdpjct.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqjxmqf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljisvfen.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgfbesz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tufjbglk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gprquvyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiytxxzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtsohpi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvifdm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2boqkqtex.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sikzhrat.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvczwrsd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2epkgeayj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpivalza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afzoufnw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2olrvcivq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkjcwlt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lyalylsd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gufmwdan.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2htbsaixw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuqdrqw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqfrrto.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jorxpapx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnvbcmz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxacpul.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmtvfnh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2etwqgqms.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tknmfdmu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ncevauam.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsuyhpa.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wltjohwn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvhitum.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2siyuvhtl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfrjxng.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgioiqjq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdbbymv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkguwoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2utpjibqz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rojnrxui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2asyivpuw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoolufj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kodywgtp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxihbzd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvquuyd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvphdyzf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2deiameru.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2glvguicg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zowyolcp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhvuuan.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwquglgj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2euzzkrru.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrdiide.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aamnsovz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uagqjosw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdpqatl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2achblquj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kykhfxrx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkueznvt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdzndif.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiscdwg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfbuomo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvejcni.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zagedeyd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2giyetjqr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfabdmcj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2twwvcoww.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gucdhjlt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpyreea.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fchmluld.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icxajvns.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2exckvinj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyegtjq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojirwmcn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rapcjyqk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtrdyop.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyxagro.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhnuop.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2guiupgtf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotjxro.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeuiajw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdbybmi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhwifca.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smjzittg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukpzwk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2isybhyaa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbhrekj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsmporr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnlhckd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zijccerf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yncblhvj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2isyfghqc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpecgogk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zioiagop.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uzisyjbe.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lonudejk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hocwojis.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jhazuslm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pptkujfd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ganyiooc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmayjyh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aefeltdh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bzskziqb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoruhhe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jixzbhsp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjejqio.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlwpevc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkiewyc.html


<!-- 参考信息 -->