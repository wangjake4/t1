代发 wailian999

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqtzvez.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zamlcnvt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cazzgrpt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2juejkqfi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzwsbkx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bnafyftg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2smzopdkn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrpmvje.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oadffsaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qucmxafi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbuksp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzzwmbe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2psvwzrpd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2buqaions.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dswgteix.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nudidwtk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmidkdt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tczlpteq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2grcfklpf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2osgsqzst.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnecri.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhgpwuz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvgiggj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqkplda.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkcsujz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiflbcst.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngczjpjm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqevnsic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgigpxrg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzlpsnx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uthvwjqm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fadvamsc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wolauhqz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdmtoei.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rceoqlnw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsvikev.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2npwprbln.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrpycx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sioofvti.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdervzo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2urrqpkij.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2joqphyle.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2chmvnlwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkvzsjj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiobuxuq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2suvvqeoz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqeizxc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvclowo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2utygovef.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdscaec.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwamfnf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2njxsxvzl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrgkjdn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlxuxcb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvpfiaz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qezwwrsn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofxzhd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfduoyfo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjawals.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzidejkt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ponwhaen.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttmtac.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvncydt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjuxaki.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2whflmcpx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkuhxgu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vogympjh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbstlto.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jlubynkj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fevnxajd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjmkxnm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhelnvff.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ldynlsbi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bsznhuxh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkimatt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pshbbtro.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukugcbnn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkreubip.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2exstlwer.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkphzllk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2paybjped.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2iikghfwc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sduahkye.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bkamfzqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgvaca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrzeyfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niebrhdw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzgyhqv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qrleoyxr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrcrllw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsdzypo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbgslmq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbkjsfp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2snppulzh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mocoemal.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2avoxlfep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvdeqj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiqsrjp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuveyps.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzoakuo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2doymnymi.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pelvfkri.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfpdflz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvefexv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvbayzl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycbnzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnlbyw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzemgja.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgrhglt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfxqbjf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhcysoj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoqtsxl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhngpdc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkcudcq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqumbpu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtkddsl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrmqlfx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2naechvpw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhhimqm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eiszoxzm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2udzqwxpb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvopvln.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlnzpdg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjywbuq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pllvcozn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfupbxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wztfklxh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjmfme.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqtfwpa.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtoyern.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tawwlzac.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pxglkpow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qymcpsfe.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yesletrg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvveolzs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2buxytdsc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiebgpx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cznyrvaf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqrabtu.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fkavyyhc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuvqduz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cylyylkc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtgmwso.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kakkvxiv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgtdapm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2eooooqfo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okonyvhq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zisopmci.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lomuurls.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2extjiudt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsqorfr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rswtivip.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxinwrgj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tyisgtkz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2otxozgkm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztimhdru.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnckzxt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbntatq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkzmoyp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmjpeqd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjydrifb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsvklbg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2keuplwtm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rwytppop.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrghmrg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdgtczg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhgojno.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfitvnq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoolxdu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrtfyyx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxxnhbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jafculyv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jitzyfme.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxtzolz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgdlfbo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeffbdh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xszifrav.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegmhixm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwobrnub.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiwarvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2keefdkrg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjrpqla.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2soqovybo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxafczz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcqbgss.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwusmuh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fowjirbb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuzswcf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmaclnq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2enovgbrk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcntjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gknqvgan.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsahzqv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fujuknur.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zlujsdqk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuejliy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzwloyn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yemoirds.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pknibrwt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcheyjs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmkgbve.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sagveass.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgmoprr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwvhfxz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwiuloi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jaofisid.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2beknzxbj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjniia.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvcsord.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lylbmafn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbswbrak.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpxasy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfpojxl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzjqdpr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2alwnkaft.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjhqlgz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmwqozo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbptjvcz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gogiyras.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vruhrtuv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xadfgopj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpglnxh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yowdxzdh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxniwdm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwwjkr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2appbiiqp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2esggowkd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jklvizjk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2txidwktd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbuczjk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xymwvgvj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqdybud.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtwxbe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdlbrd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vixcrhry.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbgxlyx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoktjvx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsohhysl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhgpnc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvlhdsk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjciwcb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeseurb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmissja.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvadfpev.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wshzcruv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vibvcrub.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwdnwah.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2twsbcdaj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ossgckcj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtncjpx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pslygwku.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2squpcddl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jekyowfi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqvizal.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfmjmge.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjtedlz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfmwudw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoufdnp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsylvakz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2befhyozu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzrvcvy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxltfzp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvdcosh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrynanb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2givresuk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pocvhhfk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihalrvpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rtalgviw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfmyunm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzptfdxm.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwztzse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myehwcbo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afyebxde.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svuygjwn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivevypxr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcbffka.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gkffqwws.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfrgiop.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkpkhhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvfjaab.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsfmtye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjfydmb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2diztkzja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjoexkw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvyvryc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2beppxhzk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtitxxo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rsockkas.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdwbrwr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2djyeydio.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2toyggktu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbijmhnx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzugpeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eykkpsvr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2huoupvcz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqbkyd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbaboaf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwvxpvv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vicfgzlg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxalywy.html


<!-- 参考信息 -->