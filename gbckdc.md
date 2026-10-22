代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwxlcyj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgevfth.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2snlchewj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrmpkkk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ectucsrm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2afqmhdqd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdscromd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkfmsxy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcncsqf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbkwrlx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sayvacss.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzpzzrs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iuugqusp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqluidzd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvvnbb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lteznuwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcntqukn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwplmkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeuwcke.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2flpkdgvx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fouaeivt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rudjeuwh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2klpkqexi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpcvlfg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxconqv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2quhzlugn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyhcjnr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mskgtila.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjxzhsj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2inxkxwdn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfcshvh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2agvrxvlt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkcbjex.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2csmsjoqg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hiztghly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2owpsyjch.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgxipsb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvedhtl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kunvhnlz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcnsefu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zsategix.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2marevuov.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuimdjjj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfumyrul.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxulwacr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmajhbq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wftpkydm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvunugjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2frrgmyji.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdzzvim.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jteswhmm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2phablkux.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jywzhcrx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbhvlzz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjjoynj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xnucedlj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgcppmt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2twnnnppf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwturae.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aydxmpmu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuukxgc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnbpywh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfekrca.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfivjzi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxihdmm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mujukair.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnotogcx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxemkn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvkwlud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxoqhsv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aaygoqkv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvroedpx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpdzkbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuewbyk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzkmejc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huxqaate.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtzsrbi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxujjjm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqlzrg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoigcbt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uylklxnx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpxjmgy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzzhhcu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqswwef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaafckgx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2zitchnev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ausneudj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbqfons.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pkihddik.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgahnuks.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeixywf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbtykuo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxnamfw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fncyyvrz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddthqiyf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdncjil.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhojwwh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2arbhbtvd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyesueh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyjntxp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpkpwyz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzflxmcz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwjgyrz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovybclch.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2erjlbkjj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsxhgdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qrplrhmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhsgmhp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aclbrtoc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nerkwheh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2umshauru.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvydsolp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmlvtkd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ooopnpoc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqajapu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhrcqud.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kojabnel.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pptjpgfw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxlsdah.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2inyqpicn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnwbqrc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyhipiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wlscagoj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwcrger.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkhztfe.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlmvwxm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxxdurp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmfqbtu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxqtcmi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgvmbhh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrdahdi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pubpilte.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pyniwptz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvbfatw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twdlzkvd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnftote.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxmhijt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaedqgo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2epuefuxr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rstamieb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxtoiyo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzunprze.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiywhtv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvwerph.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyhhsfk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lalzsjxu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntygkyqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbeoriv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlgmfzk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuescmjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reuvuoun.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxstlwlb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gozktltr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrrwnug.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2slznznxa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zodmjdcn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjpspxf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2icnjryjs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2arxaawlz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2oosltafa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cojjivvw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzreqypb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnwfrke.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndorlknv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnrbiwf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eexrfmjd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzuymug.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfvnvby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihryrlg.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uifnnhyw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfsocgc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vlshndlv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kflpdbtx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmtjyhc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmewqig.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cikkjerm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfksvyoz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2acbepbhc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2syazyaba.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwhdnmc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwkpifr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2danwijni.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2suwcbhhm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2aditzsbd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2puxsqqvy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eakjhrcs.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepirks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ebodnrhr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2slfmzeul.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bustypeq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2llcarhpx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dazdgcih.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhbgjv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xchpodxi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaumbna.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dpswpvmm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2obvhdpfk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmnuzne.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvckogow.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxkpnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdyncii.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vhekrewn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcclocva.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzknpyna.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcmosdd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbsujtz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmtlfaq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjlaooh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdionou.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zphhpzje.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dodjevod.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uitrlnlp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2osgldooi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zobtgosx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkljyhk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ratvgthb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtkocoi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2psvthpdj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2koeziztm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxyicsm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmasxyo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2grgjtfgb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mplvulna.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2awlwwvwl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoalgly.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gttnpitn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcbflmb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2egynxgaz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2thibjfbf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2htkldayi.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xmawcaln.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2snzjsxst.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyapndf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunvnpqp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjhtmgr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzbjhso.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2raecreon.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrxmvki.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzafegzc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omeanvbi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2opvhfakt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2augiziob.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqqytg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqedhzc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2thimcmlb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgugyszc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrvacwl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxopmpj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpagvgu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcptxut.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cirafjja.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tclzywep.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2embyxvtx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2miafbcgr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krxtgctk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeecelo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgmtiwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vydtlrir.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2udggropc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvvkiml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxfpinh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vruxasqg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fukbfiki.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2stscnviw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plqvtpdo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeboqfk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qibtqjvo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2isktowyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxwpwil.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hkclcuhw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pizknkyq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fepizkmv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qffzhgzi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxypzuh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppqivpo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xshbieci.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxuiwik.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqwicxu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyritmq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stsopxrk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbakxdg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2expzskxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjkotar.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlyxwab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grgkixcf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vygtsumn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvkvqmu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbfamnk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcqhely.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nszprwwk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyaiiyy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dglihhyv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2botgrazi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2esysvtza.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvheddx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnvqrap.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpselae.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmnetxp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tgicmcwo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzirsdy.html


<!-- 参考信息 -->