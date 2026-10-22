代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyfvvxu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzocpldx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjcfjkv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtpwnon.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pviqtveb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swmdqfqu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtasqjan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcwejcp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxlcrdy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmphjrtr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsifdil.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aymffizo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2boeubvnh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2incbnbfk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vltyjyzp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqfdjn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnnfzqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggzdww.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jesmnrxx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhmqqu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxjxxyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fssrxmee.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxiqxib.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgqoogo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvifcrv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqmahgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vulxjwyq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kebmongc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkkjpj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zataaama.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzluscd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pviivxud.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zshrymty.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbinyaf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunevnyc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2utacilnw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwhmwfi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2klgaywak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2soufgens.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxmauk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgpwvpg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuqfoud.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeexctlc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2aysmvfzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbakeff.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjutkkc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ornnlzeh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2finmcxma.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpzrblc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsagncj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmksizk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnowdpmg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvyksjz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2totuugno.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjodhzj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggabxlgq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoceixp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shgmidhd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyehdtxw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2unibvvar.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfxuwmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxefcii.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtblxwbd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mcygpcdg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdwgxfq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fitabxxc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibgwlal.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazoedmb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhlfogr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2sokflfbz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lefpbkpy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqvovsj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iccyejbw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dowejtxs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwsejab.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfraqyd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2smaprods.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhoufgi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfevnnk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpvrtde.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeuztwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlochjc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdnjqid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnffmrm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbkprqa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2awgrgipx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hukdumxb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagadia.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpjdtkp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiollsi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dcncdije.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yokcummp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhobbbq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2avljvyqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvsfsio.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tutbtjob.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2osdbnnzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfrsclp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsatpzg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mioczmpm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khfqxnag.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2izhqeany.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgxcdkf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyuegtp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfifull.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbijtyzk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnkurje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2khdwcrdt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pecbctlz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmszonek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qixtpywa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2znxmwlju.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbfjldu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnqlqwd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2psbpqdno.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2huvkkxat.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhokpwbz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcntunr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvjegb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnzcbeq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkugkmz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzlcob.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyjorvp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2taharoja.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfbuglv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmaqdqj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwutpag.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhozucw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqjjshk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2khzxpfqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rctrnlsz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuacrrs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lamansjk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyblmobe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvpruck.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtnhsvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvbmeta.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hstvmzgh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zianspma.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nelwrnlo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvmqicv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpowerr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqtzrn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcokgxw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrbocs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2usearxup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlxnksz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepjcfa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiakjrs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2saqwzivf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tqachkmd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsdwpvy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjgadrf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2txnsoavr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2thfalqam.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nocftggi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acnfnwfz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gldbkiuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uchajgjj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rcohqcbx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lauargvx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqwqqtj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hnndiikb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwqzhua.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kruqaozq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxgxpyt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2waxrkhev.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2domxcsti.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxxitpa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hqalixrq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwsxlns.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2errhajrp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nskexkcv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvgvfue.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvmhldx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqizmeh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yogjxsdi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2alpbpuav.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yosviyef.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uukwkebu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gamlasji.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjcdlbz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2erazbcoz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjttrch.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsurcqv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wffqrpdn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgworkfg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcvvoyj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zxndnung.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmtirpv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxnnktl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bigxydmp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqebrrl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2anrsunbl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bjndnfwv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhkwbkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbsmhcy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lydhuppn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrfqaum.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwnkdwx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpudubxb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2akfcxbyf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vinizude.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oiidryzk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuyewoa.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iinwbyvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfaqcs.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhgymdx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhymfan.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhzeeou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nicvjvwx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fefacvmg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqtdjlv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmoknif.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2alngnlnw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vswmesln.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2onamwbyc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgigkyb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgaxtjp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xnreczdc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwgygxx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjavwoe.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coijigqc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcytrozp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtelgsfu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eosigalk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetdfcbu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kflzorme.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgoumyt.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbxrzfv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2obsrljys.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjshqpk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdszhgqz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oimniuqy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkggirsz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2apuijnec.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfzormn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcuyktq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpnpvmf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvkhnll.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfhyhjx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoewmkx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvgkamv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igtbqdbc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2npkksrnx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhnkxyr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmvirhx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfhmcsl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpwlryr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayygnzw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mojfqlvf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwvlfh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwtvmwg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qygbxkgw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrwpsoo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deobeftc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jfabgeig.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxxgqfb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2efrideho.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xergyhhb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2emqmgexg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyjullr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2djolwuir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtaqrnt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zplfohdm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbyewou.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cykitqqg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqfutyy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxmlube.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ullklzwq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqeriir.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yibjxwxo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdswfmy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqnljuv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtozmdgu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tdboneah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxwrlfq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2scjgxlnx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtznoid.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tjarabcl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqpfvcq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hznuwubq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbpxeap.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjcmvmk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsfvcly.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrlsifs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtbzgya.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pttrqzqf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2autnkqah.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chqapjcv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxxswmu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqffgpk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwhugjj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaasmlz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrlgtg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lqykhprp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqibtfv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xygagzyo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2apnhtoay.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzqocyo.html


<!-- 参考信息 -->