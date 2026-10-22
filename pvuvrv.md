代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucguzetn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrbufvi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jneisqpm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2duiofowr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiiqrxj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgyiriy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqevszn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2besjhszd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwdgqdn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvpegrp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwqgsey.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtadcqr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhmomwf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyostwg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wfderxjv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoveldt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqmuoxx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwrnphp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoswdrc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tddpzima.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lixnghzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2inqvoilf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrsvpfz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2agybbrpq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifcofqc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpnmkvh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyazzna.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzihkzz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwfdfwe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xttyxaac.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2adgvodir.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2goghuvuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdvphia.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzoqzoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ceojdbyf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewglpzhk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vplcfegf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkxkrgu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2trmdlyod.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzzoyvo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2oblwlsgo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2faqycwdu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqlanrl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2glapqtqk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpyiqfi.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqupowy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiatjya.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdokavnz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2restotge.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyoakjz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qujircls.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cncwuqti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2huxiyvsi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpuosba.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoxsyby.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdllvul.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsfgdft.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2njrxapmu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdrswgm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oofyiqpt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bivzwigj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyefsay.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelousdr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzanfmg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uizuvaob.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wcisbwej.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxufmm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmchxcw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwhbpii.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmvtulm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjafgme.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmzsddj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiutlfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2shpgspjt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkenjxrr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dykyycim.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snsxkrny.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmkguik.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpixmxbp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnybexu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjcoawj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpqifxd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbbrwvs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2psdltiac.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbemjobs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhxmlhq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2axzftzkt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2texrxdei.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsrmvdi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeuibrk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkvayil.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqjjjbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkvedfv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xteufeet.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmopdzrb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oylopaxl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2axjpllhd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwtkgxy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbiennc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzhuazv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hufxfunh.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2phuvbcby.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2devscflq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zelnulsi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjefcxjn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkynhbk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdbkdq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdffufw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjokwyfy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrymmknu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsqeefd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuvbcvd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaceqwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfhdhll.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzzlipl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2muhirduu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2imwekqyy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpospcyf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoanzuc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aowwsodl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhxlqad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2izbkohdb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uauyxsls.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrjgzxw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uowoufwn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvuqcjx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhiepll.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrvsklw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gikeuqbp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdzlhln.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvypkjip.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acnkssqu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sfemfdfd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvopdu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdmcjfc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjnrgte.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbnrcl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfvyfhu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdmdnkz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuzfydj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxypdf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgetxpka.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxhpkof.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhqytva.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2huwvmdgj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuzaqup.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sroxwsxs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlkdzls.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxztwox.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmhkila.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mahwmrqd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnvjdur.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2viwjydsj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrpbaqp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzwthkn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2habetysi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yraqxnmx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wocawhbd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2afwgszgu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2phduapca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fspelicu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2djtvqfta.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2emppqdcf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2otggoeyp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvranfap.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2maxycdog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybgwcex.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmuigaz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbfizzt.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvdzvms.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vktojwta.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvinpdb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvhafkn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gywsyrmk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrkclgj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtknmam.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfzdugk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmgqmly.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gezpbdyk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2twrotdou.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rubswltg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nnowlzhh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcxogsc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprwexix.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmoiqug.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zntnjkwh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfazlmo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wueptbyx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vfypmelb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yegxhrwa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnydmoe.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdnwxoh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwaxxro.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnexwgl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeauxpx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvqaxjj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trjheuax.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjizpav.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yvydriuf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xqujrnod.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzfukid.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhamshv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpjglsy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2epwwioph.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbmhvcm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ientbfww.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kewuvvwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoatwdp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwnmorr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgfjgzh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2saepzsxj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2knzxzxto.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2flnxnphq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2drjmoskh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2udrygquz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyfqlka.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkinwup.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhbiwjk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcsorxm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uggnsrol.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tybsigzx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhcpqwo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjbhrli.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvzgdns.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdvqcvn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2casqnywk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2idltjblv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjovvts.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2grjsiasl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyixixf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfchxsl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzllutp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sypsczqd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqadhaoz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cszftnex.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2smudufxi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2enhnxyob.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzpzucn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbukbjwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbafrx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lczkxvbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdhwykk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxrtsgv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dkltubbg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2amydqctd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtpluol.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2obqrqmnk.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2knzusird.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2evmiipzu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdullfyt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2seatxezq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgnpvlw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmrpsbz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2blxeeysb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scgyygyj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnranck.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhfqgf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpwajui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbhkmlm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuvuglx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oppmwrih.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lntieqdq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsfvgka.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxdxkvj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzanzhm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2obdaumza.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2azziojyb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvvjssg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgputhp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzbgqpz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wagseyxq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvpnpyk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brrhyuey.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jpredcrj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfohijf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqvolaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiwozuy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfzjmck.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxhqjy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fknuxxpc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emyjrazb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nraheqdo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzabadj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfeejyq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2enthrnas.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjrfpn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lakliqlo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pkosuexr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjestlx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdfykyc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgbuvxa.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxvhjyg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzuirj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvygxrft.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvowath.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2edvqfjls.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzffwcmr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaengmp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeuoers.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnxzdro.html


<!-- 参考信息 -->