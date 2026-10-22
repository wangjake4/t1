代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rywhbghn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpevirq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2euglirht.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrevccyq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oncqssnv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djauqceo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqtmgup.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frdukach.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmwxgni.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgsaump.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjghelyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uphsbxlc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtpkntn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wprzzomm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoetihs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpnfgdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuwbpey.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aigyqutt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ohntlxly.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2umydfbzv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffntsmby.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycngwiax.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwytzzw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbnegza.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rftmfaqr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrthqjh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2viqtvkbg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jptpcnyp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2otzcwmnl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wefkkpqf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hetnqkzv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2anipglju.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwlcukd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aadjxgjr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2brvklvtp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgdmqbm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2raouddce.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uifgwdwv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eehfolzk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2toucitru.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsdyusb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aljihzjn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwzdvlz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cissnhhn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jebepcve.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbwarso.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeyqont.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stloqncb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2frtbabff.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inqgwpma.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sucomesa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yssnaosv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2awgfcqms.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rckdkkbm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kavbepqd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxrmcpv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqxyhy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhekikhn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuylgww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxngzgrg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszbktfe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgygplx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbexmscs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2durdmgvw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpahlmkk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgeuhws.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvbdsdk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxiquqb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgbnstb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacocvc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2teqmjmun.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kayzkzwa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2otiejffh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdvaejh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ioedlecc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmfcavw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbqpvgk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkqcfqc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mutyahmc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqdrfde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvykfwbk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqqeurr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otimotbg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuipava.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nujduogt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdtpnie.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzmibks.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qahlqjxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmfftot.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcemqgbz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qludlhvb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qiurzabb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2myedvwfh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqydurf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2inppyghe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnslrvk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2twvvvqam.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvodmhb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhjfzrz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevmxcv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2smusidju.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwghymc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzqbnls.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsvatwz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdwsiyx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2buzfjbft.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faoarwcq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2haisohgl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eszpwjnu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puecplfq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hecchgoq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbclswvi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2odfwqsdt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enpwtuxr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evlqcisx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rltwtfau.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhletzi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2crfmhytt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnwfsjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwvjzpq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmxltfw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpcwlfk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzitpsh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmigmoe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbogmqh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgbabpz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckxmarl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrafubr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnauwk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xssfwszw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbomxjg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yuavsbal.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2donfsfik.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgwphlj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2soilmqzl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbmqjih.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2apsbqvny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiziamu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foainnou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzawqfuc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2leugeqev.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2djhfgiyx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhfrire.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhlbyfn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdtnlfp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrjkycx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfwsiwx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2epfzuulh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyynfuc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqjgvtf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnbsttb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnujtagk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xeedqplr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gelxmnwn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yssumpki.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsovzid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzbvoxi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtahacod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sykzslvb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2clfseqic.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqdyobq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jalphwlg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2emrlxhau.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfpqvnu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tryxnids.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpdjibl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pbitbddw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhydiai.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2akayrrhd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjilbez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2huyvfsmx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rskvhyeq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwwwxjs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxzghvk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtwlsxp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgkcwmc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nhezleem.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxghyn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjxydgt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zrncexor.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvpqsiw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeloizq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lylybosg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yznavcpa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zgerjxsy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnahigm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbereom.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlampegh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrfdovo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dijjwbcz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chnkdmpt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkulcvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxzpkvm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwkwora.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sssjtckm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hufoclmv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvolytg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfajljt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxelqk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrihgmyg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnupgux.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wnanwrbp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgczhfk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2suhzwwhq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzoptmp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtkurzf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2avxkhgbn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwssvbd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xryvjevs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyuhsip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnudikj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bitemzeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwepyfm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjzvinx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kynpdocn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fshxeblq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aahwbath.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoihukb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfoiwdc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvswdjc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2armejaao.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2djyrydry.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuvccvy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hduedopn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwbzilj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2taaqlcgm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfbzvhj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2thmhmyxv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjujfxve.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2thmsvdmm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mknwesap.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjxsny.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iivdlfto.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nczopvqn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkyvrn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftygzulm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwgeggb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqchgwh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrwgaup.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2guwvguum.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2regcwswv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lplluobu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvtvbno.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2emmcvxwk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdxhkn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeyhgzm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nclkmemo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtgdfhh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhsyej.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrkoqvm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfwgjcy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxuhojo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2anxglgnb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nquqgjqa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2egzntiqk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cbprqaxy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeobdqvo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2slrjrrsn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2glfaaesq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhtaraq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqqgqmo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jufbppsg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2duoikxdv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2klwkrzdg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbxecfe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjtajxv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2imditpzg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pdniijym.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2emtkctod.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxjbgbs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfgowtj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uljiferv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmkztpg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfjzkps.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqyqgcj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbkxqao.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zttwnwmd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohikqzql.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdzovxb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnfagsq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lixxmljs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlezubh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjwhoma.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcfbyse.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uouqjgvo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2uyarwzig.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovznkhfk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kompacuu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyafiybg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqjtnhi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhjkyzn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgwweai.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2azgtwvwt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeykjdsa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dbikhxif.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xiybxhbc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjxibm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnykwli.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uryndtur.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oblxgqxi.html


<!-- 参考信息 -->