代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgxthqb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbvuggk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rbakkcel.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usvmssyu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxxxlmg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfljrql.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tujcelyw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pgazxbha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuiumtz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lceveles.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krrnlgsq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfjkfsa.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzlcnks.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmlqbrm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdqsqrw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjuwani.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuoqavo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wewuqnra.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyhbuah.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqooozdu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2neegkjla.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcgpjtd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vuifmaew.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzguqd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvcbvje.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjjlnx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlrnihn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ookhjfmi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjqbery.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxohwdmp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbofgqty.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbnqsoq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldybyg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvejuvkn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acbjbwya.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbtcujr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qalqjrdw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kteddbmk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzzfxfn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2korqonhw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uuufiqvx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zqobmxbe.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtcppw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwnfcm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2elrzpkyu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfdtjnr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgbqfvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfftydu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqugpvgm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2frhowyfr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzqhgro.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bbulcfyz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosqurtv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2judpiazf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nercccpd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bysctmap.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erzubvng.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ugphlgth.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2efdvwsmn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esosemgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgcmsfl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfefxauk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoedrzdn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrcoyzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwavpflr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyyywaw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2trkewlbd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwdygcr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfcpeen.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbrsbhh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhxgzew.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2byaztfab.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzfivzd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejrbnk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzyvuys.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bedoynlo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xacpwgvy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqvdyjv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yecveljg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcixjhrv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhmeane.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2paztmrsa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzbcdhq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpuicsw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndddfawf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdesibkl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxauzmwj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwilgmo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rspanmaf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyeslnh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wlflmndi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvoxsjs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvmxqvk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiszioz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlqpfie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pblfgdyf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuqgzrh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2voiqphnx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbvbluc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsppnrho.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewizrloe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoiqnyb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2plhwmuno.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2szcmedgp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwsydzl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zniklzxi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytjzwnp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbccsvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lgezenrw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfpdpvm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tocgtfwk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2knzoktyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkjowud.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjznyrgs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwiotar.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvzyhdx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxzfemg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2avhnginn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zagpkulb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebofhgsq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqercdy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtpuelf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwierqct.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgcjayq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bryeoyfo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpitvjo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mprtfvda.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiwjmpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2llmpovgr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2soewqwhv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuurpund.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfirwqg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqnspgy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrvmreo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxuvscf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxencrz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhwadfk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlohlxhg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrnvysm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xawnibsp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggteskjo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwkydb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tclgnfny.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xiarkkbj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbplexfw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlihrlg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieknmnmf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipdylj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrumzak.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkctyzz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zagdmpwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wubpxjhi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbgpiwc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhsnowf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgwirlg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjjqrun.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzrszeh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyrludx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zuznmfah.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtfsfpq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scsekzcp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tipsvpbq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhctcjqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2izmtzoom.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aktwgyba.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2btscsxqt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbtnfws.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imxtzfjf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdzeuoq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgvuaqp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvakfigb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2numwxjho.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtxqpri.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pofwvevk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2peeglwgg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzoafpd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmisqrqe.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdlfgk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrkwhrz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsvjdqs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xotvuxvm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2veezqhep.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddbtrgl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkslbhf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzcuwtb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlyxcim.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaxjotl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsyqtnb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yiksgull.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqqnqmp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeefaoh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2yrboajic.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbsyvy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeozlrti.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjwlgtd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuchoopx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgniuua.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whafqhqa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pnymonvk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moewjwwx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mswiemxv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hghyzfdo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lshahaqq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrosqyzw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmxsyek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yifspivl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgjhghj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvglvwf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2widcjbma.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyezioo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdubev.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ogthrmbl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dsszfzah.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeqmdzs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmlkhjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcctllz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2udlpoell.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiqryft.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzpxvxu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eximyohg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oupggyyk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwunrgl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zapudzgd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxalatl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfmnasd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sobqgkvg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dougxkus.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tznvlcoj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvodlvwm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gukdgngn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkgvkvk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfcfmup.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2palkaenn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2odefifgx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aywpcdol.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeglokp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wwctxbpr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wcayilmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlbzgwy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzpodzb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gfngwqkt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkztujv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvajiec.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zagjlxmd.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyqekea.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nubgbjgy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tugwuean.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2meyslgpz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eflhyjyb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrxmnxe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpsdmwr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcggamvf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjvkefy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2okuqqoev.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivejcavq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2umqmahav.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtjnsmi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bkktzwga.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfislizu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnyxbie.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjttotd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtquvtd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2opzbrwku.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2abymhakx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zskwidkn.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pihjugkk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omfnrffk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cyefghqd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2porhgsbh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxynvoo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhnwvoc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgqjhba.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyydptl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlqeyku.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kifrmzow.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2paxjvbzh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxikvuq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkpplrh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmzqszs.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuffikub.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpivewga.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lvepmiop.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cefrgkbh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbigrkdn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usuzhfao.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkjxddz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzwzilu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkjnxhh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcaptac.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxyugyg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bufhvlkl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wywqqogt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnjbksa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxonzmou.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtpijqm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgkcwte.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqpqdgb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xkshuiyg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxdjfkq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlhzrao.html


<!-- 参考信息 -->