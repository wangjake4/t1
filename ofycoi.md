代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rynpzzpp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wzomwlax.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2feuyydnd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnimboi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2durpunwz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqsnpii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqshxlqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uogvstjf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gucayise.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmidasgt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edywmtez.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2otaykpaq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2csgqqwrp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvjxztm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhussfj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxprypj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqkeunk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uulhtucm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxmzdxk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kdovogru.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2alogwpbq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jherlcok.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nchwxzht.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbnlset.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yormxzgz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsngqnf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vmschliv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxwcwrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtdfhod.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2csmvvgtc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xityzjyk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2edfcuwuk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfmtspq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpnxfbn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdbcoxj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqszney.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xsicrnng.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfywelze.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcfyjss.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brfschoe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xbirnxlw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czoyhsfd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biphwofx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmmdyqe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2epplhshu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azuhjhyn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ioioyfti.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwvxnfp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpmvkkf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qeizeemz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bizirnjp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfekdoli.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mamnoppl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aypzoiqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbrofz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrivzej.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoqkmel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dezmouwq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlayigh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmblvisr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdhhsdo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2swkiaybe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzabkux.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2sotkrfwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giqxsgkn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2birmuebw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvntttdf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjmpezo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwgkokf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2geeqgvnl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqonhjv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2micwljgu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wznfkfrh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcvnwhr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2sedjanto.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iaasbegg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rkklptpj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqutycaz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2momxttoj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtlxlpv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2funxyzxl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2puvlbmzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhycglia.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzghnbd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxstctbk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzduagd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaecllr.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtfofp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eteewynz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxojieh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmcaisp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eldrktyo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezriszlt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lauonwae.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhqksed.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqmcznj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyjkgaw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaskkxc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dupasebo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2slavfult.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcbkqyx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwwgqq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2osbxqbdp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkkluca.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrgsijr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2muaapjua.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wscpmawc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2drwdvplb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcwlddk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbssznv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arcojfwm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njprsnam.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjfmzkn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chaqotbe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsyoiar.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqpmpue.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbruodop.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmfsunj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtxbdte.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tonckkcu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mowyujcb.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaophnz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2efdcwifn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dnycyxug.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbttftgi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrqfjen.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwijxqrj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2olsevlzj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrkfwce.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoznusa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zirrzufm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxibwhm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyghqkt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ylttxftd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2poatywyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqiefqa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvqoao.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaarvwn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuivwqe.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcdrsjh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hromrhas.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdhdfyb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sihkhiti.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dnojkfcc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jixobndq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihutohvo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhplkcom.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iiosyavw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvropqq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcluusnr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vthvvyow.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2obcomjki.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izcxezyd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjldfwhz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnvnvcr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuanmcj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpkxpvu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arraeksy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2slfvehir.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2misddfwx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2abyyxbwc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbtkoqi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2poartlxh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ogesfphj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcjzsve.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fopyidzg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jexqphop.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfgsva.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvlicbx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txnlcoem.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzayejc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2awydtvjl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdixebk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxswgjfm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2njkyhfmy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvxvndq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaxoakb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhszqyi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qitioktk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenkwnnv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqfjctl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsmbtkm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dorjuwju.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iwotudxf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjorzecc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zayscdlq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivlqto.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vznzvyvb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoesfwje.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2luekxiab.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrffnjij.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ttchdldy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvejlluc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2niluwvdk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmgkzjf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyznaiby.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqzagy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovurdqyg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaybttu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tsitddns.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itkxnioo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrasrnd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iazflwin.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyudand.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdzgosh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwanffb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfbhesf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfxihwb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zywfklsm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2velwsnhb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlqdydk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvchwte.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkvopiu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfmpewc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2opkheefa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsairdem.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2emiuyrmm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmponkd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyxzwie.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2khkkcdwv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcctknl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nccezxcq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2siifbofd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kscssgyf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadpcfie.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfdhsnt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjxbycl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnhqhvs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmffuhwr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dolcbcvv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfregrj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwrruox.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tthdwtai.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlyhywl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhvmydl.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eiodfgsl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwdohmw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqmysxf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddozqd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2clxwkfbj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmqmdw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbfpmmv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rcryghct.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hcocnuau.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pavdmpkz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdolatl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuwdfsh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoklznb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2amiaumuq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkbwndx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqqgvvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrsstco.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tfalvvsa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onwxcipa.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oithuvlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idynufhm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jnskkehv.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkyoksu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvcmiru.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2feujqkqs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kswvstel.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2phawifdz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mookxiaq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjctdlm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2utmqgczp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnzynrt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2reemapyy.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfiqyrt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2niinitrl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlymiffw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwqgdzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djxskbfv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwwhlul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxlpikv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2epymrloq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iohebfir.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbctzfw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gpodeucr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2esurjttw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmnehxe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2eblbkvyp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icbkyfqp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbludmub.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqevasht.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfwreox.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfkqrlb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aheidhsq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzpghkb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hawwktse.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aaenbzys.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhtblfk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fewdgmdq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwprioo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fnubshxt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qshnnqjm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wykgzbpr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ixekifmj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2epwxglap.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeiztyx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvmiltz.html


<!-- 参考信息 -->