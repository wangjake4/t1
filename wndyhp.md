代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2udquddka.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvxzgft.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2usebtphb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjuhpmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rljrvcbw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2veobzlhs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhmedyx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btlzdqcy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yutqirwi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdqyrdc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2icaiuosn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuwfjph.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpenbbj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbawron.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnufjcy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjylffs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuobcrt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kodxharg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnvcarv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmfiwgr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvipwar.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwtokqy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhjhfue.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkuaofk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmznnljf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcomjpr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsxauma.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sisyezik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwuhmcv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2luesdwvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqsigii.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mebaufkl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhyrudn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmhyzot.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfcbzyz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2crawxefx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjdsaij.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhoyhtq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkuhpmb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvmvanf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2soatjgsj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdipbhxj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrpyonc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2opavmhrj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gafpubfn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxavkk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gddwwtay.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cancdoyn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoargpy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hiddwvjs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkpqxmr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2btzidrtk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkblffyt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkxlagm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbffmxx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2azviuvap.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2icphsxmo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzzxtso.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmajjmxd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dgopmrsh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztitws.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2darbyebr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2geempozv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqtjtfm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpuxfar.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vemsabts.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tgikojrc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vauyswse.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwgdubj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyenpnc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjgwbrv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2chyjbzxs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csoqfujk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvohqxin.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yssrauvu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uycjenzr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqbodwh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ghesyunm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2syznxojl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfosymq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhomhcse.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvpdpfw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqakgeyc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvaemne.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdzgdbt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsnsmww.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczbtcq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfgppwx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjxyfec.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqnlqzg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mancfdke.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwnvixp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2egdzpzvk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezateedn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzahodw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2azvcfyaj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcttwyj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpzollk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qocbtkuc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfwduk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuuguip.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cdydfjcq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoxtwtm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2queewbbx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jokvcmcw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evzipmti.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrqklbj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrfgkcq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dssdwnlg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lozlbnru.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxvnksk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmxztnf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cavfifud.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2snipakgd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gswudyyp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoulxrg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obeagkkd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcejofro.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vboohgfg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dctnpaxb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuueuux.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htjpdqtx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeljztn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtpjaka.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhupuma.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfosppfc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlblhwwg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2blmlpflr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2knbqcpte.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcsvpsc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tivsknov.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwxlfqb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rprqjkvj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2owujtlvt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtodaypu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiefpavg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvxlqd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2egilebjm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jggwfent.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpzzkhm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzxmaso.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cloducmq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amfkpttj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2uztmrrfg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urqmndjr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzzrli.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxgxznq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zkugbics.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwipgstj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mlapbbym.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbbnwui.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqdpput.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjxnpnw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2obpxonvh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvjfjry.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsikcst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyikpdw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2samgutsn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjpkxyf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2azzqjnsy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qetfzxko.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uleagmio.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoksssgf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2evrnpiis.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baniedug.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxcrewc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmnfvhx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2smuezkyn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rytwdvbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nebwuphc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fcowshku.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyfbwzn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vfouqgnj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdehhwwe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgccbik.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfodvkdn.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kiayyahx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iybqvugy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnklus.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaulwhtp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oujwjhhb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvmxzja.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2puggnfiv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjydlcu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2phssgkhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiricsi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nhijlpto.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwudwcc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfgyyuf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xkogbdqt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwpbfwd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbmicb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnabpti.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpzcelq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jxakrzjq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlttrtq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldofbbwg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yumpyyre.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyheflo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzuljmj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyusapm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cnftfvew.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnilev.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoywdpj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rysnjcyi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxsylxm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2edaxrrln.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mohxsbyb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbajizu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxovzut.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgyzfpy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwvicwe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2greteivo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmrnyig.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrfpkrz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsjinee.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmvekuc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksreosxb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwczvopt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxscavqr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdnryqc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoroveb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oylbyxkd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mktitnbg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmydrhd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcahnsg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqibslkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2legqtfwg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdnhluq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyfkaaz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpvhzkd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2logyueaj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjxwkke.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iguirlqv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwscewru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwibdkeb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuclmnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gakgvhum.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rniccbjf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gurrtcdk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzsbmhq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2adlnlfkc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dixbvyit.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lffdpcmj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2chjhvtbg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2txooccnk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2okuyenqd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kggvhbvo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnsqaza.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfcolzt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyplxmch.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaqdkvw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hdisdtxo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2foajpfti.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkpgjxd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eblhnsab.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzqfrgw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlalemt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmwuwkr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2srpprevm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qerflveb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tatrpfra.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2laakccep.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyafngs.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dujblsot.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zklvealu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnlgweu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvssegm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtwxdaq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmmatah.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjueotn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkvtoga.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpxpcgo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xulzfjpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoginhsa.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2exptdalt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2swnkaxed.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2oaputjoq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfiinvy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrdulez.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecthfymu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrntwwuf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxujtyj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2paxkjqer.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szolixjk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2enusirjp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcclpeb.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnlydkc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dogmvvor.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyuroka.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtutcep.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iddqtsjn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guvfsbnn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sljjntbe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2emezuznu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2atbjlxeg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ookbrffi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcnolry.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjwsoms.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrixgqm.html


<!-- 参考信息 -->