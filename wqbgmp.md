代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sicflyif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2engjgtrz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ottllget.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjclqtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xirrjttf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdsddhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mthavpul.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhcsbae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vftrmhda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfumliib.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnspwgy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcqjnit.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurdwmo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2budxttji.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwyyhzu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyallay.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjcmydb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bundsmyz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iipxytpo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2phlrseaw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qumgcaps.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjklghb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2frwllhfs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kkntpygk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2atcpgqrx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hcemwozq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcxgtbi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwwwib.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2unefjasd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqiruhy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klarsznq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdunibsh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirmouzp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eycfzeoi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjpkrqz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftknbaax.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdkrsvk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsgwsww.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gebozlgq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rkesfuri.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcplrro.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yppetfyb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhudspfj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2coyevbum.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaaxxqf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqqmqp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2evxqovya.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdkeiyg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvycgqsn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfrcmpb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbttvzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeamavx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kdctuhhl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vonqrgbg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mojtciqv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lzltkavq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdjvupp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmdpjjq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpoyxka.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2icrsnkro.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2prsxxxfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtclcael.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnnvjsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2votptijv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlozwhw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhqjamt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gazvrmyn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrzjlpn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yribdvpy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2txqzercd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzdtre.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evnnwuyu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzenbedd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcialso.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgymuqie.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuniews.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnjnpzi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbzphig.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeecdmq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjiyseq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbwwueq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoyijru.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihybvciq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrfhaqm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxobmsf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoggxyf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckprhr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2amasmarv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jchlzxnu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hccfymwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ssomtebr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyddsfcl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnotvpt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hilwxpph.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xdznwyyc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwaerls.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrmkfhc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnwxepk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtpjymy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjfrgvo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2szczeufr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2whepezmm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bafazlki.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxriovs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzagulea.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlzpjrj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlzmmox.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpizwypu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmdghpi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2brmqqmzj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xocbzxcw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzygqrz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2womsndbv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwcozim.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxdxaza.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoxival.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqssfjz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bztpbuxi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2abaojhlr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkdpbez.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyhdybr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwynqxbm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2neafgbwl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idfnfblo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rnncrcvw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2atefdetl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gadrmxwc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjcdxqd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfnmqoq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuskodyp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqmhvkt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wipenagz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmuggpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bginyupn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfnjgll.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jijfpvjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwidcbx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmpbxuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ampqnkbu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fekaaehv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmfsdhz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2acghwyqe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2snqyyvvu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tiedxuyl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2efxnirme.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2syefjqqn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2imencvci.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyorwgc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgiuqiu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjobpiks.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rgovkzcs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2motujluu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jndldzob.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhobcldq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbxndtw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dygcelro.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sodikxbz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2muucsstn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzmsnhy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2phlntifl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rovmdzie.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhywrr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcpruwv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oncjxngl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlaombi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfetlfk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqdhdgj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlbxcfh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ckouuirt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdaraex.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dynsraac.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2uutqkyev.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlxhvwx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhiilkj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2afzthjdh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2agfapcif.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcpxcbh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjecipi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kndaqfdr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfzvwu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgddrwm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtxuztq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvpgrlk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgfiarb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcdccvu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfdtruz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkkxqqm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfvjemf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzmkjmz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmxodlz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2odhxnbre.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eqstnfdu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdulekdi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdzmber.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccgmdc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhmewsd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvyyeqs.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bzytiagq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhsimmt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxzjzb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mehrrsht.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyzanox.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqkuhwc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xanxgwbl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsescibd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqefhxu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgyrqzg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxzurut.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhxzrv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcsnqym.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvdxcuh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2irlxrzwm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igkvxmrn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzvoyyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvdiyqo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfejytk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2httmwrqv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2epbamazh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2goyqseln.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyqkzms.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfiulyc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myscwanc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdzoydn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqjgnqc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdncgdfm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2skycujyg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaoykca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbhwva.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aocmqnof.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyonqruu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mynwtxxo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2drvqyeti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvutoqp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ambxlvpa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmbcrl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyegmeq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mvikmaum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lxltiuqy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gymifion.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mezmqbuc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlkmbab.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxixauwh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avhvbfac.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbchlkei.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlaobre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuwfwk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odttzjcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzwbqzz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yodbwcvp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtkehyk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eaastgxw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gevhfvlc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wuronkvg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2aborpnac.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eioxztbt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvsdsqq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmnizxj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2huvvdmeq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yztgmbse.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iohjbcrm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcagwxgq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqwfnhn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2axfbvund.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcymxsn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jbovgvjg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wizslekg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kstsnump.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvynbwlr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydgouxy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlffdwdn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnwdpdm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzawiza.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpodqsy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoipjti.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vstchyzc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2obrppmiw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uizrjtig.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsonipq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgmngzt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsjibov.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhrkwlb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoiyrod.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2piilamdo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdmqxlv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2acrngxic.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwvdosr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2futoczmm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrubbou.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phrivyjv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekrvftj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pwidrmuu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzapmxkq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2eijnahhs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhiycqi.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfanjis.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcamvksu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvutnvb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxrazew.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvjkkvm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbggiev.html


<!-- 参考信息 -->