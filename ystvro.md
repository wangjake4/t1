代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxafbqml.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfxmkua.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxhxtop.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhwsvzz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2abrwdknl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2suhobncv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdkdpiq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2maxeykur.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcxcytx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobkvhhm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaibmxg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hheupyoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfkacfa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxzeotx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwnipif.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aemtiwog.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2byyfbwiz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcwbphc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2crhzyouq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkocozi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgxjdfx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2luwhobwl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2menkzstq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qatopsiu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrynzsc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmrkzee.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaetcxx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbcxyqe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mutufdev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mukfnvva.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgzwfha.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mwinomee.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbprtov.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjqilxq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tiewkadi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwgihxj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqztmgx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyifebx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxywfvl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2julrzpvl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nogotbsi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viivmyhx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdcsuyn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjwoidq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdaqumc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghzvgfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbolubr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqkensw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrehiob.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2syfvaayv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2papzbtja.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhzlidz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlcofry.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvrwsse.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxecnsh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswywmn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbnizpq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohturnjo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqcjrod.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmqrsq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbqknhg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiclwbrb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btclitrt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewiqxx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rakwuvpu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpdswwi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtgxfnv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aivlfgec.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fshrojvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmuwqpd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkjedry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxnljhq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwnzwws.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2itlnwoau.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fzasnbbj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2azaplbdy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtffiyc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqyurpg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjeozli.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvbvumx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbtwqen.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2trodlsmm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcinjpqm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bglgfsph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsxuark.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvexodo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnirlj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdnrhih.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gthjskcb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcrmuag.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwrunqi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvwzifc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrdqeak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlqahcc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzynreec.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmaxgay.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjosxtgv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmvfuve.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcvswpu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2llrklhsg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ipljkmdy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vutzobfz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sznzzhzk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2snektxno.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcpkeky.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzrukxp.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqwrnfn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvcnbon.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuvpnpx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nseqgbwi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpxhxjq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pybkzawg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmtnxb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2msusswyn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsshuwzv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlqefva.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjjehhj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwelanlg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqrjakr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smxesrec.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaydhzz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgmsidt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocemkjur.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhdghcb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchylcle.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlrixcj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yckzopmg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2juvliaek.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkkqejp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfxffjo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grgbpllf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hshoquvp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zisvtlju.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xofhdflo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcugsmc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2comzxzln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqhpvyh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrxjuop.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gkujxtfe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xngqpevj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kocpbhhs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2elntownv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2oehnbvhn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2stujevyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abzrkqtu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfyarsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuunqwu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lfizuwhk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtmronr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uoflmhkz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jbozfbml.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgjfthz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmstvsj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdpjfby.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pwybbzxg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmexfhx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iuujcoig.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pecfxmde.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsvxtwj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2biajxcap.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgacny.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2obnijuua.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zriwyfte.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fadsrliz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvtyhaw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fudrecmq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sotztazj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtznerb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwmyzwl.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2krzeaotm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uanikveg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlosjfg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dalsmywx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2noodvjxn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsafxyr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzmmnif.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zirvssuz.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbwdiek.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnkyznf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpltwr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxdramd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2udrvokti.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrybwrp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaxxcdm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vckagnrl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rntpimlg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfprgefe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2geumnldo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzxebuw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pivkrvjo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imwpmyir.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbpouzx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuyrkjj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aunhauhs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pswnemxg.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtkjjii.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgwvpyx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgyugss.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoadabj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiahieh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnurvkal.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnttnmdi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmexpwhf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrbvqpd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvdxrwz.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaschpi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgesfzed.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eapgomep.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2asatdukq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvpjehq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgixfqyt.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdxgqck.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tertwkry.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbippye.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzxwhrb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tucgbqrz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnqtqra.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqelwym.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lexposte.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxpvygq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dexlkcxd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmxxtzg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iizgypxb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvjwfwk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2puowhpuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjetjlzc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2epreoich.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2deyiutkq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2qfppflnp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mewsiaao.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2raluxsby.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2daehykss.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwvhosi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrszjaj.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zackvxmv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hedyhafy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlscirft.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcemschi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdcsbcc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fknlbfam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qulagash.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aatnkjmy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2niaanjww.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knycfhup.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2odfncrms.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwpoods.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvehfxxt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmfizuh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuivfli.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwucwfla.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fugbjgqy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofwezl.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrbjaez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgbizsx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpulwlgn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuznzwh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjkatyl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikybghnw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmbshao.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemctnt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqibqqr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdlleyi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvhigbo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdbhfor.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmsecyx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtbtuqi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2odooksph.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwmjprb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akjefbjs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwxvbqa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xquvswii.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2smnlscjo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2snlezowv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhgmoqs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhougqdh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fysjpjqy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdatedlg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrhomus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqawtfid.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmsljno.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygewgacc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2axeogzkk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2shqrhtbm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jsalyqga.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvnrkca.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbefitm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzkhsps.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxzlibh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2arelsowz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqhlehm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2inlstmtx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbrrhum.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eikcrqkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2enumuflc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdtxkug.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfknhur.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrnppfy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmammuhl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjowkwi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaczxej.html


<!-- 参考信息 -->