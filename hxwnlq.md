代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgichsdn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcneforn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2swjvrjvo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nqppqdbq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2koxriwct.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2aujfcskq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgnnvfz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaxkwec.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ngonouxs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfeuxvk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrgozev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypvmlz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggryhrku.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2icjvmgjk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2erujknoz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zogngena.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2sonyrxek.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kblotohw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpzlyph.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cizfqynn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjfxlsw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jufbyimj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqzbmrt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkzuakk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2daotjrzn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2axooinoj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlqzchg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzrzfqi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hanvdqzz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmkebda.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdufsvo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnghbvi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqyuila.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyhwfoa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vscikkjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pctelhyw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iapfibgk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cojmougi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfrmrpq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2unzmdbcg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2faoheyjp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2keoasiyy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wlumtdrp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prebrtdc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wzroxdff.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcxnkes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cujxculx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdazixwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwubpkk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnajrstb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wjznghwp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjvngqd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyzkjuk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ducpxbtk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ievaygdu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhehzw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwglmxe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpamvce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiehfae.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gilmxicm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyapxhav.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gygnxant.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cemyakig.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxpcblj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmwhpuv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmgdokj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzwdqfz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozzjra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrexrvi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcapong.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaewvya.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fajqdsgx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xjznbqnj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwxgogz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2swohxmsn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvduykh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqgclfj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2prtwgrtu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgxlird.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oocabgzk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbifymty.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2udpopvgv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrbsfhk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlwznvd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrqjfag.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqkwjj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hygrvona.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmudwhe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dojikgzu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcskzmr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lamsdzus.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutbsho.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfafqufg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvmbdlo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2occjqyjr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uipmeakc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkqusvs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uihbzeoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2miiflmhw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yylipnuf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iwunfagx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2czaddsxx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xauueorz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mptuuvhn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwvyjqb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpmravz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfdzolt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglceta.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2glpidznw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoaotbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgtovri.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsmwbgz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2layphuvn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkcggdb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bznbremj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfrfmjv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjifnyl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qojmkifa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xiodqtnp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwwixoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiqxirt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2suplprsc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxobywh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzbzbii.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwuvkdx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjousxh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoesqfx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uchveoby.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbxdqag.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtvskfk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkutqogp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzdzdqo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2enarmjva.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbozkclz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkmcabj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpfozlb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iifeguhv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jejveiuz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zopenaii.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhjmezx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbwisij.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqofhkn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kibbkoyx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2omkhmpzo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okpwkqmj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2onbdzdne.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvhhusb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwhwjdx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dvedozwb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvkhqxn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhiraaj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wljtnpdc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xncjpeks.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedxcls.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kyodjwot.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjefvgbf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzrunpd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpllotxd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vsucveje.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfydjtb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfccjhik.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmtdwkl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uphwmdml.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ztubnody.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdipaau.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pganasxk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbenei.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxifzlz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdqxqkh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xtubrjsy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdefefaw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmppvr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ebztavqm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpakxkrg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bklpasza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwlfcek.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qyggizby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqiklta.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgwqetg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hogchdzt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2buhluikq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgkyniq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exbwcaje.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyqgdqp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2djnszluv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2orerxwny.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2obhfsbjh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtrgwoa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijbsdci.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyvddeg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlgckop.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zwooybjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcypyuc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2evnsxpkw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxgyfrs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhmaypj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2shkrzfwt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2leykrgmo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqefxtw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoipvcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdklbbm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqzihmq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwaspkld.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aedcelnu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqwwrig.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbncznz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdqngny.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoeulyt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfojrww.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfamqzgo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2fimgovae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjcypss.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkimhhc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnphhrv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2euexbbdx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzylhtw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2asiafrly.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2piplnmlt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxlwmk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlxhpov.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nblfywhs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvwvwwh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2isfmqbyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwikzzk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxcoglk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zekqjojr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvinpxt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgqzrpf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoayphz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvekzde.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhnxrzq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfncoiq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnebmrga.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kwybcxle.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rorqnlxl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bujxodih.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmjkqiz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpbjcqh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jilzeefb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2giowtnvw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iohymwxs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfmwmgz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxvjgtz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfywfev.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqzxnxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2arpwcvyv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kosueihz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qphblpab.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvjezag.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqucotde.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdydkfcv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fwguxfav.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2azpfemti.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axckbzwl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oitldzad.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhyfmrt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxraytoi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcvwmaq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrlevje.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyxcjik.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyjhuv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuloelt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2roykdufe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uitxhsvs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yerwzsmc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxagukp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqudmgkb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2plroqjgs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2picxhhpk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wotpoobq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abuvpowg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmktdtq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cnurytho.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrewpws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aztkprxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlowymdd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bixvpwqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiqgjid.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkylhpz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbiethy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfrvwtj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmaczkz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2linayauw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgtbtwg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjxwgcf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxroytoo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnkbiiw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiemtyt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quoggbwx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xadauopr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvzjjxx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjzabll.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoskqls.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lojuybqu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxdgvvv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2beliyxjv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqqfaom.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbdhrdl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2twswrmgy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ilptjups.html


<!-- 参考信息 -->