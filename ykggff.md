代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2crmwxqqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkvbwpq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rosmeovq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pemuwqgt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2asqdmuoz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlrqhxu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvcwxmi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgecsreo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2heowbdrp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2afzpvjhg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzntbuki.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcvqpwd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eclspjad.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2onghfrru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxiwaqd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2scceigow.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdimzhjg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnexgcz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aonxqbew.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ivihyhoc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2stoldoxy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhlfwqs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ogutksxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2itegkspp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzvqqaz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdriep.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuvdcsp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdcovcj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvtxkyn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2umrluizy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgwhirn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kecbqjyb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qccwdcez.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmpskzm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqceqhad.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2knpkjjdw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jioixorn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwxyzor.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2krucjwuh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuoqjyz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sitxgxyl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhloikmd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxciqzls.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spawvygs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybopakxs.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdukzxqf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcngchk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kgggqlhb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nppabukk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ugduxjqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwycshzn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhofkbgl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkucgfi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjyulmo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjsapyy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fippagcv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlmcubb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2klucekfj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvkssuf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmkyhys.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fthsaygp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oldnyuwn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtujjbv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjwprvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhktrab.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqgbqke.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqogvwrq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2izuzbmbg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lotndoot.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwjqsio.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2moosdrqx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnaglin.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxtknqf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2muzsxaeh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoelbnc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ysamtfyz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpimazh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjcpji.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pixdgekm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2urjdrljo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchmefua.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jifielso.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2givumrzg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrylbzt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcegblr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzjwriz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2idpcekfy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufolpjsp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eegpttli.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2priiyaeg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2osrgoper.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzupxny.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcynzsqn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxnvhmw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgnxzhx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiwpvtd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtxnfdu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tamlfzjp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhgqwjr.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoxswha.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzabclt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcjgkgb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcazlhbi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiqynep.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2saezdcil.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2twqpudie.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvfrtl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oggglprr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsjcyjt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekovpwoa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twfsdhwm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rhauswaj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oscewfje.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cdffxveq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkzofgo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aptoezxp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2necyowum.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrynlopg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsylycbs.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ipouabds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylcfhg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2crqimnnl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcrudlk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkptceo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dylsnsra.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcvetls.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlxtrgc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wiemvjzo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbzrfao.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgcyuzn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfzvvcz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wycgzggn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbutjdr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyxajps.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxdsda.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2smfdvckr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdggbxp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2urjanyik.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnylmzxr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2squtlurx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2huyxtqdo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgtqswc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctddsfa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpqkzkb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmmsnev.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgblffuv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2muahsklu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vnriaewt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpmcqfg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfmbcmk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xalrexxz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2alrwwiia.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eebkkuut.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwuoeec.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzxckt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqapzriv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bclcxfyx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqiwywd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfrazni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2skcqmoay.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbtyimz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2emwmaqpe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjawhiy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zglrcisn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjqreuj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iufhrjrx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqhnhfn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtxdkoj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyoxnti.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrwesaz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2giqwqobb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxfhkoa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxcywju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bakpsfui.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiigghx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbazjnz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2csgujrwv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnrspdz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbfuggr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2odhriuxe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhphaodl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldycptim.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cucrqjkq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwjnnjv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjbomxh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaqykuq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfsuext.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwtcsqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlavuuw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2umsoezii.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnpklqi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcsfmmh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cosusoqb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmtpvfu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2shrrrycg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdroxiwv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzhdzrt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2darmbejn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2grrpoopu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnmsjoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2luokkuqf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjgknkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkengag.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2siwmzkee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bovnuavj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdajvbqo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiqqwpq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myqbykpx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvogqqo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlhttwo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkxjbez.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2naknothz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mskvmrco.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiubpfi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yahsfscv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvitryz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2prezhqgv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfrebex.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkmhkbf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsycjuq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kzttdpwp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2autekdol.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2svyyawij.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqmpvzk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgemmfb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcgisjc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2diraweew.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2adzhatvo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvdvztj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ayizkkpy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmtvcqy.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zshgpacw.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uglyfbgg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvrbuun.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxouwlv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mcllblyq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2aegbdzcs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjarolx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxizrhb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2koaxcilp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fbygvgdh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqybaort.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkqicgy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfadwuc.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcmkmmu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2iscbzlkc.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gztvwajf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqeqkc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcodgsr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xelhuvag.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pybajmnd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxqawjp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwnmyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgpsmue.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eahsqxrg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2euyxhtae.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ytofadgu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxjrsqs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfbcyox.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2litacddd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eacsmfxh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvubkkbh.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oybgpfmc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiaqavx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvneemut.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sixzgcpi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzuqkbq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2enmhrlua.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2njvphhjk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqhwrwe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmtalch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efqcapgc.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcvcor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhovguzd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zgatjrov.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ehynmbmu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tcipqgto.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2apskllsa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zibqljbh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzusnhib.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2aekzgcvu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zydczijx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyseouoj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwxnxlj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlrrlkp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnympic.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmhswjj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvanpwp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wuynulkg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuozzko.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbflnyr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvjpgkq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqdacww.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ggerpblg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mnospali.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2apazkoek.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2szbkemfn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2csewmvez.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjbwrt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2frfdmpov.html


<!-- 参考信息 -->