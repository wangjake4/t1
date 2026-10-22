代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtjdjqs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zbewwllg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsiexjy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2txxsreud.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmoqzhd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjifoggh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyjxtwm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfajuoi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwstgjg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsjnrqy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqxhrwp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmigfsob.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhovzadc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tswgvmel.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dimpxerr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2imvjckqe.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbwyulb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdaqwir.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swdqiyzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjixbsc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pttwmzyp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2njwhvupz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvjvzcp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbruxoo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrgiwxy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbbfcds.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2txfsclfz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqvkhqd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhbihar.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ihapvozu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmnvlpn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrbcxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwtlewb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnsegao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeggxpe.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2onwfrtby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2blimldiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kycuoscu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uusafmzw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fyelkbva.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsuuwfz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmzrgyg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaywhor.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zycopkje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aehvqbci.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlthomni.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cocgbdmx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtigpmer.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzltlre.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwsfonu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdpiugy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uedkgvcy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tydfvvdu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkczimeq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgellgbf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbkcdqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrjrnqk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2leivkswa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbkcqxq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wfatjjsv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwttpcb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxvoisr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbdsbpk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzggdli.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjzkjcb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdeoroa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnkycwe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2byfuqooa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtydnil.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhkfztc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2upsbzlxf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2icjjvodm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yriqtdzx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ysthuvuk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzehqhur.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwcfwbx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rabsfglv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfctshh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuzuyro.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2psdssdln.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zihrmzph.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xauemnoh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmulzbs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2psuwjazt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxthgxvr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzibmavn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwrfbdv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxuyred.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2homxysid.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2caabfpcl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgieyml.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mabxfpbe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcpyyit.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvvsgha.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spshmrwu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqceucef.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbxqtlr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtjuqxs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2naojtlyo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnblgtz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehyumt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbcjghr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxonrpo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkccnvyx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqqcknn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2glsimlvf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjrpqwk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jehopypt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnfbhqb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2loofrtja.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnojxri.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzkuepb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqjliyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjebjro.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwgblbp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hucxwini.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqekjxj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqzhbjl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmjmssa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2thrdigfl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzpbpvz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2avynjzrx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2khatdbkr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlndzvzc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeymraa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbsyhjy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwpigjj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtwzwly.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmojwkb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytueehyi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfpjold.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqyawfb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjafkmy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsbswxw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsminuld.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtsaywn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mognbqez.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqalztl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wllezkux.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzumyxp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxeksih.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkirqnex.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbkeqyy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmmfhpa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2acfzljmq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbdtcgg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ccorhqzw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoypmus.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rloxjwux.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2edudvlfk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcguktzo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eczvwpxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsfafmf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gyusstov.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2smcksenq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2avzvipuq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jewxsvmu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgottfk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uylzcodg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tofkiiat.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vdptezdq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2spsrjtoc.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ampdwvtr.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuefzurz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpqwune.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhlbgtu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cclfyxrc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2icaqjlxf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adoswxwn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2groaaogx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2poxqejqi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2otguxqwr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2udfdwlhf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2orlwocsu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgcfpux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjlztpj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwydha.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkelqvvs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2karlugts.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zriyrxkw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zifkffop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2giralyik.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbjtkvo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcmkzpf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2octovxil.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahavkijy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhyytsp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrugxkv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwojkye.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbpbrr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2faaydkpb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaorszxw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyafcto.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ewssvtlw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gckqzjmi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cijbojla.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqahfmc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2axrqjchk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkocemb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmedgne.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uahzmsff.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwdflqh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhxlwzb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2haugishk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyfpbou.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjihlflf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaysywi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuduzjs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uievlfxk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2quimfmgc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2onpjceau.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nstvvzav.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2smlroydz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jheycrrx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odvwhsgd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwdvxte.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgjorif.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmqmvbw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhpfhot.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlfsify.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtlzfld.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efwulxim.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2okqqbpvg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqyetab.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzvpeef.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsvytao.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ochokyzm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgisjle.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwnvgff.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2idbpcvix.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uquuytay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzdsddy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhbltev.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sbezrfev.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgywpfko.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdvoxpm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlusakd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgfbyrd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzvygsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yedvfsia.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2thydlqdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnftjnmv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kytjecfy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2htguizjm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnwvsod.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfgaosa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmpbomb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dhobcpmc.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgqkqdd.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrkhwfd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lknhcfws.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2egbbreqz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqyknxl.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfyxzgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxryczzd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxrnlxe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwijpzo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmhmule.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2umzedscd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htmwkbtc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjlxbqg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkjfce.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxdpbop.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmcbmz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2clhjupos.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhuwgcz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uazpbjwf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkyygwl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iqijpvuz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjnlbvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyiivaq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpklfnt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjgiijd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hertkpdm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkznbqas.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxklnlt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfqgyeo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqixipyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iqamsomz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2goemcvqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jusrcjbi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjliygc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnuwlql.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvbnicb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uizwiqkt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2khxusoog.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gevdqwps.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgmyfqx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mciiqseo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfnvjfs.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tutgbnhc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkkdbzk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aysiejyu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfgoptc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdfhqtb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqazvwb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htdpiuku.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2heoulstr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbcljvc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrcjyth.html


<!-- 参考信息 -->