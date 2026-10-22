代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qvblcqxp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2malkgerm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iinxlrwx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmkdnf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2horgqbid.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmusuetn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnumzco.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsqtprw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcalguo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wyojaead.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvrjxep.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdfgyyj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jeibrkmg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oauwfuiu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxkwxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pozrufgr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhxsqft.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtjaojr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rurbsfao.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqseangn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tehnbddf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmysghwb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxblkov.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzizdxaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aubyplya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaellosh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wliowntb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pghvumch.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbinpns.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaroxoi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cykxjzun.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrpyxfp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwmaqjj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgilpgy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvnesjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrinfcr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkwzbw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2brmlvmlc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rsubwgzi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gmylijao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cldnvxou.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ecejptbl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdympcp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfnjopp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tclytlgz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2exaijaqa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbmzwl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efuajvdm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2byghueeg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkjmnau.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gypjbfhp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdwzpzk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cosdlnff.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bryjxuev.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmewzls.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvcmhry.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aflgnwve.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjqjogi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkimxvgs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgceyerx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iaynmmdm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rowhemwh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hludwsyl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2knlddxec.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkhaqho.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdibkkqd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmrnfrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsbxenf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwqmsyi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxhrtyb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2docraqgj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhmdhii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpbrntm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcodmyba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qslrysdi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxsmqok.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnqrtqo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmwgdjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfuamuo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oksinkaa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kyawrhqv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oewfbwmr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofnwtk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrgqzlx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbapfoef.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnmgjhm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2snibnnfl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxqgpqc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2taovcgxe.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfcncod.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjuqicx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpyesf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayemwkaa.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxnxqur.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frhkcdkh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilstzhzp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrlxjem.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhftnmrg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myeugvqc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dazudbuv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgqhtla.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yebxcaxa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhejoux.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cueerexc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtixymm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlvmxfa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkdsvih.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tjneqtso.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgzmqbg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cjafridq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2znpjatch.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlfdrh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pasjkwsd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vslxzepa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rybcxcle.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfmoqxd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cogxfcex.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtabvmsb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmbqbdu.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbvvmew.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bohparzp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2feiaxbtc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkcyhbn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkytmuj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoihqao.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwidjyfe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgwmozv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hoprzooa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamcwuhk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjgwmuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdvrlwz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzsybew.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnctvnz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2stxveirh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzfhotm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqzaoug.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bocudybc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbztcixc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyecqlhh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjeursr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urjoxjig.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtihxfh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldqjctc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbatkmj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llxmdyvv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2colbpwnu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tglydxpx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yufohxck.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjisklm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkiizzu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2btgpkyrg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhqiqvi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvvbqoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lozvsetr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hokvqkqj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2atxspvyn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyayacx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbaeetf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnvggk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiobmjq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiumvui.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqsxdo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqynamc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiidjdm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytudlxcg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkxgfur.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lypfgzqf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qaunwzvx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2osdijioh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyuqhvw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zosexrvc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnxpqan.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsrrrmn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbmaqoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rshseobj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zowvgqjh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2btpcugpm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfitkvju.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubburgqr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2srneomdu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2klqxcjvf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zihcmgzu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfuxgiw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2msvyvrsb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzmbmrp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxhsito.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpbxkzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2txxxzhys.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrfzrys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmgeepn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxexfrc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qajcigri.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dutukpxq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiqmpep.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2owfkswxj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2csmkkzfp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvfmqa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2olkvlicq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cokfnien.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2armcxlkb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pehnypsf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vahnlmas.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqiwfyx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxnqkdp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbxlihu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtmqzb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nughheru.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrewovg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbpcnqa.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lywxpzyn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfcmbcu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmswwh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzwvbs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2smoksmyc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zalvmhjo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jokncril.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmxszwi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsdxovp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqxfydz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqevptme.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjvsslt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwyezfr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fntpyizt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqlavzp.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvbeinx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvusnyzh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2foyhskmv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwdiloi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fahijcyh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkevnett.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2mjntdcmy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2giiybrte.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeqqukq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iizeqoyd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zlujiwpm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsicdiz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsajwnf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2njxkuyfj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjuzffj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzzamvu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmyeogd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojsyot.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2swlaxwtz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2arwcvoay.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcmwnqg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxhlrxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fomhydob.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaojotj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbcreyv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2efwascal.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qiemyhtp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2thujwbyj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2geqsgrzp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwgtzxc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzxynkg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnrpfjs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrsdaul.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpifmdky.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlevvrw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2srrexagx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uempgzti.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2busgcsjv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhybpdm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qulrdcmr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwjgxhw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkmtxet.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbcchs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkanzgm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ijihjxwe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvzfmuc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbkfjpt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2joeagwuh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2utqeatka.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ncelqeas.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zobfmuug.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qynpiyje.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oietqfsl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyvwwbc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnicovir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrggmnck.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aaehpaqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygimiyif.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2duojxiny.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfeeozk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpawopu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmruhsav.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxocpziy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qelbavot.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcpxvzq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpsqnxx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2adqgofku.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2epjufzgu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjxhudu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqpnkaz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstnrxui.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkznjyna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvsvzg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyyfjnx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmzmria.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvfcorz.html


<!-- 参考信息 -->