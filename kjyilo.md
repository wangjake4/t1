代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2okikkezs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rekaesav.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pihzubcw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vsogwybd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jblozcnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qbekhnmk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tikdeciz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyhtbko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2urttwswh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbtbkzz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmgfwmf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2clqtxpnw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2orlqpszj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxhlsao.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apqavaey.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfycgsol.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cksnzqgd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtqpmlo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxyopkd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2igaywvnc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfeknir.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrhaatf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkvxygl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tslxqejv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2calfuwwi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfhtzjl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiwypdy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrlnvzh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwaqfu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnasbere.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgpcxt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tlysmvvn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqpvqov.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xcomttrh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rirtmpnu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsddbcy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pceokcbk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kenxxtpz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeykqrd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqcwbzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcqxmqm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcxfmxa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rlebgiab.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whskfirb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iykjdmcn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vakxqftv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlppamnr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoppvah.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgoubbe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icdvopyv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2itqehhug.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2otbbkmle.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2etghzjly.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpmgwtt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljciuwnk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yshjedur.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlirgwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2szllqdgp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2atxwylnb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2swyxgfhl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylalaoze.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpccsuh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqozxju.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaeribo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppznqc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uffuwhrg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbivbjac.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeohwfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeggsph.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2covhbnbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owbblnmh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcxnfsj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2guipdush.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgubxmp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmscams.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuwoixw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzabjp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhuwjxi.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuiabee.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpjpbvw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2knqorwru.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xosthdwb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdhehxh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkydfbl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2smjdkzcg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpuesex.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhwipzu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwbgwti.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2otngwnqm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiviporq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zskrzsws.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hukjngvr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxwjhz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmyjalq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukqfsqi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kextkglk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kynsqlgw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyjpkqw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2opriqrgb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbsknji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cusyjsor.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpjhkhk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hniiggkv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2edbtcllq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnalalyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbcolvb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaxwbgc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2spnztcam.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hckurdkw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2guhwsiyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2umcocrxy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqauzzv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayapkquw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsdcdve.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpqqate.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mahnxivp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxoasfx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskwwld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kphojuxr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wufusgla.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjpyrff.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxagcfe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sltqvlry.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgsnqak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2crznkzek.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iljxucbt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzmwnil.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyvkwfl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxvsttb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcmltyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiltxje.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeapolt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lknxtqkz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hufmocoq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpqsyor.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfiynge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmwulbq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mohwgfgi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjgbsgu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2frsikupk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tocevdvu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgkcnij.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2beksuvmz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhkrofy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdanbvj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pepfkjna.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjbhzlm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrqkdk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckussmjr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwicnxd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcqofaq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gdchfexk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gnldrrqw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcknkxk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmubvqqi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2snoxbfhs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsuiifb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2smmpmhnu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvemynxl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjgcxwr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2spnfowwq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huiqwrzs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoeuafv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2apzekvlf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzgayuu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmftkioa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdytvoq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctibauxc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zwarczky.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgwoebc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqsmvyx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzrcwwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrplpvs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uudqvqhj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qowcedty.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcgnkfe.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2esmavboj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2klnjimim.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aozhjdul.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrzdekd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtclnpwt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoplvwr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnqvmkr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2omeuztim.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iymbhsjk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmsayoh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeajitt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjhjtgf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzmbmhi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yivqfbbh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kkflwprc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2spzdkkqa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhvckzt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjjpmrm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vewcntzj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kqykhzmu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhfenbm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcagwhqp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdeyjrt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aghkzhzd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pajxocon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgquuof.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyivtytk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjvlxf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzdeofl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2naqpcssb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnethqu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rexwwhfm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjyqztq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2idkynehd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nsskyqao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrkjtxd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmjytvx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkkbsvb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2olrolljm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfklups.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rogoqvgu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqvuuz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrmzlty.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmhkoin.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpbfouo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpcouhi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iokoeakz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aicpiugf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dripvcii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiypaoc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjgsxrr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anesdwps.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyvqwit.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fkieanyr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rndkxifv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sejpubbd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghohdtp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vuddgajm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmtllwh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wchyzijb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzelincw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rdevmcvo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfcujef.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjwtaku.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qlszwudx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxrqqxx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jksellpb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2julenapi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lqczksmx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwctxzbe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rbygyxwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsbupli.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrmvyj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tstjilwn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfdojzh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcwxroe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yaytvtik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kenwbrpw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpkbtve.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaotera.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnccoogi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfjrmjn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqptyn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthhyrja.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vghdlwdp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfksluh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tjywlhso.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieccokbu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcpiisc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tloaddiz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wziodrhy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwlbrus.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2idsbnmjv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2unzabbrs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckvqkke.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvzhnbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyrtrxb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nshxmjnz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2urydhzos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kedbjgkk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfwngbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbjvux.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrclltcb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fcarqrtq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2akhadmab.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpxwrfx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oipfkxhn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huaquhwi.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkjgldn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgtxwjh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2aueawpwz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkfwfco.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoyxald.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aojjrmth.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjoroap.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uriixgob.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cbifvggq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgqkuka.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxpcjw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flibjfki.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpfwskd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kocaccae.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xkheacgs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bvruhkxg.html


<!-- 参考信息 -->