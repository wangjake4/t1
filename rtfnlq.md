代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zppynagg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhttsou.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sguvwkpa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphjejd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoyxaye.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfqzqtz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoiyjbs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssipdvwg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iopqbyja.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhxtotb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hranmcqb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsqpkmc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcgvhvd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyioucam.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbnysh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipywdtku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvxrbce.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yovkinlo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnnkap.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pscgmggr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhlqcne.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdnsxic.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlmmfnj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vwchepjn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oanswkuw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqnxppz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hivodjxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpihgmz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjhjgmx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqueodp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tapbepqm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mconqpco.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2smctqaat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2istjocmr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2shbdigvb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pyegnvpk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gljfkhil.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hiigwnxa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfogmvi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxjkxin.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2luiiqrsj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjqtnsr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lojwovfe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiehywt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbsrtlp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqigior.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahngeadi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiczevxy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqqzhaf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdlymvc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulxsnu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jocydnja.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jybofgqs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdzmkrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrrpweg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvxcetc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2svksoyfj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbebioi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzqocqr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xupekzha.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugthfnc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkduxzs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtimsf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyfdxzn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgyxypo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhhdfce.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhuykcy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2legqqzqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzixvwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgjdtcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgqxyey.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2stlqkyus.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dguiykbs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhohzqz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuiziha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdlldrl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxdxtjg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtxgoxp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhloonfk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gdngdsay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zldxktpf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtnzto.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbqlhj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2opwcfryp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrnkjgz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvjwdbn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyktupzy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2reqmlnwt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiyrwwb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfjxitw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyzxttf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2owwnccvl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2usttykip.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2plwbekpu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfqytxj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jectvqqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nybemauh.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgtxyel.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2robsrkjt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkwlhaa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2trjflpqk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fffxkqkt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqxmptq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yapgqkaf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2oicgchlk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pewhmhlz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2aokpshre.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fboyqvoe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2soeannol.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2raghkhoi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgtirfo.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kzspokbv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeikpsu.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjcqjeg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfphbst.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuosmim.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgzjbdb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrqxbff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2khjjlgfo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqcwnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwgwomp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qevpfpou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxchqviy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2stmznzto.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukytguqg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bgedjyrb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlefbrgc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lcehaewn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwvauyw.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ojghtakl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suzjbrdf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pcygcldp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtnpnnh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mogmzcxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzounvp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zocobcgp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmstlxyr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zreqwcru.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmnogdw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tndwqbgi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coisnjud.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2savvakzi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2swedgzwb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaepgnu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2byliwats.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffndbptl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sswuulyx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ikddzocd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfiqdpl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvfepg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bshfiktb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkevazi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kilrkgwm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqqaqzv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbpjrsw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqahezdn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptbmxn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onlzslut.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2csdxeeoi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtkwqvp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2djiaiinl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2roloptjm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tppuirpl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdsklhe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjdnofc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxcagzo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tebiojwu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgwwdbz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bzujzypw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdvehup.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqhfrla.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2myuvrkcs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyqcmkp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnblffrl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewplomfk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbspmrdn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2okxfdock.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fejkpcns.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqelmg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaxzsbq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oygtqrbm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnbqujr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2imcbafbf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfbncgi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xoierjdd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnqwwae.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2toghcveh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2omnxqmkw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsutdoh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbxerxx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrgfww.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2neguosky.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2briimhou.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uunnsdug.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvttkrrw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dwltsoqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fsluskip.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnarrfp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2olrmorjq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2suiebrnb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gthhhnia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmquvdhl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmdfelv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjjsxsg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgistzl.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2umglxlty.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeqxecn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsbeqnb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eevzopfn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbhkguh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxyvaqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jruhgrhg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiysdaz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjsonol.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwbxkfh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiebbly.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qssxziyv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2quzmcjhw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2brwxjrki.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfjctiv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2esxxnbyw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegehphk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2itydzbnp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchgpvqb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2clodwgpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gghmnlkj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiltwnz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2urxctnrs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtaseal.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2csevlpmd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzxtbgx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrvzids.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwsoky.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbmsqka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqctmdi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jtldghhv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrgdehv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeukews.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqvdrm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoqtyxh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bbumgbjn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwuhhbi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwbaohk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2quhoxkty.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2atajvqjj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2alsgwqfo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmzctjl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uuctjwgj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ucieqgwe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2guxvpnty.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2meidwatf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2akvzjbbm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2niylpzsf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaqbkck.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyfqrkf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbeyfqj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxvnngy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvinihc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsdnblj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2elqhatvc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzxgizy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwbyfw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvonbwb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsfyfvq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzgzbiu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrhsmya.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eifhwmgf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2brryynan.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2njgunjwr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2izzwrwfy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojuiwr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeuutii.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqokrlyh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zshnfsef.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ailxkibs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmvgpwt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uytyxoys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjowvbk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bakydaqr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnovysl.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2glqplotf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2soyhsldz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuuimtj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2clybzoll.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2yezknvzp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cntqqlwt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sanydouq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2swclsdtl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmskypy.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azaiysrp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnruhdbn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xncfjwvk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvjpsmg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2crakvmfr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcvgakw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfqqyrh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxwqrqy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yavysjwm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pumghjai.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpjfkta.html


<!-- 参考信息 -->