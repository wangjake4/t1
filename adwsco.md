代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hadaewll.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lduethaf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqmxgxj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dshtkrwg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdlgyw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kcojmhoa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dasozymb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwoqml.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsrmcuz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdspnms.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxolcxns.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gueztxav.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuulvunm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2whekpivw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yiarfirf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zizudljh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2quyvtcjm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qypeppya.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxpjxqa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaomnfbu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpheugtw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yboqnlit.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvssaxv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpcacww.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxiajvy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2spwovroo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpqnpon.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2spnipzsm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaftosxm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pstfhzlz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbggihe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yopyassb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2apmsjsmh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhzexzl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fcztanev.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ieymneao.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifhihxq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tosewneb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehspmhy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvgelzh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmpadlf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxuzwan.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrltnfe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxgiolr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2slslmtqg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmqzqew.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ediperjm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukucpeqe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolzyonp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyjmkex.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dtadozph.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqjykj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qwffzmtb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2esdrhcci.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psiiisfl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkmwytn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhtggjx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2itgbrgvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoizhlm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tduqppdj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmpuerh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uejylwvm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wzajkjsx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifbcklh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoyptnl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpptrko.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdedfiep.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cjluaxvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzpcpdt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvxxhjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhvqiik.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxafadhk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtjdqdh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ftovkzii.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvmmio.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxunknrl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2csrgmcoh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxqmpgr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjgejiv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznjenu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2awcqfjdo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlosahi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2brgzjxoh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yecodwqj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jciatixb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdpvhbf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiiiios.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjmlwbk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsjfosm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpefebr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2webdzuyu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cskygftk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnegbtx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2onpenpos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdewmxjx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ogucsilq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yscwvidt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oltwjyul.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2heydsrsy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2epschpzh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvurumj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jynyokor.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwxushx.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rpruvkas.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2huvsqykn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cituxvna.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kcunonda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmwcdvb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2okfgjrtt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2znwlfnxd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xylwwfah.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hponrxsj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erfdsxdr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqxrfvt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjgndhy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tidhxjdf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcseijuv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2andzvzgp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzaypij.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kurxvsgn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iigwfizu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaipwllz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2irkwhjha.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwaykdl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmetukvt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jstyhtqh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2chedjymt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvprvny.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpkumgk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvrsdba.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopcsqhx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsuwyby.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdtoyum.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbsdpez.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmglobvg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fatwtxoq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapdske.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lftkkjal.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vojqvyhq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lagnohvb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2voewenav.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2owtctgtk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfapgtf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2urzbmmfo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsriwxy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmjiqzm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uutkilti.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnntufk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjvwuba.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2devhuisr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2moiohkfs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntcreu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2thvdlieb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjncwvgm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apsjmfgk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2srgpjdek.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdpyard.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryywghra.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiyecdo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwvemle.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oitkuqwh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwwszwb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpbykcp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uahgpzzu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoiutzy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkvpswg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwkczac.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhokhmz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2btebuchk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2djojcusw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtghwchw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzaheco.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxzilwl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2smhmggde.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyklede.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqfghi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbrxmhj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfbndxn.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbumywj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2owyfkgng.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjfvsmw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqguekb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khjulvgq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmwvkzl.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjhzyjo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubuwwdk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwtxyqx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuoymmy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2efwodrih.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfvsbjv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyemuao.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iwklaaht.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cymhvwoi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2glowqjcp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupvwsyv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2thpcsoyo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbxwapp.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2otdhhmfb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkapibge.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpaqitr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2anudhmmh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gotvijbq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2abtplskm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwrmxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vushidmn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgbbxww.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjykzier.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ewenspgv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frixnffx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfefobn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pvedtbue.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjehbteb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwhdfqe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpnkyhh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzfcsew.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrysbtv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eyezgevl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsedycf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzhirqb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bicckyjh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwcsvld.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdwfysc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hzepwkbj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulheaujm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwgzvmu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eexjbyvn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2catcpiiq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qncmxlrv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuqodpt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2laezndqj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2sankxjtn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkgdmzj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcdvwrp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxembaj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbenzgq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoyusyf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmgrhv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnhxpvh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2utjxnwts.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvlhcag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjqbpmt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsexqir.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vozhxglt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fnerikhc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnsymra.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahprtgkh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2knknzequ.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxrwayq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaklgfp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2znazoedl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2swrsfdwh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2smumckys.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ocphtxav.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vddjcftp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2imdwhjyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ateabsfk.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqongtg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2loruuaky.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aoggstwj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsmpozn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bhogfmnn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjqvtdm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xecotgzx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcgihr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgovxri.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2blccfmzc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jedgthql.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2otjwayju.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnygede.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cruyajra.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtenxbk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ffppxops.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iovipqtm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2purtuxky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rswtocaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmngsxch.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcpata.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdflkavo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyeiabt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfqmzye.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyogdvd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwuzvy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfozoan.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2reagjuff.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqrkkzk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcncheiq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwahops.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2miqdnspq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2miarjwdq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrdvtrs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kauysjop.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwnbrik.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdjzyly.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkolicp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkgwslm.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhzhmlr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sewfxvtt.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2atpebgnd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjtitwj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xzutzggf.html


<!-- 参考信息 -->