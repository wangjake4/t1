代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzxmkog.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfbikys.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yafjykih.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtywkvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haitdhrf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyjipec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnutha.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2apsnorvo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2nayzacrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfzvcgq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtpxjrc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2iovdwhnc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eczrzmbb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvsohvd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2donvxzsz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kafzuscs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jamcauxp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2odbzdigf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlxwpdt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgonfrn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlowkrv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eipvntja.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dszoiwhm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvecrbyt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhklxqem.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsrifrj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeugglts.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxhnzkm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yepxgbqc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2grnvrvou.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wijeioyw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuayfes.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnarzzdf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfgphud.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yawkbdql.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwbvjvm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbyzewh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnpnpok.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdtyndq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtlrdyl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvssvqlo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuzjdxn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ujonzkpc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dceiqghp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2niiizcud.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rudwbvkk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wejeknmb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtwrrxp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpesahkv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxwdjj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyueoucy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jllgqoaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xurvyymy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcdqjcs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnfrkbg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhtgznr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfaskzw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kobjifxb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfuvafc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsviirc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2syoaxznl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2etltdmyf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnovujni.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlhrblj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaltntww.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bwumoaym.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqtmqfe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oylqkywz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiuklpl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcscgljj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shhommgx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jelzdois.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyjxqqb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqjfagq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmzoely.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhtppdy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgygotp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iuircszu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvyivpp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpueejq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihendcbl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvflloz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2evchtxhz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2btuxttkb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjnteb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmdcyhb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrikvqz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfozjng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2igoecoqw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxbrljn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oeotarky.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjlmiph.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckphvsel.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmhiiok.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2upxlxjok.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvtmolt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fghkuwiv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcrjusd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuujpkka.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqthjqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwgoigc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgipnncs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxdchrm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iousvdnn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqujlco.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnlrlba.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwlicje.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkgufpf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2obpwfmgi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnowbyjk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzmcbpf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnlrfsv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scvauiwz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bznuqyqr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlsinxb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nawxpylr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfkilcn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmpdazk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeuimvx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwxxemg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxetgvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqcohhl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmgipuz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcuhflo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2paswtmfx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrwttxe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhgiyk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuwjplg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaesjwv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gabyjacx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzqxsrg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzopqof.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2disnlgwk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxqudez.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2petcefam.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yolxvmvd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxogxsn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iabxmltr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2onzxhjff.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2okiticlc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxqpcgq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2plhjshlz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpjisia.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzzxvxn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sudtyrik.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmafqtjo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uazezeag.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxmqdxp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmpysak.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eemfgdpn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2swudzgzv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2crewkwxz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfraaal.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2neigvluf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfagptl.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sftxkgso.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmysbfa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2admxxdac.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxaavcl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynwtixe.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dledaojf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxknewap.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdniaf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2komjrktu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwvnqhr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsvbxfy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxueleih.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tdslozjp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umexrsab.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2emzctvgv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fiabfedx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvtpffp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomlgxtt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2flcfiqsk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xemnlpgs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vablnpcu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvrrbyj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxjvdze.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjhjgld.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ncftvsoh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2geoajlxk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dulezkos.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsqkdlq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsaehwx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lnstobxu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdvqgut.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbuxjpc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsjfreh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtitpzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrcuqvm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwyktel.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsooqcyz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prvpzqmh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcwlfj.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjyzycf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2velgoxkh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2torcuqld.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2youepeqz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcpvvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2avijbzme.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbsfgks.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jblldfgb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uipljzid.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2efdncysk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwrdudf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmjcckj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2irmctzhz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rimezwrv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qoajfbah.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbipxdt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fomiqflr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztktigzb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mipksddf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdqjuqw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkpjlud.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlkenie.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtgvfgx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2iuakbejg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmdhkbt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udvhdcqu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpnohov.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kefpuaqx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwafmexm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzehpgr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iegnhhok.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vftjvecc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifhujcn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnksegis.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2neaaybwq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjflbfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmwxqrp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzyqsaz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlcucto.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcioxdo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbknznt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lfacopbd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbjybk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hihkcwev.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrhgqah.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqwrjvy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdjsjjb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xinhcgpw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkuqkgl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xlesmdhr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqocrwk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2iuojrghi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aglyiofk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtfqlxn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpnnrja.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjoxlxa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlfrgsg.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkpaady.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvjmieg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzuubkx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agiocrzc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdesszx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfdsaqn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2prvswwqc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2donwbdlp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uiflqccl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqkjgsw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkrlagy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxjwrms.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmvrerz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqypxzpx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqytdaag.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbxvhtv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtuuobb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtplesi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcgjtem.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2esolvpdm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoicjpm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlldmnz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdcjhbf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rovbmdin.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jljqeuww.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izixofwh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvivelc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2stvjkske.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oglcmgol.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfozeyj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtbrxgm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dukmrsvd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxyxzjc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeystwu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2thwfppjw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pegwojxq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2naskexng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzmvjsa.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhiuofl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xzehmaae.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnglcxbl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwgixql.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yyomoegl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xzysokfr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsmszsu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xiktbkut.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tijiboaf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2shdknidq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2goxlawjk.html


<!-- 参考信息 -->