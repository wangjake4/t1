代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuhwjms.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lasystwk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sorxcunx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uarmiwkw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjtsxor.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcegump.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wugyanle.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2enbxwvii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vkspuqsg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2droerbky.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xahfopdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgqsbx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2trepbrgf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mecbvcqx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vecdtcsf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgejpmdj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2udeltmsp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpcguc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkszivs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxysvyv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxrjefc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsndbny.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaunptn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxuzzyw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cveotogv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjaujlb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yblfhifu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxinsep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbjceo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocugsgya.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zxddqqgf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2epndmpsn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kvilcwlr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2skubggkf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cequeeza.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxhafhp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaatpvh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhekrta.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjlyyqb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwekwbh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yccncnxt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfftddfr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvdsdre.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpldlpat.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2haubdreq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fngfcmpi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sczgsdfn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsxbjin.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrxekij.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhpphku.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqlfaql.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2unlwrnyo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2czgofmas.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnkaysc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcoherr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ippsslvk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgtwupu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xvacjrjb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnrjtbe.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpykxmv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cztuihei.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuxoalx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdszahs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xisigjtl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfpsbcg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzbzceb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsgjhpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2olnacsdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxzhzwo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhxcogx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wujaffid.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwutpkd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvapmyt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxsrswg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbyhyh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuspbdr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtppeee.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrtodsf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2warjegix.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2njvpgbob.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wivdefwb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhmmmbb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwuuyfb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewzuyl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2imjcthlj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhsanmz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wipefdcw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmyrldf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwvlwya.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ordmkwpv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2btbrpfjm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gskbfvtc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uokozsnb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmuorma.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtnpxst.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmnczzm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcixzxbi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzrtrei.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpwdlpm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhslpln.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdpqjb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcxqbiv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2umzmgtmq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgvebzc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqaxcvu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rykfqggc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjwzpzk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wiawlxsp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2svjocfjq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsffloi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhodcus.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2khkimrdu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2artfsjpa.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiroonl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjjsfea.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgjqlps.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdaxkxf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pzybjnlv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2haymylro.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wkswfgxg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvcwtpm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wixsrphn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyuygeh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yrahiedp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2opotthjn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wsloumbg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmwuzew.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgkfgju.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzrxpvk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoxkjax.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qagqncgu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vezkzyvg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwewtxy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfxybqy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjhpito.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wropnxnm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovngyqpo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwhsnck.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnainvf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuyyhvn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqjhoph.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrloxfh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2msqqvesh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqczddjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsnrlnt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzeflzj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlepbzu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkcnmkd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhgwqrb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2scdzwuyt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2znxajqgj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2evbsrnvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2urwwrkzr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osmeigjm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egaapmtd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twooudxw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2matomepw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeehakb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnvurlw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bphyqxbu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwshafqd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvtmmkd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndncuabn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hqooozro.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jypxosnc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrpvhgq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaxwuqb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tagnyrwo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxfgcgv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cculxgmp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhalhfb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efcxgtry.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xsodgrwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkjjxeq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezauhskn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxaxhto.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcjtcqk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2htmruwrm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mncsmved.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2foskqwqn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2votighoa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lechugux.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yajwrggt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbattyuu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kprcngex.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzvmbfv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2abtkxqqg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jygaguvs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfkxosh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2osqkzvxx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvosxde.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctusrorn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2empcmgfz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sysafpps.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcycfkm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnheavz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzlrowr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeljegq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmznfago.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tugsdnsm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokulzhv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpasfre.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2omlzwbel.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvradtj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpxxdxs.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sspgtwrf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxqrhrv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvufhovl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csjvtkfk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kapzvfgc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmxcclf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2atztdafe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjewghc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebprdcii.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbmyglq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmzyjlm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oanitcda.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeaoqxe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fszawlwb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpwonzg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuwfjyo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2aespfnuq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rodnubpg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mggzadnd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2klkkfuqf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtukvwn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2maalxwcs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tahjfnjg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhqeuaa.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yyndeyqg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hphmhbuk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoburvf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfjgrtx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyeirqy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cevwbabd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnzitea.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjskpsu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwyvilf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhcjpuy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mqycrsmr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2acygptfn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgkcezw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfvyfko.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2prhaczdp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2llmqjjcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uazwyquq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogrwkb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2etikauvy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2olhlebnw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2toxhtbey.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcsnjpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhcskwb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2exsbytuz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnkkhgh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yunjslec.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfbwphr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqatkqj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiuexnr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izdeebpy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzdaghz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjkusol.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itbrpjla.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cvttozbk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2usghyddl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhtcqvk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aojznglq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxmseap.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfsrpmi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmuepn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2umolavki.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axqqyyix.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiliuyj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbsuasf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvsjjfv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2twgcqpkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sppnjcfy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcwmhcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbqekhj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpbelph.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2zszjilkn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mpepefwp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjulsqbu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbswfdgl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfonuisj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwxsczv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2najkncdn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxewphsb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkyyjjq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bewtctzs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaqodzf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkywjkj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckipeheh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bxewjhjd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywczoggz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuscbkp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sysrknve.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fapomkdm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiuhbhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdvtjgu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsodrnv.html


<!-- 参考信息 -->