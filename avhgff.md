代发 wailian999

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtucnoc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvqxwsb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwrjpiq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tgarqgrf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkvhqtj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vljcecmo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mfguiekf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yydbzcqu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamhsmbo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzncqjqy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2latwvnuo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuwfqqz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plctggci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxvfssh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptyrkgd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzrezvj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahifetie.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqitemsv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjlflb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcatei.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsttyzw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2itgbfqir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqgwspw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoytegh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqjlnlg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlrbiuq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqchdbkl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2exyzpusm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbfzdbl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cabaewah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpqeuqk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgxjrnw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rjahmvvn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfagvex.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bohmrrih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2shozyyex.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vjauxjgh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlkbgfs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmqpmgl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ednjxfwr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iihuhaip.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzzrmri.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgouqco.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2evyummke.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhiipwg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2omggrslk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwwglhb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgxsywf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qchlpyne.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zvquddst.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2llbdfjbq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpphrrq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygccnjfa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgeqjqx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoinxrt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzabzd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2okfnaydw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oigpgoda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2axdpnqcc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzthotx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbeayjj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmdhfai.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xawbhcmw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nepnsmfh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbargku.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmhggfz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inbtpmqj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuccaql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2adzdqyeh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlsdhrh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlusxtx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqxaouk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkyqufz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nerravqd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoxeczt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmcrnpk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aeasbhfv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ooblzwaw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2krobgxjz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvftzhg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmqozpx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqokbju.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaszriz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfmkyix.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaybtox.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjwofxt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpobuqoo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlpvaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atetsiyw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoawtnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxiczpj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fyglmhca.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkaeiwg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jokfweby.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycaxmw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wsierapi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvizeij.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfedjipy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzjteyi.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jgegyfyy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlyvcbi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwpelfn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2frcpthvo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkzivtk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyxzvie.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2noonnxvq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2neseyuqz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2myhbtkcp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjfihvm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2htchlvcl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdjenly.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rymougft.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2unqqukzz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2orympnjo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lluctoyw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cautwboy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuxuewd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgejvsgt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwrtgnq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2uylfoxwy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qumzzrvk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpaiunm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdykuys.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhawakf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyzrkgr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vcklkdtz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hielldpq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pcennirh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2neodchcg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zeilttia.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gztghrjz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbatljdy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxbaswn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwjsmc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumdjlex.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irilnblg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiwkdik.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsfzxve.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebyaeg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2drreexup.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nxybbeei.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hngtqmrx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqqzwpc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyefhim.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oxszudwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itajwagi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gofaqaub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xiodizjq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2urkmqvdw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuzcvnw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2njaqpgha.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvmzwyb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfuohuf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjzgcwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2foujdbtu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgmvtwv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2duywtvie.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uprdmfiu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwwpuxr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2purtieql.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2diqfvvuc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbfroju.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkywqac.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiucshvv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfpcrst.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtfmyws.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2psgurwpw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiasurw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjclxoe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tunhvenw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwwqsqq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oweennyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmiivgq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikegftmk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkgciue.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgbzrra.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ioazdntm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iteyaioc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dqawgbye.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgwslfa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnseujm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dboibkyg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeblplu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ruazmonu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vebbmpag.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lzutxlts.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vhydijlt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqqcxjj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqcwnff.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqgnneh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpubciwe.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwagzrm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2trpjickt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmsxjhh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkherep.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuhlqlr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwvkgld.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpoohn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2escwgnok.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwxsfhm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzyvvlt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnecjcn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qyviniau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wmstfnor.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfqhnxg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmxbmlt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqkxlpr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svlooqim.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmzjsao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2odntaawt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkmctdg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xdayasdf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjajzjcn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iumorlmn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2meirwbgv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvskeka.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2agyvdfua.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zhapllwo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyvhpnb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiwjqwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhirck.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbimavm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlozitm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tulvevan.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvenmvx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzmzwol.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xbybhvus.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2sonuejob.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wdetvbky.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2eikgejpq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwcrorh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xduexqvh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkgutpr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmushwv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tddtqume.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ronasxmz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzrhksr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjycwjo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbautxh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nuadxrco.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoasyjy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ispzuqfl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmnewid.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2icainsik.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipysdpwe.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnrtgec.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvoleyj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpolcoh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejgeodo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsuxplk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzegjyrb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2neyyssnt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bapiezgg.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhxryfu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuocrci.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2idxbwuat.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrjrmjn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dvisopgc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtmeojf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kexpngry.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qylgrhev.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2yjujthbb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vifnkrrq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjoulhq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiqxhcv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xncmtvuu.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2goyqddfn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zqziykjp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plpezmzw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2acijgwsi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jycjpnet.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaptfrz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2owbbxusq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqiwnhs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sagvrpam.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqqvkfn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmboubnl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvafbwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvytzxiv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2cekdzxqi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ileitnwu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gselppvk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhomxiy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ingxvquk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtizkwj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2shsfhkum.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqmwenj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqmarwc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbrlqva.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqrjemc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzikilrp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxppxge.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pygmeijo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdgsutx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qruhypwm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jvffohgf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnyxeom.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icfgfngk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctfyrxs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoltsox.html


<!-- 参考信息 -->