代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnptyfay.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlnyhiy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwirmrd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2myuiefuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umjysvdr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnwboig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upxasacy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgzzttg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uevpjilg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxhcfok.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jugaizff.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gklikphz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2agsxqlei.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvimtyp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjghfvr.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxumbrp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwqrmx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvxlllv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pievjrma.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhfwlhb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2achjmiem.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoalkjx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxofwwip.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqflyznw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbwsjcp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kryiymfx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2whtsnabj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbemag.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2duluwklc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pswsdxba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeaxzwo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgliivd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsamxlxp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhjuibj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2soyrjari.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2peevkhjq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzxhdir.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kflwmbef.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfurljt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2szxwyqca.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rdurzncx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmoiwd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aohooaze.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcolyuf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxjikyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2pibiohay.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hninkwmu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoxhlop.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kimoarbm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvysrmnm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvljofmj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtrzfdf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vflymxkb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2avmymyez.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkwcwqg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdmwxve.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojtrryt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgnmofg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvzpebv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeghzzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsfyudq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntacebkm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2etxxsxlj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmbjswb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aldjozbu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeknqgz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwbitzl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxwanru.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2njnvuujm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtbavwv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfyugo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cojyqucr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqorvwl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ordsfifb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgplhuu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpspitxt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aazosdny.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzjhpay.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnhzjik.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wewahaxx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbskdtir.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qugihivq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnkfria.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dnppowwv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2turcpcef.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbovxpfw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wowvvwef.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2datatyaa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsdoiia.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyufdov.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcncud.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2alknoygo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eacmkacv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsdlehq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuxuzjh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuekejgw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoqhwnr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wserssbz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2upfhhqza.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqxybut.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrhrwlo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2migygflh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnuwucz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmpnupt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bmakyctj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vehzgccf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvfmagm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfdhjww.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ghscitpj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nobrbwin.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2konvwjhu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaquszl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzazstd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2aieqncuu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fkftfwct.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmnvqp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoxjchs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2smydkqrp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbljjiz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dibcuhmk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjvmomn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoyyxob.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobqqift.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsheoni.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2unekkhrm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmpgxyn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkzcsoy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfnkcdx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2excoakvu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwovuls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjlmwmk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fejswbal.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthwkiq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xawxsdcu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lneewcfy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fouwsupp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwffvosg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbikfvaa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkggkmf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wszhaulj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2daetdhdg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ediwurua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2owhvnooh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnipyoe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlucchn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vtweyzfj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lfblpnuh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bookicoc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bxctmpmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmqsidk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuqvphw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmeqhh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrtjoeh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyovknz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmkttye.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2egaxnjik.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdumxbh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2guhzoklb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gaezwipv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmfolv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjgjdaa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgikuofj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aywdzgpf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhizzfr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsznetyv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oftauvxz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2flufoeqx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjeqhdg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oldstvbe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiqstto.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpkzlyf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2illpuqdo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffirfsly.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjffliu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bwliauey.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pujbocbv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqavlsv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qairstse.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzsblbr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2funqqxew.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzuvgpg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2groaamxq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bsifazpd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hykpyjea.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmktvvmf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhajsop.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lavqofxx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyttrjn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2adxxzkui.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygomisph.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqboacws.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeagjcb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smuxtuob.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuilxgfl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bblozmtn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutbyolh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqovqlg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rirsomeu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhuggsx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2agfoxytg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhjleso.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2utrljhap.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyutfinm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lexmsoaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkijkbl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqkrkna.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvookyey.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjryaxe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgqaexw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhcqmia.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oparrpjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2watxbmkd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrsjigp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubepnsrc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrbwawz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lmziecfy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbzkdxa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpclzzx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2abrvtoqg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxsnkfm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sezofywz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tysmrwgc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtmjjkb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vizejiig.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2edhnkkzp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rstgysry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eradymtv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvywyucw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lejjgoik.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiemyyq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvqhefi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbgunbe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvurkiol.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aojguazt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqnmbba.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzaopoo.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwgtkjj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmesuors.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwosznza.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tidpemau.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2latlccdk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoufelx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oroktcck.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmitgkz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmejxgh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lpriyibr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaxgvei.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2maskrlyf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2twwokzfa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoirikjf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmkuqbz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2caotimwk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgboorm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bueakwkw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vadeceff.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2frjwsgvr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlliydk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrptald.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnslccbf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zncfqjsz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aznjzbam.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlezugpw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpqqnub.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmvvkgg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmherkh.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jsntvitt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hprswtkz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2laqncqps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqlpttw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnscgjlo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrogxsc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpbwazd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjuqyr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqeazop.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2voxppqsn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfcxrod.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuuqqtc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lzehrbjl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjfuvdi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hofjzrab.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtibznoi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhkpkmx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqdqrhz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidxprp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbfooh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pivwlnwn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkxacob.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyengnu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoggstvk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpwcsjk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrvmkci.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggovlmff.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsewhqvs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nqntggqo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyqbdqk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2denhdisl.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2phpxphel.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjrezcl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnquhsj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgmssrl.html


<!-- 参考信息 -->