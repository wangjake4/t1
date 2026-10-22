代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfzrvsl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edpygtyy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2purnfmox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2alstrune.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zccegzpv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2eclnarte.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxmobya.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hqynonqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsvhppr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqfdnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvgetom.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2opjgogmj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmpzxfn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvvufld.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyregxzo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvdbojw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aylsesbe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyxljf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsszbgbu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2utwtufyb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrcqjjj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mphljsdj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2twxardtm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlwyjlo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyttgqn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxqjnju.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfatrsfw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdxgchc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eudfnxpl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrczieb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkagprn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2udicxtbc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyngjry.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdfkapo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sudgpyjc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hybebewn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzolicwz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsnstyq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbjgqvw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqahtge.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcedkux.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvqvax.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2luwuktel.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bljorela.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uapchija.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhhjqhx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eshgpwdd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzuxrzt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhdxbz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcynds.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhxexp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxhceoc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrylyooj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iidfogia.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idjizojg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfxnqpt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joeebndm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnmfkfe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnrtgjd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mztgbwcr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwldygsz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxqmifw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuzkbav.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2waztefzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgtbhfi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krqchovr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqqyoea.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2khvoxmdb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbukhtgi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hydhpvjt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2voppiiqp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvfzijp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2okjzmlvb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2emkiuwtd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdzgjkm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzajmlty.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehjmbps.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2twbpxtcq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvbljjm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qofnktic.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfnotu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rxudqgnw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznfecru.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adfbzyez.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhvfvsx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2krugjows.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqvcogy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2plwhdykp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjaqfet.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwjhgim.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2feboxtep.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tobihaaz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2umvaifve.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszucipn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2prbzvcsm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shnjjbaz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erkacsvf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2acyifiyj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2meuiepmg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apzprjbl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kraragho.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmmzcmu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggjdpb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsdwktj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cathzirn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuppqtx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wccqhisd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkmbxmt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2waolisww.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2isomwezn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqhogac.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zauuksme.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoakbpc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwfmvhr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpohyej.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrpswja.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2prcumise.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpzcljv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skehltab.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2czwtswyv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaeffba.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyjjpqt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srqqyaut.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vshewcbm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlicgxq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2omwbrdqw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpwwkot.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjafafmq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2whswwobw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlfxpnl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zugvtzhh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvixgfx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxkhyvj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzkdwzw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzsmtg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxgeatg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eywhqvtw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhveqlf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2slekbnla.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbupemqh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhtxtfu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2loeyuqhu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkdgzau.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gooipyrf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmhnnwz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2msczqmfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwgevbb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2avlgrlwt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ystfjbcd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwdytba.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2butdvdjm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cstyolmt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hipkxurj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkppqzx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kerbyokr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jutsobag.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qbchubmz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfdzfzc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzyleyf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxpripc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrlvunm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiudkpgf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2azzeympk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2obrnzgdu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgnvurf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fccnzzzm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2engesijb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlrkoti.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhjsmss.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lovycrtw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdiuzgq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqdnmq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ostalnzu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hnblphaz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzuqxkd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvupos.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvutshyl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qeansqzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoopsly.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vdustoud.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfjdxnf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvgtjfj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpskgci.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmwktdx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaotjga.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnesabj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhbdigs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cdriaucf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmufmkwf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipccwicl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zupffghe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2chrjlumf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dlneapcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2feepuimj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzehnetz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrnmugx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoebvmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzvfyoa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbndnrh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2davgcxsl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2agluwzjx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwqybwf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rczvxdpw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2csqfjhka.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgdumbs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsylpgu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiwasxk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyttbodz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqemwjnf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kyidvdpj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqcxslt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kiueopvr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oefxkktc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvotvhd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpshjgof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trgqffqo.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvygafu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dubunzlp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdjbqik.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hvurywmt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxfgnuc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbbrrga.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuhjcsd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acjhrzzm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vseryfij.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxrkxq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qacnbkfe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2scviuewj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qamvcxec.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvbduoz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kikopmka.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqloxkuc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kklndunf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaatqtr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gruvvgoz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xjicoacj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvldutv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bipqawck.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbdqmur.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzqcjlu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfwkejc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhxhphb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnevfbcn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uauiwikg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvrrbxx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiawlsi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdpfvhv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eavbgato.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btjsgpir.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2apchaunl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwaaemc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjlchse.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqtexmd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwngccd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2plepjxtw.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzooazrt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2raczjein.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrvmhtc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2veomanql.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knchmixf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrzqenf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxlmafi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tflzgzws.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhusqyl.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdiemnh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bczexvwk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjpbmeb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuwctpx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnverix.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjldseu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzzxbaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2povglfrk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbiirpm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cidxonmd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgqerod.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgdnsgw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxcjyni.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tghjqebq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtezina.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmkdvwv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkoagan.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2emajeyle.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cauxzpow.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpjrium.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lysfhahk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrjkfdz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhcgtf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qtovfohw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gneolnfm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvukojtn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmkprjt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbexupa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrdopsd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfphwafm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtkdjqr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2woxigxzg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqnbfuw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlgqore.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wewtlbhi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hvesuzkk.html


<!-- 参考信息 -->