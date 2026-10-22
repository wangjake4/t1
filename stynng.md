代发 wailian999

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpxtobw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgsrhxd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkpclag.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2boodynpo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fodtscwx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mopuovtt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wasysntf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlqimlk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbhphlf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldowkebf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmowwtx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfshqkg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsoblpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qrggfdhs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2futosgrs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2txkpdoag.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabkjmfa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhiquxe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbgrog.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2etgfxzas.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtnlbxs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwolzaou.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwujzf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkbdxoi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzqvfhw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzivtrf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjndivfl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjbdvpb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwheuxg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2staffhnj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oxclwzha.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zitamlkv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnzzavh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxrijne.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crlaozms.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deweebno.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxzuwhv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aivdcfua.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wwktpzcz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2anckcokd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2foihaztq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqaigno.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tqenjkjr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndezqvrm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2txpfjemz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bfscufoh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltttltxi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2omnrhjox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2andezglp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdzhcll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulctjtdm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2evccsodf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qurjpxze.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjonhyvo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdynxru.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vapkqfnm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuvtbek.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruptbylq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmpwdyl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2stpwmnwf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2syltmktt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jusdkvyf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrsfcqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqejfkr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittgmcno.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxchzben.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsymwyg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwiikud.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpyhove.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjhadhy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhhpyxv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uagygdfn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdumsmcm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnijghhl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qguvrhtw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgtqgj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmrjomc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhqgcdq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lidfwcni.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2papomjib.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzpmblc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrqtxfj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fggmqozm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzracpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2knhzjwpn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwkyhxr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfnsuzf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjitvme.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aixzflln.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xacsrbil.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmohegsc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnlngla.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcjqjpo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuoplcq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krjngqou.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbbrsdm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2canzsuop.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuepzeu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqsfcah.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtzytbz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhqaqau.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2twogijxi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnpixsg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqnzkjh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fobccwno.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yklmslbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyipbiz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2crqtqugc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2szfxtmkt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqhwrpe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrfiefq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rzazyvxf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbcoyjd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfybsej.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvufonop.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvwrxzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqscqaz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhnkldt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiavyxp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnlwroq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwniwehy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oxleaadq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyiilwk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qsicmeae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2msrmsuyu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shalclsk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2irtzncgy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2shhwlfrp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zojsliyh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2txsdydmd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2inahlexh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2misflzeu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xorugerl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unysweiq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcxmioz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdldwgza.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hbohmqbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyatogh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjnidxs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlqtldn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzkgiav.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lehkxbrh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2goqlenic.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yjorlopt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjtrxsu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujubiwzr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvydrgo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmyyybc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ftapivfj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbpignh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2meumowiw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yduptjol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpavrde.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrqusqs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpsieqe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrdnjjk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rplyetsu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lriwynls.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otsqyjso.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlunlwl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jcudjfrb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2brjbeqph.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2giksuqwm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljodkxvk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fktxtmpv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2siricopq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoshwryh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brfndgrr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwkwea.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kjahnajc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zykhdjeo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ikalprnj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iouhtich.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxrqhuv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyhyfqt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgpxpal.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhsazup.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmyeekd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgahlwa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvherzdx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxzder.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2koiyybfc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2stcuudbs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2clzqgjfe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyorwgsz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjbsxgm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjyqlkm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zircjktu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwclqxgf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2plipqevr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2msmbwdwr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgoybke.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwajyxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igkfxgqe.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kiijubcs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuumjzpm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbhewhg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rrneonfp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hlapvjvm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zokxvscs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzjanbo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2afqfmuqt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsvveab.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjtjpfs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxjmwil.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2srmiusbm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkddtpg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nifnmbgm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2whytdxzp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hagotwrn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cqglcvxu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuvmiyd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfwgpsi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ujatydwl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2npbjsiiu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvsmrnx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdnootu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxxjaur.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplvydc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yxewnntg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhbeurm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmvqins.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpoutqf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2twcwayvp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsawklt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyippjf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kepohyax.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjlhvwu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmgzwpt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sonkvqhe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeyvqvl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2npomcaof.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvvdzti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aybnbnit.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bylbanku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqumvclv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2habbhomt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrsmhng.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smhqnhlf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekjmxfj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oogwuecq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnqvmhm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2almdlojf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2llklullz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhhawlq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxdecg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwpovxl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzwmact.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rloslfqb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbsxvwa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrnudey.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2knlyehxp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctisfkxh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcvenvj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfglqvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aftgsgbi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdwkqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpoehwl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2saenpwos.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnzusf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjnjfdc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfbqyxg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqivkw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aopzwmuk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdzpzki.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngidzrbt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2peydbfli.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyepucak.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwijxybm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwcfuup.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeuolek.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akljytos.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aeslinip.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mttayknn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bupnibjy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azjphoig.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cubyyfap.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkahqgm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eqamsaaj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnmkxbw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kihmhyel.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdiehws.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtntmbqe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoxlnqw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqpvbjv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqzjips.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcslppyh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utamffsc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnmkypx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2dbselnum.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwscjlcv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dczsquzm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpsbgqj.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qazidxry.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnpgspx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjrydwk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viukfzom.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlycblkt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlfsff.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gofkvhzd.html


<!-- 参考信息 -->