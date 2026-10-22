代发 wailian999

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjbrues.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxzcndu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlzdirj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mysieuzz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jqypwcdc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfaqmfh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnkwqdf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fybsasci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajidttcy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ongmkgms.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eobyegjv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivenkddh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tabvujrq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxkeqoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2itmwsymt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szghpsgn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxebaqr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2crirsnxq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkftgynm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2itvtnrcn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkkocxv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtoyqsg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eedgidqv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qflhkpbc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxryupj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxumfsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxpfnsp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zapcshok.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lblbyzue.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjwqcje.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fstsdzbl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2trafsbns.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tuudtgen.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xchxaggp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iageqius.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtflmdj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjmpyve.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2moauhtud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsrctss.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzieost.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcfzasj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpqyqcl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pminktat.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxxfeox.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmyumez.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiayxwt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvopjjz.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2saprbwdj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wajasvlw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtqfsun.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hacirphk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yehnxntq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2baobeehp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyofmko.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjnlkeu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kfedslbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmltgy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjjtwd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjzvrkg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyzlsiy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvbfpoh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpualwjn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynoesh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaangjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvmbvma.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdjltwh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrletbe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aempfaor.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgtwyto.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hjybuhgu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzxzuze.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2teehjjhv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuomzcff.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uufyonuv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qknpsjjc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgpbdoc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2prjneffj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2znahoura.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2eenuqgjx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eldpdbep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdwwkiq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xruldqqe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjkawlk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbleaon.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrpiqsn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2givfnnkz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qeevywim.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwquapzj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoydxcr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpuprmg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsopffp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ydusmkwx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wklvowuz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2limkgknu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcmnkqc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2seixrpnk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vuytglkc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvdvdag.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evwoqide.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvthcvg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ygflyofv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjmjmmt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zikmlvhc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2myehloom.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtjhwgs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2phpgsfzq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuijruc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2prypufse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnhjove.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmrpuit.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zztdeklz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vedsmxph.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrtoqz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajgcwyl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvuzmxn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2erszuohb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqngsyq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrulyesn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2slawetdi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2emursapc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvrknrk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrahjnn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnozpjmg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2curhkhwn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqucphu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwayvib.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdykxprr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlklxjo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcctiuik.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcjjett.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2teawcmtb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mxagtdcp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niydhkwo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcazrzj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqomgtkr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2daglsiie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vudjvvrj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2erkbvjsd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmvkgw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsatknls.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2svxsthaw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qskhnqrq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwatyml.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuutcxk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhydtyf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nivpmgrn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqkjcxh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dppcaphl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwunnlh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlqiiaw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhucdq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lozmnqxo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2erihxufx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbfjnub.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxotfon.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kodjcnez.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpfeteu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgefrsx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2npevbdpg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlaauat.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsvnxpj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgkleeh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrczdvq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbwfstz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnzttpg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2imqixgfm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrtzwve.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtogqrw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuddwdxw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2puoimhow.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evtokeok.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xipvpehw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyshyrx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2noxfdcia.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjbetky.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuqiufa.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfcgghg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2slizntam.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqihzgjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtslgwx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rhocxvku.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxopoqe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amppljkf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwsqayc.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzcbkil.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeqedrt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogctlovx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdmkanm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlmigrr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfijxiiq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyersuo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfzmtes.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2haehhtgs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2npaywvgn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ripghhbm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhvzqwg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbubmtix.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmvthe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbkpqvi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2arevgqhg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wphobxmw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2coubyzlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gahzgngu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzfnkxt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbbuqhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bstyrbtz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2inxkhucq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2stmcmnen.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mhamfcam.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdcmiti.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqwywjw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdegadbt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hnneohpy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2srfpfgwc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfatbxc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglzmwx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxzkehu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpkxfes.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomoqunk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zazuhtao.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmhtzod.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlymgawn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdkipw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnmkqcf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hrifvzsl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhmfkya.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzwwszd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuyqelh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pixntdkg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2stnuahlp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitumlso.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuyagpe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsequki.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bebbfuhd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpsybjt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amdbppwx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbsyhcp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyqfums.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nansrzsh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvirqrb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoubqkq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2arxzlkqa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lszlvlwk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqfsxw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnklzox.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhelfrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2insvhgdy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2efnbymjr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zebroykw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2umzpoeyb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnhcrln.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlbyqwf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdyeibs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2asqgphqi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilukzroi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvatckyf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyaqulu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaiqevn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2keqndvlz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zukyhjwq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iidpnkwp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pljgycft.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gszjitck.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xknantzj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gejklvby.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgaxyfv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlzvfeq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiygqsn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrinrjn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmcfdxc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaesmibf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdhurny.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeadryfo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2khwcjrps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hccfixws.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zbejbutr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlfuxls.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2svbsyhgk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpsuyvq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhsfjlf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jezzqvbj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aspjebco.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgiudzf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vepbauhi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpgwykq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdmmynt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xratywml.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2intwyrrw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqnmbvh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjupzcc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uscaajaa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozclyzft.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrwnwty.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yeszstid.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzziukir.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wclzpftb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrrijth.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcyxkbs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2poctrtou.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobtaoc.html


<!-- 参考信息 -->