代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2idapeomb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjxozwe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2epotzeqt.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfkaaio.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoekadk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htuuivyi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpwneeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnnogwh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsnublj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcfkyiy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkkrxyk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2znigqkvt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilekwbgh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2axywjxie.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdeiszx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuaooiy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2paezrixd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsnieul.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilmkqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iprvdfgd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2atwoialq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwcxbhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmbwael.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jezxthpn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2szsecyyb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmfpyfj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxjvnuf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uznzurxr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyhevym.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmetuv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thhwzbxo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2toewhwcj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtoudqf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcxuxe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxwigic.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tukdsquy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2laqutlly.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfmmysb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eupflqud.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ceabuhfi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2preopzxx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdhgqe.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sizqarfa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyydisf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pguutqvb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2obxqzlac.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mghprmmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrlkwgx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mklxendh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjetbqr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzxcuik.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfgktqx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaelcqh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2owodybed.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmkrkdg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlcpjer.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jlamoqas.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irbwgsmw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhbysdk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbipggg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzalcrvj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqiqfpi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sofkavxb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxbrgnj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdghkjf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnnftbg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2crvnodex.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hblocjyz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2axcjvsgd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgxfyjv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rxixiwqb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsrooig.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwulcjz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkvvask.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlwnocu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxgiyqn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldshwhii.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2spaozxwn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhegqhzd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cogygfto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcielixt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoshrwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfsrkkz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjbokco.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsdjndt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrxgkct.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bchpbvvd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uckqutap.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yefnuzme.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzczfpjm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqovzaqw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2libjeilc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxrcuuc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vihupqpi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjikmmq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmkqcgj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllbkoa.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrzeenu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2csvjurhc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiegkzl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeejdmz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvazdeg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eztlqquw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaiobyd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wauyareq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqadmie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aprztlcd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trbkzkwr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdvuanf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdvjcax.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhkuehb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2seiuuzcn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2plhgzdcj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmkuwyq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rjckjdif.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiuxdrk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfssngl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuoulpv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wunmvxcb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2darcllht.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqyizxx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2emnavick.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2eobwmory.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yoowushf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsiyftq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2etcfudkt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2royweexf.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwxcxfi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jegeznrr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2koilmdxq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsiavar.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvxhcou.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhlaeeh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgknubc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aytvkrea.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gieelrba.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhwktwf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnjeatu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuiyupl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbkumrm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpltxmkn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfzefjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkqibqv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2woelixzd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwvbzcf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgzefqg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgcvioh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsmmwhb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiudsxr.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2idmrlyvj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcvvgcy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjxxkaq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zntawuyi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hbooipju.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jswcthrn.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfudvhx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iniqifem.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzpegck.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyudyndg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2flruyqno.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2askhsvwi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wixndbkx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vazhfdcg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2eztnzsbl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2asgydzdi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiuqrcm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qidcfgmi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjvxwkz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xxusnfsx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbpyvwx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdhcijf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqtrmdh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbeazbl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvgxajy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcphuqnr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspammg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdaoza.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2eflyrjyj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2moghmlcy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaufkqhy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnuewao.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wplnvcxv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mremdcei.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2onfuhptf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyhwhka.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwjhnuf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqkdisd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sicmpsug.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfybogu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vperprcw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfbtorb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sehmezeh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kvixbjda.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeauamzn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjvqytk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrthfkqp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnupsn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jicisoca.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2leupgwon.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiyztrq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsijniki.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcxkfgn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxeohzy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2guseswjv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsrwcvh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yllemfce.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnjezap.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpbegrn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlfbvyu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2suzeainn.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxellpl.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmbdhud.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvenaaew.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qajwnuuh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2riuwerfq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvvwpnj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzciufqd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2meimvfxg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbsmuvb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gftrbzgv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxyfqnz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2testcjao.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qwddoxqb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2twqklctl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2njycdltj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwuldyr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sapffubt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wutkipby.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxavswql.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwnrfzt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsryldop.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeanrhmr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfztjzmv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjhyyyf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mogqkplr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyvzhpm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2xcndtnbh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dusrroya.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkyinpm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpntmkpg.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mankvfuj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xftgmgxo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwqnhfs.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rruogptr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeonhhpe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqzbvmx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrlercl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaskgkq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjgqqq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2hggwpsbl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxycony.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcfacit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cavaqrbl.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfxcbyk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaeywfv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2etxzustm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqfnrch.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktixdwnu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiettut.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbrktnh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uktkcnwq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xyauefin.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtsslyx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hpixnmch.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2flhnuiko.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwcxidu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wopqmipu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjsauqn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glqjwehz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgzusrq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cptevgmv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmblknap.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjlkexu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpihuucm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpnlnax.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2bohegaus.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqldnyv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zibgvssb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxidhqbz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkneslx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbmffav.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aclkrezb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaqlosx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvnzaxe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvoguzu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2siblxsfp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qplvvhms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mauetpgl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwhredx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rittgqjv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghhcfn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2twuawpmj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkayqbi.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrsufgh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcidqry.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqxckfo.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2soevfirf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxfwku.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2skklelfn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdnnduf.html


<!-- 参考信息 -->