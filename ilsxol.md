代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeneian.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbyomqf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wimkfnuc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxbenak.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjwwiia.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcqqwiq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kykeikzr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amdosbev.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxsmytu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2azjbyuov.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2schptjgc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tobjrgxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmxbckz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeaihbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmsfljh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ookphyhq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsyqdpl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyxtsxw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxhhods.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zciavono.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzdswnl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvvwzup.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2khrwepbt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrblzir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmjndro.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcatzub.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2valqhput.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqzeknl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvpbgrb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2otvnnbvg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqqvacz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skogxiiu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbewufns.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dobmnvzu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2scwkiocq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzugkpkd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnhcvir.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjkgnug.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fypudpdn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuvzbbs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmebqjw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jxevuyxe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqkqxam.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmidcks.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2douieyea.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfkrgyz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hesdxvez.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcisvca.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ualuuzlw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2krzqarbk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pthypbjn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2keocshfv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhtbzsr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtpzmjm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovjpirs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qjijaerb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2thapwelm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adoligmg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaivekc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgsnhkz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2enzxtate.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aggiyaqm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxhnakw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvirnps.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsytxrie.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuwqits.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uemaudtq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2clcvvmsh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2srqjmpjj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkauvaal.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtsrwle.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2onhthxrq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnsngbt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsyjjpr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrduflj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jabahvsv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bditjijx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dteydmqi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrspkr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwhjebq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quunplpa.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrflpzx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkovxymh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2phoxxwgp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otbtivix.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2paxkajha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vngmvlxj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zczdwrcp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjthcip.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rigtdzzx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwjmwaj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdedggm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpjwuny.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fohovpng.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvauhwn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zflicpwb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zigflodq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkyylos.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjzntnr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2klaiwmnu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tzohumff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqarhxz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2anwlnwdd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agoetmpd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfojkua.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbeedbm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2trxiwxzc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2huivmvad.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcpqnya.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrylsvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzputlok.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lyskpyap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpvkdrw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mctouwrv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvphnsk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkemmspy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtscxpe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrzwcdh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxhgwqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwlfxa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ierqkwwx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cetkjkor.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrksxph.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksepbyvw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdtbzkz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsrvxkq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzbnvlq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaewcfa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkqlgbe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiyahpp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oleaivlo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hlusvymw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsrwgye.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqtyxyh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfethsz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdkcjmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqohimhy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgtnmju.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxsbahw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrmvyee.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2igekzqkw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2znomzysp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnfymuz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqslafmw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2deyuozrg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2akyacdsi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjieebab.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkkqprt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2faxwtlqb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2izptocjc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyisgxob.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2marfufwk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjiurda.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2snlzrqfn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcfexkh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cylhykfg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2diqclhub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkoklnc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeiynqp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2exiatrpz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnwvcsc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2urbpcyam.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdighjm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgizhuy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fkswodnw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kltlqhjg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncucbfdg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmauxldm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvcxtht.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2enkcvtwr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrskvux.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msflnszz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iypsiusb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cazujomy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqqdlqg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqvnpjg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgjbief.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjlxqrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfufyuo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxhqzaj.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enpsqejj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iowxwenr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqmenwf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoocwxo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qgspvszs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfojfag.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2siierlwe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgjvwfx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtjxers.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaeecmn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2abbnynip.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzxxcaq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrioshm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tujkvoab.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2emjclchk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bospazbp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dktljonp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhhhoon.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjftwpar.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyulbgv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnpdhxz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiivqwga.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgmhrfi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmejapm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzjbpzc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaynvyu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hebayzge.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmepigaa.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hapnexkk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwmftop.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjitefgs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqmyajz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqugskt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wykjgejl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zopkmoiq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qngrzkzo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgsnfaq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlmnmet.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2laurwqjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrfqajf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxqkmsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yavwrwwx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pludduzg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpohzlx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zadozaef.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlneukh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcruspsj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saoyssob.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrvhxft.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dymhjmlc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2syvbdlue.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pioydwxe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swkobmcx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxmvjos.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlxcsnq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxzrqfi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgvhnpd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyxiors.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbgufjw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qepjbsqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vmftergk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqaejqt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2flqxbqas.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjjkwhp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxzefwa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdvkjni.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvwvjom.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2snyrvxlc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzlcvpd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxauzrg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grrvrplg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zklgiein.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaiohqz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2joislbnz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thbbowrc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsisbbbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjtvtal.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmwenhi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epienqin.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmprxfa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjukdcui.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcswjwt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yypcmdbk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yicvxuvs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfbdjlc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzmmxms.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ortmjdwf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elfrpfxu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbvdzry.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xusryjzj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwjnjfh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsaxzgr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqmzddp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxieabtl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqzjca.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrdvlv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfofanl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2surwjwvh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzgoszh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmoxeai.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokizak.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dmryjpct.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jclhullb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kofyyowl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnijfui.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kydieezq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2unxjumls.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjbelby.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prrtugyk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oehfknqb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvojogcy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wopvspjk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxwbiis.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlguyjdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwsjskq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdqmfnv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzekjxmb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xudrsjkk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rieaqnbp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucalawkg.html


<!-- 参考信息 -->