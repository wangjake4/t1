代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfabeqiq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2idreykeq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhaycfp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhqtire.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntumixrx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaynpqc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmyemgw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hfascxmf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcweusso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoygshs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyazhnm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjrdoy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kipllssn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrdlgmd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqkaesp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ulazqwrt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ppliaiqm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkomwao.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsknceq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cijonuga.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpzojgp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlowmya.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2voculiqi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmprjtzs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlnkfek.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbxanzr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2renvippt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnevilwn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jdktjvss.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjpjciy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmdogwg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqdlpay.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqznxwsh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mleqhllx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2txhkbojq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiapyom.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkgjvkx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmkepab.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxbajpd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmgrqcn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vvraastl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbukldy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fxccvelf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2baofhifr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbexase.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzsmutn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2evoxzaua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxypmtph.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2akqlqsws.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjfnlgm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvdywsh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxgkmfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxdtjix.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwnmlym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzdffft.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqjoabi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhuaupv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkdvhu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmstzid.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyshblj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqkwdqf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpwetmh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bketwfri.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhsqwoj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hulxhqel.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2imvuxeho.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2togtfdtq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxgyyik.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpdcueh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmydxfk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvvmwia.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slwsvlrc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2snhekuzu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdssesil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefcfxqq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivixnodb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdowaarh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoqwxhn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsvrvuq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzlscnp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iptdhdim.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2szgwxesf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lntheone.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvzmgis.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zywqdibc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwjrala.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmkpxtb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnmoadg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2obouzpwz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pacuejnh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjcmoae.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqzmxcx.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwksdrqh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdocwco.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzdkzqm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cynhydco.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzohkqb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2feyuwmzn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pltozlmx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crtiohza.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fplwwwdf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hvopsivu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhzyxcw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgwsyz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vplftasq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uuollusn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfbmpcv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jflyhnqq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2otnsdtej.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpvjapu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bephetqz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsxmtvu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkltgyab.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2osojnauv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2copqfpsv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrrbunl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuhnrlu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuotrhht.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfigmvu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsejirrh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsgehni.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzvgubo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsasjoz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uilydcre.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjltxsj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pswyuxdg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2odgxznaz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvimrfc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnezfibn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbykoxx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhtcvxn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpnabfw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2spaquiep.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dszjskat.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkmpfkx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeqkzxn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lijujzyc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbumpask.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zyccgjiq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2inziecwz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qpecaubg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjtkzps.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvlcqxf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdhgrfr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhokjznp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhqhwly.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyqzoha.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrztwzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvyntwk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukidgitm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyfcelp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcuhgpx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxvffvs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfzpdwi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmbhney.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kavaglql.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jfycnkfe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiaehya.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ablpvwqb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnerhgk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zeivmqrz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftatenau.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibgcln.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkoqony.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2slkxbdjw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2flnhxvcv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oprndlxn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbllqzk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2buxdyggg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vihvmawp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpitjian.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrqjgoa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebzsqoi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nimexqjv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzqfljq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnanzitx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjfgpqu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2imjoxgux.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotqpak.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxtpyca.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2puqceefb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpnmuzz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2thzavvyz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2styeeqki.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdjtqpa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2auehawry.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mglmwtox.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdchsqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtkjvlg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiozbua.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2inauxifl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvxcpvx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mziwxkwu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2svmaquum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uxazwsdw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtbshfy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2weyihapo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdspkksu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2linjifmo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuttkgj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlwhxlc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlcabik.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqssbpgq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmdocbm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rirdiasa.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlwlihb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhuhmqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpuzopl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pgejpuhb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tajbiluh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpkgrgl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiquhhs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kojwsiem.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sihztabo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjybuoi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2abrittgg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smgtjulb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2noqcxcpt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeaufes.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsodcav.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emozuyrg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2vnieptxq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eskmcdxx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uscizveg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2malewtot.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeuscxb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujtagel.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eiunttjq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gueyowqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjadcju.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yclyrirw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tquqndox.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdssqsk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ustesttk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqdbuyd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pljbpkpd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfzwacv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2remwjwpy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhahhuxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vukhhmbm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afrttwkp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gphkwswg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvjbqva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfawxzt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yacmbnzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozluwml.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mtamomum.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bojovwbo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2trbhfbfs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyijymq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnmndmm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2syswdicv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrreeozn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxevixf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iabizzha.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2erhfjfhl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hecadizk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdizphm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzabtjgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdlcmjt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2taeqqisd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blnhaitv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zdivfopk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqqiney.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgwdkis.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2grtaqetc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfndpbx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrndzyq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmyevfo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujieodtq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fddttmpi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdjipuh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdpxufo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdvioui.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyynkrjm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbctjlud.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2djfwzuhg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxbjpnb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2osdjfgjh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rqosvmsm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ywurddur.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxkfvwo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvihent.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrzgnrk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjkiwzy.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uduscqvn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2abesbgkk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwxbesa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rrduguaw.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjljbful.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rymdkssd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiousod.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoqremu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xonznowy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkzjms.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpykdyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2buxdmqht.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kipyfdad.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2coziomij.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjvqll.html


<!-- 参考信息 -->