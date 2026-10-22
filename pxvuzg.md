代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcfyugs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwosyecf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzyxfnp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2liygkjoc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vemchavf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxazwfx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rajwdsie.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kwazulmc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gafagyna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvckhkqv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pwslnopg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wossxapo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2prakwxxw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxvqffd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebmtify.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcufrizk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdprrzaf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdusrmi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoawbxx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvahgeg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrqlhch.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2datgbfhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfetqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzwsqbu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycthdkwi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isuoiunh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgboykbh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqprfnkn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ythnzmpe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2miwhftmf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnverek.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtksgv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtgavpq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgnftne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrvwuil.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnuiwit.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbzthod.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2avlaqazp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2myheoyih.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uffbywkd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdkmlkf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svynildl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtyuzlj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnuzzoh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znwdiqbr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyhblcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2daqibejs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2reesxmqy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fenrytfa.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmnccnd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twhavfft.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkxvzgr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iemwtvaq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zetygvtg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbofqko.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrzjkdc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vemkppgd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xilqliva.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqpwbnc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwedhawi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzkshyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyysoce.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdlvflt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dirkrpib.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2juiedrqf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eiahragz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2scyaouhr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ttetpuey.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjoiomr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zibfsffb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqxpbdp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjzsxjg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvaeizu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2srcoanet.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfgcbqr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nivppykb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpquemng.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2albvkcyk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtunyaz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjevzge.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rdygczei.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkpxgml.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkxwtqx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmghwfe.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uydnofuh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyahxtju.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idsyfrzh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbyccbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hbimtnma.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfqcfvc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ablpijsz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2araabswa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmagcf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrcmokr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxvcnys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhogycv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljpsglj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlluuckw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baxagzev.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejanhgho.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsxugkw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iupicavh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfuwrvb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nppljesa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2twidzezk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuorbyb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfljkec.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crfkeqqh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dpywuqcv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhhwlca.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhowlctv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjzounr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyggomn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjdzbm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2snwdqlwo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2axwroayf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elirdtjd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdpnoyl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczloowq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwuhwbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtmaryw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jdctuehy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vipgifbu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2frjqnuhw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sulgeqir.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uexknpeu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlafrcj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2objcwllt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlbonpt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfvqpat.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kobymrcq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwwhxvv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkqrsel.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipistyoc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhytawr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfdzmep.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkvzwwg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbfunxv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2omrdkwdq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrfjyjh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2npzkfuym.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqksjzc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uobkpsvx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnoliwm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2emghdzci.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfjfzti.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupfgxdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hssujdzd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yesofjxa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlfogk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nbirwakw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjdexde.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfuiexp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfzbmjw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usjsjbbc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjhnamv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxlwunj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwmtwri.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgmrbfa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaugowt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfdiepz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttsaqd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrczuasm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmoidwy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eerwbkat.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrrhpdm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqxongo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lusujbbv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xigakdwi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pguhjxba.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfjdhff.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iadupoaa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2njkhspvi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsvgvlv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjibrcv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ntthgpqw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmtllm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xurxubsw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhhnzab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgjcsww.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aneadeow.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpmicxr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnlxxvk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iycswdwa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sovowfph.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppastaix.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lifvaxln.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfyrmcd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrdukwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2axzydqqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkidbbwr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsidgvuy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbetdfl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnveienm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xamulkuy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hghdgxzk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmrnamv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2poomavfb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2montitbq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsewkavk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qncblczi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfediarr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfipzugl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcwwwpr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zegbvvhn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2roussfbm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uvslhrio.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnidnokk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbcxkky.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2towyqmaj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2utvxlksj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zglfplnp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqyxpem.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhzexlf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mswyxhzq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwwxcej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvhtqja.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2isgobhlr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuxpptg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvviyuo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjfzmh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpetrel.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwidkbub.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkxpzld.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbcqiwx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2arggzkuj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxuyjkj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keuxncdh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiqwxdq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhemupf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfvghg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crhqqzpg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2obnbhsyu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcpfdze.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxecgvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qygikwjw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpqkoap.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsklerzw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvlgbym.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfajljp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ifizhtly.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dzavyqku.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fasaembr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uwikvlxr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhnehyr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2byomvqed.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyohmaf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2befhsefw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbqpcm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dsefflqz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvylofby.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fvurotio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzqlzat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvyhoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zihaxxgo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lezrpnki.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lihhukfs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2upariqsq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnfonor.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2euepbgjy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2evlovami.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxktwocr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhmhvjq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iiedjwjt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnzojtb.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksaxkh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxxiarl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcpfkjd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlguvpno.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2mftpdtzk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwjawjn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdybujcr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iolwfuxc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jowbhtwd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2swjhvtlz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2grfknwqd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztwewy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhpwkfe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruggssnr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbtxyof.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ditwgvng.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjptmha.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nomphsac.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zolxtnrj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2irmgcxtv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iaturhyb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtydlgk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qogbqtox.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqfeijs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zxigesgm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2teogxreg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwmkrty.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqgqnag.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtgceqy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnwyjfj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rglksysp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtbhlsi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrwazgm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klcocrwh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpplzmo.html


<!-- 参考信息 -->