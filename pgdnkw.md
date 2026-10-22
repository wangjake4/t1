代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsikyer.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaxpcko.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehglbutt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmrujiq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwjrjjx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ploazhno.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrulkqqs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjkugao.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhtiwqm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrltazo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urcolwtm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgigdha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2raulqisc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxriiune.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxoizke.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwakici.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbddeswz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawsmpwv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvvsrj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkeizjt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2atrmqhly.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzdrijw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zauwepvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzztirf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yffiugzh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhkeetd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2srixnqvg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhcqpyd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjodqje.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzuvtgr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2spleithh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkljfl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrmzavl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yezahtnf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlhlwf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkuwnzd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ofepiqkj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2txrpxisq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxpcogv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jylvhovm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlwgfkf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csejozir.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhumlxhs.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drullodt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2euufokjm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kayjmlsm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yddnmmcd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpghotc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2llvjxvud.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpxqurm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsbabyk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjmtyuh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uumokoki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmblfoh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pxusaely.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fnozhtwe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2quxetgzm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkpktgz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbllrdt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thxadeur.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2euobcdih.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2iugbrwra.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkezakuw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdagyys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbsbtw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpljrjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hglrtvzy.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hydxvuws.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eggufxng.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmvledi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2afrredfp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2npjmxozr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2avcakaey.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbysxjuq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpdopsm.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2btjyhttz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ybozsock.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zplpmqoo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2benyrtns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kixarwpg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rffyxlnv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oilmlmvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yffzadrd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqozapgy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2isipashm.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2umofgwmi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mamwzogt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjutqcw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2libicvzo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2iiabubva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2coqnjgre.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aakbotln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdmzzpu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeslrze.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtalhwrr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tafbjvmk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2elkezkea.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmxtrkn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmfoxld.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lihxsckb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcspldj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pquqitji.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mopilfmm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2psssindq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgsvtxk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2gmysazlp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdazxdxf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaoerze.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xypxadqs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqobwzk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zapiufap.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2caepnsvf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kskyzuba.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnvkehi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcdpxiv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hugeugrl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2erjuaclc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2isqlwyxz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rarhirld.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iivkyhcz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnquvc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdqmyak.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqevprw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjphxaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iixcnzeu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bykihjyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkysqvc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxlreea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2cchjxzau.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqguagh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtlebyl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfpoblu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qahywxjp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvfxdia.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwzrdwz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeunynnf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkobzjlc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqoszrx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejugpbdn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nvydvdlm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynebvoxg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoxnsqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2osecorvn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvmkmoq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdstym.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmiosrf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgiowmt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuwztqy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnnehzi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrzgfh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcjjfcl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bueesimx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2brahhxay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsgyvdr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmnhlwt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2coffvazf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdakdmn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vivonang.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rinsiokg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwinfms.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvorhba.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqwcnj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2erofekrg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egtxmjlz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ogynzniz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmwzlbu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xullxewd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pszqeaod.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhuixll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfzjatr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2remddrls.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfgoruu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfzbvij.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqibqldw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hizrhqdm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjeibmx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rqddfnzi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgknrgxg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrawfxn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhvccf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpplnkv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dawwackj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrpmytl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zskvhvbe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdpwzsa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltdwrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aduguhgj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkndmvh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgaxxhda.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2bppiywzp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjiogd.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpsrggc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bmubxbdz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2saclvrsd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbixutc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lltffrrt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jddkiugd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwflnmk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcrzwre.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pcihywcy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypacbcgo.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vydlzctt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsgpzjz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wtelqsxg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcstbyw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2haclyyjs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsltlle.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grplgwbw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hnofzcbi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxbmigw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ckygihqw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcyjubl.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqwffns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdqgnqa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxywrkz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hptseduj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hznvngbd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ninkjzrt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qhezjcyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvizlgj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nftdqiyt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsieizwf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gidfgzud.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2owmtqdmr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2unkmqbse.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xruhhigr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkpubts.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qmplqool.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyihlef.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jktrfwae.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaxhjml.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbddiuvc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2blodhkij.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhduxom.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ahaabfjr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sbquohwe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbrcorj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xhetzmed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhkostq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhrqcob.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuibyri.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbtcypl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyjyker.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqamyo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wyutychz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kckamvxz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lshfrpje.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvosxna.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tfotfoag.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpjvicd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eiutjsqa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbhorwp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldytaiyy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjrxrbd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqkoxgn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcanjvuk.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2subwvwpy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twsgnach.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzjirjd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwnwcek.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfdbmyp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2toznyrmw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkurlpmo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rysmmmvn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtaczfp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2yszovshx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwifytyg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fssmztul.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtsiuza.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzecgzh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjlwfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaglldl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2evwfrzwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlhzwua.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvtseyo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2utlmfmmh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlzbauu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzklzaj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoqrnza.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvyqvqw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2baprweuo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mljyctcx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgexrzk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dreivyeg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhzcckn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eulbtcrn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jboixrtw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnnavcd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdqvumy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afvmldsw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ikibzwgy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kldokjsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2amgxxcov.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2caxbdrbc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ifciofss.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2avzrjxrj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2onnhuffe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvckywe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxnxlth.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2maivxoij.html


<!-- 参考信息 -->