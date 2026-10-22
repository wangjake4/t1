代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbbzjal.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2unzwkcst.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mayavpya.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2afwoagte.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmtlsre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ishcvbnz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2waoejsma.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxewtxen.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iwazpxfn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcqhsej.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oofjalsp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgajlhg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfjsrqj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xegikmgt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfdkndt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2njqsuiku.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqbjzc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrypcmhd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbpksfq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiiupgh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ktikntgb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjlvnqf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jvshyxqj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzltsiz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxkpcyb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nhirnanc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogutkbp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgybfcrb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqpxzyy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwbxzbz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jocrfkcy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pthpynyd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwawqkp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqooiysm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xigakxav.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvydkhvi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoyikfy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snrmnmvt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjdqmqc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxpuwcb.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaacubq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkphuvn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2avheuifb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzlkjej.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wtikllid.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ygogubst.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnhwjtc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeariuq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkmxtly.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vekpnxpm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2phyfpdmk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijspmnvl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfbidqa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bconqnwd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2onhuzdzq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfrxxlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdwcltg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlmrnvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feixbxxl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2aruaownz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2riiugpkt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtpxhig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxmkdox.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2poaxlvzt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbrnrfi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbctnsx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcwpprh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eqizjvny.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxceule.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pedxdtjm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zybhgylt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fggwmbhu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaweoztz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uldiielm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkfacht.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvjtzuw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlasqpk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2giafcrge.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeppkugx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uadbnzvw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2convuxja.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2unwmnoaj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uagjevym.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsspmiu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbocrlb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gjthsywe.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiovonoi.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfykaggh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qyosxzmg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsomdov.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcrjvza.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vvayxidv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pyanqtsl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrreuvn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuthyqk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iswpujmp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2myirfvmr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsenagv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiplixt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbhxgsg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdsgahs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jascbaaz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqkufpa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcxxzrj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uscsqnkx.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bnejptpt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2geiqsqvl.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bijwwblg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgizxiv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkvdgc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2crzieuit.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ceodnmrt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2btudgjhx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2apjepmnr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyvudot.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xvttqinr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuulwvze.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrtjzju.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjbjxyd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeaoovy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kqccbckr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqarynqt.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvejyhh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfcmwrq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsybusu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2boraejmu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzrrrxz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyfnsxh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mynvdcrr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwecvh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxstali.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkabkpu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2daqedolh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrstgiee.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbayiub.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkqdzw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqokzoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrtmxfn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpxcxjc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxpkzot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfkkqnw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhzmxgz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vanlpsnk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaqmfft.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlqhfhu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hejwrnur.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoxqeoy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cirdwevu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtftrlfe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrwgvqd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2swtdvsgb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlcetzh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hewqojuj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyethlnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyfzbrl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjnojm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdsaoif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvdovqr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqknapxs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrouucfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxpdheg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2krfbebbl.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qclzsnmv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbonzpbk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvyhczv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyulfiip.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qrytqlfh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmpzbuc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sracmqgy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqyotcr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utyxdsto.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyavfkb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkigldw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdttwxs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pupdyium.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qocmogpj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnlople.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqxfwhu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2owklzypu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sufllbwf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aascjxzd.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhtdupa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyawmmse.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xcugsgry.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjzizty.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygphstnq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhferny.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsvqabl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqlxszk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2onfdttng.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceijjrab.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqxsgwo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlywpst.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aubqsgza.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ligqxnmi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdzfwh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sktgcsao.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qahqzgxd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2scnlpnbl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gepdhkuu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nasumwtj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnpiqsy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjmksps.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2edjqwceo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcblbxw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mstzvlkg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nffjggcb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsuihmf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2btetfobk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdxyioe.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhfpdey.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkluzbne.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vbitkims.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzwzfiw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tfstfrxo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2frbdrnvp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njrcaina.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsjiufs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uguarriw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uupivbdo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vprxkexi.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2blqwtxax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfgbotu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rihrrndl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ongpeoim.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2aitmedhw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqrdomc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pbctapoa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcsrljv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bshnhppk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzyaous.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgzuuio.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2czidhyjf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2chlxikzx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nmenitfb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eaevpeep.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnlvcia.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lihgweei.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfjegxz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxzyepy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2atcxntcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrymwuhi.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhwxxdb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfhrmwu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgaeszk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raeytjuh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmauqwqd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnqtoqe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2gplrvvmy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fchfcxsa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkdnnho.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwtpcob.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2roswiyfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyhptsu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2evdrormv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqreuhiq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnmofbr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnytgea.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmqjahz.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zicazlus.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yppnsamd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iynzmdsk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2goujdcvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oulxoaup.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lorfhayo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnnfjr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrvtgav.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyeocls.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jstynhtj.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcmmonv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ainnjxog.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmheovy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2crfhhval.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlkzmzi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxdjmsu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dawzprkm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtjygad.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uytlkeha.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nojcmrpl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqsweiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqbpaj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dppeslco.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wawslnhn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtagre.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvvlqwr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfobhgc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaafvnk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqrigve.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmweukd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkiknja.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwczzkr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kruamzde.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxkogi.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlmdhyy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyhahoe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzjkxc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2upnpqlak.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvfopi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kemiyltn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxeutsr.html


<!-- 参考信息 -->