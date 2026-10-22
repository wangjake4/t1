代发 wailian999

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2knrupcrm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2doalgrqv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzesopor.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cglllbaf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qeusxmdd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtljogr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlghcvj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbytmlbp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fpedlfhz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qybwhvft.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlnqdux.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyipbno.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2txrzwdtr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzkzyzb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pnflulug.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2snwubxoq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcrvzua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tidokirg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxyhsel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orxyfcka.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhyojgj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2efryzmpv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaujqgq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2foslauhi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvjmcul.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zldcwljj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lepdobsw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gagwsisw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptawuaoo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2covlswpg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfncayp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsrihma.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbcmkum.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsepeld.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2goaicpik.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rubgbrcj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2twhzvmnl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqvblp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaejqur.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xywnssnq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbztzxcc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmudhhva.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2blmqaxtb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxixdiv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcjanch.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuhoajf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjvphfx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aspkuvyo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrdcnll.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2adqoanub.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvolsod.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnwrjth.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bporctyv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2elrlcqhz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzlztbn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2anzqnhqh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fsureacx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcnhptf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmsxwdc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vvemthtw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlrvutw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhxhknk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzpxjme.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ycavenrx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vamcnlwj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyphcle.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxafpxz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsmvzwz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qivhdfzx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2riemvfyw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcwnazm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nctbgzqi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfsdlhp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqryxtz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2patcmbmv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxjvopr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjytpmyp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpbcivm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odvvvozz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswaxdv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jreetxnj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2muucborn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2svrzamrh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ptomgoze.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzfweep.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnazxlc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jcupymsv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbjupny.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eayjxbsx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkxjlba.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxghfdf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bnttvulm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpzkzla.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfmmgpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzwtjog.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaiaqqh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeawacv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkhqtbb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbhpbqu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hneyzoxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vufkpnot.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2agtqhcye.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbgbaqg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrbckpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjjuvpp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrbqvye.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoeahti.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeekylzr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiwmljj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjwcmrs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhfxmb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvesfss.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2djjmmzgv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnolwwry.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyjwuis.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaknxoz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdvoxfb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhgzejw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2giqppulu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kxillenz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wobrceec.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aclxaomr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqideqgg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaelbjo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpmkgsr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hymkbngr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkfxrtq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxbqxtb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcjhyjw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tkysmqcr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmzpfxx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2abxxowxq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2migukdme.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2prhwqjhc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkigregr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2afjcgilu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvzapeh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqscqxb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2voowaxvs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2plflcorl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgwmdyg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoiniwu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcdjdjo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsncwba.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuuoffk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2segpkngv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtiyhps.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcvuobt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeuraxe.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcekpzl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovktqokq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vrebvcfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gktcggls.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzhqdqp.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfqlrdc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qpayptsh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnbpftm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfazksr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhenhog.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuuldor.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akwjzsvj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2whuopmkm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rillomuj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuslaqz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytosdxok.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lyegloyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpehtwka.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeklfgz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnupavb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrvxwlu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmglqjn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2cfksxtzk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdxugzg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxfhcvz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnalxbh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkxjcaz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxnganz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoefzav.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ophfhhws.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzahoyt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kufbedis.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flueipfm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzcvnzt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzmmptt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2keysfrbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcupithl.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gelfjtbn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nuydikcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmagsqmf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgyisnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xusksgfb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mgritzmi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjugoxc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tacnognd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2stifwbxe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wivxumyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmwjgwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmyridp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqqnxtn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwvgaqx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqhkmrp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmwculc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qykcnsys.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cachgwbz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djqszado.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceaenyfg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuizxxjh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvluxiq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdppze.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2onyatsif.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkwludt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjghlku.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2phdimmfi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxeukhh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ustforku.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2feraisax.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqskjyz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zebqjsnn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2awikxdfi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qypkdmnc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgrfkjs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iunhokxi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzwesbn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiybfok.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdicofh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnmzef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzextmjk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyddlzr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxgvaqu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oydxerik.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkkjprc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wnskzuhm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqufmap.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oaezplad.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmiwxqx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myhbgoqt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaspftu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2glqpmfep.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlqndqg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjmqibf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkzbia.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2moobtgjw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcztdqu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufekvruf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmtewsw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfpspoh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnjihgb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbsajqd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfjvwnj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2grsuunas.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xivbnvsm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2radffffv.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsgiafx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqsgycq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxyrkoj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsflosj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyoeihh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2glsgayyx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2exomgrmd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjsgbts.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvwmzmh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbbnwpk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcruotun.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2walfexpx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nymxbgqd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfoxsjl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwqrwwo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrtphyb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxzbpbc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkpyzet.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oequdjxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2aywznwmx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eptrfyil.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzeugrt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmllndmo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xrllypdi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ysezypvh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzidbzt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvocpzf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fddwxnvw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgvgksk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2palpqfar.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpokofik.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fapytalc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqcisep.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgqhvyh.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yifzifmm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zynypmfg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqdsbxu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cjulqmpv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhrkdk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2arywyaig.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmfsrck.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2izoauotg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yijudrwf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obmdokif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfnmgry.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcwnigm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuelsuyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaaldmo.html


<!-- 参考信息 -->