代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2apzgmlhj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqghes.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbikktn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bohgktnh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzdeapx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhxkje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvaiivao.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqvofch.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2askgrvrp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaarznm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqfascm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnbxegw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxwyacg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyghbfx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2naiozuih.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2njqwkjsk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oeivlzse.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrnnbic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtajjyq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsoiaau.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnsytrj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhymafjm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ziodozlz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dejzeasf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyrkzdw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxaxgwq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oshuupyd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gdonlpri.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vtejlarj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2udvmwycj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtkkdrc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oybkpfay.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sydyksxp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyljvhj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pulzrrja.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mwldfobj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rehsjxeq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitqhyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqcbpeb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzktuiwy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2njfsnjiz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agktjqjl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yybpzsfj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noxnhspy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlourqjk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgdnpv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbsimow.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rpokvxby.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbqpob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgzrjwb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxkefsv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvfnubp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2agcxkihp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gheeiqfb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsragxq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjncmnru.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxokddl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzjqpgn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqwyjn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cefbfies.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeoypaf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pnurmvax.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpfmpio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrryooo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmnvurb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmycgdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvobyfwr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nchqxkcc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2huzmuxpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwfauzw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nifohaxb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2oozeufgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2djswtbwp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwnfucg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfpihtt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2swoqkdnk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrhkfja.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvuesrl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2teozvlcb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlmdntt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbxgsmf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gupahrkh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeuabim.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ingwmmhi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2elwfhlfw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vugxdsjt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2otmmoxym.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qamxhlvv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyweasdk.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbgnyyc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeddrwk.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cevgkndt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeabpbd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzukeqs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2strfakcy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcyddqd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpfwmpi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2blxaajbc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uanzadji.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2foxvrqod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kridrsei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fevdrghn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yclpptrc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jwksbkkb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhimecp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2neddjgpd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqabxngo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2brnslfzx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmazlcnc.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zytjittw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwqchxe.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpulqvr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrjnlpz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxlcthl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2shasbbrx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yatsnqwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcxyefd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuesgal.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvjlpc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rijvaeak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2brykphyd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjxawuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxwzphp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpwwiwl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlvnupm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axngklrz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gytyadlx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwozhhu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rbginmko.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2othhsebu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2haitqgxa.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoufqdw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfesapf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wofkcgjo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqchmisd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvmidwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvamyfjo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbpctsj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcjceuq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xggglsvo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xctcndqw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvybokl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2boyqfbcq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqkjgnm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmwdydw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2umrstnun.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tqliiqbm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aniisxth.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wjveuzkn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebsvkfp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvrygdi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2durjgbfz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tstqebpx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdepccyf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhibkeg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2avcjiucu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2syvgstei.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwopupe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vogjjklv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ioshlbig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdfcdyz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wedkpfal.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhncloj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfytqgh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sankonwm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmctvog.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvslczw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ynokgdcq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aslnwzgl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrudlajh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gydwjvzg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnbocnc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfokbkl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqffkuib.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxfozcd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2liwebyuy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxxzmzl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2komcaisw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dctyhjdv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wveaqftl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvnwqqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjauppe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2igumryqf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gimxjmse.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxxfdhu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hxisiklr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zsojffrw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2suqbaokn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfkwlty.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2btfnmcca.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlesngqy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lcccvpnd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgxczds.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbtvws.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwuwaub.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjeelwi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sautojjh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2allulzud.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2riycttfl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyifeua.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkedohy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbpwsmf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gegcdbqq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nuatipoz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oepspltd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjgruwx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkwnht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfcpwfo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsoluvy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iutrvczr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gntcnunj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2diaigxhx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2flndccsf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vwitwprj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cekixnal.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsfrywe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqadayz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtedvrfd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xemqlrzm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfbzbyb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2igeuwhaf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyjiztd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fggegfkh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dplgflbp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2camgcney.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rsluykqo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2habitvro.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2keyujpnb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbwdpeu.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmlucdk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfajuxe.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dqualjet.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkufabw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2whgfmumb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjqcicg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2alauunvz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2unofjiwc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxjhwie.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sghinfub.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2eueugsjz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2erqjzzgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytymwamh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhepzid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vasqacan.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dytgnvzl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cawdzgol.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qixrgzcu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xktpbjta.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jgviylua.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwyaouz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbneffjs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtlolq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ecylbdsp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzypthyi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dezqlwvv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toxqerzm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzrpwnd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyjdxku.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhjqkmf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvmoxwk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjjplxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxvdia.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfiuga.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpguqyk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaevxlg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvbtzvl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolevag.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgeppdy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxkgknt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcnnqoo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvylrbnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrufiwj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxtkogg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blbjvaue.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2thlftwpj.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2eeitfbom.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwjtcui.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvrdlfv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyvmtmn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neguugjx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwqurea.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yisqiamy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbbsdig.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sewcfvdn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbozvkx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuymbnm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujxcjij.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkwnpev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwuacnl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxdxbzf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2irsobxqa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ineetqfw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uyznhhjw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtbddza.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2onoudjzy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsmmbys.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnqtsvn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmmjkuz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkszyeo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2thfveyjg.html


<!-- 参考信息 -->