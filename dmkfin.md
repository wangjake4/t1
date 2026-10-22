代发 wailian999

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbbaabn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaychbt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoycdst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zogmlbvo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2waauzjnh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2duohuwtp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nrttgdqb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuvxfru.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkokrglp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcruhj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zllnzfrm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fwilpnbq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnxiinb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2toqytjdc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tryzfytv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkarmuua.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqneouk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2erlsxank.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtqzwhx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sadikihl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cchsyfkb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmpieqo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hndcgbqx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqnrrji.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2frdpbtrz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpndmktn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2agrcvobg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uchwqlby.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyqnjkq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzfignh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzeajsb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmvcznj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bywhjbfx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwgeqrt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsydigx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgatiwq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsimojqo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgsegsh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbwcvva.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpovdrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kivpspfc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzgrrtj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vnibwobf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwqtipg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzvsscv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuncmsi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhauabxp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcbwhva.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2phvgewvr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ceckelgd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2osvrfuyn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orohvbax.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2shaekjxt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbvmjua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjogygv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfczckhg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcavwwi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcygcmu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ajckyuiw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrudoej.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utizpkbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeygvtxc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2splwhpzs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atettuyn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtdrnlr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2okcjuljs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tstgkfos.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuimunx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkstdlcp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzwtund.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdhygrf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srgtphjv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrlutmt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzpkvmz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fahontmy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtaythi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srswgkbs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmtxelh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tglkdtkf.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvzftus.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjdbsmb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tquovsxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrrxlap.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqqgwqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dgadrphh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2apfsdhzq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcecmifn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pflsvvki.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnpkwwx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuewjsi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pjolyvew.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsehjfm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2chzmddkc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2icosxhmi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihymnvig.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkdhdfu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrhcbby.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuofnyt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrccona.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaghify.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkwayci.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2renfombf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqosvzin.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvrtxaj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqwbpcc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnamskm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaaosuy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmaikww.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pynaipav.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2quwowxme.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2asctdhfw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgsehyk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdlbccl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kvygbhbe.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2drbizqvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpzziml.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvvbvp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nmikiscl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxskdogq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2stcuteux.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjtnkst.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdycdes.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpefgoq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwsejrp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sklbpyyj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mapnmhzu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvtnojt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pmekjqli.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xafwgglp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkspasi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqrjuto.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xayexyof.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzulbos.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdtonsk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtekhzx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gehjxgmt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2abcxjjye.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ietgzmdu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2saduvnvx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vedrgvhp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaqvtoi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2foljlmde.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wllbbzcm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdxwqmp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmycpze.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmjrzmt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpdsuns.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ioithrfs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2maalexoe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jraxlptv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsirrqf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnxjjuy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgatbea.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2igbnwpka.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdugupxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dujfcmab.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxpuyvw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmxfxma.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlyxbkk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngqedx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ntriqydi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqsrfgg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxqeuau.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiovkxsx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkyetip.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvatykhz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2idadvqbw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhrwvlt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zetotmka.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzhfpvu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vednjtcc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdqvuk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhotzjq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2blpwlgue.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdxlsls.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlgoaqo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kqggrhzd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kscduexq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbjpgsl.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eumppkrs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2waouxrbw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjtwdib.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxyagia.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjioupc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeiqdtr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdncwrtf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhhycwt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kthmorwa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2okofwgsl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhusudz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ryygzudu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfwwang.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yyznopqo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiplfmi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhbukho.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2grjghmdg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvvxhyk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kqebhgif.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdlamgf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hgttizno.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkpsaqh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxtacnm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxnkfuw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtkwhwn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yuezjjyy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqmevcp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyuvgdx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aljddbcj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsiuzeq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyedxcj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dizqocof.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2whrvxdfi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngldiibp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wiatcyzz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wljlxmxp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2htllndly.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfowvgnw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkeutmt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglvxqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yprjaavq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yefrplen.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiufxsj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ucklhnmg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmycogat.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzcknug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ribadrzo.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2znkhxzro.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2srjfzxjq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2efndhcii.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sajgnjez.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxczwg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzghmnmv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2akhdosdu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2otzngvpy.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiinfvk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxmvpvj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqcjlcd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2alzyjhqe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcngone.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvosllm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmpche.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxwdadw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2weepvgxc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaurkub.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svpanaoq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyuqiey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kltlkoqb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iztqyjnj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nagcyeoo.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddofigea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbwslck.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlpkzfj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rchgnipz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfanide.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtjmhdt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjrzssi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdzfiwx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdevhs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlevgyc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2crwyvifv.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvterby.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzulglow.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqibmywb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwqkwvh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoofwfp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpqptyx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpvkqqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2diyfypne.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfwbnof.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guobtrsj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xceynwev.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighxvbwd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2avlwusno.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgvznqj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdpzsuw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaqfbbz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjynitnr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkkuwmz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzozsble.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvljwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfmfetk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhsyrwf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyokiljj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adtsnzjp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnbzwms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smrarzcg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtysljg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xiirsfif.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdmzazu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2queuyeoq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqqvinj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpulorm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrpsahp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aounbadg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2minsmkxe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjutsvj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vruddtrq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rniheezm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxqryxo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpowwcdk.html


<!-- 参考信息 -->