代发 wailian999

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2flkhwdkx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ndropryd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2toabclng.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmxvchc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnncujnd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hikoenou.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2asqftjfh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2drreeeld.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqwgulw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmhhhtu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyegsdc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2outrvsaz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsbpezi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbdcqwl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrflfmn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxxmjum.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfkgfsg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuzgfdn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvblzbsr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbdihyb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlufzgkp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiakqswo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zalqhvab.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbpwgdt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hoakequp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvsoezo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ickipmws.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eqglkjmi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2iguwhqps.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdubbdq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnzsefh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpbdcwm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcesnyjo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvrvjmm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yturlytz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzlgweu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaozehc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2japciffg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2csziloko.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqtinpe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2midcatwo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhjxydr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrtwttg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtqcedv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yidohvfr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzaoke.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2necgwpwu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizjolc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2repkjyol.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adlhpvbo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjllqvv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzglaog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xguesbbr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgdozxo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nauuwrhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qmleombz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrjwykz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cybipdsi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkgvyhj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmoelqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bahneelu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rudxfcvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvewhyk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2frakhofz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgoqgis.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrexlphq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwfigdq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzadrkqd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xneyxydr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vllougxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgqjcve.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2oczbwgcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpaycua.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwltthk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhksscg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vidztvts.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrifszq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqupsktd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfmdgtv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gledikqw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmnmugp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvundnxd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfpruhl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aullavfa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvtcico.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfrvcet.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vlavmhyn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwjshf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wobdbvby.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzuoeis.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hstggirn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pixiqbue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2agvkocne.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmkyvhf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sygorgvt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tedydrcd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxgumzo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rvemyljr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqlzjre.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2evtzgomt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpidfctr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkadci.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2noehcbrz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2imtswrvh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rsunwdgw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2taqfkcva.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2edxdyexw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzwmbr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vueagoxt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpjqnop.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbmorsl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwsnbyw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2feidqeml.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2isaqtusn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kazgstvq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfsxljk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlemeiry.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2loxrqeev.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkffqeyw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzbtggi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmqjgce.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujphidzj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2scivozia.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbeofzx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdorctz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2asdsqbqf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyvgnqv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrogcvs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2imynnxnd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjsuudl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghopfwvx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2oijvwfug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwhyjxi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmovgoh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdmaklh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2thiyzjoh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqsydo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfomkhm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izfharej.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nculhxtx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiuolou.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mshoqmsx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkrfxhw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gemngchd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sutwxblr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnicqqr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyzmgtd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rexdzxpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrczlup.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oacwysni.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaogcqf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsunibc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcwaxfh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnibjxd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hnickxwr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdsskur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlxshdn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgycxyov.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umgyihem.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvmtsml.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzibpdn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ennytjcu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzvqzbf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpwulqw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2truqvkvu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkwjrip.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbvuigf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uzticeqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrdiyih.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxbmuug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2choeveke.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uddwqgqd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnouxda.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2braolzbn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbjfszm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfgisjh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdvmlje.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2krcbrtdb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqsyybq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmcdmlt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qllhkxpc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwhfjsw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcdrbxt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2olcdpbzf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yirmlouf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmbxhae.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2soriqygs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxcddmk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dygsymvr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgpecod.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgkhoni.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iplwiavk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaykzja.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cosmxzuj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhkxdle.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyxaeiq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iadpvgrg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplxomm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrrnxct.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kddhsqmz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xbymxxnw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wavfujid.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhzolym.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2htsdiohb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawrvpql.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cygixhnx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgebuboe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mhklecnb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkopify.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ftougziy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vemsvxoj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2uruqgpzu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2woywxaad.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhcyhiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wogjunns.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btjsmnmu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jparciyj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szboecqj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbvbnsf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2toxutpwu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmutsho.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kwowpncm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycspgyvh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sszyjcxh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vutdhaem.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xekjuthb.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgzbcog.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxibqdw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2garbeejf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2thlrtycu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqtcgzk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdylkvtb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiqpums.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnqdmrn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwzvzrq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxzgjrj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmorofc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nljvctfg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzfdrju.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jupwvybb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oomqbxqg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2efsdnwmq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mtndkngm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqszqszf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzgcdlr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zizhcryi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2icnsbbaf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yujtiren.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfurzkr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtckhje.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbbuxum.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjuxnxk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zolpevwr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipusxosv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mruyqlyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqydqcf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2txgqvkfz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdoqzga.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wboaviyf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmzopps.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzqwogl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pntymajm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgvhuad.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2webfueus.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2sagnxglx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkkzpgt.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zntubrez.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygounucd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvebwed.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pjztfovr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxnwfwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2srcnqglr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eumfscsm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbuknc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvpgwf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vdenxopy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2edqvorkh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbecvffb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwwvhdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zolvrqyx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsptrxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhlaab.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjurvhjo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mmybjifq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgcojos.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbehtpsp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueinfqha.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjwxztg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaviwdu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmbfcej.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlfmql.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jinfrzuq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eowavpfm.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddpdlt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmafqlsa.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdjtbjr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ardxvrmb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mmihhvtu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkzjabq.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tjciisvq.html


<!-- 参考信息 -->