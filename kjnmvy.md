代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lprlhqob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmydpwoh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjzufli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drszgbqa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsumact.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwawdfg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xhetdvzb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjrqfbj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlatwdxj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoqyqjg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvpispx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgcxhrs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyupexh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrwkivn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeeufum.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aehxpltl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjhqbns.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiabbxa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kloqfniu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjycxlqi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuetvfwf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbsqcuu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chcmiuiy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgazojni.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfsyjeu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrscutx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyitkwz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgudprgp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzwaaxd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjkdwet.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jtygxktn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2forjwlwa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2werokycy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvpwgkm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsjpavw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjtmpkd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvywfyct.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbtppbb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdxirlt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvtodgl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjraxyr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjxewqw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2burirbzc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uctlncxg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufkulpf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gupzgdxy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaxybii.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2levydkvq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdyrtdy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaaqvmx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxohpvu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqludqbp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxwguip.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnidwkq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcwylyt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llhsqjnh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdolasdw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdknyikx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvhgeyl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrygrdc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xbndgiwg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olugodrx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdchmbu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoptgkln.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2dctjgxzi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsfcwej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrtiycj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvzafzn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2piqsmpov.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzitvobp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zessucaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvstcnwo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhcvaew.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdicjoo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkxmgoh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2adewrytk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edjudbbz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgezfft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbbhmhj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2etdccqff.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqrzfsq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqbyhnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2osfwgskk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2irgjgbgd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2txjvaikk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgstysch.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzemoagn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdapmbb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaacqev.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcuect.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lykwhhvv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzsbvly.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxbffbs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsohuofi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyufxlun.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dscbfllo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkleztv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfamkfrf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjfyki.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqpksca.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmpwjsk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwxyox.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnwtizf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdvwqku.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzqcbqm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkgldpw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkmfbzv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvckbji.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2luzbdjuu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2undekrnm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyotyhe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2epmsfxom.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2psszxzlr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2iugkajsm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vroolmdp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrotonto.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmujctnf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhravej.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnzyhvw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqjlzpb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afulkoun.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmrwqti.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygpbocd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lclylpym.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2luuimpul.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcdddel.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iuomvojb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ickwiaka.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbkjomx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2okpfgnap.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kduzrywq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbzrztx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2degeasuf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyyvddk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxdkahx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsohsfv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pktqvnwq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hkysxajz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ochatovo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqbdihf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiyxdrt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxarjoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwfhqgx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgdsus.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxdiewj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2emkwhhzr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtromhj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnrvppf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmpvyhe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fvycwtek.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzetnlgd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uumwrinh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxudyiwi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjbftdr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2npuzpitp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2plkxhpig.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pajzpukq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfipvnth.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tskcrhnf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaewepj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtdfsiu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyfltx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ojstojvp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiwkikm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjaqzlq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxnftro.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tpljcsde.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrvzkvy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2emcofswh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2geiccxrn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcfwvqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwkgepo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzegcmd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wprpnmom.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgecxst.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2smzgcvgh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rlegdmaf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtfhqvx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yngpwdlm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjkvzyp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzwhrk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwcoysh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeespac.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvuwdav.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zusdzdci.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtpjdvk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mognismd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qacoudag.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnbhhyc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbybjzg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2psnxibif.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfdtgdv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfkqmbc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxglewoz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2abcgqhfn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ntanhgis.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuchtqf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2reqnmdpk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfzpjms.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjhfhch.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fepqwcvz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2stcyuxww.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstufqla.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yewdhjss.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsrpols.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wahvkzao.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2abojuekn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaoxfaa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2smugyjth.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2saqaeynd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdwgzib.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtbuaak.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twnhxfqk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmdlbgf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vetquohm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkqulix.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezdjufi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfvxiuc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2snpnykru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwbiqfl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxaltgi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbkgnur.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jjulmjxx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtshlvlq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmovhvay.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmphjly.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwouiw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldbajzi.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdyzgoi.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrspefd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2atonbmeo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjceoxk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrwnqpd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xabfbkfr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2frjibcml.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qexargyw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuzphxf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nflngosr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rftynzsq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdbrrvn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexccwmu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsrankd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcrvldk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvafiyqd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvvpiiv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwugvkc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdrgali.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdpwdaa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bldihsho.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdynrmp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnpvjsp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlgmjsx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xownrhxb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxqfjsl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmvgbxw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdmyhea.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vksovvom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmkmrxw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzdxfmw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxtmluc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rbultgwi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopgclxr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idpzhkae.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2solitkyk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bffqaafa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkgucyc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2scyksiir.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgzpxoq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cvntviql.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbxnuux.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2byckobnx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnthuxd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhctofv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvxorze.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2voblszms.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubajahvk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhugaru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyrrmp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtqyire.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efxugwac.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdvnqum.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdqpuox.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvjpulm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfxmmjv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvwmvxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiuicjn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eaavnkka.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjwjuai.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtbkohm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lydmhrwy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpkfuwb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrovuixp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpiplvv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnznuwww.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mndvrjbi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrurtmc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwzlpaw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eeugdyjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2badtidua.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wflsbxei.html


<!-- 参考信息 -->