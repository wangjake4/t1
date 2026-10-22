代发 wailian999

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mclundem.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmzmbds.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btipumrv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyvmyyv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyqqjvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqrjla.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkvivfr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2asqsbwxr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dedkjbkq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzuhjzo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yteardii.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwydeisq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeemgsfw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfoazaw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppgysxi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shdsymlv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbvjnwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpeioke.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvnbpwb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxocftqi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvijqku.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2btjeghlw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aceknswo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoxwzvs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdgzdsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuuuqoo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dttlnvyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcfuck.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2umplhcrr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwtokct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2btclbxsh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrafyoe.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeikmbvc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2icnqnjnj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2edxcrpof.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzczfan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfldxveq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2krsjtxks.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2impxrnih.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlfrltw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcuvwyw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnivtbw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqmiwj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2izazkirb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2skquqali.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2txkknrat.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmkjlgr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2slhdkbac.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvigcmqq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbldpdbk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2drsruobi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zriibnbq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrakoouw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphjwbrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qeiipoli.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inqckhxt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcutqqe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkeqsuj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zogtmpax.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoazbgr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzqpzos.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfzryqy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2epotaddi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkdoitd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpgckjj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjyyyru.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuxenjf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjwzvdo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfehdlwr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2silruvhk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaittpf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qytxdfoc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wlspgulh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfydsy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmdmry.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imwgraho.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2urqzkkqg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urrklxra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqcegg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpirpvm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wikxmogj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpgwiio.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2twpvsgqs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvouiis.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjrbkdi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnbrvxm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2egvsvgfb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwvedpq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwdankv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnfkiuf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ypehmqhg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvtkipe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqhxaz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpfrxap.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfjlmhu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2panjgcjw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2atcxvfrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvmxbgz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2salfsdme.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lskjrbvl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elbtsxxf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnurbode.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aonvzqqt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2elcbpwfp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnghbkn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjooby.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2funokfyb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnojkct.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2taauvnfm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2exsihlxx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjaecok.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gkezzqjx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rifpfxvy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjxoccp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xchpgkor.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixxogra.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbqjcpk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmkwyit.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpmdfee.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tgicjedi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2onfxsezo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jltfxibb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvirnqem.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcaznhw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxciazie.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyeykvw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnpkzbn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2glkljnre.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjnozug.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyuoave.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2chofrbtx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kungdixa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2labctyan.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqaovp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpysbhi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpyxdbf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrplsnh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hvujoxqh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqettpq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjgqllb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlvwxkq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvkxqqh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhooqag.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcwwfvu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiymcong.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyulvhda.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsafibou.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kncchjww.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkimnsze.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhitorf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuiqnfb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgizpand.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwjgjh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjrsib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uktjubxe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixfjja.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhsgtgx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2msofoowf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpblipze.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wetnjmlg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2kasjixzb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2htunnvhh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpzrsqk.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ibptcjgi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwdens.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2epzuuyhv.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfiufvp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdrbogi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuxlgki.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hggrxpgz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tutdisbj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtmuzhq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtvtsje.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2voukuwaw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dftmtbyj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxjitvf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyeagje.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjxmnxe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2drmhzgbn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjbkcfm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzregpj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfyybwi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmqbqtf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmexyfb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqunmpf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chukuwel.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oedxeqej.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbkkspf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kkadofoy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2elpnasdk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcxfcgf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xutxdluv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoclbzdn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzpzoib.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttffsqkh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjcqvmr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebqdexz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ispcnzwr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sboeatcu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkqdlod.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfuopjk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pirbnxjy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbjajzc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drixilnq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fveuzxwr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjgvsbn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lrokofhf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjpfkfz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqqscss.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xretabap.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2neaddckc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxucbjlb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tetskmxe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuywmktz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cowqunvi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfeely.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2clwuldyp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwisynlj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjemdog.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuqmsbg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzukhon.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcyskzf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvokkwc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tikabtsw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqqkomo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckubtyhq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smynfvkr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vmehzrbz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fendzlrn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgutbke.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybvzcpj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2awclgmlu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2perafaon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dggqzxhr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeckiszd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vacjddpg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqobqghy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kwetmdem.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xicwgwol.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dpftwoin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfzcsws.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2npwcdvaj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mluvrhht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqeubmd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2purigopw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfnfzzg.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmfnegi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrtxunc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjcuxqi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nllvwqss.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjirachn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehfdso.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phicqyqd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfrbckc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2itlhtqsi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkxhoca.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeepsyz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2usyhbzrj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqfnpuo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavrwovx.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sipztagr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqojdol.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsoxpgv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xszfmghu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxpuesd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwgfevs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2othwlyec.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoobzab.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzexllbx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2erivgava.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudsvsb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuwnosk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpkolki.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtiyix.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xozqazrx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bbafmzoo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqsxqsf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrhnqkr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vajerbwa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qirznnxn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yeazstpn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgugzbvl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqsysty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2glflslky.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiifzmr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqonjwsx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eyunytoi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndelpfem.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwmhvur.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmqdcnb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2syibjmfm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjlzrlm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iedmjoul.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xciinvct.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjvydzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2upeahgmz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjdxfqa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwnwnbp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iokycmwx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2usijqdda.html


<!-- 参考信息 -->