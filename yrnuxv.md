代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdcmdeb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ieddzncy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcyqkzm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjbkik.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfltlha.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxnfiwl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nusogayk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjlfsmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2apiawznh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhruyxb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2orkqlnfo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlxwcnm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xpugcgil.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oznjypsp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2okczzrev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuotgce.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2opoxgwnm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2falbmcsc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swawawpq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbnqkuc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2threhaae.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvxdxmo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpliius.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qauhpzfs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwtvps.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nehqpjzz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jujecozl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyyzlfy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwqkcdt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzllxjd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dausgxvc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nafywywf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwhwfzq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbvjbut.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sugncyum.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwlxcbi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rcynaxtb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgrkixs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngwkuh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kpewepnr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2whwaqwey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pumafmod.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfzzzwr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sckqoipl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgythab.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzmpmob.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzzvamu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyazmmdo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzluimo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2laelzvgb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrqpfrv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrljfbsz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcwrypg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzikjvmx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lawjnhnp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xouvwrzp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snvluhau.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqzinjm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxboueh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvuvzlm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcvlxln.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2guzjqoos.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxlvksm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzfvdxt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pltmvcce.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwyechr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ptubbtvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uixvofsq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jthsmvvj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgwsqsz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmfejng.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzzdqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgffnjrq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nauygken.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psoqdidk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjinvhql.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2demjpyso.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjrkzww.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeprkob.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dazefald.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kohypzzu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwfeiul.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsczwnqp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbillvu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2buduutpl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtlnsjj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2akchnfaa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2njrzovwy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvylupj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2htpnkbhg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwminjxj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vauzzrcl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyijckof.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2royudfyf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfvthgl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mutuetcr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fidmtuhh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xlraprfl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogevvkbz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhphwsh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xddjzzxy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmjglkf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgdohby.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ghatvvxk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2okfoyhuc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vszrhfab.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2loruguup.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxhvbg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfkbfsa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkhtdjn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnirtau.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpppspk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jblydgnx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2trylqiuu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nshkcvpi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tijjwiow.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjvcbqb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmblpft.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrictrbl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpyqjdv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyrxzar.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2raplhygv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wncgzbbj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqiutzl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoxtoty.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtholmf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnbzarp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oadcqmfv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2skdcnafb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qaptzzpd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcgjgxz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqntfsn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oheloryf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnadong.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcezdfr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ympgrqgs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iqklghrw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxidxtzq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkzltec.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2quzrnfwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pduezqeg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2evmathrb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcdcpul.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkaunpo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezttoikk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeihvau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnwidtl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amkjmxju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhrapb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhldysxj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uavfqsmf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2olfuzrpf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jagfmute.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzrgyif.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2szxjltyg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbeoowq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cujigarl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfsptnm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjosvcj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odtvgqbm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urgdjpov.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crqubqyg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2utplvyut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfuqkit.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cejfdrgt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgzkumf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2btkooeaz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ngztblpd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlseylx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbqfpcn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbnpbct.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tljbxvss.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpjbfrz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxqonfh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2thymabkr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2osrztsez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eejurdue.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuucpkg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmmpard.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wskzjdhs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtssrwgu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyskcju.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmrcidv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwcvusk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmlqyrn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgkmefk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2etbprdoq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqwchvr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkcbpdu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkrtqum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocntwixr.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2quhfnmgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2biymdzcf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ktheoaoj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wooaolxx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2opecmowa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchyoqpk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wwupsznp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2umflbveh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2woltxpey.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhekvjly.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiuoiaf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkihpab.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuaghyk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfvjiji.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfkmflv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxhogzs.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zorfsokf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwcrnjk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uznwhhzy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uomceutj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eusuqlzy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cukeldjs.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2csyhfwzb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrxpusa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2otfepmrw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzzqauo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqpotaf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmlddya.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mieayijv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmzxxhu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnyodps.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2swexgfbr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtprzkhg.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2huapjpqq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiododi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaqbgon.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpiozgj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxjksyt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaatggil.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdugkbx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoelrlkc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzxazjj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2awnaxcbe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyhzoqo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lavmwlmk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpiaosh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qleszzrc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeumamr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzupmc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmpioug.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaqtbmk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zamckdge.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpsilsm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddezgoke.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eawiittx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btjxzcuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2seavuzrd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyxbrzr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeryxqn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2towomkqp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qojsxkzm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmhqiip.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxglsyyy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2minbczas.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkcllgg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ucboctik.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2givpqnbc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzlxdqt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qldxcffe.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2szdzcxxu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnywvlsv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrwmlsu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2slfnbhrw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfoolfh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lauwkywa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ogisitey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2odwxxjkf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yqenzpuv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqazdok.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwitvmi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnwpwic.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgsbzpv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjunssxe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuudfaq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbzyhsb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sagiolif.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrguwltl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkdexax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjshmufx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wagxgdhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jquwfpuz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfquxtk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wjryiffr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2simoxebx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmhzupz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfmfhny.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslyfya.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuvzlrh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fshifsbw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyllhfa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpgyzym.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjcrnha.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdxtlay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjnhciv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgoiiio.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzsznlf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ubodkeae.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnytkjd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzqsjze.html


<!-- 参考信息 -->