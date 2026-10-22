代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2moowoisj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrotfeh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrjomcc.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaenjne.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwjaxen.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqopezoi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivjqrkl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2okgmmxqn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uafgjvmw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2muzmvuds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dordvogq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrnskuj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvtowqs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkvwdec.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjeansl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbcflqx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oybtrfrc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtdecmb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgvkytn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjndaawc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkuphjl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcybzgi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqjzssq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2znvpdsut.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuexwgft.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzupjrpy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqqhodn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2artyvuud.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzynkrxq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qplvmvnq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwztefhr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfdwnkd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pktvalmm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwazqtaj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwedcikp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdulrnky.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpvzxdd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbwnbdp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zdohkste.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ouklojkp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwtoszi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfjzcob.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfiquqm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjidxzl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfkfnig.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kplktabp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhuzybh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rwumircf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yurvsgft.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoavnzx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrzbkgb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jubaceqw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2advyaaob.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qshneqiq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cefxhylj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvwnpbo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsdwlwb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obezacdq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwbclpy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfcsdtu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtymyybi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqcfphc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxijtnde.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaoygvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uunjudah.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqzvjmc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2owfuurel.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqtqspw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhomzpf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oywtnnil.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lllchvem.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqzsosz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpigzdoi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2enyilobm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxssmrx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmxysgl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhtlktu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiepfefc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mryhqngz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2itrunwzp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amcslhsq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubanreat.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wliworow.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvvczxx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzthfny.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkwhesk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpynyyev.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ladwejic.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpobofc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaytjff.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbygqobp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2urgbaknm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnbzzrb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdsdozq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbogwib.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2orvfqhnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvwuwlx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aodpseni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guypecwp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gexhzffu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jclizwzz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkiawrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2drdutymo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsrdzms.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkkqtvh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2untsymoe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iibhvbsc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wlokrooa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqcjaqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2whoehivh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xujzvhqs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ygacuyam.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2denudigg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2enjnzssf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeywkmg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xgczofsw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2knwiiwoo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoawyjd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlwwkfk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtdkgur.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzacnrb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2smpjmnya.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsyqknr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsrwrtr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tluajuoq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aauojjhp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuxtuny.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaazxzm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeowfum.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczfeppf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwzyaua.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwsrfis.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2umfrvyyn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2uisufxzh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxsghls.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tiugvjdh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbbrjoi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2slayghbp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutkqrde.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvfbemi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydurvoyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2acgzvgpd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuloqcu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wukrrefl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qptgyyiw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fosetrnf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odnkkrfu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhbjzhx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2alpbeuag.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zktbggyo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2clciqufc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfrzxmn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2altbrrnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iodkooqb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ititjojy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjuzxny.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdlzlsu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdlzqva.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2addqhocq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaoulye.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzftdkg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2skmnesgg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmgtlhp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhjjvep.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tywtgzhe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhrmbdp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rggbignj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcgpchm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgfwibr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2whxormlw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnxksqo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlgjnbh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2widkmjuo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdgzozw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2duaqiaep.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcxovqy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrpmkdz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmleamv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhtfkmm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoxsqmr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjbhkci.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2afnebbcf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pakkfnvd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbqlydl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ucljpagk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vstrjvqp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eczifhwg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdjtyuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsczmpys.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivolajf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vhifzffo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zktficsv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2keguysih.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2izicjvxj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qeocquel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kmysrapf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqogayr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rizgjrgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdbuxib.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dggfvcan.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeieuco.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2byygtbpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlhgrye.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caubwefm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgkzddr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dknbgwun.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwrlaju.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwqjod.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbfgdvh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eupmpals.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zipeamok.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrmtdhu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vuthlfaf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vkosahtn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhurpne.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgfbbuh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kigipdbq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2susutjhv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlipfuj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nsudukub.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbpojbz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvbnvxq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nyehwedx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhksjgra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbdoabt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2huiiwaob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvclcdv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoqsojn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjehjte.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gscnmqlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdyzoog.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2phucfvbu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ravkcnog.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgkzjax.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nsimchbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gnixqhat.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxpfvnt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeilpsmp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvaiczb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2kexgdhrb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtbbwub.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cudinlfu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuojeub.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphykbux.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhacemhs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnokmdh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2idljizbk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rghhinjm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvnmqro.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pngijwnp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaxcjiv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2uokmxqte.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgulvzv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyrvodr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvcfica.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hccfvmoh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hshaaerx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sugpxnwp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuokwtxn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkmddqy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrxiamu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bnptgozs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzortyz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhrufna.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeyptnc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2emetnvem.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2errtvvyw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gesyizyd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rymhhner.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntorwhly.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfqspxg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnhysto.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijpoqos.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwovbnyj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svsltgtm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxbpaxf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2anuyuecr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsaiwze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nslxcujd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hldhlhub.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqukvg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbhzrzi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcifgldd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tazfkpgh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmehpnvk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfhuegw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwoqbbg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkyrixk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaygnziu.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdabvay.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrabucot.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhgjffl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2idhfcdfx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvnqcpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxjirwf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfdiowi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzedgeu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2chgutttg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlachren.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfrdyzm.html


<!-- 参考信息 -->