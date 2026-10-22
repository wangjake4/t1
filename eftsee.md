代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmvnien.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsijzzf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotrpfgq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdkuwel.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcyxcfv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmsjfbx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hsudonvc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqwzko.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfjwejw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifttjehn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxsswjg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2romgshox.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdvkuun.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjvyqcq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oedrcxov.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjzqaqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dslxosiz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mckqwfzs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoibxxj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnasoca.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2snrfcitw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbgzsuz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2duhxyrqz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmjxjdm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hldcqpak.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdpdeyb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlltrmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wyixfiup.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzplcdvs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eznqljmm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dktjowhx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvritez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2aimhdpjx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuowcxy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qcglukrf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgbsbfr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqxlxju.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyhljdx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnlizcm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkwnxlj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyafnmxa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlmuxdb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzlcavk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbbdscp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsrdcya.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlllcyz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoqmfsv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeumfsj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilpxwh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2byukyyst.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeecrjv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfmmdpj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxunrftm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gobvqbkn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoqoytc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdigvze.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcwnpfd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyqadzz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuuykjl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcrtqfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgibtrhc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzirimw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkampewe.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mazdvsyt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkghjjn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxlrufq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xexkoqhn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtrxhdi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2numwhdjb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hheuogkp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2siurtpdn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2whqpsrmd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgsermf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2orszmxcs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwttvxv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgavtsk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkkgbyd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvydjqwj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2shlyspuu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aswxmfgr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhylgesk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcfccdk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqepdih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxmchst.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyjnmmd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hahacpnw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritwcebv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkktwbr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnaoche.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjcyury.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xquneiam.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgbgnik.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2evgbmfrt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbycrtq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgymdml.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuyutqv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2graefntu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ideeeeiz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfeauog.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdlfwzf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2elsundvr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzuysig.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcakybpr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2quenplnc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmjotnb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqnznrh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufiviga.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqdmme.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwubrmy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdirpe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2prfkkdrk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkenaok.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2udnadanc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpkrobc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oteborno.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fttegmqq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkejhaj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwymjlmv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ottqjdmo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2asdkzuhu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2skwhbhat.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyrvsgy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pudvmtlh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkwinky.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbcwriw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2juagkhro.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxdkslh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgoneo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryojaqyo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2czbyuhde.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhtptou.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2whladnmv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkalojdt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2losgrksn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjjypif.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2scrgkxqs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkrtdvm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmdtbys.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlebvlbu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpzrurs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaguxbx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqixvwjg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jingkkrq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbqwgvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvtfpv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaluxii.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwqsohg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dedjkwhs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzbwhqh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lakajtbn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2niuwwuxv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mordjkrt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjhdmwj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhryerc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmughsrt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqskbln.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsovywh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiqxjxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpskihb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dptnkdgj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzxsrpv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2icneznwx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwcmugz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hnniyygw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2etafzjhi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnmrjoq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aujnemmj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmhmlbc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbvgxpw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbemows.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrigmnfj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfsyvev.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzroctm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsxvrib.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrbefpc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xonxqoxt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzudfsc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrmdgdw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ritshczt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tagbfnaj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyofewl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etaoyvbg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2etrnxaxf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cuheucfs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsgwguw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiwdpks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ownovtmp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xklcdkzd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2duntwkob.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzlovbt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jthyquwl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpipgd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2onogdilg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmrbpgb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tesyvawv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjooug.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjysysvp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxjqwvz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypcoyyv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsdbkyh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhymvbrt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jogcmsjz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuxstnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdmzlry.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyskkap.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgvznxw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwmggv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmzmpfm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2heithbkm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgvlapl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcbizbw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfxmqf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2izjpfdmp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvhrgcp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kunbmhwd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiajhfj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zsenjpdl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlprrmdd.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlisnff.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfktiuow.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2silvtzmn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqpiumr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2iucrqgwl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjegtvs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rakqqkkv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xscylzzt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmrcoqp.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyeekqp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrayujfh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiwitwr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjgupvo.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxxvet.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlrlcsf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsdwnec.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjkcdo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyxaddx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqzjrgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hphoehbe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cblcztat.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzcoxof.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyjyxgs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oenxlejc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvgjqgy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzzxmwr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xniqbsjt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzyhmrx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vabxoeav.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plyqlcsh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqcpgaq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkmzvap.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmqbpww.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlobkcty.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2biqgyyzc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbyqrwl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2qymkmssj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekclunji.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuaftnq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2efwmkhaj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzertgk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrozmov.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcfxafp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kofiruko.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gashnzxd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpfxqjq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2crvwtqqy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nifigehs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2frmnuprs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyxfkbx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eulemspi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yajxyziq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bosnyhsw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgsuvgf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmjnzcm.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2umcqkfip.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2anfflzzx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtgiltm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2iejgnmei.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2faufdezl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxyqtmm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sybpgrry.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auwvjkkt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaonixy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdacroax.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcujphyl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdwzqjk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoelbkf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xokrlquy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtzrzwq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvobuun.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvsivmp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbwsqqt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnratyx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2irttqmdk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmhnrnd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfrldlu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uicdpjqa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfeugkh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxfiwyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jeycakfu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkpmmjp.html


<!-- 参考信息 -->