代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzqtlpw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvelmkf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2slspcpfo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjginas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqthlxn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcfcoaf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfsaxbd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzdqpix.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thoiroxm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvesfrf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xteqnwdy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjnytj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjbjpuo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qswmvela.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrewtyd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjrnkjl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2djwntvhv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlihsljy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jutvbdtc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpjpnwg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2garggzdu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hngiitxv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rshkmrqd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2emvmppam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qudcmlkv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojtcuhg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2whogdqcu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyhvslb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dcafkvko.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaeylhb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgwlmwc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bderwmwr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuzfalu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqzcrlj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysntakdc.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwrkyex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfxfzsc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pleqnvuw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsdbjtk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yunpcsow.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2snhhojsz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrqikpo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufltglsl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjbberx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2clsxxjld.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjwtmch.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzaqvsp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kskzudtk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkzfyvr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdqtfbo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsuwqro.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvwmoaq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhkowm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgwxos.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpvyaqc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sqppmija.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nciecose.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgffhsvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2auqqxcct.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzjrtab.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcrfqaw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fxguzgnl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqyhwug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuwzblt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjyctyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsggeafj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjqvsqj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvcoxyu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oeijqpff.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2axezcqgk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cdurqqsq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2meqzoddh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaalqdy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2apttdhfk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvhjhnx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2omcebpat.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxjjyda.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbucfjlu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2scybkmhn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2shmoehxi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2clrchoni.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ommxwudx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpackbaf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjpdiku.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxagfoxe.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucckjpck.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lirmosal.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgpphvg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhjfryf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2rydjegza.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exicbnkf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rructigz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhehdzy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhhambm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2udsymbbm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtcrkcc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhvslli.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2azjjbzjc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwcxmsw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlpztpl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjkgqta.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cjluyutf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaqzgxz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrdsnky.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eitimmke.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2imrpozkk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbsctkc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbljrft.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gftovtbj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yipgxlxd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvmsvzx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vqatoymf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2natggxre.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sznnigsm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2grnkvdtq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgzgcjw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2imponwgj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qckpyypd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2reyialqw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pcppzder.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdayxyh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcrtetw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyzbpvn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bcinoczk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzqojpj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgpbols.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiorxhkv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ojavxmkj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxefyfw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2duadyzir.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhmtxv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2amotjmah.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iobfrifx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aboswfpe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnchdgej.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2idswyerk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqtfyun.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsfzfla.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdesgfc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2arzthzka.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxoqogd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skuxycpx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2udoacexl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wajtfaar.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhtviuz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnxwora.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuduzhp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2radqkdfi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwppumv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxxthif.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hssczslx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnawad.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgcbnlm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlwedkn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2drnbtcsk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okvrxqmp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtptbkj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrntimf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmkzcda.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdpzjga.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlumdoyi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaoadtx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpkueyt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvvurya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuxubsk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdooihc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwpbty.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2romegmfs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2byqpyrwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfhtgfo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqlnmtw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcvydfu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2azeqwcje.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkytmbp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oeskzgmd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrussspu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ferrkwel.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2niscpnad.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eigyvfng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxvemoa.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sejywkjg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzeenaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exityryj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gchuirey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2udiymspd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxtivjs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2khlpomwk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcayzjl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjmnktm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxfrmsa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2glxnlypz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dahwckte.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwjiec.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2buquvvve.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2muidpgiu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jroyxvkl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2buybsdhh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuxolip.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnecdtw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bccvyfcb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoadzvz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlsjitc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdpctsi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2divostcr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llxrfopv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2odkrlppg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgtccdz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljctlgzl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhixngs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zifondog.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nzywdxrf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuacdioo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbvxdjv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cmisaaeh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phowrnsz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxelhaoa.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tomswjsn.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpeaofs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgjdkrc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaupfsmz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wexenfpo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzmkcnn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsoehsx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spqnlvqc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrakjxj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxcvorc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgkhegp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uexjqaxv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uckqfljn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjakxlf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdgteyf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sodfjsfb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgooobc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2urkxkqni.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoncawh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsfjfiw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2roscdcvs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkgpmoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhegasig.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2enxgwccw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2obfalova.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyponql.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oupioutq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iltdlvrx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wubiqhxe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2uulwkgpu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eywwpwyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mxygedaf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2udweerng.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzjfwxa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjvlxql.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnlksiz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rowqumaz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyomrjv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jewvyaer.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsapbnm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xbclhhmm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbncvrj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2owyabiwr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zahetnjo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mczymdis.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aiovijpa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2savnfqhc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgyeqog.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvvyrlq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwqakyv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgtzsse.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2alaxuafb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtizuen.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jeewmigl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2laacukcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhzzoct.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lomcasth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skyyssce.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtidicb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aouoxrfc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeymwww.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2orsiiexh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaooamt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhggecgj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2neptfzft.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdljjiu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jigbioyv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzmuwq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjakbyvb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvaaumo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgslnxv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyewimwq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxgtap.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rthyodig.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oktgxtrx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aadpzwsj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qshdqryh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gomtqeol.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odtmdfgz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2eqifbany.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfeiwxg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmyxnbc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzguujoz.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgkhcid.html


<!-- 参考信息 -->