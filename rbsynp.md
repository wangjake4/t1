代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lorqfokf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzhbllc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynklhneq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2khyntzak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxwotnk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gadhikbc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2survtbhr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2keoztvqb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxlalgi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2acidivdl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzedbomn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gheorsng.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2sicoiexn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmyvdqo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iclbypqm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkuhjdv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoiexbn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbtgczw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zywtfavz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dprepkiv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2drkpuopr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2otcvrojs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdmbqyk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2khxbmikd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2inszecls.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlffrxs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yioulzxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lprneciz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2izovqrun.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoynqpn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gzukcdgv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixzmlc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgjniqj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aezbzoug.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpmnmzn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozldniir.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2edykameh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2viixskln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2opguevge.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jykqomlr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhhlbmv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwduxkdw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beblhkgo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdtichs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qylmolja.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjmvwan.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlifpzp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwcxkgb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyvrblm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dctyocfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qchsvnqm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqamdrea.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfqwcwt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pequwftg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpxgort.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kddhuwaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2irxgqmxy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kucnmdin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2iarfubll.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkuijrx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2umyrezaq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfmiosj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxiluem.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbreouy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrcelvz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2flbmlhen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olofthqa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dossanby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pukrdezc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaqegef.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2writwplz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrhvazu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gcituibl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aohdaxhd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsrvoxw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2byrvtacc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrgbvvz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmcrdpg.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2kpttaire.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptznlvlg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qljnkxji.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgyxgrj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsupzlub.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvklzxn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlimyknq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2punublwh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtknfs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrfauu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihexvhyc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mobnxlrn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmucblf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgssbtv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahafeagz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sobpjvsw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxjedjm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kahsiynv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lzchwniv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqhliip.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iswmuhss.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaqkeqv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsxkpca.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eopzzanq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdhrxlo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2somsyypm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvktywzl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2psgnwsrp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrguiljg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrqrvus.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2navkzlas.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2itmwgknz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczpkota.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzodhre.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmifxwgy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxydbfuj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuofyic.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbmrkyy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2avfneokc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvbvdil.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxmqwsm.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtizdjg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2snitnmvd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gashinai.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wftvazjo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ayceanzs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybojnay.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2glmzfrfg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkgjfsr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqsgvkq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2plnzyqro.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbttecf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gialiekj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aasyotkx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyutulg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpyaepy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlppdob.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2inydvcop.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gelrhtza.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrfgilo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2obzytqyr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lphzxbir.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqncfwj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhviela.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvhweuh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mokabnzw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eorhwppd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrsvubu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpcksxv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kxudqbku.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtemzat.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrfvovy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2whiojwgd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygnfsdq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cxckeuyf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdfhvjl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ganvdhoc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzctceg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eathvdwj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gisrkabb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2izwvdllb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2znbvdtxb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gprxcbvx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dozoaxjo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwsrmsn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaawyot.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2galbrxmn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gstwzpaq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2halkybhl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cwclhhsc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoajadf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnxwqhb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lscyldcj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmmgvge.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyrogqc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2czucjrsm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uleabhpc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oalkykgw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ieeytqtb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrodolg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gudtlnnt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaebtpk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzzjgvw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwomasf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdrifrl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkpspbb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kllfoybr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fsplbmfg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcsbatu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yswfulcp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbqxvup.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2emuvlobz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vguhzzru.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2axcimuhq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaoiiaz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuqecvn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2relkuujk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wspvzeqx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcklecyf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zipbvuua.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxubfivg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqllucz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnciudx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvjhkbl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbotaelr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qiehiarm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cujlijsa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2woqmjzlc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqoolyz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkynqyf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyhpfas.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybytqoqu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkqijh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugthgvnv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cjunzmfi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhcqelc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2twrsvoar.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvvtmlh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yngdqjsz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyinxbv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2motsbqno.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhkplxs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2szftmwoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbizuef.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbpprrm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmiwyw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtwldnk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcnomjc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2okhxwtsx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeuhzgh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjhhloe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkjunqh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjrgwbx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zbukznex.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uthlfoto.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmzqbps.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tekpdutf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmchndl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqumbqlu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wchhcgrp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpzflob.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2itimhoqt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrhkkqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmdexbc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhuajjb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2shvozwus.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbtklvy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxsqkgj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2krdenbkl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeartfl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmtnnqw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrpznrt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsykbhwo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsnruqz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmyikuj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwjatrf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwgcjkd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhjuxht.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jskllcse.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glecvgej.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2teezokqs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgqpmmy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkomjht.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gedysdzu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egcziexp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jezpbinb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmezcjru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgqelue.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgydnfoe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxuauyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuczxcj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2minenvix.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2onigcbie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvfvqzq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hupuuzuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwixvmae.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzopaal.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkhmaae.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnuzmga.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvdrlnq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuibgyh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnwbvxv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rskmkjbh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddetzmot.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdhaqbq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfojyu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzefahw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aaorqrhn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvphcus.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pihhdntw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ittghglm.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgunxavr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tamvzovy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqnihya.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2brsjoeha.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkmfwse.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2evlonvxb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdnvnga.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhnyiat.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tepixbgr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuebhrxa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqndade.html


<!-- 参考信息 -->