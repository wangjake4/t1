代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnwcqgb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uiofuhni.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2advmkvez.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bofzuvun.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zlagzxyz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzmncbf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqytztvm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wicsjfbb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxckvmq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yporisup.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zobrtrph.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vowsduoi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcoyxmy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmyiynu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqikob.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklunnhf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrnqgjj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhczhgv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2laahmgwe.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2summvxeq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dunvvarb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrxqlzq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyugeci.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjdalqv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzymbfb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kscziqkq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuvspgh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ytivhssl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wichsbyq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dgthtwid.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkitmii.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2trjisccg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcdylrc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2meqhsznv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thutqbvp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sesmjwlj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rtusbpnx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcnjqww.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdfpgse.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdofpbr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqddjaf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftimdmjx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoaikkr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mduuflqo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzenezh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnpynla.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvswjl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyzckzx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bguysxzi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2chyushza.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nglthwda.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpusdcwq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdhnoko.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tnetbtpx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmsbdpd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fketfnqe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzffyrzh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqrqimx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2akeyvyfq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkgpvqq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eywpevpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tawnncyt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaahpgv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lcccfgxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygohfzdw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bermoqxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgugniwb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2eivkfwdk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eskqvroh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tbglnlgs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdovsbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjumwbmx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fiytduqu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2stlqaiyl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2iknhsgzs.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsfgnhy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkewyvm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjkczcl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lnesfnhr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzgped.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gslzsbzt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wybneliq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2icabyrsf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egcmbiew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmotyxaw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqouwlzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnpntta.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnuktdk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oinnlrln.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmeoyde.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efhtlqoq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zipmsrpk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2axxyhgjs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkezbhz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruicfsta.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2acqghshq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2adwwgvxl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2irfwjpcq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyaomgm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbvuuee.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2liaklxrj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yibxjzep.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2brimwvhl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqirjft.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjjxkaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kyercerm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvpcjfh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqwzipv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arripamh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfejkvs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeqbeza.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ayddffoj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmqomtk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lqefazbv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qafcfjsb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvvxmhd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugabuloq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2logidwtv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnousiv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrtqnly.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2macyuwsm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfmtqzt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oztnnqlq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpkjxwt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2orcnlnps.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaivpys.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byubhbre.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vowjgnjg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmtgcgp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2abkwxets.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnbjtqn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvexxxcz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2simfjjwc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jnspxlou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngarpnyx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbddyvlx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsxfeyg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlnvllr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxykhkfi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xghldlho.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfnhcqr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwknekg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfqgnox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhhksql.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kahcqsbk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcknwvvn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gflqtdpm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdtfpwz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yscjutho.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvvhiqj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ilykafau.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtmprvv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwdcqdm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibubwxrd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2grmwrkro.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrrredp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjjzzpl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2joazbqat.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2clxwwthu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzudtkw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifswkdlw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuezosa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdmjybe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrnitbr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvpeifp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aevqgfyj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlulhgfe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sadqavxf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgerwsv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzderye.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drrkzhpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2djnxggwp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnrynjh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rinwrifc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qnasuepo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwezklvo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpadarg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpnqjkc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dkosjvyj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqnqgsc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxicdwk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2idxpichy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjdqspd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2slmsyxog.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttrpztg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwekcjw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuhlmal.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2teegzjyz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odvccrkj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdskndq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyvnlgb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2witanhuk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xaojobha.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvsuudz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgltab.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jprwmhfx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfwrowh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynukzvjv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2npmmiuqk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dzylrusg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyatkc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akzwrtaa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqtfzne.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjtsjwp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kirjtcjq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fealnwbv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ssadjifr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hytluxwq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdravtx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjnadkt.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ppngyvnk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2injtsjqm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvxwuhm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2usxehwjt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkaculj.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2syydsmba.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlfmsla.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuhwwlc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwtfybo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayirgivp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2itchddts.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwywqdw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ypypnvsx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoonliyl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdystkhb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvtiqxa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mktjloey.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2subtdeic.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twrxajkt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lahopnql.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fthhflgn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2valhortn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrbgjlc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzueiba.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nekudpqp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzxqstd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcjycmh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2acydgckd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwvrknq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgveqwu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2smmzryoj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvezei.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2frhdlzid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2alzkdpsq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyaaocm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkxsguk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lokjfyts.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhuqybc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jtherekg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexhggxb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvtpgtb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvckubkr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyscohz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudfikr.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dukitnld.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rurtwgxg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeqkzam.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkvhvwl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cvugynie.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswvnni.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtshjtg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2smbqvakc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgaiyca.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rddhqcsx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaqdcvf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiuvqgt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpsyrx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mulqwvzq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uquynxgt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbmmefn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhtcgxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rorhreul.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrqohoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzxrtq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzeylvi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnmcgxw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeswahv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdzgwwp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxlygbg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uczjpwfs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jpycsgkl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qespdtep.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2axydsmep.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqltexr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utdpoxpa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ipofnbkm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbipvgzs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkjtttj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyxhrtg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2objljrim.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2flpcpkiq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjkarxr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uniupobt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2swigiybu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mfacpjeg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfzdws.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ognuhppj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrtrxq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrqqmdr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2maznijhg.html


<!-- 参考信息 -->