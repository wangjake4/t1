代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gocwekxl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwochvf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kosizmwh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2biedkbzh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeohowus.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pieoatlx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqixwgpy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozagwjxq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2efwnbqyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gepjksiy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhjuqvs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2douijmxz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcfgdpf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcswpoh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzwsdai.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmczgyoj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2undoubbp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkfagon.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wswhvfzq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2amallqeh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqujtsr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuycgog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qarebgsh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpuqgbw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2znnkrppf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hekknfwn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2phlbznol.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkcfqbi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2teekjnav.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhxlwbj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mrftkhbi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvghruw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kgawghkw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlukgkr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cwztmmhg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzzmwpk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knujpksw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiqpaho.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgacgyeh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrmkgil.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfliuhj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjvphju.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kojyljro.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffonueri.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zysygief.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fntxakwd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqipseog.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cliqptkd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuwvspt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2licxzzeg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoezjcm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlcvlap.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmndkkcr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdklxqre.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxgmbyt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcuhwtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tdktrgjc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eyejudce.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qndkwkha.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfiowyh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjyyqpv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfhodbn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2txcmobst.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kscdriof.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdvdzcp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2onlcolyl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2aodgblzw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wmctmyir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyufarbt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrmhimn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaybphd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbujujv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pqewavuf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbghnfbt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgmohnf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2utlkgmyd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mdshgovq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkflxpke.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ketuvlwj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2odqphuln.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfaqmam.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhopujh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2aljizzhy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kplpaaac.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnepbjkt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghufzlku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnyrcwk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfssgzf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2amqxmywh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xakhgelp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ythwpjyk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmnmjwy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdbqcum.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uipwtknz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbttlbme.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlbjqwt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwmyabr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fyznovwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeikkpx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aebilwwm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvmoeoq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdelprmq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uyffhrnb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqvyetk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dnftmmfj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmvvvia.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cokuxpjq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cneydokb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxodzvq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kanowjag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmekhgq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzfnkxi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhhxamn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjhdval.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sriqmtlr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjibumf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwzhtqj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xvolnsbp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bjikrbxg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdtszfx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2natfdhxa.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwemjucy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzerhns.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgkadnh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2grytuthi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yzznaqrm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2huyukwzy.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2imthatja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnfhojz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pktpvuhu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdifebed.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwdncrw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xezgxcfc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmofqagg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdihqozz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdrsate.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scorwtyj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2byawtgdd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmtwttw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2trxombgo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvjxjfm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rllqhdjh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfylgfle.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnztbypd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgkdahc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dweoaayz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmddtmg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vljntjux.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hjafeuwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uotunfad.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2muwkzxyj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xngxmizk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lypoxdqd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbhrexh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bstzxrfz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbocaya.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apvrlgyr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcdbgxp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlymual.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kefwpxar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdagmbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2chyiaayf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbakypcw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2btvoojtj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyacmock.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprzsumf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ownwiagk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtlqsqt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqfryou.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgervyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxhciw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pahdgguv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjctrwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoovcrc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcspqpt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2meddkwiv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzonidc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoedfbx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2puauyqpy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2impsihke.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2brkefaei.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xenfmsbk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgievez.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiwelzr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2txurwpnr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2trbqoqdm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhhpnhs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdmwzxk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuxepfu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2knwjwwor.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2silkpmia.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kyunvtsc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwvbug.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjzxbqs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgdlqen.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2stlllkpm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2psaaylvi.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iemocuzg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2stmxvbjh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngctfwyl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvtnwap.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwthdgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpcjukt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlkcptu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpfbwbe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfrisgo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjjlxsj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkdtwwo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2payropzg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnojids.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqtisuy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kreeoqov.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uegtpzwx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxajxer.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbprxu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jigxqice.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsbcsfl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kkphbrbv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hejbrppk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpcajnv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlusbyt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuypumgg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ddemcsiz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lchxziyp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nsesqooa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nanhktgh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aooloxju.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oubttmhm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbjesh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qskzoedo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpbwvwm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbgqcya.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxczuhyt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxlwkrm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2glneohxq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xapbqpen.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mapelslr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthjmpc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vuojbhwr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2usbvtwim.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2evcbyqpv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyhljly.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyeuznt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fekmwgmi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rtecdajy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2quiggxxy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbftsyh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzbbfvf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzfwqss.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kipabqev.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdcvnva.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2iecjssuf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzqcuqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfipbxgq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrxqypu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2filwaioq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjmsgx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2syiyyprq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtcgump.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajdasuu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcbfmzm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egyzipas.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ncspctbi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2niarpwrx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxmgqja.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qesrijul.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2khrvjtwh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltndfscj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqmkpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqeyowb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzduekp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnctsjs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzvthxp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwainzov.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpwnibn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjrlsxx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jyikelwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmtyrwj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzejwpz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkattnw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcmoxut.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzzawml.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2enmggstx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnixwxca.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiuinjw.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkedcqv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2amnszqoe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyzxpdx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxzdgii.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfsfoiw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdypsvkl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvndijk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcwmvci.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ydihjuxe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aormjwqa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acwoakvj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obfyptvg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmuopqu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwtdqgw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxnprhh.html


<!-- 参考信息 -->