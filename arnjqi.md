代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrowbedd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ataffhem.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kowmabrf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtusulk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2thchblmu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfamcwp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npteasyb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsmsuzv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuurrnj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqquszxm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2flquzxmw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsuekdt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiowtsy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsdmucc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdshjqm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjrvltb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkczign.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zertuejb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nagjkxcp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpsagcj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfbniso.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2evxnbtfj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2abfihzcs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2koznqpuc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2isxnxdby.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrhpwhs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaujprc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqchajt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2aooxcdne.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfxryec.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gemrkfqr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2msgoormc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jygvdvvm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rripvghy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qibkfpzb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmnqgiy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbdgkya.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxpqbmw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2caluscmw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lejctogs.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpawesze.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkrlqhj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvinhbr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzzaasg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzielhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xnydqhqe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjujgul.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxexmuts.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvubcmsl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iykkajrc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hryyjezl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2steocpqj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qehzkrid.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2whubityb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjpojzd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzyjxgj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmltldk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkxwekw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjdsdys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mugnjeym.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrwfnkj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwowotd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoxzwcu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtktuuf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dibrgwzq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcttvmk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaunbox.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jelmjkvt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhhxuer.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2omdczxeg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gouemgyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrslvyk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2llnigzlw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnibnji.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lforictq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kruauubc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uelyrutk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezrydp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfeefhv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrzpwxk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uldsmamj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpzmpoe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gcubrbcs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eeescqfa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2otpzupqk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2twdyqjka.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryfzwyh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yisitbet.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hujamuac.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjbxsao.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzzvqbe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzdkpcw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bivitjqu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpgzfbk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwthfwef.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgdwhl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2psxcuzxo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jahcofwl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrpppuh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uaryjpsc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2crppusrx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2otsxmruy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyldtai.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxzahbz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaatemx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjzutue.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfleefm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzsckge.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jswznrpz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfclncv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cecxjhjq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcinwao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqbvety.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ccufgvhp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sipgdokr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaowhdp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2usmhpypz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqrxbpa.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2scbmyuvd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2acgolqlv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrbkrkd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxtaush.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyqtpi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obznxace.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mipxcyon.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwixvhmb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxspwdir.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jscoffbs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2syjckjdy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyinqis.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uaapthxs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwbpndm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2taittduz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gadfsojk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnsftgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoxhoup.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2arqmatcv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gycucuyf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpssqkt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzacrzki.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2skraqjgq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bchvfrto.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcmhrsx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrffhyl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbencjom.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uoobcpis.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rswvmkxx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzywafxo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzpnodz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnatnolw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2futhogtd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xyybllsa.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcshrws.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zihhsibt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2esifixno.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqljuxpd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhmpdar.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpcpgfl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2icsdktua.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzzgvhy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xidjykle.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oawlhsqz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iphepypu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsnrfnm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylauruax.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzbxhku.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2owgfzygw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwcbbka.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmvfhwa.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2arvbqiwf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcbcsmg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyvkugh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdtttcv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2behrxgfj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvhaxlj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xqntuucj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiypruwy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zajstfjg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiscistu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzmvzsk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzrtjwo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dultnqsz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dwomqyhs.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwggifh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjgbuhe.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrosmqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwelxvjq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrntzlb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajgpojg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeitkpb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gophcvbh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgwhxzr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqfnoig.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgukkmq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2seurjefi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfjzhyc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfpbptv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlywhsg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsigzuu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nofundyf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dejdxlaa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfnofkd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2exnvdpda.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2llzqpvkt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjdrxtr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbbetpr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rofembbm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2twjbyfph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqrfhic.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mahbscme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amcfonit.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbyhwby.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcvksnz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppshhwtg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktumyrij.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hkegfeyl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxdctej.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfawjzu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qojcbfef.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ydllkqzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ywluhxbe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqqqaow.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vprrpqkp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlkracv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmpebdx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvezhux.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwlhdbb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twinjyok.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeumgek.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvdxquj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybflwz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbffzfjy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnfllli.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2azfzapva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjmydom.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiwgqlu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2llyuiuga.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdqydtc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2snlmtbtt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnuolpe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlgvxnh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgceakq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxwkqde.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2odmntpyt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbwgcif.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxekhum.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxjzcrr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aexrveed.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dasccmfr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cofjselt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2emcbubpl.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sarkfwim.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvzgbgs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrsbtli.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtqypfy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwgxpkq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2msdnuruo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkaarby.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bznlwywp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdthgckv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tokenanb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwrcjhe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhawecdt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjsrolb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcawnbib.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtxzwnp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uihhrtgk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsfimmx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yczumsgm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2efpjrqub.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2raqewdmu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjabhjdw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgfclbb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2asujdxjb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlwtvec.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjqeho.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybwkoyu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnexlzq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snvqyfib.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2coclhcgi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgldxvav.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2udlwoydy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrjhpwk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wauhyfnu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnaxmao.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmsjuqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tniqshmc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uhabdews.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpwpbyt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooljkdgq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjwxstm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ippxtqvs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzlbsob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2klasaofd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bneoqadx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqrlyck.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urxxifcq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsarmqaw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sprygifg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsxjljm.html


<!-- 参考信息 -->