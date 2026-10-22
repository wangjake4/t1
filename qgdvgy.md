代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkriguy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmgqfcu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mffftsmt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiwfhsv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkitbym.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsmfcsy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mboywbem.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxapgrh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2frjlvbce.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdafvvb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqewbeb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oujdxqiy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mflcdwez.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdirhrmn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbmvnza.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpoztxi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qevyobpw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvlqcgh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vblpiyuh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2anseqjtp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzwqbje.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2junwjrsi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxnbvxq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaygbyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yypadobn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpbxgbb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqrookr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbxqmyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gechsawx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsruzxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lacugzze.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2svmyhilc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbvkszt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvinxoxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jyktxetr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjvgog.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwoeyme.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaqlrqb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocopiflp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgqzckw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2thqwgxwb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzbmkwg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmqcmca.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2awlgcbcc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yffohzog.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2txnslfrw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhircia.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjfvlar.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2psurekfx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnddncj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjitgso.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwaidko.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lljyodzd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2epdpswls.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyxpemn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2reaxwwag.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthasaet.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2efleyajb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrbavuz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfcmyxw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ejycsyuk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnahxvr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hdylfmuz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2drfqfexg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ystaaekg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bresdoih.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbxnheh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrgsjay.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyoruhg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnesoen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mshgxtef.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lhykhqyo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwjdfhz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2etadhnqd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iolpanhm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqtxcye.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdnywar.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhmttmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qryyoskj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2biacxlor.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmngwfgr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2siintaje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2skaqhzde.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qhueahem.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrbxsok.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gwciveug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnmeoqp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxypttw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qicamoku.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lexugkdx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvugtbdu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbfaujn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmxfjne.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aipjgtkq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvozzwv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eychripe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aguhvoea.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyooxxf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mynapvae.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbqszgu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfexguz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpfabvs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiycshzq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaxelvn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2armcqdwo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgssknod.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsahscbs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tpicejhl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgfyyfy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jreqiiht.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tycqbooo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qxisecpx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2renfbjre.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjwhexe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkugqmt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqitloq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgpppoh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpetudb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuvphtb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmymfnns.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2avjftgyj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pepquesq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qafmsyry.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2obvjvejv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvenhyom.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2auilqbvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjnremv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdawomzb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlcioas.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hqepwbah.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rolljdbj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2clhtikvm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdqpcqv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2syvuyybr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtlbkyw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbmdwqh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlseznrx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2flauhkoa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ompsdfrk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrripwk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pvllkyhj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeuyjiy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhmnyol.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnadfzr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rittjxzo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqojrl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvdaatu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsltghe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dakiobok.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qftzgxus.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fshrhach.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyauapj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oanywbzx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2idbzzydn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vueiwulb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkmjeaj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdyoojj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2htvvciqp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kunrixis.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpbkloh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvhcyic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcixmwxd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxtyvrx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqffueb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlpcbux.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xjybfvrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yosjkwnj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wntiqzqb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flzoibub.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpnpaqa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjvgllp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiedriy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpybmvu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dryysdgt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxwloya.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdjwgda.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrruzwii.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pemdoabp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrxakyt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidmtbum.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfabxti.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcjlipr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tibrktgx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahowqwix.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbaufjz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyiiihf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2neajhkay.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxqezvk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypzpcec.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zapishfn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqdcbew.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2clwvmuka.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqhghr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xodydeei.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzijxcv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmzfccc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmemkzw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyskjhq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtszdgk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lafwaatk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eudtondd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwnppgz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdsecup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeefoag.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkpcgpr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2adxjezmj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2omgslzdb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jaroksno.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfcqqce.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2msvqcubm.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxbkdwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxpwfnz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pasulelx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yddzmkxx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2azsxlmri.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vitkrllh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aznayrqz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgwdopt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2raidmxcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oppxndss.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kykjabue.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpprmcy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2raguprei.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjzqpgn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2unhxtsxc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2awvzlckz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiibdaqf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjinltn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjhpajf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnustsv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bscbrvnt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkmscxi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2seagvwzp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2asovavci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmpywmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofstjhiz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2higrofla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdvdfbi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fotwqpul.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2viicpkeg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxyokgn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpmmokq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wguswziy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orjedofh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjitllg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvarjmt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2deaokjgo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxldwqph.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmkdsgr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwdvcqr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdcwqvr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asclaeis.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqspfsi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xobkqofy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kccqmzyj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyedcgt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwyzlce.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkptipr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zufretnd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwpplzu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wdygxiia.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvztxuz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2onninsfg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwizphy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yglkaouf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnitqcm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swuuykyl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcpudqi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgwrcbn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2latnhdhj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whnsflqv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjptefq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbhxpd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2turravwo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkkkejh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nczadfij.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sopqziah.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fbchotsn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vcosatyt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgpqvuv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcobasji.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozssndwq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvnrel.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqebpqv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzdpsqv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjwfoln.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2idjpkoof.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwutthjz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxbmipt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrjftqy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yljmxvdd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoskloc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhuwwls.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kglrueuv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdthdvs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxmmeqp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2byvoegsn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2laviijql.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2facgxptq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anjfeyvg.html


<!-- 参考信息 -->