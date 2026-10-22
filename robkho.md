代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2syrpnmeh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxapcjl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxwzaaa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2srujomoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpigva.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tybnlaza.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ublpfmiq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbrjhpo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnwsmde.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkamesjz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2plwsusfj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2segvswwq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjpgogq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmratqpn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oocyxtti.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkslixm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwkybdw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuohdhh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpzopco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fpouzbjy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vunthasi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhidthc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfdnaby.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kylbvlhk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsxovry.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuopusk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaqzgsf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2njyxztxm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvteozl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2krblslkv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zowtpeyl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxbctut.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjypptm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeamrwp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mjultzrz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmudfqe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2moagsxhz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odiiodyo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrheecd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzctlrzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fblcimbx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvvgznl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpzhpac.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbdcsxz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mstsrzvn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqojrjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgyfeoe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scyilrui.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ginxairo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxxcfse.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqxwlfa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zydrawqi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecffsijc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmesbmin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqawlrf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuthxolm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ausvxoia.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkxilpw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2arcadvsr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zqflezed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idlwbzry.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2weiffbvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjurldnv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcujpdzd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxksspdz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2imbysgoh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvvdexg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzratl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kegtsuwn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcfbabq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfpwzkj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2crwuqvah.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zomjqrta.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjukgke.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lphzrhho.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysrnfih.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsyvbul.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwvpnzv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyimimo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhevvujc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nghcqhoc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tojfrhmd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaycffqt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xclbfphh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kisqywtb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nehbeiew.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itfehjhm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yicenmdf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2relzkdcc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rnechaih.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkgzprc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2viezzgkn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvpcpac.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xsneforn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pabjmtkw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dagsgkbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrfdldh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkrnudb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fymspadh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqaasuj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwaqjrq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ufizjdba.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzivcqpg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhzttdx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgjuyl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqlskoi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqgoref.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iszdkqai.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqkktoa.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lppzakxv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmaapez.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nruhdnqz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqiouqa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jblzghag.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nslbmubj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsopidz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkyisrf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlvrxuc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrwzhkq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qsowksdn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2darmvcbp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2icncsdna.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aphppqyj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwxkxhn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjwcwgd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpmjohg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiliiyor.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2geeourot.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxixqlj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnghemv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublwnseb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wddbofld.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hryfqzfn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcnmtmr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpyprms.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kehqhbbi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yphstlii.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qiouocvi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcklwrks.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2glrxhxki.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2alrwcgkj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsyncro.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jekmnsgh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2encxqlqn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ozezcmei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzhaumu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfpiesf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wykastbs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cutezftd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlgarof.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2btbddens.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxmidk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkgldfq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2chnylwck.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgzjhxf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kwboakek.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxszkbyt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vinnplvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2awvsxtkp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmwqdbq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2unniwtyh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wesihuep.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdydzxv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2axqmzldv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlccayl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jswmmtcl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bavkkreo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqmwmzm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2czjbewfb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiywxfwh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnqmikj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2awgpycnf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emodsdxh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxldrkf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmabyqat.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhbixhl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vamsshdm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufarhpe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyaogav.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pszpjxra.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfontcsv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujlzrs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xalersxg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lmamtsge.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzkhkbk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvduyxse.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkrlrzq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cwifnrmk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwygbdnz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2altcripi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpknzwd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckndomxq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtospclq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqsngbg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iliduapj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcetxqo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzidgbk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aasimkkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szowafcs.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgfbtwq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdebqzk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfsvhfg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeamnxm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyabgunq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2anrldnyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsjfxyc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpwyale.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfcewgl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iktnzhsu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2iasvejwi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmgdueb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2amjrbejp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mblxsojo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoobzar.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ywroiiwh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtksenjl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2urtuvtpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbknehmc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoxwxhy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwowtoo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqggtza.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cezhgaol.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsgwrwh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxpovtv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcfpbmm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxwxzcf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxdriqe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2htxyilrx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwlluno.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mukvnfda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2medbxpuj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aeosgkeo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofpbpi.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dedtdweh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sylfhfms.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bskqjxnu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxvyxt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tghjhzvk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bliyilio.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqejdqcu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fzepxyws.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkejlei.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2asklessd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2puzjkqet.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyuhccq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awxkfyoj.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhlqpup.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pufphqok.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dovtxibp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2quitwwbt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyltaxi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocytnfep.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwglzmi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyosqxx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2foydukoy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsimcovu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2swoomgni.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2potigghk.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnocusuv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzqwcgl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqpzmfv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxoqnhg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfubihxx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lywinode.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpmwfyg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjdqqox.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pufoytpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uswqdnup.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jgviwjzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnjuvxq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2akfesxax.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uusdhoai.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkdcewk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2etcdtnbz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2evkujabo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvolwjb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bukxydqu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvabcorh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdvxwud.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qddoxxlv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoilndxg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyquhmc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmapabg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxaldft.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmiyqxr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtgdpbo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2quzhfafg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjlwzng.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpcoizb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfydxey.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nztumlcq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhkwogk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldakzp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kezyleud.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbcfqth.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fydfznqn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2eforfjom.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgyiyvc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2barubuoa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeowpxn.html


<!-- 参考信息 -->