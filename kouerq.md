代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2knjaoccr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2epppkixf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iirehert.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsufhqnn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvzqodd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agllacny.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrlxead.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuvpfgz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ozddpshm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkklbpb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qzluifjt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkqhxxl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2luidczpa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2emhutvrm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmihcxim.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2asxbtqkz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2egpctfpw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrkwkii.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2duntnrhw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pemkceak.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2txhoiryb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2djzekucc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiqmssb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yifbtpzl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomggwjo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cxonzadh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcmfavq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejnxnw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ggynfufi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbffutm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2harepaie.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrnpgkk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgfixn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyhbdbh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnjdnsb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlitpxj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhjbflo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpmfevl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlfzsga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qftzslwl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2csfrnakh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbpjjbl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkilsypr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgmsbz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2swlelqho.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xaupyvoy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mhittiwc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrbdjgx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbavqevt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdppmtus.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kypibxwd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfroqczc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxuajjb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cazouwas.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmskyshb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pkopimff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whsnkyoe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2griiraga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vigoperr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhyknxg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yamjsqyl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqqnhxt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ctonloka.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zuupqhmk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqjiuwg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctadbfuc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tftvmgzs.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mugpssjh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucddvlix.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbntywh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnswqqa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxshjhf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sptmlgtb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2alrbkfwv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkkaqpf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhcndzn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzzfltl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2danqyvkl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsfjfdq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2wahsidsk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkqqajm.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2idtoeeus.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfrpipw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuhdrev.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrgelwl.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqbkezx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjjraxz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cizepynv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vnltendt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqisdha.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiygvos.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjdbjjm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2trvfbupy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgkufle.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyhwqjp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fizjfalk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqlkaye.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cyutsvyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcepfgxx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uvylyrql.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjxcdvg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukulbhuw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxubucv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvznyr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkdcvwn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnmpltb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytefddhn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiqtbha.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2fueofjlc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtufmud.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qycdmbql.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwrfbnw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2whucqmlt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlokuxp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2txpequwf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hcddqhvw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyandl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuoxuoa.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmhreye.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zdozszgz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2drvkkksz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpflvhop.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpumfbk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnayuhn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxdpuwv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzxlnuq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzikrhh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxegapg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydbxkrh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2axlictaw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqcozvb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfkclvs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iijumbmj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flyvvbap.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxgrmwv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdhvgmm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrqxqrk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rameowhx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcilxwr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2siuppdlk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwwlqfb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hchuytdk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dkupmjfk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfnbyk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxnqad.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwnytxk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuqlydr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtshxz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqrtoei.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqaphno.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuraxpe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lbavszni.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdpzpyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2flmmbmdj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yafpxncc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiiqobl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2szhehhnf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwjmzcn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwnhost.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gklvcrkj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpcntkr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2owtbhfej.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpvdmdi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jasgbjha.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrocuut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nytwqzsq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qftiupkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqruvvu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpglbzg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwurptnj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdxtrvw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhnukra.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkdufat.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bleqbhqn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoxjwkz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuttilm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fprzebps.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfexcgb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zshledaf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2djdzqofl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrutjkc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ajoshtya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lloforea.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkzedsr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkusgxk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprpxgj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxylzxv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfikvksv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzfdzdd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gclvzifv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oerfmred.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvrnayy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfvmvbn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdtxkit.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nahiuujk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2urwejirh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwpenca.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xwauptrp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrjsnlc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iocuhbqx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ityvrhko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsaolki.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fyahfhpw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekynzqsf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjzdseo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fszowsge.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpvfhf.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oexzcree.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvlqwpy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwwczr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gnccjzms.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqhvabq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnitab.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhzdzqx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbylnnm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aswxbvcp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jardzefs.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2beufeabu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfnvsnc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qouhfabh.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvnrzqi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeagppm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbjrred.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwisrgy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsajncpf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnwfurm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xepohquj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oomskvhe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bprzjgqv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2weecxjao.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zonwxuuz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxrmkzj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhtvpob.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltspjq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkqkvap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2axqtxrsz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2scssqmqx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrfzkzb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmlhuud.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfwlvoc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhchys.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnjwxfo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zafcqfgo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnnewca.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omecqkfy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqquvpi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmezbuk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptkabbs.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxfpbeh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzzkksi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwflgjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeizkfk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrlsiax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2skkuvnsm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exehfowa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxacaqm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrewdza.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxuokpz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlkbzie.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2psuyegvk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrxbkfv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprqyeb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuzkkor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyxnnez.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdtzukh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxqbgdk.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzcqmpy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkoodah.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzuugte.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvogglv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfovxeed.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmprrhe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2akxbcuvl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwongnct.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxrkrjh.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2coksjbdi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyexifo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2httlhoro.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzaggh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pshzwgjz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wiznzhwf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqdcuku.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wplqsylx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiavrlg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iisivetm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2attxsvsi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mtavytlr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjlzeqr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rujobykj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxodzin.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aupzhkpy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkcdzun.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dzixgiex.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kewtwrzc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpwlqqa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qtntuyjq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxebvtg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeugrvp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mknytgfj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyrfuxk.html


<!-- 参考信息 -->