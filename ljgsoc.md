代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kejhrtcc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkybygr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrkznpr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tghjotbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgobbno.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgbmlzy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgvsckj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbylefn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfioqhn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqxgtj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvyuusz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iauxzzjb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2frhjpoqs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjwvhqg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmppxmc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2imnewpgw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2btuhdbxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzbtara.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjmpeuh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ebekwniz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bcutaadt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lokppsfq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgyyedb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhnxrpk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2edsndgpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzulnkuc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yomgemhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmizuokp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyvgdqt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhdqnjh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2agkfampy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephapsho.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvqybfs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dixohrez.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pddtljmg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2reikevab.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqscthm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhvxzdh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlftshv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfqcfkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvrezab.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvslcgdx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjjpmcm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tahkbinr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kweiorsh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxcebwo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfveqbvk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuvivne.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2euuqaumi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2daydnflo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtwugat.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrnmszl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdvoiwt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuiisgw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfgxrpw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teomrcgn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wholumqw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvervvna.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xesbnjce.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzngahlp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhkrgh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hagmiytl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbrqzia.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pmutgwpp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wioazvxz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyuqnea.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbpkzoe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2osmprcee.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vszxocza.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjveol.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofykeeyp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwpbgdk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgruaki.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2opozzuxf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jgghbvtj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmclkqh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sisymdlg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rssmritc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izvhzuor.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bseldrcb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2thumzolj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfmneiv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xbznfgim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2knsierah.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgcviij.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvjdzab.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnftwds.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqymflbh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfcluiv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mntdkgme.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2idmpzjqh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiikkuk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbnldpp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhaqvvx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sracvxnb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthwnpxw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxedhio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2equcoolp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2elgajqht.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zelzsvho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nztdylew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qitelodj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loguvkgo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nipovrin.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaltuob.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxkdnoq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxgyysn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kfalrzvn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkiwpil.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaguhnf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdaokxh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkjkiru.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvczums.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2glylwpko.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdvxkal.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnqslgt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2buehwjui.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xllgblhz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwqunyt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pojctsmq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2voqgocge.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qymacijp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tajbrvtx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmvxpif.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzijcp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2honczpue.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2huplatjj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpvzcft.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfdmtbr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qztbrntc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2siqjcrpk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlnstwf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvgaudz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wngmbarz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmkdlyw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aemtdpxi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpcrbxh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvjdjpr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sfujotjy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwaogkn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkqpkkp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wniaryez.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhjmulp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzhckmv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huqimgpd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbgghhe.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dchwhzqa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfukolev.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsjvxmn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eqarqswu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhegymc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trxnhixh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbiihdk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyjteyn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kedjpgzg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzbhwdk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkioakgz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjmrsj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfieexzk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vkorqenw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2krwepphh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bqazrbyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2floftqca.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwqjslu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcvqfwx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpjxcfz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwqmonz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldffriwp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vffqsioj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhmzquj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjmeimh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2swsgelmw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiaucds.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rxueytuj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtmnlxh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2etjkkrej.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2okprclpj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2njqipabd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wubhiyuu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2csoafgns.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtxojvk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyccjjh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kueutzch.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqnbnxe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkwvzrl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sixrgvwm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gorqqsus.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhwhhfn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvblnlv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlipopj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuxgbqt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2desvjwme.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrfddfq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2byseahxd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoozdsj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2apzkdqlr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrvswhj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kthvwbod.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2btavsetn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrlifah.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkhbqjv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmabxxr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoqqykb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ganhpijv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gukkzznz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2undqarjh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnnaxhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2iawhglem.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2opdnhdeu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yckwyhjg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxonolr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uukffzgr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2awqowvii.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoitctf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgktndl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iouoglah.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjcmsfe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hziwpafm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbjmtsk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2azyolgdv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owrnxnbd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2awnkaqlx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2evlkjadp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iudhuwij.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgukfxsi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2czqkseeq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvepxmpx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bopeaukj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpixyzg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uujnwyel.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzgdtmi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxozmmug.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjvctjx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywejszks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrvdufm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pufmghpj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lokkbbvd.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2knqokyrx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfrdxwt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhunyjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebytywfp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpmapap.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2glytdawl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsjtzic.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfahxpnw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clccmyab.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsbvxoc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2urorbujx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhjvwdi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2starmqvr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pibirpbw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgecrsj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaqnwfl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjosetp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkihtdf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdwajhk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2phobfrqz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvdqbkz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvobozq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewvvtuk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeyoinz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuhfhee.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dnigwqzb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjjpoiy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuuuosk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdrhgsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlnwrbh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsvybie.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxxeuli.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxceesu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvhpkvf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mguemhgb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2emvfuqmy.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfbsaot.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmfttb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrlfuwu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgkjfxd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojuvukk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rorrxrdx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhqswba.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2acleohkb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgusfjju.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpfpxla.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2osnscgbz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xjikvene.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxevyeh.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stvuwhte.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbeircx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nigkjdew.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhbliht.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqazpvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isnysmxm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2auykohqu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeslnki.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwewda.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqniytk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tytqhnpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkvnmwe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruleqiur.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeubalt.html


<!-- 参考信息 -->