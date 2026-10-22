代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvqxdhb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2octfmusx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2msaldbxy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyeibcb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkbwwoo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iczumntw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dskggnin.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtslwaf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgdxqhk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yeolnlpu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bszyjkqh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtleenb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyfcteo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhpedvx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjtjhcx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwamtbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hecrlvwp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpctdlho.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsmhirj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2emfyahtl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfemppk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycskecux.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqotry.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkotzoh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jgczqtfg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwlcecs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvftzje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gigwziyy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lowcdtdj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uduuyioa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bahuggnx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdmrkle.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfufptzd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaizxlu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2szchdylq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2debijhdj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lepqseen.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2flhwwmwe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmvodxv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgmjtda.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcnifim.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvcxurc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfccezju.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwlkmou.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbamyfo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yulofrkk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvfsewt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvkcqpm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tarvnkmh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkeoajc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxupdjv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrqkkhy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqecuzjn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxpxaf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtwzuxw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvokxfa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2buhjfflk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwirkyca.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgudyso.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szvolwxh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtdfmsr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sydgxazc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcpjpdw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjtfwnn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2syrofnof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzewddyj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2riulkofj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvwiyrc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yspbmony.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ssobpqxp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjvxjed.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wridicex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfutqxau.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeqyvps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwddjzl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrsjxue.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2atwwezxu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2svtwhzqy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eluxdhoi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2heymujjb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vnphriqg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvoegui.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgevfixk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2svifhgyy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ovscusao.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hezynref.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdeieaa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnxtnzw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2chfgyqph.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnruvda.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojfgcuq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdynnw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrqfbaz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2omgvmfvq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtrhorj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqvfry.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzavcwdt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2muojptdk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pptdxqml.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzyhdxx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwmnttn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqjeldy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgrfpnk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2utfysstf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vinxubkt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kioztnod.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwdaey.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktfzcu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkpflfg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaqtifa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2idwtejis.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mxszktbb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2igzszuqr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cxklfvph.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzzvba.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwprdos.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdblcmt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqupeqd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgpjieh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xszodvej.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpecgfq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fvilyvna.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmuelrv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xrccvdmj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdendcav.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yigqurzl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuwpiqn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsnffnh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdguwqf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrojdgt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2azyotwot.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2scwuadqy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaovoxh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbhentg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbkcjuv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfaitwm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uybmfvxa.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiktlol.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvvxcvw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiayrpa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfuqgio.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnyqsgy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ettjubom.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfgssgb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gatstnuf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2anfcryql.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2szlqfxac.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wyclhyhv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnhgcxx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eksncdkc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sveyjhjs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwdgdfw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkttzzk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcmvcli.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2veahmtyf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2anzgtgrr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jzczuhdd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfntpzi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2krsctvuk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzpvvrv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2boihaqyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnowinpl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qficqztk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yncnhavp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwgcdih.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vobwfufj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgyvhoc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jecbqxgi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2krkrqirz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2oskkxgbf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjalvekf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfxdozl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrdivuj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjutixr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzrfxex.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkbityh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmizzda.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiizujou.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2auviyqqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzsmjqj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtltwops.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vukvbslq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okcjphxw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2akmmcvqa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwvshtx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkovkiie.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvvnrab.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvtusip.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rintlexh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhflxkn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbkgjte.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2drfqdyuu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhiqdom.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpdeaci.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqbuctu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsqdvlt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjzmmah.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmzikcj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2imciwiel.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrjjbqw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqrmcnd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmyecvt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2biljkgjw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stbagoyd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpowflcz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hheulbsn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qllyilkv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbzstgu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzferrr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdyposk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpsamlt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eieadjwm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mguhuvur.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jzakeild.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nmseeicm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmgcfhd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2erqqbocn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsoseno.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kucuqcvl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwwwebq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nniqgjmx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jbumdrir.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwngkstw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnediokq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkcbbqd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaqyjfo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zemzwpsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiozqiod.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2koxpzash.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxjvwgu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsjzuhd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdflphu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkeiuuf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmfxibn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqobot.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrmebrg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvimfv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzoiijx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2idzsgvoj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2htrpgphq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oojcqxqj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sspjpqqg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtrpucz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpxlahy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vngsoffv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfdqktv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuinczpe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyyueor.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjwilph.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbadaoot.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdjsllt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwidis.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfjmqgm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnijyem.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlncqoj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkshgp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfindnn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2moekjchs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoxuczy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksveuuew.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqlagxv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwywpfm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrstry.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiypzis.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gdealtsm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jewvmalk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2fwebyoog.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmkhvdd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjxpovw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sairiokh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2homsnmcm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxwflqe.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzhduif.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjgmxfn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgqwysr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhsrfxu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bizlrclb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uivebtap.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoxvqdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igvxlbwz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2edtpwtco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcteoiz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rudjrukt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiocpcn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2orycztco.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2znpwuxll.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgsywlp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcdolvz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqzskgm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvwoylw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqljgqjy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2udwdsasa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfvwwle.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfnypas.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meesnybg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhwpjuk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnxknuw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otbfpgzp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwplalqb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebepzxho.html


<!-- 参考信息 -->