代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqzikwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxfyibm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhppugs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2faqbhgjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmazjsee.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpevfmlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swfufrsm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnnjvac.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkmtyot.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lewnvahy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwbzppc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhwdobg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yheftrnz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovqctu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2juxcqygy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyowfys.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nowqeose.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrfpigp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2abjrxfxo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2auouoovz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhnjfhf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gurpkkty.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tykerlbs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeygesv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzdprkf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxatpobg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtmbuti.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqifdvng.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhtgpcf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qnphiigm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2synqyjgn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgfdzzw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2myxtigcf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqjihyf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfexckxu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhexopa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyizjdp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kewrotrd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjfhbeo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zayipkqn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpspqcss.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdyujkm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vlolvdhw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwoesze.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyremrm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzbjbws.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpoqjbl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlclljc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukczzwpc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2llmhnwhm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmuemnc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bojanzoj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdthjnpd.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hftyqudz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhmubps.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgwppwi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqkrhxt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfheftgp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgcktse.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrybxos.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wineaqju.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pywinshp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaufkioq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xyreveqc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyrebxj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmkjmit.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpiciqk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwyelf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnnzkwv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iynqnpje.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmdatcb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqekfqgk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epovauvr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjddeae.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiqcsjl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tobxmejq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjslxioc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pelnvnbg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjtpwla.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyizhbh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsmtuyl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrghctj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aumrqpfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2piscbnes.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwkxdfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqecdpo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgomndst.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjgfoyf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpknwjw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axymybii.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzunmgci.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcrafoc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2svhmrhuj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflpmxki.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zewjvlnn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gphhxfvj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpveqvxz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2deslcedd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2csaqviol.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgvdfsf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrheeto.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpqeuid.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfarkqn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wexzdzxw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcskqe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhmzbwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrsrneo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrpswoe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eutcsqah.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjavqemc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcborxeg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyrifix.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nizxvdpf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2swcfejqs.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hugnfyfv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfmpck.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xscchuoh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwktxya.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvogljj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uamcrhlx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mszcxfwp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsuwivq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipekimql.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkiqkyt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoysoxd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvjniaq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2chstlmmi.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aewvzuzs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmumptp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbouljt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwasbtl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vexesbil.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqzzgz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yesjxmny.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhxtceo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvsjvkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycndbhzf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgfkrzh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2icuncuhu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2elalbtpe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdjofxx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbrlcry.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2npusovde.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxpxicn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzsxoxf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwowwdz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hjolkdux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqxehba.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2auybrkix.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrariau.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbnopgt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmsijv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqsjcau.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvdgoom.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2razmtymt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlkqmbi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzllefyh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaekwobz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvjuhzs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeohzzb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoyuxac.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbddtez.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxrsvhk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbafxtvi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamcanfg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2joydzznk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvpzqvt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnhywx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yckbokuy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2erodgtvz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eouhhqwh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcaqshb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykujhtbt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vonntlcq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2paushdzl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvfkhfc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxactp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2shqjtcyy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrgpiv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnppqig.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfswgql.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pftathne.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pjagslou.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2chomvmln.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tclmrrzi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxbuylp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcjmtqn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2obcmrsst.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fieumnjy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoiaspw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkilbkx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enufqoot.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zozicrlf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kopoabwk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pynvkjqk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idofioyl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2danvkjae.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rduqjljy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kspxrpvz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2oehfyifo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dfufbngo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mkafrobv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emmghobw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2auwnlkce.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwreuvwr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rzahihgk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkqwome.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqyjgqa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2htctywom.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2febyhiva.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2exinjkjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eawjirjw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvcbvwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afrbykhc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnfeumg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tgouzinz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nfehefdq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rajivdod.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkhwgcz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmwnxfs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2divmgduz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmufuum.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zalntbqq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2spndloxo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvionphj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppybnvla.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyyzhpz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcwkwth.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wyibixge.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wngebbsl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgidnkz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xitgcfnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwsugya.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2goeqrnym.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxmeqat.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsukbsz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsqutj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoeosgh.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqfiynp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2canklwoa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2slrlvxlc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgbieye.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhixshjp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgnydif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqyugtf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqdlkts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjdqkmm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnpvjco.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abzfoaxf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdmhvsd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2euwcxqyp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nwareazm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoujtdsu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeesgwv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flhuxqru.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbmzibw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbwlghw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtkseyh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bevexnbj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2trpemgka.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2esumjanv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmkgjbv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqhdgdn.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2woexfxgm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efgqirjb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmexqao.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoijcse.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sstxkhcb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdrlkfk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2erdvsaoj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgwutlb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2veoipejy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qucnzzqy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2plibtxog.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxlzict.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swkbnebn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyaqbpp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uudzycdg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkygsrwo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcpwkch.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pedtyeei.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqtzodz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfedoto.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2clsjrzsy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2odkixvyk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhjjkvj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kunniboe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcpjvlb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjkdyrh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmtkutm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qpftlacw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqbtuhv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2orrbmfsz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjppbyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hdexvcss.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtnqiil.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaamryh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gagmhooa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2reoetgxz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jvglejvu.html


<!-- 参考信息 -->