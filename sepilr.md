代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvvnwhp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrclqvx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2eloomhlf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2modzaxge.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqwppev.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfbkvsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmztsdw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2unxjwezw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjvhpsz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdlaysj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdoelpc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxymuwn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2drpzchic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmtxcp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2voarblxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkqeic.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2myuudwxk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwyueev.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2keklilfe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2edxkjnhc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fensxcfy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrdipcl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kblffphj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgbbxvm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaylwuu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxyiozd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsefafk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnrjzmx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoalcdo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvmxfre.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2utrbvmiq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nigucofu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtxhpim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugeukm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvfwyyp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdgzfmk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdsatgl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhvbqbr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbhmzyv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dwomigfi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oujpxfbc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2azdjsdpb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uygjdqya.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2voqnpmvf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceczjiyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjswzszu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2donpqaoe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2otpbssxh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azorhcdw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbxwxed.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcygkvxn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2idxuneen.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqearpc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkagujbp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfepokv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxwmdgq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2linfdeyy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgmaiyh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhsuasz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoozkqa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iunoqyaq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhslcfat.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjamrnc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaieywi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjrsiey.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jymlnfnt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvkjzqy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcaohyz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jonyijhi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyigxys.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqywiat.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcqkded.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2aioendvj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2boxcepnx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oltfqadz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsozhdy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2muddyolt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaozlsx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzoydeg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpkwnss.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxgucck.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoulast.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hlitwrlu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kddviqtd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrysaiu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iricuzez.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wklgbxco.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaigubm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2augmmmpo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfateji.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgxlwko.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyvtsei.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qftqvzlo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2waolziki.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ornfzoju.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmmnwcg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bifwxzuu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2znyoeigw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyayrek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agpylwmk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekulzwx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dciajhio.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbwduej.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnewpat.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrjcymk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psiomhjr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igjlikni.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnwabba.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjceboa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rllpgknb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxunwig.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fximvped.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjbaaku.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wimrnimi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwqepvt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2anoetjyf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bthbseob.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gujkyepd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxiczqe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2upsygexd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjmenyx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkueteh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkbbshp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiwnssb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buqidmwv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxniyju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmlkhk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2egypkgbr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2apefuilj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzdxdrm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2elfzijcw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrvobkq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljycnzzy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnszbesi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwywvquy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaevstx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hecslxay.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyhvzoy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rguddjre.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeuvbxo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjrrlsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2enggsfcd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwysnaxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrqihsj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpuaxby.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iedqsvpp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tctdbryh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2aylbylpz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpthhel.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2edateteo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxphzawa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2eodmfirp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2endtmyrg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdskwbtj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2palbrler.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmsulki.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoqojri.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvntvwe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsammjzk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbscqdn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxyeaiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnzyypa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmepshe.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhzmlby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnowege.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjkdgle.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgkjidj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkruijv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqavftf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufurvldw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2crbdwxbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlatphyh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbnbuhn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaeittc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoxddwh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gamgdpey.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoyrllp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vylfbsct.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbojdno.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzbopoj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuuuqwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcpmikx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttppuarh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gybitjis.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiydsyf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2esetijnr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxwvmqi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtijfdg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncygnxjr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2efvqjvde.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2atydvxju.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnlnzxm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2omyrrzhj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fndvfxcf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvuftsj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pejdopxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbhmhfc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkceeatv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzssoig.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxtszbr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrasgzh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbmwzmh.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjinywc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2obwsufil.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtlhyjf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvjcds.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2glaacupo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzypcbu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqgeysp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhrujoj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lctylhmr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knbtclie.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdfuzs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tahosqpn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvlpoxt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzhfhjh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcovpluv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcarfgn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jekqwdti.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kklfuuwn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmmqohr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2absimeoz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jkogccjk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvtsfuu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2akjluqrz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkewqur.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tezlvjqw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxhtiwy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kalzfemw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrviizno.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtmjvwj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxccpmk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfxlydt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmmmfna.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svwkusiz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaqxfkc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxijpcpt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnkvmqa.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2drrptfnl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnnfcse.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpwqfjz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfrmwsu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2driiavuv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyihpcop.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsavmew.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2plvtkotn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bdydlhvo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvjiszo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysrziqx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arowcudg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcybjje.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apqdnveo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfjjdts.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzabnds.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxqyfda.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tiubdrgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimgpcf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrzbujw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxneyky.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeqvjxu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gsulgjqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprcdoc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkifth.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpyldol.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vubgekpm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cugweyly.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjegkng.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2acjsgdxj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2roghwlfr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ryypqyys.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uneqztma.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrrtjdm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpsihzc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuhscuy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbprsgu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iggglxfk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxqrmga.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwchptwj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vopoznvg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhboebu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsohdtp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsdcmxu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdajwxrf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnggqe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqowlus.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzdxavh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dztdhdrl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlmsete.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2upcobbgw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgpimgc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gmshvddu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjnfxgv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhchsab.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2blnbecwd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjtorvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcmyocg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyagozy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2klxxqnho.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfvpuqi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fonpdcja.html


<!-- 参考信息 -->