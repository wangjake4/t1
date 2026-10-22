代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsxjmzp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2spgqxawp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoopjfn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uhabelmx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmfhxuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmxfzf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiodcues.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrvvkgh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvatoie.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpaylug.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2luyhbnau.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tornplqe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nojlyyxk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2skibitkh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfpazix.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iikkeosd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aruyfmty.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dicegfoe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2szwnifri.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2adnhagil.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjurxin.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwzmijv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvkbwvb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcbfboi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2spatxece.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkqpnma.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsrhvfd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdtzqfb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2virrucnp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2czxfuwot.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eerkdkrd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhfzdsi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcspauu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdiogw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zhenhkou.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuvevmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2exqzetdg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjngttqp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeyfwo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2efqbbbom.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjevhmhc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqmmjjd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qwikzfhk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmgpkdo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qmileryw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkqbzxk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtacejk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ujljocrf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwzajzp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nahwfgvy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aivtkqtj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sinaadjg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrcpdna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkheyyln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lszbrwja.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izlcsarb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2smljvayh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfllpwj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmosgbcg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmqzpwt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhxcvbs.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cprebtra.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wekhpuar.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkyibyf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxkcvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjhmjra.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pssfvnqp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfibyxi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tsatkwgq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fljtdtbz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2notutscr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2spltrzyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrfnabe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykynefgp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvxyyst.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhuzbcw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhzlvxj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzyzrdu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2berzhovq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnxctbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiusojo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2itlgwpnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plulovlo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbmxvvq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbotnhs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qperzdzo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiajbgf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mpovvdfd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhsierf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2skttxatg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdpnni.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2phecaabc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kabuvabo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2auqjazfl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yljzihzk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmmbpyr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwywgprt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbmqvyc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gedvdunn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sncrtrap.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkfnmqc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwlernq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhavbzrh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiacvms.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqayqbx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bewpjguj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyxkkgq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqillnp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sektrtyl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tcveuogy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhpwdgg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvomzfhb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qjajgthw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjediie.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2avtxrrvv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjuqvuf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnpefvo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2szwiorix.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvvgqsk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2snutvptg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfvbgvl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfxfilk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytepdzhi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdbvybi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipingniu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2stqarnnv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uimzbaze.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjrwwpr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitwktme.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhggtpk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hafoujeb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cagoruak.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtijgnp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzcbmuh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqriqxsr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2colikdmh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhzsvz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nyavknum.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxobchl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcmwsls.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2czsfmtfs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfqigmh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgneudvn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2scwntfsz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hrazhhja.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxshuwc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqspuoah.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ievncqla.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdwimbw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fobvtzsz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqzsord.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2csgosevb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxsufha.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pthpzjfx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vukkcgjb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fqncnjvw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwomobhu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ueainbni.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vljqmrsj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eagqmppo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2owwqksxe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlutwlh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoushyj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhsfjrf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2loivwxbl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxykelr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvoobkc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzdazny.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zacossuv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ribprwni.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rctfbufk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnndyhqr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2txhjcycb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqtblpk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebziuxft.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hczlpxbo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbqdjfx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgajhad.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jramngly.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erzskbhe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ozapbxjn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuynnyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2euloawjl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsvfjil.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2njxctbfu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyiewgl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvigvif.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwubccc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwggxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyglnqck.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dganssrb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyeilkz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2axrvgnpc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jknffydm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbqbswn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2khohyxqv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuyvjhb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjvriha.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdocreq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcvufsd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwqfvcl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpesimw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkkddlh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsysawe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaljbfq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmwsyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsbnptj.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnlpvlu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnwneda.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbwwpkf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2serajsbz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vquymqaw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkotlypm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdubqyjs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwogxav.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2krqthxrf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bosdwcdy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2loulxgnj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xngjvcri.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrgheoe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqolbhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxlryaf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlunylxc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxiktxq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrkxhge.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vifmqouh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xddqisww.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2otecxygp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnnfsou.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2whxeptga.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjasndk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvoyehh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frxrgvgy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlxdyrz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whqvxrcj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoyxxrr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqrayom.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvwrzlg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhssnqr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbazprnh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudpcydc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwcvbv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjpozjt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvdtctg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsdcfct.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2geaiywjo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2euoxkyru.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2utxhftli.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unrpawrt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2migfnkao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgcpuu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfogzhn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2odaluppp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzcoapz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flwoodvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnhheua.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oybaxrcg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyroguhv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmzigw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2itexeino.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpsbjmi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxuvssk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbrfuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrxwour.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxrwrkf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhhdsrz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ricifydz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhirnge.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxtbdgu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcohcce.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmqrnir.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthuopat.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ogixhioe.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvooxlwq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wxltlige.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexsbom.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgsrckj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sflzmxbm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2reulboek.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyygnon.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfshcqc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cbymqwiw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfkysok.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfzkqkw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2llaknmrw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bijbsfqf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzctdvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvidwsi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoieosc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnysjnxv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvmoklv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmxknhl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ioczrueu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlkfyww.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehisszex.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omviawpk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvvpgkk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzzoncz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxkqjxf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lajoxdvv.html


<!-- 参考信息 -->