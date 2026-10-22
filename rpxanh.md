代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iyowjyfl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbducwn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2phtofpto.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgaaeml.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmwgqbm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbojioc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mprnyekp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gflumzfk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sereigzi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iozerwbi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuzdjsn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjdvwco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rogzhvcm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvdfdxn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiihytx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcweobjc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbpmdfa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeyipby.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uysgqkwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrkuubp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2syqpmwaj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dylsyfsq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcwviyq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2amijrnpz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbgqnpd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqxglhl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zounybdi.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvsavii.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnfeapw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqotfxba.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjdgkld.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2occxxmce.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrnlyhk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fshmfqon.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cbejuzxr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kllhdsbm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbleula.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxqlwsg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsxxkmm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbwhlm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjyfick.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lkotigvr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuweyyk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsprgfpn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwsahts.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sklmubol.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnguhfl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyxwcag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mycdrqar.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qviggsnk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoovuxa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whuxbyas.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2scriobqf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iubxqydr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cmimdvjd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwyhfrx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zztajchz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmosgjra.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zphasfaw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfhfuwj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fllvefmk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pstctpia.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nfebazwj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhyrnat.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmgmonx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2stlbbjhh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgaaznn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwllmktd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kioshpzo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2onripzte.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tehorftf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vykjpbpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjggyyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjgtjwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smzwjpap.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdqiieo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoilyip.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2govrrphp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuibywqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjnthqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuidqvn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwlbowd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlymbovj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2moflavts.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdqoeod.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlymtqb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdqbhgd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjqeerf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2buavtlgt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhlzubn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrioztb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyutezf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxzcokh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ultplglk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzvhvkw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgfavzd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbannto.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzudgkar.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxgezc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fksbidhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jendypzv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2muqulamq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyfbtbn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwednbyj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2htxzmfhv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzywigp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsxqzrg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eydvqndq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wibjqrda.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhcufjo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwobiee.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fawuyliz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsarkgg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoowwvs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgcedqe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgaadhv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckrxbbm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdlkfsn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvimvqab.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2teqpjyta.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuhmdun.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjaolq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewphfpew.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpcbkhb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpxbbaw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2stxbimmm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxvxgf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaufbyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdcatsh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqerlorp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxvueze.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlnsjjz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oglfsxrj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhnmtbj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hluikfsx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2prvlgawx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hltwhvez.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxubwoii.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqioqhy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2crizhhmu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqohjyqj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrxynue.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfaobyi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkfgdyr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnulblv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aofdimxa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbuwcb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfxrrpw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpyloug.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdmjlh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopviuz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqstxlo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2getytxpg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqjtyve.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjzwenq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cqftflim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnifokd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shifmlam.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hswsqrie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxxlszk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrqkmrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpnebbh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glusegwh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mohahoct.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwlfvon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpdnwis.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobljly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyzjcbf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikklewdg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvztaret.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrxuzin.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2prnypblp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xluqxosp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdnpawm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyvhwzi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xfktwpqn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzlngbt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fayxuzgl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jxetnhkm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwtybl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qazweanm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmogzefb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yicbbyou.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2stuxkvqd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpzrzpx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgsijdu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvejpbn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuviioj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixizqabm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwhvtmm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2djmrssju.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeppgpj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cecybxbw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hudrdeem.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjyqgwo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jordvxqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jklseasd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzjpwlz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfywkab.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwjdccs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qotycolc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmrklmh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xutsbcod.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2repbhesf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfgqqyf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iakdmxje.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eklncgsd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpmbfce.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagsytx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2osxlpeco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uizaypmi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2revxphrs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxbqhpj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrimdkf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2sfezwccl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvtvtnx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaezwve.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdtccgf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2cwugofhl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrravdo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkbsmo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaitcsg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhnerht.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrstzmi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2egaysrks.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoxytia.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mqneviox.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvejtijm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuvgwqy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxkaohz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtreiwb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcmnlpb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2inmhjuff.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2htbatiij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqgjqea.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpvvxao.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbuedgd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaxktgx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgsajlt.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tqybsbux.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddurxgad.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pihcxjqa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbpgyin.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkdkjng.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kofcwuio.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaalalr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijjahsv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eznnrmhf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfhwofk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vojnuonh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2imqxnrhr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2othdedjs.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeexkmd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yruadtus.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvthjvo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tjueexls.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2aiidiemk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktybccta.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpcvmcn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skybauch.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2krcvhhwb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwdmyfe.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2duhpwitk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkecvpn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xntywsdc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2caordoaf.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhxntch.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaxtpgy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnhcsgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlkgnr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uklkzxjc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxbxkqi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wumcidbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcplfps.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyllpjt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhllxue.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xntrblhz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwejxppb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoviuyxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hohuappp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xszxdghm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjlbxsb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2egxvdcvg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zoogstgm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpfewxl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fircrbhq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2humiszdz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjtkwoa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fnegxiwy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eztnckdb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlgriwo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sucyvhlm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eczqjkfq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsclktj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vonfdngv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdmlnhd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wsenipoq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgqjlqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmhhxu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2miwjfhag.html


<!-- 参考信息 -->