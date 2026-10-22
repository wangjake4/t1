代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2aufgwxqj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlrneyb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvrzaqv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cuswfgrx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2prupvoqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwvzfie.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2speftuqh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujicatze.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmpilhu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2itzogvlv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkirplv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmspxtu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiissbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvnjqyg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsweldb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffunoihh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyilqubi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvutdxw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2baauvbio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nfewnrjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czlsnvrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oavlnyrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjfbztd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjakoco.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbshfij.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uammsuyr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdunfpez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvcloli.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ybktmxvf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfsjcqf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvmwuvv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wckvlutw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnuizlo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2irshagat.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cftcykpq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndvtzyc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2getuekix.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbijssx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqyasrj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqatqzey.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ingnaqmj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhlakoz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfjrjxq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2warfomzu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pndmnime.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2esiwcjni.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gljhvqzf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeuwrch.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymngwvf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrcswsw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzguxqm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzsjdep.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dukrnnmv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2occotdpr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wadisvum.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2obyjwduk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjkdjbs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xteqhvaw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwmvxof.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mynogtkt.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wuataggy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sebddbiw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmddluno.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yllhzqdc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrqyhfc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcyrotw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqugrbpb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpfeeji.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujifnus.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvembdh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxcfbq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwmquwe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwfltoq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnapdcw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkjzmdj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2anvuyujc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2akrmkgpg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbktdcqp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjchodf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrrhczs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hylcxzjj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzsyvtf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsakeoc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tinuneyl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fztehhfc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cngwmtgg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wffgkqzd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgqmdc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wajbtujg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2icdzbpfj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fanamwyw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zimzxyxr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuobbjcq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwjvcki.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2chpoagcd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnumrbh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnxbunf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxsiyoj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2czxpwgdv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2girxclqf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeucouh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrqguwn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuxdtqo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sktadtgt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aywkarob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qptqedth.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvbenxx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qujgtuth.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gonwjlsq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfryneiv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgklxvw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzwobbb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jehjlijw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpxcjjn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoemhbm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wumqgfyi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqcaixy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2acvawepm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvlcmgx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aualpgbw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oswcncdn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcjvjsb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoityfha.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvccrtx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2thvoqzmx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oejyntch.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqppozgo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sndqlbte.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdssuobl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgybogln.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2decwmhvh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtewmed.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bilxzets.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2asliznyc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaziicy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqinjyq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhfezop.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbjdhnc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dquvyupt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aygxncer.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmysqbp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdrcuze.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeyxexo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2coolnzym.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oauwcddw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxwyhc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrepiyi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcosowb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sioikvaq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwevjmq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nidygfur.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmutlii.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvalthog.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlrlydr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rspdzwnt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusjjqk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2asbiipco.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzyvipz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgzfcqd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2taqeuxpf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbarjpp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcuzvxn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxjxxdh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsbspeo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qllljwlt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjknuzxi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jorqvhqf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxnfzjr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcknwlzr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgkctft.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjgudug.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdgbotl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hvptqhem.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdgxjai.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcqmigm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2htulexok.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2altbkfoh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yohlucxp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uurvnjzc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrlbjxt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkvslto.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjysxrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoowmbt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2avvfaxbt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nroxwbda.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcmqxxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pruesyfp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jedbnunu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxajvdmm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwzjske.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2njfvuuge.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pidfauzn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfuecds.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkrtxsx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2otclxatx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2woorqhzn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzrzzdm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqbmidm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ramvfega.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2trdqwtao.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrikzdi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iiavgtnz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwhokma.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxuoeu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2krtysqzv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbmrruk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtttgpoo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2otjyzbju.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hwanjauz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgocyxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fiicpdgn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eortjpvt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlpibpz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snycdfjk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsbbgf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmftwsto.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfmavwr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjrsqlu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbyifzh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fifnrqnt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvwxqz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxibmowj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjzktzj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2deaoacuw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuyduyt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmnnslu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pocrtdbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjexxxt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzclpqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxebemd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2echsujkh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2arcudyud.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zeckirik.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaejiuc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqzblbm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcvyicg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvuldpa.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjsfuij.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnnatww.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlopfg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oktfuqhg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rdajefvi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umvvtfug.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnazrxg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxczkji.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhjyqft.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsaiydg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2glillrnt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsabdbd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmriuwgi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2himmyfrd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqjkulk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyyuoei.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfjcaoo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtddiqgy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2otelpimq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlpsgaz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnxqqll.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhmielg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpjgdft.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jwggdsef.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cimrrwwi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrjumrc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfhtueo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eewyeelz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhkkjgs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bnemqncx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwgipsr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvossg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2niumtirn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2voydfdpz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2smctxzex.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjiaown.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvlapvv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prtuahsq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzujitj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxntrodr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvnydna.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bivfvjnm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glvptpun.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vkihulki.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwiagvy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbfclkj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vyumbhdi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxgsubv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsrqpej.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bckrhqlm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bojfxupi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gidigppx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2esqrpqzc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vmefvpnh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hknjwguu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvasvb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfboerg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzadlvvo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2klvdndmv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyilrlx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2prummkvr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcogruh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lghioksc.html


<!-- 参考信息 -->