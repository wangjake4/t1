代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpycunlq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbmghcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnhhjhw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxsiuux.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmodam.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdrwjmv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hserzbyz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hlybavdk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyngaxlx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhvhxty.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcisbxmo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlgfidr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sughxdgg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkztkpxt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxlpkzh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cywdbsmb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zslpmvlr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojhlmri.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlngrkgt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fssvzzyd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiutxlq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yznwvxgb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2buebtabr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jngnhakr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxevks.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ieukgdyb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaonoax.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwpkjmj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mybpthji.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etmrucox.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzuwbua.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhtnyba.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2axkcqasb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyrxvxz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbvejag.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxfprst.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jhknfmot.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2edvnvvwo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgtemgt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cewxopsk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jscqvzjy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mmatytcd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfjywyl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisurnfw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmzlqkb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdisuwu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsoydby.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijrvxo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiqlelz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2odezbcie.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjhwki.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfiwecc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwbymej.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gizyoxgd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cszayqbi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpbkpic.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ctexaumy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxerryz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtmqesy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuzolhb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2geqxeoyf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2plycxldi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gqehivlx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhslogq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyajdaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziprtbzv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmcrtnl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dttawjea.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrbbebx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2byezdapc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtzprgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qknavtyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vieglfij.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxngump.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxurflda.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2arqiphwi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gohbcier.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ootbwjbn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlguznmu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkheqmq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsznlla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmngcwq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkqvvnr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gusdupei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2edapbrjj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2igrjwmxz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaogjvy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpinsmg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrgvgtv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2orlqdepm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bweonmmx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnfdmft.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqcrhex.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmhnalw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwhphin.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wixpjcuy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bmogqekc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyjrhtx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkycfhn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xnowywij.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbnbtas.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqwhtkn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwejiwet.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhmdoim.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ighgdqer.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jceklggk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pijekdvz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqvrugt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2eljhtgus.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfiout.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idlwuagv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2muugndkw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznfefjs.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoylmvh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bqarzbam.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvxhpvt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbqxlwm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wfckocbk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2viewwtqp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkxtknk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeeynao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqjqqoa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbzbkio.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsrtqoz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahomrywt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tywihefw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbywidj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhcxvlc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2apzftjao.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2urorlhiv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbaagpm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rskpoxyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwbceib.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxqevau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zetkjcgq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2grnxldcq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pmysnjgs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xocatvvm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nbahfaet.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckndytyn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdpfkjk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnusamps.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nbntbzmt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiozlvi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzedcecd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bujkyevs.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgmwhrv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwczselu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbegzzwp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmntvzly.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2opvsyovh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuybywp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkahtfbq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2doapiyhy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2abpenhfn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvwmqrg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptlage.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2awhikisf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iblufahf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoslqqp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcymjib.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2brutxcsk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziecdltf.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbrtcdd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zsknbfsk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsncwqyh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazrfdc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbpppkt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vslqquzi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnpiasd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvifnlb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aawfleql.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqswvddv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2xozdoyok.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhqgbms.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqvadxk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthmegaj.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfauizyf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drojqvyq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwrvcga.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxsvlfj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyajmot.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2puclodlc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeykpbn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwemjcxh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mllgmgga.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsjdimr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzgrbbl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbloluxd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2arrpqnzp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhmxqjx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2loobfmwi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eucdvqdy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2irvrlnev.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmtutlj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmaqoey.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tiocnigx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2twzlueiz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfsbuom.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2afgfqseb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhbcemk.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbwvujw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgmqvwa.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhfjsee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mftafuyf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qefnwzya.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuugrvht.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbbervm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhbxpe.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnplsqzl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlqewuw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjoyumm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsgnfof.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkawzayc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaqjpgf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2whufziuy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjqvls.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxypbrx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmzvpd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgtllkf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ccptdgbv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ventuubz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxmwmxv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eggqjtix.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbjtika.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2piejanyh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfizurxd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2movhjchn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2earxndkx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmbcjox.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqjkbwj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvcbolg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qlczpkld.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdrvpry.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifscailn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhlfeer.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2apapqawd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnykhfv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abzchydz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uddzqucy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzovyhl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnekzml.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzbkymq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvhugt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbpicsy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uidpvlni.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnyfkux.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjdgmy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qihkjarp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljisomyu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2youslzhy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkwkuwn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqksaqfg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpyowvw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jfahyckm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2shlogdvf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edbpicrk.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsdkjbb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcbjmpy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qntrgfhq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmoszek.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyefjkh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbpqqxo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zphfojcq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqfche.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2waoqmgrg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdcopkp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iontydzg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzzlabr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pcijbqey.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpumtnpa.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzecger.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxaiotu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcarucd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtanydh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxndturr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2khooaenv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2akoycpjl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fnndfnpj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcehapfh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxprper.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2duqhcczt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqvmvwb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyjrgir.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2temqrjok.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyfvsso.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyryaw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrgwdws.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2prpdmtzh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydoutsg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcqqxer.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyknsmq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjpnzgh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzfeytv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfauvqi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqumixw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amzzlgbb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oufktcsq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmbeamd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wukfvpch.html


<!-- 参考信息 -->