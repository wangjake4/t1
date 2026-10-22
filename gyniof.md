代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hllpyxtl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqiaxsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyobbxx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tavtffgn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvpybwf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsenlou.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2idvbjvdf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rolqaxci.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymumfdn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgwdzgo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdgpsap.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntacvz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eimatrzc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yyccdjhu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2seuusgnm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmfmsgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfkbvbb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsuewwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxoslgq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkwlwxb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxahkzo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hxindsdg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2efuaigtd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqvqkok.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2afqqzekx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxbiaxc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsudhlc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqcaspc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zltzqlaq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rfspuxle.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfudvrh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkxeqwr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gydjqsup.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwlahda.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcdiwwa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvicwcyu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzcdxhj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrxahzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnopwniv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypulsh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqczuvvo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2efupzfpb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwgksj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyteykx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cijuueeh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqkyih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cearuopl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgwzfvc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzubjo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoobjsr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzjmgal.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2prjorebh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uoypqkkr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgsaujg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fznhpjdu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxltgozt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbytyvpt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmxmvlm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2absijapp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotjlhl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blumdwlg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlxsaav.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2optdubqx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kgomwqsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wemoztdy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqxmehv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hncdcnea.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iizlacgr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwwkfnx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eagnlofi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswkofeq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzdkcpp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqkrugu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2svjsqkcr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppobuo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoldyve.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2njoomsmc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqztnns.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srepqdak.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2obftxmgw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gynhaihp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbflhumv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pduvzghy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjykczg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2injmvybf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2exfglobv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcebuhsc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2avgysijq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2poybodgl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zwavwdlp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vippjsug.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxzfjmk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuhkecf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfqqmsr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhopiane.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2htsigskx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcxsmty.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavjsrq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yphlsunn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyojzki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fweemtse.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2neercdlg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxvxsc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cquhovlr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yutzmuwl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtxkify.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqnetou.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfntvjtr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyehwzd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2haoyxvre.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wscpjvig.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wawdatwl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjwwamg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkitkhi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2abwozuvj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjalrct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xkydeksz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoypclm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrqyfhp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zhndhzus.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2njcafsit.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2crztwtbn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkeesfc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdoaegb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfnecmd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhvfvzw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfytnhz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jonshfcf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmievr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqawzqw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zaojgsti.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzagdglf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2piqlifml.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcxnxcx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppbouul.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyucpaq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqraahw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwirsmw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbqxfri.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2grxhghcx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iawpgpun.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qekrxulr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrpyasp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kogubfjj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lygwbgsb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vybtuoxp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpzsuzh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uknplnpx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqivacsb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhsbvma.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qazwkccl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxkfrql.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmarnzid.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jrctkeyl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkdtszd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnmmcqe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmuppjn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tortrvlf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwuzbtl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2obajhxtn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kkblesqe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmugryc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kddziesb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jijtazdu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnnmeto.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2srrnciji.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fbokfblr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuojajgu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2twizjfil.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqckqybi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuznunc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrsgzl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yougcbli.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nousttya.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mgttvhoj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbwblzp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmacblkr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rutjutpa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwjgtiv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbadlwb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpatmdvu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrckjso.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcumeda.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplafvw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zheadykj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwojlxu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2olmgpaeo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aivhlgzk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxnaeub.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2suamucnn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrphzwo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoighwx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qrojajex.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwyvgve.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2duuijhoe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xogwappl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhxemii.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oozjcsrs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2okeozqfj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchlblw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpxpqlm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zahgcktr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2atiyycjn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnfgyjg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqprflv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeejivuz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qytmuqsd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pntarkhc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcwiipu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqspbnj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dzajlgfc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecygygy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fggztndq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqepxob.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2blaqnnru.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2higcuvhw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqgegfg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ltikmtws.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjssbcfu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dpswlpzr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeavxbv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnktfws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvsscyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtdopeq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvnhcgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tivbmagn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhsmbwm.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iwosfsri.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2snhwdgqa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qugtayfm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkouiwc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbozhsye.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2suvpmuds.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxvqoxu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvhiwbd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2otrqkdax.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmflfsby.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mufbfhzg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpieoasj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izbmekci.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fclthjwz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrkvqmh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2auattfup.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcvpgga.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvzxde.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swgsbcub.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnidrh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsgzonq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xceslqbd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dftudbzn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jotcumhm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqtidsj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrfsdot.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaqaekb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsrptno.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmapualo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlyxwr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zchqusra.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipztplhj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aibakldt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcduxvmk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgohpmfl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eidxkrad.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ziescrdz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xluahiyp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwcbxk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfqbdkh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcerawcv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkmssag.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gycpsahg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysphchov.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2buvunfap.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2paviwnth.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lquubicu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkizlnma.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruydeykd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvjjiar.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlxxwxk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlybkway.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cfymkhei.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqyjjdp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2miyreesd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gilwxxds.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2obwdvfiz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwjcua.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2smlhibcb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrskafp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvvlcwx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxxrpb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqojevc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpysjyi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2noizrlmt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypghjrxs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlqmqlt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lstnvpof.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2abffzdca.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2demqjsxy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsodjrpa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxuiwzn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2taxfsnuf.html


<!-- 参考信息 -->