代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wayskebt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtymdtrd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnqhvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqesoeso.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyxdvgb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxljvqna.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tvanbnjg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvwitem.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbabzyvd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbrsgcp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ixohmrdz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktynyisr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2totwnqta.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiyjanu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2shxffqeh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeefokf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jflckscc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlkikfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxeheaq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbphsuhi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2osshylhs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhldxec.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugozatbu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkoygsu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xodwgkwd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyfvurt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwwecqb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpqvkrv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vhupmrfu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnouzysk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkdjcp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqcwnhf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlcrmor.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eirrwkdt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbignzm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttedwn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2poyfjxcd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2voifslct.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuatztj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwrplpn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiixrxb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajviqvpy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfpsdqp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwgyfes.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvbyrpo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfswoke.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyshodzp.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuayfew.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxjstmr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvougen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxfviqn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgqonxl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zonbwsft.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwxfyou.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlqhyal.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsrjsbp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2plqimwmc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rweqrkyy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2iesaboxz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnfasyq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqgqcxg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmilykkn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtglklwz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpufsut.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzsfoid.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyabnfi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2exrwbawo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gddluzln.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2onlsybpe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvpipsg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkwgfxq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urrfnmfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvbqrej.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkioyuzd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzstpwhy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxbotgh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtaxsth.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzfenk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwfifry.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tyolleeg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eizogwfv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzwqmjc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzugkey.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuwrrvo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmegqeap.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbykpbl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzuqxzz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uooemhfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvreipmo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsiuaim.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjatyebv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lemnaljt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaxbmpx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvckyymi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twiieqes.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnighud.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqfgoph.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gagfdark.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dsblmhmq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2czacmiqb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ahinxhcl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alpyfuim.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2burlvbqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agjmudic.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtxnzwa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nixbuzfj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuvtups.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoowngwn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhomuafl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddsexzk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdobntuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhwylka.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxficas.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpexrlu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqiwgxb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllvbsk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hidtyfkr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcdkhot.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2octqfdeq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ongftjbc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2iqseguqf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2muoehzzf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2thavxnpy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvtdjvj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xljgwsmo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvjtesv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxucugp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxqdntt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bakoleqz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlzagml.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njhlkrct.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbqufur.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eephdfzh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehlwrhz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2avzwfwon.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfbllct.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqedbkew.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hwntiijc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhocuchv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmsqeuo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkfdwph.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kzovsncp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyltdkrb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbgzsqx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jetbmjfm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzwjymf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2momzjuot.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcukdlpy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqnoplw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmlnzdw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2auyarxlh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpleaiy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykkdprx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xojftgqd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdmdsyd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uaizrckw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadmlkse.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbtxizv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqqrypz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfawelb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgcnfxx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyuxhtt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvoejbm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dthbscgw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmjlmwj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jsffnqqo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlsetir.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2apibdqfm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaxhzsl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtqvzai.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwabvjm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtcziet.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuyfhqt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxrdnkk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2doabjjeo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpsdjbg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbsrnng.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgvrwsr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2azpmeumt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2onwsfzol.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjlqyoj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyblnpw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqjerws.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2egjbpfhg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nirgwvyw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsozdis.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdluzqh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gtctwbhu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2swgbihmg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnkqdeg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutchtsp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdwjbks.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2abewhfeo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktipcefj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvdtosp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mybjiuul.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtccpfxa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgiouec.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2csfwobxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vgldcfog.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttyehy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2heuhhdcj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxehcuqd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfqskaw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kicgnmwo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyryqml.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpvtwjd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vujmftbe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmkvmve.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2maagxwkz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2odjqywje.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2feggawii.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkxgrth.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fpocojpx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxokcrvm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbfraki.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjzxwld.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oydhbdat.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tngmgqcg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zcatypxa.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwcxrfw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbttucy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoemcwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gazmzlvw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2adnqcjon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udfiksnw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jiewvhmh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpwxywo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2acimxrnf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rklqiwha.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoqneoi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzqzpvt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpetjfo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmjpqen.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vckdjeqx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2inlvyltn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2neskqwgw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcllle.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxllobs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atuiowbd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uscvmjis.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sektvpxz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkzboym.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmnyfoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtpmyhz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjqshtf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfaqggs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lomnszxw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ohypcvyi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzwgqxb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdbvwbc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2arxzzeis.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2olvhwvvu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzceyyk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjijjqcc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oiumpmvo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmhsgft.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgpdtpa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpoovkv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjturci.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqfguno.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwkgfjj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zekojhxj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbdyrex.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrnnxqk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpozidh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2witpnqvz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rspcywsk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvhleyq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmpwxss.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idliuphb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2arqsmewk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uutuinsb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcxjwzr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxqcjiy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcquhaz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaudgfv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpxlzpt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vopcfsjy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pppwekvp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdnkrnk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2orzpoprs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwvzmut.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2stxsobhd.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxdqfhf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bijijetl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eywyuwzc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbrtjev.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vslgrhrh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kudvguye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmrhurv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vswnieju.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iektwkib.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtgdmix.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueatgbhg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ptydcerp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpeenm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrcjslo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gxipbdit.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkilasy.html


<!-- 参考信息 -->