代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qashrbqm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgygusl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyqbinf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2emldkfnh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlttbxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blgaabjq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oooqsmlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmowzwz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprrlzca.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdrfkmy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfujlrex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsirpvjc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkycdfsd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfoctve.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgvjkut.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfzgujd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkxpsjb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xobfzqol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojltapxs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgyxusp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtewybbx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xibjiock.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgylhnh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2btrqbyhs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgcheor.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2msycpqqc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2njmniqoh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2drmtcbxs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdjnbvm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosxqyv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqtvkri.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2buqzeeur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrdwoyh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeilwhn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sypozgvn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsxoeqk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqzojop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfdioct.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2racchdja.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaxvulw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixczfiey.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bongdkie.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsqnmkn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2smjtknne.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyahxdul.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnriurw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baefbaoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajdrpxl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzolznkr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyeyjpr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmawwfo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2feecdykb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgynjsw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2slkbxmis.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cafkkzdp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imknphxf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oydzfprq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2colbwjrf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkiezkb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjdjnw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaaqlsf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntoegg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyewosb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ethxflfb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvjckol.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxrjbet.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwuhffd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbsnzbu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2amfvjzje.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zrozckfc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lftxukjj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sndlpzal.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meeopalq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhpajfy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crisntxy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vuocvjae.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2smubxtlr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoqlbic.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyclvsn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esnuxelu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iadtydao.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqufomy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqflfdbj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsjfzup.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iunpuoqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhqgphl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhxsmxa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqajludl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkocozja.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lljlloax.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2obekecej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvupshj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hznpmekq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkueafw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabakvff.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqwmrxa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmquhmfw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkppjlll.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gntwoxga.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2napalcgu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvhcwsu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2djgkahjx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qksogtmy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzsmped.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rslqwokb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tknihssu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqrhaqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrgjcrr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zgszsiyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2brbffyjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cykhrrzk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2suidozws.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cftxilsq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvudxaan.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mivkmfan.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzlityt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqfaajz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hulhavcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neoodbsc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmsshbt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztctjcon.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdudhmik.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbtczb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpxdomy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpbbjbq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2puymufxf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrpgcw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxmjcez.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xdazikjn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvevsjpw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nvidgbxn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2thrxmpua.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhvqjuh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouicynha.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbopgax.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkaesbx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvefwmz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuszztj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdinmfpy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkbiqk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2boieryqc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaovklf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjwihir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2doawdrrg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yspezcmm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asgvtxoh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2khgivsug.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kddczzud.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmbzxfk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcvywcu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgzcslj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpekqrq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zapohmyz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxozxru.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuljelcd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqocubf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkepplm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vyikrmpg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtqmogs.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwonpfu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyakyqs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhkpokr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqhywtj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnzzpxe.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgmurvd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvjmuvl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jngfqpqu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sduzgpme.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gsngijct.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vutdnnjk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbghwg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mzscfhjo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2icxakvxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxxcofx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqzfhyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehoqjn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dszdfamu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsqlmg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2plnusyak.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2spwsrstv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2keardfng.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2atzzsrlc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fewluijr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjyphec.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvsshqu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wepuznlg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwomldnc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibhjkxh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xlslfbmb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzfzqbt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2orqpokuz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmtnpr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2buheeihk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xycrqjdu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfgdxdh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjhmrpx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpsrlbk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvxffix.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnkhepo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2erldnqaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqxysnb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pigqeydh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnxekxf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zakaqqxy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2njedaqmi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdequixn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpaqaaj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2myxnopaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnodiijx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nspamraz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxihznb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmvioxq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrsplbx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjfodlh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kclmyrlq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctxvcc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzhynwk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqhzddi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptskqzyd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fsibowci.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmqowmn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2njdhlyks.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrkckuy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuqbhog.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tybgedpo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayonwbdp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgypjgi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzjzzkh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2leeisjxb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwgkahu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2stfcsnlw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ulprwxmz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2diocglsi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2blscfndu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ticvnpdd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypzvdmp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsnvsfv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afwecnyd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrctrnf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwkvnuf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhoqglq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcmshki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvzwgiz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrhfams.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjihinah.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqthsjn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouncpkgx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhzxcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phuotosl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2guxdoduo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhqjtfe.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqiuxpu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeneszb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdnntyn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mwelrbaq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ddabchnf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpwjqyi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuyblda.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zatamixo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdgdcha.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzfuwbt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkihpdt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfwdlzf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcplnols.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2grlrkuho.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpgvcwf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdhaasb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kivhanpj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2akmplebh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2junjqnhg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvskjju.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2swoeglsg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmrwkfj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrxvpmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdyhqcy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbygczd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2seahnark.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaqjanv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vswxwvzr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgqszyg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sapmwrgw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkkllsf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpahaon.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvchujq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvfwocm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrzbcka.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2artjculp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhsgphf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhdagxp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2svqhsitx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhlfrrw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoldoru.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnigpy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vixhqdgp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaxojga.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwifgiw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szbikwos.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2waetcmrh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tflkpvec.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxvmjyc.html


<!-- 参考信息 -->