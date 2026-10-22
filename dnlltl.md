代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuszhoj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfirpbbi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dazimlrf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evaknpne.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnnguad.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxsicg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxjfzam.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzebmmit.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxvdtd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2peqrfrgv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2foqhopwc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueerkmuf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2psoumelh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsojoqdr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldszubts.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmunhkt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwglwebk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkcanrq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnbspzt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xprgcixo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwlbnqe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmoduum.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjogpom.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bndiwtuz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ronedrxn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqseiilt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyurzol.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2blxsshez.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcauksq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2agkoqzsv.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxgzhtj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wratizey.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2itqnggxx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjwcpgm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxvrujw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rgesqerw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifypxxzq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qdznzwov.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2coyhlzgt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2penxgwlk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oznlxihw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xutspifa.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hefvpjpk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkinlmez.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyjpkgf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnklcpt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llvfqwxo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjpydrz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkqfbki.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wefqdumf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaruama.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgijhfm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxpbzpw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrvkvnu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qepkgdfw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eagdcmkd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjjpmjy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zihwgfcs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeqobra.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbomanga.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuovfrk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtdrsng.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kdognwmj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwfacko.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvajdcuy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qksqwuio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnfbjsa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzrksrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etkcrozg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwngmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhygxa.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrdcjfe.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cieafnqp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlznryi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2glxgsxov.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tewdxsho.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dflxipvp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfilkkle.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyohsyc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2heblnebe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsspfdu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhdefsn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2limolwbd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcozntzv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaesxsg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrsdryx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2npccfbnz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnalmuw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqmeexb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2szrsnsry.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnxbkpt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kamiacoz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdioohrw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbeyigu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enljuypg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wubpezkc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpiayco.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlfqgw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjhohtu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2akobdrcn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2orbzwrfn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbtunjs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgyaqfc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcmitzg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjabucb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxakyum.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdnbxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2logzxfeb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqazasmn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oajxtthb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrcdjjq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vddaphqh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gacqaclh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkbhtoc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulymmsmn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlqbdcz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylszqquf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoyvcds.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tllqnhsg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yumxbchu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2npwngsnp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2luofkiol.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ormmzsxq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqipxqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vclnecoc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmmgltq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pisfwweg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfrnjwc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2unyvekph.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2skhnmezr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcshefd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ialfkjik.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iopeufjo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtbjlhz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjnwnqa.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhculrd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbazbte.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wydmpckq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfscqle.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytksocpf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bloslrwu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bifnzapf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgdybja.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eplnhbsh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2spmsawnm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mydszzzk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgtaatd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqgvdur.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2agqiuael.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2veligzyw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wvajfumt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrbvqvl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfnlffl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsogidg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hohlitpy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byaphvki.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlrxnth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyynqgwr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2utubqsgl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2menwdlpo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpryzqd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xquncuww.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2reujswwp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2enzxvbaq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obljbzpe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yngkgpih.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxuqana.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvfwqjd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaekdea.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbyvfne.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuykegr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zslvdroi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcfqfpe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtoawys.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2drgbaqkq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwzxwme.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rhypskpy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyaeuqk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjzyrbq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2patczyen.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjksobt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgamhrj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oaplgwoe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfeqnxz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhkiusd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsovqqq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpogimt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfjlmsc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgoujpv.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2imcivlai.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2icvoiwcd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfhoqfv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwuuei.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaigvik.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kanfpatr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cioxworj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2evgykcfn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjyyjxv.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jewsuhmn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjyjbvs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdjwnxh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2evmgebtu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeibfpd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzcqhxu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2baqdcphw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmqfpji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvimspyn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2twxtawpx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwzyeak.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2swqzizxa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dayxknpp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lohlkzok.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uzukqfpo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscgppxz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzrazbo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyaiise.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eohnhfic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nngreifa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2myefnuzp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jovqiuua.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xsguizst.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yncgwbkc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zzocguli.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwtnine.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2prfuyixo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyiqbht.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cekptyhk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhdrvpz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2afykpikt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hclrsbnu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceflvqej.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2plostnom.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyjwozm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ycihhdcs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaesetk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpkmdun.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmzrmxs.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjsrrcd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrcfnuw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yiltlzox.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2eimxzrli.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifvrmp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxthskn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vthhdjnr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlnvodj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbizuxc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2chxjsbpu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbmgzpy.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvwgosj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yifvfoaj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhdnfjk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlisjhe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uuruixqk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xutpyorv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhnloiq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkgscsj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2diudawru.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yogamcdl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzyiwh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbhnjsp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbpmdzp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cowirije.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2soirgdia.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzmngnp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrtrvir.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fnesjmmx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqumcup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rajosnez.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fokvakfd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfjynoz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyypgtx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2avheshhu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtsfzbx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2msekanid.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdndlwub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycteyqiw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvssqew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqududil.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yagzvdmv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yqldkqyd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgjtfjz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjmwnas.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dancoxrj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdhnyv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnhkfbw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnyerul.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcpajqz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcrlzeo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejidckuk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rodzmacr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khwjywws.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzphoels.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvokxpd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ujftkfto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnigewo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbwdzyq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awmcenpd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ptluvmog.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqpacgm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qrozxlyr.html


<!-- 参考信息 -->