代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkkirnf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbpzgkq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2eklbcsbj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfznela.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qwacnnbx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmwxxmm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2usbwjlfq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtazmhjk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smlgrbxh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2egdjakvk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfgrlrg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2exdyewex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2oypqeork.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkgijhe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2spucvuwj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2otoewsgt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jqypzbaa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2axguodff.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvtvlnb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2snfchqdy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfnpdag.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhdgsep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2aypjwjio.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ienzypmq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoddlwd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjqqqje.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhxghzt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpxfqdn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2shhpjqap.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sishlivz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zerkqojw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvdkxrs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oomkwxdq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjpjncn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqosvjc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpzzoqj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiangxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxosvzzu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfhgulw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvqgrbp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgqnluv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvrzczt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaqhhyx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcodcke.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivnslgd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcpaqhe.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgtjqxy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wepkwqpj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxpwohp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzsgtdr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tztybwop.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krszheam.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqljtge.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnzxagn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpqslzo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqmjgfk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpctfp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kesgntwq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wojqqotk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbejbwh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2trpronix.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2piaskpds.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2esktmdpd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2uzadtiwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbvcrdq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubicnpvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crszzgse.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkijxvn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqwxzig.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2itziuhyf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dperjuis.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnpevln.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgchhkr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwqtkyg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lnruadwc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eqktvwnb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpfcuja.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxmepa.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgolyod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bodushee.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtynfkh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cabbusbf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqllqzbn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfzhmsv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoymvmgl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhvvnam.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxcmsai.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfphidsv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbhjupu.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2crjabocp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyedjsho.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvkwdcg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwrulmi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jezbquij.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlmgchu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvveqlv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ickronwu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwwiozx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbyivzg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qssvaglk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvofswiw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmtflhu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2opfryrin.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnrrjic.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzunwmkl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ritzgseb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjamnpf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpaagoe.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uquaryvh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kddbkumw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkmwvfo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpyrttv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhzhgqt.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pndntyxy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fixdvyyi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2isnbqvqi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2epvfuemy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2txulsfts.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2peszocnj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rkovgvrt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuvuxob.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyxzkw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrekbix.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqttnib.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hakhccwk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtozvkg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdxcurd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgwtehs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2guczxgme.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bztvjogp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnswutn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzondtau.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyihtuv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkssmb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ythwlumu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzllfii.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfzmccq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2boqdvbcm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmjpqys.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eisnerqt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrrxsco.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkcatlm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdsqdpj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2abjkbutc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbnsgwz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqvnatr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lpughidw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmhnkpr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpairxq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhincsf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rgayzsqx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfryyid.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxnjwfm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvwzryr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqgtpnf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcsdvej.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gulkeevb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtkilir.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzpybka.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fualivrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fupocbrb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrdqfuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wekdesml.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzarfce.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnreawd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxsairb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbbveeo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqcjgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zknebwiu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdnizwt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhgcuqg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwidxc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqqumb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfqmwco.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvynmck.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnjynuz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drlqpsoh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrqhsmz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqcotem.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2asvgitaz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjxftrt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyktiirs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nijlnnje.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsasxdo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnteanc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ynddukqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnczgvf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkpvzzx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljufcxqj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbhvayt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oynqgkxl.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrmhyqv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdmxjlu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcspggng.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqydnfmn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsrxtlo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvarelqs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2noddtslm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztshujgp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnvcnrl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eodflwpw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kknucnvs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxlprim.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fyesneau.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhadrntt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmxsacr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkxwxwz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kezzalfy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzeumca.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrtbstj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpcyggh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuhsfaz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeporxv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2pwialwqa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrqgbnt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokcpput.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aykaaupl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zimhjzlf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrvlmc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zarybxrd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ovksgutd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfroilmr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2naereexg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfplmqwo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oytdlsog.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdiednp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvskpji.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgkdseu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aymkewet.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zxycyqhl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tyckkvuv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwuhvkk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeokkgc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2emghivje.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgqjcuy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2maabelzs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxkncjb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yevxwkgy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etknjzks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2iebxdvqb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eozlfjhc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpfotzo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtilryn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmvcynt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2shpglhuj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtkhysw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2siivfkap.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrhfdqk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfexilt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfehpnyp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgphppte.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwfudgi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tentolth.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzptjhxs.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhjkcxu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2medgydal.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pshekplx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiwtcch.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtkmczv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaajwofz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iudlemjo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtbjind.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlhyukh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmejjjcm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlihpgrt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2iisjuqcy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akpoqxux.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcahtle.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pttsqgfm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nabgcpvl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhdewcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjauukrm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oixaxjjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kboimfix.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpsxlck.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kqblieic.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nrawpoij.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzhyacy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwncnbx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zethzheo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tuychgdm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2luoehmnr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlfvli.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fysqtaoa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leknhthy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtrjvjl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnsddhy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbmfzgc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wztnhfqy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqmidkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2quefpcyb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xsesmuwr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2imcygjjv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2penbkzvk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllzqhq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nbddghci.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xodkgvlr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpufekv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkpmaxt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfylzcla.html


<!-- 参考信息 -->