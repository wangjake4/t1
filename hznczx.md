代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtsgzod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pisvjcqu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyprnevk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njdbbpqy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2byckdwms.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2soyncotk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hznjuqvv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxlvhek.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfshmxsr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbbaiei.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjjnxnp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xvthrowz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejscxycs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzkdnsy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlobtpmz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrlhbrr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2asysiapz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlhgvx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlktweu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrqmydl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pysecmjs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxupdzje.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfedrpl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxgyqmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tatjvnlp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aokbzwvj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhbpiif.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxowxh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgdmjcx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdgnxsy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxqhnbo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2txncelco.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjatlco.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdfeazo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqducuc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdmyujx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgyqds.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcorusn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpfdixc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwmjehj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kedqimkk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyppdvt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjxzppo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xxopzfya.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcvihoi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyawrqs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gexnuiqz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2btgyoalh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjeutic.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uccziwci.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bozivdyw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uflavfil.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jrekhyhb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjehglnn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiihrhy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okxgwoak.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgveljno.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugadufpp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzqkmrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2skpoqqjd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsntygei.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cemyvebe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phhwmwdt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlynxewf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ukepqdlz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfrxywl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqngegv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fqguxakg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ierultzg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmszrkqh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkoxxqb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfurwen.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjpwntd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cysmdnpm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rokjinfe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrounhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlswevpa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cprtentg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyujmxww.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzkctdm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oljviafo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmynubm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxstrnh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgaccwi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2haevopqo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2adqzglze.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2afbznqyf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2azupqimi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2itlwjjjf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qvziwldw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpwxbjs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljrkbh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zesjewzo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2azbrgtoi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxdexcg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evvcxvif.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpsuwoo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhrcdby.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2evxflhqs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ambwheyq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pphehudz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtcyicm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iafbghqp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxafhlxx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bswcfhar.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2svylxcnu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwehyczm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mngxujsj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bbffcsjb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlotfur.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zczwblpq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhubvha.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pceashok.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiupxro.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tgefqnsd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bedlmtsm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsktafty.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiwegjg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyrxwa.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xsylezdr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uinzoaas.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zusviwva.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coaxuigg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wlttiynr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvclfvkh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuwgzde.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aldeeubs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcymghg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aacbnepy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2omsswdzp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhwtxzo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oezuwshp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbybseu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2netvvfbk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiiscpl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kvenopkj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfcqddn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmhuioo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlatium.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kojiuijl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnqswtj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjyubyf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eladzgkt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2goaotgit.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhauoitw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2smkwthkv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimgqdan.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwdsffv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xglphtrv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqakrhn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvawtnt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlhqxab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrzrklq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iahhnzhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lorvwsef.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2saehiwxp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbzlbdp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnxosoy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oppuxznr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrtdqzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqeetzu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2avtmkkrh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cknktjhz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrujinek.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqfawuv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfwayxk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnlqvgi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uujquxxf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrxkzbg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahirbxvn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbrtjjw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ncluidio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxgpblq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vskskfmw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aneebrfp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnxzzmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsnonuf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kexnglzh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvcjaov.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2agxzfyql.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fddbggoo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqypinda.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxjtsjt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdonrfji.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2huwyhysq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2davvjcsw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iveumxuy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdsrcan.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edgxrlym.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcykfvyv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtkocdl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyghkwnd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvavtaw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvssumtf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqoxol.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcdolme.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzgzcll.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlyhdbq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nusoydkc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlxbqyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkwzjle.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqdhxlp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynffofdi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmuacsy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ednjamny.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfrabds.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2svyusthk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmwdfvb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwexyngb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvonzur.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2clapwdcl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2erouzrej.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqqsyob.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrpoowk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjdpbxc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnksktb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2slyxxvbm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phladffn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2szxzsjou.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnfbmqi.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvibxkx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msqyerab.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxjokhd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxcebfp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gffedeyh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2webmvlal.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2skxyncyh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdpeqp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdwgwgj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoxikmg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qelsztle.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbgfaqa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzpjxnj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixxqpik.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2okoomypd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2txfrcxqz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwletpo.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzxdvio.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjsdxue.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zrayswea.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsprajo.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxytshj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2biyhpufq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdsfhyy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmfywky.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdjjgha.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2scwflkpi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkefwdo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhzwzul.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ybstytwq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ascvrubr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gpralann.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvaiexw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpkbrsp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbqogwi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lohullly.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjnvvbp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdwrrsy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qntfrssa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzazvls.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2poptjxjz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blxmhbvp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsdlkpu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbwmjbz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njmlidff.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfruqrn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvjeayi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxurnro.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fipdbcjq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quztormx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfwkauj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvzgwzd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfzmmjp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrvabbb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeptvvw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiovwiip.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqxrcwu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwnwxcn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhphtnm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvleufc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyganba.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufctieif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2adjriwbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poryckpy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhqkkbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbugrzh.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzldjow.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2haxavjaq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbbhck.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rkctxaxs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjslrfwi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwkltll.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjjhxsb.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlhlddw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwukwreq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkygsyp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhjocuq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kysdgmpr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pepdonks.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjggrmi.html


<!-- 参考信息 -->