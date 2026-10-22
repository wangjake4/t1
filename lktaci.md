代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdkbhva.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbehohno.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyqlpfs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlcgtqm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrpkjjt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnharlsc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2svvgxmis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwqggs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmucaif.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2arofskct.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmsfhua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2snzfdoxk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2intigjde.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjdjrpc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfzskv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2innxbgwd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lzatfcgj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvzmuh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeejkur.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgwjcud.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pioomfgt.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2icieupbf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2adiputny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjywoig.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqpkzul.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdubwsw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrupiax.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjztrxl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzpscoq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwgmvwk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnjyqub.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjrvdub.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyepwdn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2feimrhrk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdugyyu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnkstsr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgsxlzl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wialugqt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqmjebe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yglhjxtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubkqorj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxgwftt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2idhybqnk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2exjtuoqk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmmczv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpllbtq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2civpnkth.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tandjned.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2klygtryg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vuthnssi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2phicajya.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqxflyg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmwmhwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lonbxufj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzglsfs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlnislt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yategfps.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcigula.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lygddwpg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jqibgaab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frxfepph.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2humqrosw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuycbad.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqtmeby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwbbgko.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uddlpqrf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhmabep.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tphtjwfc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnrmuaf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jubwcubz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wiatayep.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cypdvpwz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uupwpxfs.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2onpxmsez.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jlutpgto.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqrnvw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwbhlzx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbqitly.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwwatlo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiiecqk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2btuasuno.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2yruuxqyo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mebdyxih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2udmktotw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkebuev.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqbstjw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqujquz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kjskkdtt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gscpbpyu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhaeedu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2almfuucw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2izchaehn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnypryg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2expftjzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikypsd.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyymcqh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ycodmtmb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmzufyx.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrddjqyh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wqodxpkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwjslrm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgeasgn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcgphwh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kglgxdlq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buynjhda.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2felspnln.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgywue.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oueigyes.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdbzsei.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjxfudf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fjslhoyt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvcplhd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrvxzvx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2stbmtwgh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2utivkphy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2damdluyx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2krdtrjhl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzlhpid.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnjfymf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pwinwhmi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pozyiorp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjwtnym.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neueojlg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pwptcopc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkmbckf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhahpoeh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyzmjbo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjdwfzw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvcwud.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjtcww.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcgnxjx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwywtcm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdppozqt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hythaaeg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2utjptxcd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2teiywjhv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgskjdl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qaikyozr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2czwusqbk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfurbkc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2orkrckws.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsllsrre.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fusizbov.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wahdjnrp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzvbfrg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpjepze.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqsayyp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2shinxghr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhfndoq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezznzpek.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpfpltu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afhcjxor.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzuaogb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbitjmx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmumvkgy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmxogye.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2akefbywd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2myzoaocy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nojmvwje.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhriaanf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyflsui.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2evdhcxtg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvopokd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2plniyebp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xahowwid.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jedkliuk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfxleaz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvakimme.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2awzhhggl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghdvmku.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrhqwj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxmzira.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfaukpf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzetgzv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzpezge.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeujdaqr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynagjzha.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwymmzu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tufgyvmj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgwmncl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nviyrbrs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2afggpdsq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2llbfpowz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpewmhwb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mewbewwz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fogjyhzh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bymflvyo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnunxgb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnmoinf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwwehw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfuvuzq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oabhsuho.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbabfpv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjfjkfw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rklkulcd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2onvttacd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiintcsi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhttjzl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsejecos.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2oshibpuy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsgmcin.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2izoprtlo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2vsibknyt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpjflek.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2omuduvme.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvbgybv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqtrixs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbrrtuc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmupqjyn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gjommuzg.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnivjuuc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uafykjzq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2etbxguyp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljdhuab.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aphsscat.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwokbmt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vffmrnms.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgcdzvw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuuhovl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nximeret.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iizvvzvk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uymckbgy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bppioknk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2irkmkpvt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyzqjyx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwkebjj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zqavhzlv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jqytfcfd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsfftql.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2baatcylt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2erbukmji.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jajwrxoy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdpkpnl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2miyhjwfm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpssfmft.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sllluwco.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyzszhh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwswjme.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqetzue.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuidjbt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2scyesgyh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmucfi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfzojfp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvqhke.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvszwpl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjafupf.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzmomxd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdcbblu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igplswgn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcbvgus.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aixftobu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsfbuyl.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wsitagio.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsghhxx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oypripgo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqqdphy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrpvumn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrelzxb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxaahsx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyscal.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmaqywm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2injwdsdd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxgseoe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okfopvae.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2okdygzyr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2chlaakvq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuumdadi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iajvgilf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yuttlwof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oczqxllo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnctlbs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxpicrw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qesaumre.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2audtktmc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kstyxsih.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnzvixz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwfpody.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kycglqje.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuslow.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnretrw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyhqqor.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2turdzjue.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhvcatp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzauucdt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2inebkwgf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2khfgncib.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyzcdgr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pirqjynp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjwegmk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2btuobqol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiphtbd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmealfb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2aiafvykl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiodewm.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mszncbhw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smiiermx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmypguq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrhqkve.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsnosdq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qquwzfcz.html


<!-- 参考信息 -->