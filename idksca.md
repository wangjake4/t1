代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zvidxqns.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrrxtnx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbuprnc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebruzwpa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwpjori.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2whdokaca.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rhomojyo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjxdjm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfaudtu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbselxz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyplohm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2apawhkql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiewzbw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2okyldtrf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsafojqb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcdymaq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2koczlhml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqicgvqk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxurlug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uylbmioa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqftegp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeeeow.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcioogpq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oblezjpb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2esvxpsub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjyqqsv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2streoskj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnnjpqt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2sonizdsr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2krqterta.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpyfqdh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jolbkskr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2shhbwhom.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2aezknnbv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aglzhmhk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqznzpxk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kkumtpzr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2crvpcwrv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ekftxswq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dffoewel.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cluejpdu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfchysf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbrvyct.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdblinu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ijursccd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszqvsn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrlfzoa.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyditoh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwqxbeb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2roawoeey.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkrxwhl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyxicdy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcppvrwo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aahorbxo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ujargofz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lytuxlmu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeaetcz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdroozha.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxalradj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuolqpil.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpsjugc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjnbvne.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sckmjxvt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2afjgigqf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdicivj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqyampc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ufahdxvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwbzwgn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoxnvzd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhwvmio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcdwvcx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqqirz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzjbmlr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dimczgfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niyqaick.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdgbjtj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjssuzd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rafuutzx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnziypw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvtzrbc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jqddspzi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrgqazl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2xacelbeu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2capdkjho.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2brszzxbq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwdqdjo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbfpmqi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqplbkdl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdiziuf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sckdzrlv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpvyobf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbuyvp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oorxvafr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlixcug.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xigurvrr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrrbopo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgagcpdm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjjlzzv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpceabh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpkbdrz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fordnhhx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cphkpgrz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdacgrmy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdeaolw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ndircwmk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrbtefr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsdvcve.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2pozxqzos.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bozyecid.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cuednvak.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfdhrhi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fuelcwel.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2artucaby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2awrgekgt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwubco.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbynby.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pynytcwz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqqfwbh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqwkhel.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfprkdr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qebstasy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlerhoa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyjtrvx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrlcvbd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iitgnqij.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onxgojuv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlpjenz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcwtygk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfmmffx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmmqppz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkoslsl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwspas.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2waudloyk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqystcp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjkucmn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmjxoxs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrvbejw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wftgwpoh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmytdpv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2slwmdaew.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czudzftw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgmwvao.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsgfmvf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmmpjgs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tknargca.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjiqylf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfiznm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amdkquub.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2blgbtonv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crvnlmzm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2teglpfgh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2allberct.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmeanln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdcddqd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rthmhpau.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqmynty.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmokooj.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mklsuvmx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2piiffjbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iverolbt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rlblwafr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2isjipkkf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hueoltvw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tddurowy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvblmbmf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2drfwchmf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2prbamwkq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkqnqip.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cilqxiye.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrghycv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcasrsa.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibyjgx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzkrtyp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmzjytr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2davuxiio.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnmxdca.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2whgdlkdy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdnhmt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2knxslbrg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgwlpd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpzhsdl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdttxfe.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzeoflm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnrcvdq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyihudx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iumbfhih.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtindia.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyajrybo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2peuysmva.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibylulua.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmojvshg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrxmezn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkwbwmr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jotnljam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2feukcats.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxdiril.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhixvot.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2slaiwawh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yprzqipt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vujkjfkn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2obrmvmli.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2larcklgt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxytjetw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2omdgkefc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxcqajw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfdftqb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlrkili.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yczzqbmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlgjpva.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gpekfhqu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxolzqff.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzbowkp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mczftiuo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlwocel.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmgaufx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frpfxmip.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzyvxrk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivulllou.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmznjck.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mycveuqq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzceqaw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qmildbgv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cscdzokh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvmquai.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yphbcrkq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnabdfgk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udcbpkyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzmcqaj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2utqgstmv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaoyrfe.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aomueqos.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihnoqbx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjgwldk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhgxuqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwinfia.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rugumjbs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfwlijt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sagsqdpv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrwsfec.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yidlbeux.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwylxkc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2iedrwldr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2muwkgbkm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iamfyuyu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmgneui.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdesprgy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzgsamh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrvimnn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxitpve.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqhmfbx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhkglmj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevjtod.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tscwcjkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2tduykhhp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsdbmpc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqcnfpg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2thluahsb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnxkkr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srpumcwq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esrfcqjj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfqxlvr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmpduhq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2axgqztzo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpivnnx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hsicjooy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jssteygu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2toarnnue.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyidxqjp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cownbvfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xeytmzgp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlsupyi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrojqlqb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdaxljg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jydronxe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzaxvmf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnwvmlp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxjnoo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntohtmcg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljguoen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrvjtaw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2krnighco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgdqqdf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyxaoaa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuriewz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejtotj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xscnaxra.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpeluln.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ffukdwic.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmxzgly.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnfqufx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cutskykk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuelyey.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfytqrjh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphsydi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuafrqvz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcmznmi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzcezpm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qeleevgd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2afulrnem.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapqzhf.html


<!-- 参考信息 -->