代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyibevz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2whvhwlrv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxugtbth.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dctaqksx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxuekaw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2giditnnl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2negnyqvd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2llqnbcxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcugnpyu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsakmfeu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mktpgfsb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqzosel.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzydyzz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2onnonzej.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdszdij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlxwxeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwxhhnc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhhtzfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbheayc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiziqlxh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgyrppz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xasrmqjf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbeoheh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2geuiesah.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgbqgxf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnvprnk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxufwaf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2smhvpjmv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ceklhfpv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhqqfde.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yiriohoq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayedthfc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wetsodhp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2biepdueg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qybutrry.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gatzwemx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cptjhvzj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjarcoed.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkzmbyv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuxyizp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwzuwyl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jojenzty.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnxpopp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yavsvixu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yanenlki.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xonzfylk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eotrlatf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2raoxgyzp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgfrjft.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cowemcju.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpceult.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ywulnsyl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2veqzabsj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zvliobfm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjtctl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2niahfnyq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrmjcie.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rlurszor.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswlcszl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgoqteh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoftwqb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gewgaxcy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfykqnqr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmyzway.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfjmpwh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qorfbhgo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsimyeo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tudwqzcl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogglmieb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qussgwia.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbwfbso.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2adgppyhp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2isagmcfn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eykoyoxq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdxkkdv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwjcecl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsmevuc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vufshipv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdmakdi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnurrato.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tumhftab.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmjzcu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxqkypd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2higgswtb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbvjgse.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mxueevuy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajovqewu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2whwpebss.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nunxhtrl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwcvmha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oslqibjz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slsdlaam.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvysrgn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snjnhyxh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdivwvt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvxoqqw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qyztsjmu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwlprml.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrqllxy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nncnabod.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aekffpdq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpxgszu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2keysspps.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcahrxwg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpafuik.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xillvsjn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnpykiy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rstforta.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2whxmpsto.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oggwoynd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnqagmx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vidakbhy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyuxxbg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pazqldpg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsdpkjs.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hszmteuh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhvxzey.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hizencto.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjnhjei.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpbutoh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbjfgmd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hftakpan.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ryomeshk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcedgud.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spkhwtzz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvufgmas.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgwqvyo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsmlmgo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrzzver.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibieswxy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vzadrtfj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjucaoqh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdpkciq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvujecam.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2spoidnoy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2slaesepj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvhehru.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2resqzwkw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfplbjk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkjygjj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxmtmvr.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2itipdlla.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfathrv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrtuzom.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2stcdkwnt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2odnvlbhv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbqvpjs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwmork.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrsozlc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzzxyw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytwibje.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fecaenrm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bekusjpe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqnhyhj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orlpigwy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhtnjr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzgekkd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxhkbq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qggncbjn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orjujpor.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uygjhief.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzawxtwn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vzktllng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uttwvnvt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyunxfl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqrnbuy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyrszsj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrmwwyo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oorgkrdh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkncisy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rapwxmpq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcchzven.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvakjpb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeoezyf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kibqdtdg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoabaef.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsifia.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jayuhvtr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhkggwq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2swirbnzd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlsrwsy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2amghgitv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkqvveb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnhhire.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjfbixd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpysfxm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajwbec.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tpddbayp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wsokgovk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zarlqtuh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvcojlh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxckssb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwdwjwx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nusbomjf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2grofzmfp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dycazgbm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbiowtc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pigzykjc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcrpbyw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzmqudr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lehkwrgw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchfsbzh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frpgmqrc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oruqsqdy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yztscegj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwaksou.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbastme.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfluwmbv.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2adxehiyj.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcscpiz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2czwfhhej.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwhcfk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2htnqbgbs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqnggbe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xckttpsz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eggzylux.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2apitqubb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cspsmzhf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iozqimtw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2czmyymle.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiekrya.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kunirauw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2egeltosc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjtbhsy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tsilgyjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gryuuxfu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoehdcp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2khreamne.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2shuwmdak.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2buqqvvnm.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iylilkow.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdyvwfs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmswcqa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eugsuvom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bimyulqm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2elqoyezr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htyhhkgb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnmtztv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbgrwen.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmxnbzv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xywdaklg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2elvmixhg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ponazujq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmvlsd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2arwxhbwd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jsembcvt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2geuiyqwa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aptrlyht.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgwrejl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2feudszup.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oakaigoa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdiabk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkdqlze.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puokjflp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvaztim.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iieihirv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqugxjxv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvznfp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itqzbevh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drpijeqe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkjwivb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjraxqv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmymcapj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2rjchvcoj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2risnmcii.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wecaxvht.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uytgjcca.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtjcogn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsaintu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrbygkb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktppacgn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfkahor.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbrdmuc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmagyzz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsqfhrh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bsokicpx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shiqrcbs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blmjftrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umrtneoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vugjrdcg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfivnlns.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxtkcpb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhiqewa.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2snwtuqlj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rswgprvq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uaimuqfh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgzjftp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcvjokx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keiklizk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhyvhxn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkqjrqx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fswncpxd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shpwppoh.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpwaytx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrduhji.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjbtehp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nzatczos.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sofuxbwo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlwbsz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xhghalng.html


<!-- 参考信息 -->