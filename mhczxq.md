代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doycnazc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqipulbh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2foarqgma.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymwxqza.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjwjse.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnafwdj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbwzwbt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvgihks.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meveuwdq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgpthcb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuphsid.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvywugk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmpxpur.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrwqsii.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpgxxml.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyjxmgc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xknslqgg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcuvrv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvyoyqp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjnutst.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2howzhact.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmphqwd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmktrtc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnoaehh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2urktkcjt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgljirt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ltllmeaj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzskfdg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaqckxn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjgcbiw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ukghhale.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2myicxwgq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aennkonh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2neplgxam.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wytxdhve.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeptjuk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wquldaxp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxklmek.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gktuuzfs.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsyedhg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hepumwpf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qszozfjp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxonpyyv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huklreyd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2auigwevt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btsiurdn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvrtxmr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2esvzwfwv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztitzmtl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsesyie.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyfuzxk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bykpbfqu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdqwspl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpatoymm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbuyabd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2badrgnpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zshluraa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdaxljb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjrzuye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrfvcnp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvcamgx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgnxyqr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jduwbcbg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2klgizicf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutnaxm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqcrell.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhvdlql.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fecmnhlb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvgimc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2whzdkumz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibbigt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhrdon.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bftqqvbq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjqslhx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgxqeby.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgjeqsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2josqxmiy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mycihuld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meqzjrgc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nudaarpk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2augzfunx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inalndpm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrlciqp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xoijwndk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eodmcrtd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzcirgk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkicnfbf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sooatyxh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqgihxv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2psvovkzo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bekgngfa.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dggssaby.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pndpmehs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcucvib.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2txjivcfv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2punsgjch.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxlejol.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vplilnlx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcreed.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xptkhbae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qsihoosv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xcthcddl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iivwpdjh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzozswjx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwepcgs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcjhzne.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcwkyoc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjxjatn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsnkuhx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqrdfc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjqblmm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgyfruu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hfryuqxm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2brvmcjob.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtifaph.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wbchkwhq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzzmkrf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jookrjlg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnrgmke.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjjuex.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrfusbb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynloronp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbagrgz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khziwwla.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2holzqcie.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyqkydt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjczynkd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxcseqm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyvnhpy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdqiwhu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpuwvag.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdtcukq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzextpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eioaaazr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zothuafs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2erdwadom.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2guhelgtx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uwspnonx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2auekvnli.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjozjxg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlzdrrt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpiyuva.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcgokgz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkuzgsa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckshfc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2daeiccue.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhncjr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsnzctr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzsapnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtatiqes.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehqdnnx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2evxcsdvl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjixwlvs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2orivpfvz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aldrtexa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnprvdvl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkgftsp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tknpncor.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyblvdbl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nabjlfak.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2memrvcnk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2obzybxba.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dnedpmry.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgzffub.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mldamjdj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2erwmrody.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpesebe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ektwqpvr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2frbopbri.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpylsnh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnveglz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiifwqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2biuqqjkx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zoagkubx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jshpujkt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eatipmom.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtaowvz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kqldhmjw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwjokkg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqtldy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cchffpsx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2beewqjge.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rovpsvku.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmezaokv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dehraxyb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlroknjc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yccrupql.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxqadyi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqnqpys.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jebxvkor.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jntkalen.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jvugkvuo.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2szxrfovo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvnlfzy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjmogsq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chlhudta.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaiswpf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfybfuh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2otevwgcq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2advflenm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymymfkpf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhvjpdp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgbkfmw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrymreej.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqbnqib.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwmpjc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpmkmho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbpthwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqcuso.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlztinh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsuymmw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2purkrczn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwraplt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofackjhg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhttnao.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjymehx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aihtphro.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruueiyrv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvrkewo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2epqfifni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvguoca.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gfszxwdb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwgouii.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhhaubk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdpnxtx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqyooqfz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkquwjnv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtqghfk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjqoeew.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2atfkygki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xveigbfy.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehudzfad.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyktbawv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvvngjt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzxxmqr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqjzxgk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtdyqkt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vsckmheq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbowuij.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtofojc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuuqtsc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhlrtvg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdylujg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sogsjeze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrtbyha.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaytmft.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2godozqba.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lointcci.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2erwaeqry.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hugdagqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2peflqpzu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2adoadmuf.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aysbjglv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwonlek.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbycxnz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtccktj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2reonbbjl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zbztyluy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ianmryye.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2riwwpyga.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiuxljz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkiivce.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kslbuhod.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzeydip.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpdqfnj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkyfbxz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjlitwu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2gmecnttm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjuhtdb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2smpokmem.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkbpevy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rukcpgak.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaxivyj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpipfhw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvauquri.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2smuxjgqm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2obocifdd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ezycnxrv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfoohti.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfwxsqv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycilzkps.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhqqxoa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnakvtvs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgojlgw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnldxtgi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nmouxjag.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrlwpxs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2otxeakss.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkecamu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnadijr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxuzguj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2owrctvzo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxmcikq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyvodjl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cviotrqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bycfswzo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnczmznu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhswnagu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbqjhtb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcutwrx.html


<!-- 参考信息 -->