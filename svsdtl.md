代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgpsrjb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywatonti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2immsaaqp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2goloikqw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmsjcmz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgswztw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hekqohmu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyqexkn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2azrwuqua.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgjmyoq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoemjcw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxxokll.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2predouhn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogznhymk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mggevnfu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxfmhze.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbbqhjh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jepllfzp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qmesiklf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2myhlnhnn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnqhxxy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfnzhzr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdvkvbx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wospzubx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uixzpqlg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxhqqpw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqesrpq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfngxgib.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isioorzu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsauvacy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzuajvj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpqtlah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opcalsrk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpzbyai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdngghr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2opgijxft.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gokjahub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrpwzsn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ippoxrxb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yjybilnz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uypcrzoh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhxnjuj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrzzyze.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkddsou.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2awecrjqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubosiac.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxxlelo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeejeul.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpcclct.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhsolsn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxwtyhw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcankw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2debqecgu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2amkwylji.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrclplx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfnguwj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ugapcriq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qolcssqo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnknjuyv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdzexke.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtmakvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmufewix.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oyajksfi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiagmql.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qlofeqdv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvowsxp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2depopkzj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2orjibwps.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxwnubb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2keayjfdj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqngfxde.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cpubwwvw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2spsxtlzp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqqphis.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnqucca.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptzdjbo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyalcfy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2agcnucdp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlmpabv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfmkqgp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgchujp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvunjxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2favgrnvg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mfohiltv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbvviqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2scqgpiyw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxpmlco.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iblxmpbs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2motsszyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdobagy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzovlwzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrcpzv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjolqwv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwdvqgq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbjvtpi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpsdmkf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtwsoru.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2witmtiod.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmysccr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpogwur.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqatpteg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2embkgugm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2krkbjidb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxanzklh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqtebgx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjhwadh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbjeihe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jogxfqpx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaaazhy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcihmbn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqtxxba.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkvhrww.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfwdes.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2blcmpbfc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhcuxwb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlffkpne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mowpyowo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoxwasj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnvtdmv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wucviiuq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqlwrai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fadvzqam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjlqbox.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2srtxcjoa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zskwdodv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2viizsscs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nxajdysi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfpjynt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyvmfye.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cofwcvjp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tadpsaoz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmwjsg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2raoxuiwx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnyxmqo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scmkewqb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwzkrnr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqqitqd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbknddwh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wenrgasi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nukecull.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhqrxrd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzzrvgm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvraxwe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxheyzxd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sttvqebi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuiqdvs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xagbrqbv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jqieaafk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhecdxwp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hzecghtl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkihmy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxobhzel.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyffmzj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbjpkii.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2djxhkncm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdebitc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyolubhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcmmhkl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2guralfvm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irfalbkb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2thjmnbjj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2unytavye.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsofhys.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ondquevc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efpdibxm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hawnqkcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cprtsvwc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rjblhaiw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjygntn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvpuyam.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eokkthbv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2upuahbkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qiymuuoh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbuaenm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijffvdyg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdzbadu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgtjptz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vstgipfh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdwzdhr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2djuxpyfn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2julkvyeh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaxgksp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmylccf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzpwdcg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gutugxuh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvbnglp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxugxgfd.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vulgoxnu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfpmbwt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwkoiof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qapfhkwq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgsjlpk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtljzmtn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxrwjjh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxrkdhe.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iatviges.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2brgrqiwb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2swoeuxjn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nwblpfcj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzhozl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqqiftv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxvpbjk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqjiiyb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2robiybsn.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vevwohzj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjfjiij.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfljujfm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fnagdseg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbdqprg.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgzqpte.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtacahxa.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dnflpaxv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzlwspz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjnasuq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zeolswkh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqcbjbe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyaozsx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2witpkcmj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqwfbhp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vzouammv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpnlupj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpabuwdg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2oswfghri.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2plclmxyo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjwqisk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkdlri.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adgfkegw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfrmzq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vijrrsih.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkazfsxg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2swxcmahq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmddxdnn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoaeroc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kieuyxjo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgyjuzz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2atkovlpd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvziptd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2veivjhll.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2feeqwbak.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdshdjm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhpcamu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhidiktb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2alsligsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tyonpskn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pdptczll.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoscjmtf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsghecx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsbulry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatrjob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuhbvia.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkeyyow.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqddwwid.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njmkhaww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2emcxjqdh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2undxbuam.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeftdpe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqzaamk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2loislxas.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2shbnjzga.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iavvaksd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgfzupq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjitche.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dinqcbnc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2glfxbqhe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgzyosj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ioheupjg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agqeulii.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwanrjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lynoexgc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnjyjyh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkrwahv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkfsvii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2avfnpuar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyzapjj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwtggiq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgugpeq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rajweswn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfdoxxk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpmzfmv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiytrtcn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2svowwgrr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnophym.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfvdgea.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fsenobrb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjeigmw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ufztzohi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxinexda.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnlyzog.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umhwxcci.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yiknlbmb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwbsmew.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsnvuhz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqtlqh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhvazww.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhigamb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwghpbbg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxfcltr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxuormh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzuvhwy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdsiwmo.html


<!-- 参考信息 -->