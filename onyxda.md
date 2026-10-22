代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhzatdk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2elnsjtan.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kderqklw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2syrmovjg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxryenp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxuhppr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bslzjmoh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpkhfje.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnhvrfe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsmepmh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmutuio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaftzxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwlsqqg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrsoeac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsfyday.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2syomqrbz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uakdkila.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqprbyq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aibtibes.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnwrmmt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2adodqfif.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2duixjnpx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qktxltpe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwzcpx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrqiyfn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wawrhuom.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwdhing.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjusbcaf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qngqfawt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjikubp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxtrtdh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyplapo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rathlhly.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvrsjds.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2munomcgb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeagcpq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zynrcauw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2oydsaviz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2muslgwta.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gxerbgoq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bafgbngm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2onqnkglg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdllbuxv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbeiimx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrpmvvf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2frbewicl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvskkvhe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfiwotn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2buimgkbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjutvfo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqblbnkz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hozumgxm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2reizletd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2litbbrkw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzgjhvl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcemawx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btjggcsq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlmoqyl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuwhxlp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2khjsbsqv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpgqvmn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbdunbs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdiyatd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsptbbs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgknllzo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bifinscl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcmahgc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xphmfmke.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnhxavq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrjeldk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxbysqe.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhyivvr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbwqnka.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qintmfyc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odinfnuw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nttgalba.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nwttgkyk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2buvppmih.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvrzbde.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlcvalm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zokzmpci.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2spbebiab.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqsllgz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwbomc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2igdtlufv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrenqvg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiuwhkr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zirfthcl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvmgpqz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjalmee.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvmyecz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqhibuh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgiimzt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgznfoaj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqqrqqs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeolfjf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vewxcokc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjprphcx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsnbgxx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yixdhjdu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkpjuec.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzemjmpg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fffnznpb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoadydp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sayaryhu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcyjyca.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoskgkg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkkpoyg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpsaaub.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpoaxii.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvioxlg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjgwynb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrbxjej.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcyenaa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tazntffb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mygtayfq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2thanigow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkavcf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewogrpbo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlldznta.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2smbvvoof.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wimzesrf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emkjaskt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gblcievh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cazxixtr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqgjzoc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtazrztr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2trumawgc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rymhqlkg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimiuqbc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgndxnr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqhttjv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvsxgwm.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2neuywtzm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qabfycyu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjtoaep.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amqampoa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2guidmron.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2npgbpmpp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtegbmb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwigkzni.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gzexmdur.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgpqvib.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmekks.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2reukavtd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaiabie.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslassps.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpjxwmj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yywtnekk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wukixsod.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2blcvoagn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgycvrj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxfwyio.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwwsdiq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsupzpf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkmumcf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2szdlgtdn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhgbsv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jswodnoq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwthtygy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ricugktd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdipflg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2scwkaczg.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqmusrb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwunscd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyacagaj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zezyussg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2auspuxvy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2btufkkgz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uywrkeye.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2txpecsxx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoteugvu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowjxjuw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zesdmxor.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdfkxw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pwghaagk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwwmojh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtllgxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2goklhpmv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rhynrdyl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwnhceg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqjxvkf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzciuhx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbuploo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wexummch.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbmloiy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fosjxnwf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqyxmjd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlnvlha.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2etfjxmux.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqnlriv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2okbngybh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uampxyom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dleedxhm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wuysvwzq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oflgxmff.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2upqeoslm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlhxfva.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhtvurn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfkdtvg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuspsge.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yumdzsgr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ischkziw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtavdxf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hvduhiho.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhfidlc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnargkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgvmmbq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2geilqjwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2khxxzxuq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2snhikdns.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2emkmjfem.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xisysahb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjthnl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjoxtnt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sodjizor.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cdycqqwr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2etaumhhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2srjrwbnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qliircac.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvmesbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwixtuqg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hrujwzwp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gworjqzn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoytblg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnweupzd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwananp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wggpmkis.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnoocwp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qajjcfer.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjbbiib.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eahtupui.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgzumo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpfcdyp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlaalvp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsexsub.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nyclhubj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flvlykxm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2atrybyql.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohakbhkc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gdewxxmc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jezqruls.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwsbtau.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wicigyro.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mauqioxv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlroopnt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvxmsl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdyycji.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hqayugra.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tepekwti.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyemhzxx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypotzprr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyajbjq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2uydqgsio.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfsmodx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svczqher.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2perxetda.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmaqlgm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdvjdgm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcnpsb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2upwttrtd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwbuqh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evbvxxeh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgetdken.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoguhbg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnvwusf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhqdlmz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvnqmeg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdglvmnu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2eqovtknz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrwpljf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbcfxsl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zihckpbk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqwruei.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvybcufo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzibxqg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyinlrrh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glibprau.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxzqpns.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqpunn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fprqbjtb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhqmyw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhpmygk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuezdpfy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjegwbm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kruowrzs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2prlaazwx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrupqmj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krnvdzxj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2efvdqnyw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onejklya.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxvstvb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhnllgf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpztomj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ybokeoud.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrshujw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2thzgjjfm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nitoizrx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzrecmh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tearrsqc.html


<!-- 参考信息 -->