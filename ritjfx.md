代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbhgxaz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2icdkgkmv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbwezji.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxkgtem.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqgzhiy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndffhxjx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwqsenl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixljdoti.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2elldqkvr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaxotzk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsndnxec.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ginwljfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqofbdfj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgpfqvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjffvfix.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaydnns.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ooetxqzk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxewmgfj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2juhyyvug.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbjbqds.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xncfgrfi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrxhiqe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhztzrnf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvvjwyf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtupwpfv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbwebcg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sfocwgqo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsuksiw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuuslgz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iskqgycl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhmcrms.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zronrmco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlrluct.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gspnoypp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cewwqwxr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuwrjlz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlwkmig.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkwyxco.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfdcbty.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rokvtzlt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2csmfbfla.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaesthk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnwrktd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2amnaqyps.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oivswvej.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdwsyev.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pggnizsf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzyimih.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwhmagj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnnsiha.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbcjfxc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tktsynjl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcfledc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfxwfpp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecreinsj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tcacdwul.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcmzjbr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2atqjkgwn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxgbhng.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvdftjg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psblcniv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gixdsaqh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2birggllp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkneiwco.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjhoeya.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhuvucm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2camdbihs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fezriijt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkqzpvx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkyuhge.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeukatrs.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2midsngil.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqrujrr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrqghnh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eajnjrve.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyfrile.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nstpwfjp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmrexej.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgrtptp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkoszpy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtyjghi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ryflyccr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkregdp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrlhcid.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzhgllx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nufrwqlk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2omwnrqde.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzsxymj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqbdqhs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaixyqn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjiplse.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2thcjilbc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqypqvzk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqrxfm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2torkvknf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2shqguyix.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxjokvf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjtjdmc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpjoqir.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvceuxmq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkfylrk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcwlzba.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2htudpewl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfnaqwh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtmwost.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfilkvyn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymryzcqd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhiivt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjadwil.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjkxtcu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcemtpcz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvikvgk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pxohanet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cygzlorw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddodbtet.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gckulitc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiasyjo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkghhowf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2szbmqqla.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhkigji.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pcetwbcq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzjbkyu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrweupgi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2stjefvdy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfptfqq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2npxmflfs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhraace.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2btfjzzkz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvhxygi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2voquufxo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjskxqk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2guxbmzkk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sksmabwv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2buymnmgt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvatxhe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsnriox.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khslbdvj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfuktmb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvokmtll.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiohgag.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwndsmp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnhoazk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiunhcdw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lipzeqjj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sosnjrlc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmslwufq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhigpkb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoyxjeu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaegvrn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcgbdwr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbvhco.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zghyadro.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2knlwgxvv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmyeage.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqcpwlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcufvcx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2htepwush.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkerno.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzyiwph.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgthvbx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onzxzcrz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxjydsy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2leczefxf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmgtijh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2urihpktm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoftums.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2huswkweq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyqnwab.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2keomesvq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2acveuwyg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lytfvruk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwnwynj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqxfrvh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cieuhlha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pimbamwh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwwrnf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clyhfalu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2doaxgsan.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoisbho.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ilckwyvy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzpwrz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iydhjjdi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlyevfx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ommxtwdj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcnauob.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2apssixjf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsxahvx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wcekvbet.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyzkxax.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjooyvaj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxhivjr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gicvyomy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdndxyob.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yepuzjzj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcgssbq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfvsqze.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pokwiveh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhomoth.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbmpwwf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ossiqeln.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgkqren.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvujmgz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmckjmkm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfbitzd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnlkaok.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmatvxi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsicxag.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaolputh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wyipagpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrlznqv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xndfvadq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqevkrb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwsyqfh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkebxgsx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwupehn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyrpmsv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iqypygud.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xepzdsbg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqziatve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzvliin.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lncfbgdp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxflkpd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwsqstq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqspxvp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nxymqyek.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsiyqzw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwalzco.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mokbajgs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjbleff.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2delhxgul.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqvdme.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eokuciaq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2heukhpyr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdzlfkw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoitcxx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqzttbf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ipykzhph.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyswtwj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aaalwdmd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iobocsdx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvbgjmp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpschvxp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2axslecar.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cdujftbs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2difzslkm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqevqau.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eotgfdru.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonsdfgk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2apybznug.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdygkze.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fldeyqiv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwkcww.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpalatd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sihawaql.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxsvydq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaavxya.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoedqpl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdpupvh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxtjnpq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2awkxervw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2klqwutqi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhlvpkk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2irbqitdb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tyexilvy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyyapzz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrezsfr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlunncm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eztynqas.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrilvja.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jepjslxi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slnurobj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrwmeij.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlsdllt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqmprbp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfptvfv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ekajiawc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgtqqbu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twhkakyf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2smgurlfs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvflevc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsqkezq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2knhumxxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xaisbtlo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whxdnzeg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmovpnox.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vheoetpe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdhqhp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlivzwpw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjismjdz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxarkvz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgcsmah.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2egfmzaub.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmldczs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrhgpes.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxqomwi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2opkpggjn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdssfckw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfejlkt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pecjcdvq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmibcib.html


<!-- 参考信息 -->