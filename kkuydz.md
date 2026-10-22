代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgdvvva.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2amzpoths.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtnaeri.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2akqtlojx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xidkihes.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dazrumfh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdkguow.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvtxqez.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgileium.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyybjoh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jledbzix.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzfrmcv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2izdpzyxx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwznnuyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxvpevq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qjltdyod.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpjfiam.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lropfmze.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuomufja.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2whlwrfig.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2emvedaae.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktejqwd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qpydgnrk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqkavtz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbwwqyy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeuaggw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cibxgjvh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2avmqyner.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpqjeom.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ogealtlz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxlabgw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgosieel.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2csvvtsdl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxpdnfb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nnerpuga.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqguflh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eubfynui.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxlcxhz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnetyedu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qidppwit.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmltzf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhcvbsv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcwbuoi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmxttrk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiqthxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2taxokbjt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mergyqmr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckddcyli.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmqueew.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dasasprz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvjzsxv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtkvwu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmbdxmv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dngjjfqj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoykdty.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkaudyf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuxhqku.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2arjckyde.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpwpgml.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrflokd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blumobxp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjnxnos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnvzjaa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zealtmlo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtfvkad.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxhqtxy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xatgvbgf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxykfnd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnwlxlo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2coqwhdey.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhykazgd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tomtvzos.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvoucqf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegbfmk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2smhwoafy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdwhiru.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdlpoqv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnjdiox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiazepkt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcjgkmc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2duolotvo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtudmgj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvmeeqa.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnxctg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lidazulr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgmtoqt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wckxqmeo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lakoojlb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjondkqf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dctoqmtb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjsccdm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2guthepoz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kymugelp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2srwgkvrp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcftttt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgkzldl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sujcnqfj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtcgjdq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aquakdey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2baxobsjg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbyrewg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oxridrys.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxspgov.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkzfyha.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrcnezs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgvryqv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erzvswea.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eieybsuh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmohrcs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdfjwfg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrnsgjj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnzjyxz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjevxvgq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrtwqv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvffcvf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2touvykyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujzrwvl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2naskcway.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lscpxwby.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rhijnnll.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiscjtu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xesomegw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoypoai.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbfbeff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2taukgbbt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbjyntw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdicjqu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkxdxjv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqooojd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2puworhjo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvmqxlh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yflcxauz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxrifoj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdelzww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptikci.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rgywqqec.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2udubuyko.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjehqmq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjnuktt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvccpaa.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbbguev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsllorsa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2quwloerm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2edunzxzz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhnnste.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yirdgfqv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyyljqs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwkinuk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsnpgvp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuiadxt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlirokhb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdkvosy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zihpuwvl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dezlpmbs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbypswy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrcdwts.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsobrtsr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hncdubqs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjathwp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tiemhwdv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfcumyv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2paetiaks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzbyihq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efzpwpit.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrzvfnt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkuonkt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gamtykhp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jotdalle.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkhvinv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkgoxcr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2slobdjpz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnbwqxt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zehwbjvr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzwnqzm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xqanqjzv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmkcjqf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwekyfy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwehmvp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhjlhza.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqorwqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhfmgsn.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fftpgfpa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqtkcqy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdmisop.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dztifxmv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnodxxb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hacykxoc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2iswzbrvd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbklgvnk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kajsjhvz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zucppdwu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dawbzqzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvksujqf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xymyjcxj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrovgti.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpfvuho.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdlfwzb.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmizwsx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2naucqcfp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gciaiwbh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azbpxnmg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmkkkcw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gftzmsoq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbrtmbx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfboenn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfcnsih.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2verrbgpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvntncs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgomdmra.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqrwfhb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzbsyr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyiqial.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbohalw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwiuyft.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgxyzvj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2npoolezv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2msvcxsgr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadktvc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2apxtoree.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsyyuip.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkchiozl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gvifrcqb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaxwsxw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qudoaaeq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2veavznvx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdprbrp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2faikukzg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2atdfngix.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmykrvq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzyjiop.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2adtlovst.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjklwbv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwajdgeo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jznilvfh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipijhxou.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqmgear.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jelpymvs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdcudhf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qrubdbam.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpdbpjh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhydmggx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpegygf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wugdlsuq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xguwwttl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoewkjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzyigtl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xtswsqgw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzebzzl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuwtnyw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udcctslx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hichpmys.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwtwbhj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqxfikf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gabvodax.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxphjx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcuiinu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzouvis.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wfripziu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swjsaxfc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwtyics.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2thvhsvvm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgnypnq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nifdcbik.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgmbhd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmizval.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iodnxjzm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbebpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnryiap.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhonedj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igjfugnw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbesvzby.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuqohpi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfssmnq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgrpmir.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuarnfje.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stmeegsv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2erpkaaja.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2quazgrhi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopnonz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgxgeod.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvqhpmv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2defrlvyu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlpvaqj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlwlzcc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcrcjef.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfchlynb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlwhjif.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwypbcg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bemtjnaa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qoavxvwr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2svuwitlj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwxprx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2azlbfpqu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfgghzy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjxjqan.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwsvmwx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2expwqtjh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqibkmup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wtppufry.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsnkqsa.html


<!-- 参考信息 -->