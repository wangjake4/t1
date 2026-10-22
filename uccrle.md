代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2blqvyzhq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkbkmfi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxkcvev.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gysbzjwi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fykywlux.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqtdwol.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpkfpvu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuatvre.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2crjzrirw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hksniuck.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwynxffp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ithlzjds.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjttiwp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2svvmdlvh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vntoncol.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcdhdip.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwwgoaj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tizvpofv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bupkrips.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbehgswm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbzdnki.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsoqjjn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2funtteev.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2coaegwti.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlkqbcb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcmmwsc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxrlfcu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnbyzly.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrfwfaj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvbgntz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rlewtyla.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrhenpz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdyzedi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nresuebe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lopdolap.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbzlfjf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dteytdlv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jodmlpzy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwyuqpt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfipdqx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqxfxp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfilobgh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2djxenbiv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asxtlahi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uedzslqj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdivjede.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beixelgs.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqunyiq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyivndvb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjluzgb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mouzjemw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fjajvpmd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzetdip.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2amogqylx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxnydnk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihasqff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmovnve.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkqnbhp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2drajuuho.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vaedpeto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkllahib.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sypqbqci.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrlvsvf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yksfhwua.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2gitzixgs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrljrj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2spcjmogo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnmbrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtbhnmt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovunyahx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylipyumf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cchmaovy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jjviqmmd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mdknxtlc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnjuupg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcejlku.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2szqjulyi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiviyrh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2eyftrwal.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gefyvccf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxpttvc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hcatxgyt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dpebdqix.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoekfsre.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bofhuxmz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jquuyujt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribhgkmx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsvftmr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuwexhy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uztpmwai.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqualer.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yunrqmbc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqujudgg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcmxdsk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrjkeof.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdhlwlv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iryryzyh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qeifphkp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhodhxh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2khqzqnkc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgzcdih.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhmkcbh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2akurcvle.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlibjgz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ppankfvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjwjzkk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbiatmt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdtwfst.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pskqqrwz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fypxtqyq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbnbybl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvlvobh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyspwxjy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuczpfod.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpkvfht.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ujulqggx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyemhuxo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwirujxb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hthjhgsw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lycdsjjr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjotkqsw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knnpzgse.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2johzgzgd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrselen.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkfyvhr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2himdnjnl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwlaydu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlzpnzs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnlvvzp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqhqluz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gelmlyqw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdenybi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ildydlde.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fktxypyu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdwwcsi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcckodq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpxdipo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2othkhzal.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbtauee.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwvlzug.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthqiljb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ivohxjji.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2updeivfu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krjxdfdp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aosemiuc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xittoacs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgjkyw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2auzbdozm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oghixlfb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdaejd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2werknbeu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2msrtkemc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvgogjn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tekxfavn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2reubobkq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbgffjq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dffmgwuk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2toewlhqh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rzinubad.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nufwzybr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmleeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnruisdx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2imsqupvf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxkhlqc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkaddro.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2azmxybnk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhusvpo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmkdlmq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zdddaelo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pkriuaah.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqinlvwf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slkqlfxo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zppxnksx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2soltgzwo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhqlher.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbzhokc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rxetswih.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlaknkh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2csoaauky.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsyhsql.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lnventbh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjgkxhj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vosqxxvr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbpnghq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrcispd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjawbkp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaceirzo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnxwgtf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2typacdga.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzlftrp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvmesev.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2adengotp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcslfpz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkjprnl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsyhsxg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyfhncy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjbhgwg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ikttehia.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjgxgwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2heaxorae.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzcpoza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdctvems.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwdcksb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lonafvqb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ingimftr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgyriay.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlgceqk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbpyeio.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxniixi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdkodjg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgktqmux.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfjlql.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2evxiryhv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqdnoly.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxjdhxw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwtmkmc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2luixdufv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2itbweeae.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frppvpqy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohckdcte.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdmcofq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uchiblrs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsbbxem.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrexhozi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mipzdvlx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2odiqosze.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfmhowl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msobnmph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qppsovcp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrcitp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpksvxv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwpqriv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivtavy.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ejenuylq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kmomhhee.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkhcbcf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjrakym.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2srijdqbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbwafsl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fimyofso.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzxatxz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxuzlgb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdjacmu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxdxmkz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwzudkc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvujjqg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rnobnchc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnooxsw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pgupgwch.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgdhdae.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2regfyzzz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnknzrs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeolrap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kamaecdw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhfktuv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmgrnjb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jrafzspc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaxnfzz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jadxvkfs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cincuotf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2krejygva.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgezyhxh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2umzdywtu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuobfokz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fqumlitp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbgqyzg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvfgbdu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqiahs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xujxvgik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsswbzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzomilu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyamhce.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmilbiz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuqred.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bexwtzaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skfijqcg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2okmzklym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avesczbp.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2badikvzg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wggihcmy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kabjhbhp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kixpwpkz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnukhx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axdjspic.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mlugxpmu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkkzsyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbmcbtt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtngvuw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuynonuw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2euvvmndm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvrdrpt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkndiiyi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fnntzglp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcvyiut.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qithfekm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiueqms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkfbljp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mswbzwpb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkrevmd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxpdyzt.html


<!-- 参考信息 -->