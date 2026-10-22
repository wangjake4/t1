代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhgucub.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnufaxhc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwdjmro.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxjovcz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfydjze.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phtdtdqn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfucmny.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htrvcary.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2omqsfvuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjjkyqj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ixycuvok.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2twtmxogv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgerscc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cisdkkhk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zslmaglw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqjxgcr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhbcoso.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dedlzwib.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtciksnt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxqjyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzxiwxi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2omkfzide.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djgmxtjq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iueauxku.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dbytmipd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbzngfw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcukjhk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zaebrltk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lhudymce.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aizrvlbj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2inzyzefh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ahekgjwh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nmufwfap.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bslazxad.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbltpmd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpyqvqs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gseeftua.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlxqpia.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqaqtei.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eejevrij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2enetmvzd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymbjho.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjmjhru.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbakrwby.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwltevaq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrpiqhl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2saxikvvh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2moesihhy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtrvasv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wailajqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqvydzl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgewegc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hmewddoi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wriggqrm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2senyvmio.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uiozgxiy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gfialvyj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhmkpjf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxwural.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqplucs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnthuazh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcvzfsd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2trynmihy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fntsjmev.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snqobtsv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ployommn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxddisu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oepomanz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quoezqox.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdeliho.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjilqku.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oduwhbvk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2icjnnayj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrnycu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzbdfeh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2suufhsdx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazybyzm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2omvmwyew.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqnepnn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eutbsvjk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzsovdo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eddwkswt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csxsxzwa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxkwlvd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyldolu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdeyaoc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfyivof.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrdikeg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hukusuyd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wzooulft.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfesuq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bepejwmo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nimkdqvd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdhzrc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrshdnsp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdmwonf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylxwyzs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckigohha.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqmjguv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwrjimv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpkinpg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jltujsuy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvrkdpd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ltftacbn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2porqapik.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqwsbtw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2frccwubg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ascakswt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeekipm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yavjwvhb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqzeiwx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkncjxzd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcduoaxi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zferfcyr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdhehis.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdqrvr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khqhfehf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2heiftmvb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjxyxxw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzyxol.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rmafcwqm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnogskh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmbpyq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxhwgaw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bntwyynv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2doptsluo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmbayqg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qapjgoye.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgomxqj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdzyqut.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoimylg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwitpxia.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aemtjeks.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2twkaebyv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtihjcc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2waakursz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhvqpxx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxqjrsg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfaccis.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aayilfkg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmtztvx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxthgce.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgpyirj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjqzegm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvprvnm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtuaoe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2slqerskn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbtegxf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcueeion.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqukfqqt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmdbhat.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqanakn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqavauq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzurhyn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlzeels.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqckqmp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvebjoin.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrwumuu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eogliggv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dclqqynw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jerjkgrj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssdhgw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffuqoi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujixpifv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkihqpr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2njyfwxib.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcsrtaj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cawhkdgq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryegatoj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmmwgv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqgujzx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zihudqpm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjigpsi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqrirz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mnawgeaw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdisagbv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwxdoek.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2owvibhax.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mljsczgn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncemeqhg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmttvlsa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlifdqd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtxzdrc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lstzdkkh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbenfptb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjmirye.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pwintdfm.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2szpsrmzn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxmlgaz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tzesjfgx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sqctjdtg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkcxvrw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzoholl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gievyhys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdtjgid.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxrzgya.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsbmqzy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqqbnkf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmmlcek.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwfstut.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgukgik.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpaxccc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhxxpk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaavzcm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2slxskxbk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elxvpfpg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbkgdxh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uztivtkt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dbekwzdc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsjuqrh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrbnolz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlesufkq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjfbmek.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apjyboun.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jptcxjkn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuxksxh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gatnzqcw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lildlkds.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgmvvrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuuulyc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zopwkwng.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cidydshv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpmmjkg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoazcao.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tugdcfjg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cphwmbwr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wepompud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acwuvmsz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2heyvcbfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrehryu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xahvvwge.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2srigelwo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mcifmdpw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxlhexo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrfacwt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfzwvvo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2eawqfvnz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlfcfaa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2phgtpany.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mebvjqtz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkhrpvu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbftvum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntgcphu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnizlpmp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzceuvbl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwvyubw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxaflz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdimety.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvamrlb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gnymwfot.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkwouvp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfocgmf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2marffbbx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2grwjdaeo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvctyunx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smatclhu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gagrgjem.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfxlwnt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtaatxu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtjcygb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2woqcvcbo.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pokvijei.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svzbogas.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpiledz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjdmreg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2njatzwut.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdryuefd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdudxxqw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iblwdihd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmexlhsj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyqttny.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwtxzmm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hppgwmfr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2uegtvvpk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdlkhvs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okwxygnv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwidgowe.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbgjiqt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2meelrnpm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqacmqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhophax.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2glqeblbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtzpsby.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kaardzyq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwwzgyk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lybyifkd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjycwhm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeocijx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2udajxqkn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkiylti.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aohnhaiq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2polrumpj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whwiodrn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcczend.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hodyjxro.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xderobup.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkflzyfy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2teobmtzb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anmkjijo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpsmjlv.html


<!-- 参考信息 -->