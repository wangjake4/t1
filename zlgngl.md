代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2miolswce.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhwumwa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yslswkzk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2elpaiamz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgbxpsj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdynydis.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejcter.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2opdgzmch.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmphcgkt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjpido.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcmnnih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqfwcji.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxesuos.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbnvvtq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcloxow.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwdyjjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzgxisj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jafsouym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siyanbvr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2exsbcjxn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xziceqir.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwfqpa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbruscd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrzmsky.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhhkvfl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfupuxz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpoufpp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cezfulbg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iitnsoho.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrsfsac.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hoewyhlx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2iktygwyf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefzbval.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcweryt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowgbjoj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcnxivh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qynyynic.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzmowts.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wclseeph.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpjwxns.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxbmibu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ppreclcm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijyoat.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zipsczhr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlemdfst.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rllhzxce.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsvxbm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfrmckf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eresihlm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnxmvfb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzohlfy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rfybelzp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pefdhrnd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vwydrebi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnkafh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fofqoklc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoktxiz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgseejad.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrxdbe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jhytxpym.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhamvsii.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiokgttc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyypmkr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjvcanh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzkhtjk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umeouyyh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfmjajh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbvxzns.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cooozjxl.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktogtlzn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptqsveg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgpelnh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnjwesz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhddpdc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvgotup.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvcscxm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrpbdoi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bniaqelk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcrlojp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjaxrww.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nesuvtsf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsrsqcq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwqhcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztamtxmj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexrznpc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xapaqzvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2klswskoi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hajilrtu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnsdcvk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdrwuwb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pihqxkyk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmsvzai.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uifkihub.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2izujkmyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxvrjh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xoetcmid.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2udqmcvwv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvgbcpk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2strtnmel.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fixyzdmh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jffahldz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeopxgv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qofevypq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzqrfky.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpiyizn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvyygfc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2twpfhygu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dighotsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbkaodf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsnshap.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2arhxseuj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2offhxwqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtnydvr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2etkgxfot.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxvlusi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiipiab.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhdwvvd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpjsyjg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhwsogm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2plaunzao.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2psnptxgo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjxuifw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwjcaxt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmrjlft.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxomwtu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2btgrqqiz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwjbdq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tecxqhfo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bghfcebx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvodpkzx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfpzlld.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiiwqfy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rxipbmlm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhatbvz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xluzzjry.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qobcvvet.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzvbpau.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mprzocrk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdicaef.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jafoijie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbcfwvz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgvxjyq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gajbanuv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2duigqnpu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzlpfeg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqswmift.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2govtjgye.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2incloffx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyocsubh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvdenoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnpfosw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzyolpr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykoiufy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapaghf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twnddlfr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2axkhdfcd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxbdvql.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2njbomank.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qawklavi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbbqwne.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ddakobdd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2necejbiy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bmznpcbi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlkrihb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcadwro.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkvxnwn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rozgkmdo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwqlpp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ccexagqj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qznyjjdl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojyqyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2flmefxsw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrynbku.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnczcpt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2twkamoqg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmjoetk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjthoidm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kokwwnnd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxhzkvm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxdkkel.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwrgmjr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqvblvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2asskwusx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mbybcbts.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzqrwnz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bgejccsq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2alwzpevl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvevfce.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2girewyts.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlurafe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmvqmuu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqxkgdv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2obdruibc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnadjmh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpgookw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2radqjzti.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlcplkn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tulwjehs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpucjtc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2txtlamlt.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fivstoez.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtqlpeq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvepvizi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgtvfns.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agmdmqpo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxltbpus.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhlyvzi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cchansrx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfqxsoi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwvwdjy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2isbtrvtg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvmwugu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2biasydlu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfxdkog.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzzoid.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfyvfi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzakehhz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdskxyx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvclhfi.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsamldf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsdzbms.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2eccycymu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wecfoaau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnykztlj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2twylcajz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lacvtldv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jiepcfhs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rzitdvhm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzwvnmi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zveeszbw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyaswkp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfntzgjh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2skzgximg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjimkdkc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aaodvnei.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjezvlgp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgblyndb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhwtjlq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdjoioa.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grucxmus.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hfccwjpi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cnahhvpc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxurzbr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnahtvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dofljqvb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgbhilv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rysnfttn.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hqigqtwx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkxolvp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfljape.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dffrqisj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2querikox.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzzmism.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmosujm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2venyvyzd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lvltbcib.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2talzkgnl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2whzpxpet.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhdexcl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbspgncr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oijtthcl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yshfwyzf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skncklmq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdppfvj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yujvdgda.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwiaxrw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcubhym.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lesplpbz.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2igvfbdab.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2paubibjl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahunmhka.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqptrxt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jncrtgqs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nresunxg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lciqohfd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eookqfwi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edjlahoa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdhjfgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuaaujy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fzytfwhx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hefckqzq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkntvfm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tciwadce.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvzbkyc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2prjphdty.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2moqrehtv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqqriyq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duttwbsj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkeswus.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vozfmkoa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcmxpcn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbtxhrg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxplxe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2amdfycyn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2legfjyhe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjiwzpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdtqyh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vumggqxd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2suxrhcgl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpydiwx.html


<!-- 参考信息 -->