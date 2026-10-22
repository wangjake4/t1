代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsdmkgj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvpves.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qouxhwhc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzifozw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzsfufu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2btlbnsaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqcxgms.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2thbladal.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzpkqcz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oryodgvs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeapiad.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2myegtimt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2acvzoygw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzqcwqw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrzgbon.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmqriyn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpkuhqo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfhsmr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2salqkukw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2caknjykl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnwljbg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2idjdrkrv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yydbebzz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnbwyzl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iymkiksk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2odkclfld.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqxokca.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnqkpsd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdhirto.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqjvtx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mvusuuta.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2opiyyjuw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcroflq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyjvegg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gjssgpwk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjfpdjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxwrgh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvudggx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosjhgrc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzggre.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fasnswey.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtiahno.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xsodpdvk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqouooff.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lagqdprb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyqzezs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjamapo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akazwodq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mokgugio.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qezolhkn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2atwmzxtq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnbesvc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ceznsnru.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kaigswhr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sicamszj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2milkbgdd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2epasqwxg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cqurzrht.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2reakepcg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2crxqyeho.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tesvbzpu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgcsyqj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bardkgvy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tezwnmwx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2knuqiwao.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2znbbddca.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2igobmtnw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkexllvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iorubran.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfkvblq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfllnaz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fowruqlh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2egcpyssw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nulgnmfa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2amssvghc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bpleipxn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ndushuzi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsrahsb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2clrkaztj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuplbue.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2onerovmx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsfjjyq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfbczop.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnnzwsm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lostgxxu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmynfiuw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpfbrwx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2panlkpwg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kehdqwdk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2czjtwsjh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbjwapf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsksbqg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2idolxwqj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoykiyr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfcyfsh.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oddrzuvb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqbgfrb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkjoblb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2diopcpks.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzyzumt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kcarwiux.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bbncucqn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmvwxst.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyfnkny.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2benzntlv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hiebeweu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gagoymju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zifdatnr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyedhwng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgrvkmk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzmscet.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtaghqh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yetgzjtb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwryyccu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2geezklbg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsowopb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuywcps.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnnavoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoiegta.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfclgoa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgklsllg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2trbepseb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqrqjfv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ybszdwma.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvndtzy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebroocky.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqteixdl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2luwmidji.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgcovn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhoaftz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgxmylj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgqznaf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vkekdoxh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vifbsqlh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxgeozg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfgzyao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwciqrn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yajwegwn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrpiaxu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2davkbcxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqdknmy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjciwgh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrwvudu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2orwdldbc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2neoohbcw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2imnwnvpz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwuzbws.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nqihacgy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwxmmcr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqixsoi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzrqmqr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2pzekubrq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftmcso.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyhcikr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnpxzpp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqwvqkv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcvsjwz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2owcqolvm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgmfwgt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhooearn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uotroghs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwjjaco.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwzqflq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cevbaiqk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdtkviz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqvchlf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhijhvic.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuwpmef.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdguxft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pexcuuaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfizblgq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qeabbmyv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2flxtwdmy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2juohlhqf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xudierni.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpcfbuz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vibshucl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnzywfn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2havkhdmh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfrevxw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxgbpde.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyvjnqo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eexxietn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2irtsrrvx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpaypjq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2skbzekfq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnweuxsi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qeifasqh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxkneww.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hhetxnwx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbgdxri.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2geypdtjy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2texwakpn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pklozjpn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qypcjbqi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rphkwcbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2btrmngyz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hilnkbnl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2traocjft.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuorpwp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaqpcak.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbtqnnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eueqyjzy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kinlwqye.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udchtjbx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2klteobfv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsitvda.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuxpcgn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psmveqjd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dwauchlj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwgtban.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lffjupwa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvevhvd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprudvhi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwvixcr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brnibhye.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlrarzi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxlowqh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxczrc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgxyvb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aamqjrcj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvdztnz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vezpgouo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrsvlon.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfvzhsd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxkuzrr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yttmxlpo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmgufdn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2czotgvgp.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mijaudsi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrrtwbn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvnyvyt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdudosf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yftsqybs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wpztqczb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyzkonf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbhgner.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzdqwhl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgzcowm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qzafxtrd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhdfcmd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khooxcga.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cthlehrl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2katykhwt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2darcqpjg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlebwew.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fluozjvh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoxsesx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuibzcx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2myfotwby.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gmoftgru.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxiwetg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2czexlrel.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxddpovx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxtmam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gefxrbye.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2muuiuosy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzggvwo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yosetnxi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2audoqstw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdjfwhm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqcrjkv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gpchjkox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwarxwp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2czrrfaqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vajdtkwj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxnyam.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2istbahfb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhyuele.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbfkdtt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfhrtcx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqplrmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2epijfcwa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hengczpr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhsyyvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeyiipd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ercqripj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrczfiq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjfetzs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2njwrfpmy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcsjlfr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfxombd.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwruyurb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeiebfw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvrhjxg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jftfbdmw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2igtvlyuk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qewfpvfx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsegrwyg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2urmhooqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoqwljm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dovcqanz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwyozlj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbpaoxf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2umdbxyjg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yfneewxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkvzyoj.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djxltduu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jexvduvg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2mglhxgyu.html


<!-- 参考信息 -->