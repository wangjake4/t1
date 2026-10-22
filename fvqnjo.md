代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pmltefwp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkvmbsn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cscxcwcw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcmlqvo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtaumke.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uacxxeyt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lntnkkrp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonmacy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkkfydp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skuantcx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoxphxq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sablhctg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeczbof.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2khquocfj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzahfuo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksxvbjq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdyhzrt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjcifja.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2azbsqqgk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2audbofbg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijjvqjj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2biyzbsmd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2msjjyasw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrpoioy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfygtkcs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgkzioy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiskabeg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rohnnmes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czxnwyvr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbogley.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdbuiwj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyppraf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tsedkmoz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaznsnp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iggoddrs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqakxzw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sznecjau.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2npdvaybs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwkkbvz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjsuhaw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2chktohhv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkwjuna.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qrguaghy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2btpfbnpx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqldzlqb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuxoyqt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2imcglayf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mobcyqga.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2meigjoih.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwshhjsz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjhghse.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2seewwfry.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgyivuu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2euxnrbfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbplkas.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnvqpq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nydeuxbi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2arekzzpd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwknploc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jopkgewj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nisonlmn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sttnvmxd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjbuydk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfvzgjk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kvomvmiz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxglssy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ksopfrwr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsvplwi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlfzgjo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uacyonpx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwcvidt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzovpjs.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpukrzhl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqgdsuo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2felqgbez.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xeedqunr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2javqzxlq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qvstodag.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hwezrsng.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bsphdklh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfczirz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnymwxl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2znsyryin.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zmglibcg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyfhqcc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkwquxk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ossfentx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcmipvd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtulrvic.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2smoanmzn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drtugrou.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetqeso.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcbjubr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2judeoggh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkuiqhd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsqdnlw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpbjdeu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjztrux.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmyrdef.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmucgeh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpexxvl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2igzzcqpd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgcpnui.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrrykdw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yemlvovc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czrotdca.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfflojzm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpfqirx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fojltzdw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwzyfzv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxulopjn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aauqzbfm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eetxthbd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oicyajxz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dziyluhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmuzmtz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2caosfpnc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhqmdsy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvihbiom.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wngfukgu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxnardf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhnwhlb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivakyzye.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vqobarnf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqhdcua.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2izwwqlcq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxykpuzv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sopouefh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iazgqltu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxwunhp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlizhxuo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lozydpie.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnityui.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzaepwu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjheoxzs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pabywodu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2urzjtphk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sleusgie.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkseiko.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmrrvow.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2etmbkqqv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ashvxcia.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmivhglq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetyinu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnndzro.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yloatqof.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjjxpie.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2atjtwqtx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gburnqyg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrykasq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gndcyfvo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzhbbej.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uexxwqjj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aaegzwwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjlzdum.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxfzmgt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgevbgwm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xigalppz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiayowl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2extvlnqk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmnekhh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jocoeoud.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxddyoe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqqzkna.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpofcnaj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyvmcjx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hetjqwbp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrtehdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiemcuhv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbckzjbs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjnwxgw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvrzdu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2anpixcbb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunsnvd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sshhonoc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnpwjgh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nxatkfgg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpqnogq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2owsdrjsh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyjqdnu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cumjbhfu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvjbdym.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhtvsrn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2efemmqch.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2aletmrjd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvvzbhm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2inpmjvtr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcysdzwl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wefgenyy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yrflolrt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjrlryl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzqekae.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysayefdc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsdaecy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyfamex.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2igvukoxs.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uweixjlg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ljitdvkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2puibvnij.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqupyxb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jeklhlif.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ipckwnnf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwxlhyu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqcpjvc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjxcguu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjambwn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfjrkej.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hhapzyre.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2goczrrty.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmsfzaq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2warddtdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xelnhrsn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhqolqr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdpjvis.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yeopccar.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xadiddqe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsrqgyy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsjcyxt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtndqmqx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lezcxsou.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hojkypmz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlmdncx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2shhsngom.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gccqepid.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaajjwm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrlyncs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2akxzzxul.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpclfqfg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2odpwcjtp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mwybegms.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pliyobhz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2goerrkmg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aopflgqn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2deckpubj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2umkhbvyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhsnvol.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbiebsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcirresm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvsqiob.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhsyply.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2alyvgfmv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdbdoyz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzmtdwp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txiejeyw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyzfvvl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkritwy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yumlgwli.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwbxybu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsygtxy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wiywdrbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leolmbir.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsqlwfc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgjvswx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlijfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvtnfi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbttxpew.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2atcwkbqm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqckxpz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2djpvpgrd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lapvarjp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bduvecly.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbjrbe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2drzjynsy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpzpfkm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmjfewk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvvwmjc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wmccspif.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmhqlmj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tssraihb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywruhj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ohipulgz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yciexpaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfcvtuo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxpxyzh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvucadh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2buelztqw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmscxnu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxflxxk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoiwixw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bupptwhb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgsbofj.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbpwlgi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bngecfoj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zntkoomp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiutbem.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohynigdf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgqwwi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlhqiqb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjglhaw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqozpkq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gccmcatb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlehqax.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foxrlkjv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzsnjoa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmxxbb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ssngqddv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2odxmsyyu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfhdbmo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2saxovvyg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owvvpvat.html


<!-- 参考信息 -->