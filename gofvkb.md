代发 wailian999

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chmyqlvz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvtcjyr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ncecihga.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtulyfse.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmzkabc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjmaquc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2faxnygia.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmjwvec.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtbdhct.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuqbbnp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdylqz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dtflmkwb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpcaymb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiwubwn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2awxaydbp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxzhccc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgvqdok.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrjlvbv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqjaosw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fykrxopm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cpybncxm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvejnzz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiebjkt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ooelilse.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxxzoyn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaaejaa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjdnqiq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwrhuxj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jufbbwww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krnqmjvb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kinkmafm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpmzyug.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoggwoms.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obczrvfm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqywfegk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhrnvae.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qryrcbis.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgwuvdl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbsftja.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkxqcyi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2srewtmqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdjkege.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmzumng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrgfaes.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdayzbfm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtsupct.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eomererj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2upineeea.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdqgzxy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2syimsevx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2faeryhhj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkargwx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbmjsuu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pelyijew.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbqbrzo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xphlbdsg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfijnbx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dpznuxar.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcgfnir.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2upaxahlc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmbnoqo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkhyhbg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kouyqird.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2orvlctbe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahryltk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhhytbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxnempj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qppwtgto.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgamdmt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkbropp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsnizqn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anrfwzxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvvscac.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxjusko.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwggjyp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihyagpd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xizuhtis.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2osfpnsoq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzadzob.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurzouwr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpflptbv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpjevwk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qfanmxrx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvesxro.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2puoukqlw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2npkpclzh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoehhrj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nukepkba.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2oorlottr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyquxkew.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yduzlzna.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkwcmwt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtoxbxz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hebbeunh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxlwerz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgdsqka.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgbfusn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2haeembjs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuicedx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxofosp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kpupfgzm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqvzuuc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2keymypeh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nneqwzfe.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bouohfkt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxwiehd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgfzadk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcnvztv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2txknezsw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xisarnbu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jptipxwd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbkfjsi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkosfbr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pogbzqgr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtlzyrw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunqpdtd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdugenpa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zepxwtwg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfbdrgo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrbzbat.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqafetbg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zizjkfkn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2unlqgffq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwtkvch.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjozcov.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xolhmnov.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2icesogab.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msbkfgyr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaxxpkb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2afpbzync.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvcdcmb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjwumrf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rihfwiap.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2akayagnz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dndaxkpt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vzftapya.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvgdftj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoptsyb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzhiluj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbdzqdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feehbyst.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2koafkmuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmodjhuw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yynerjhz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hemafwpj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uatekkmv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfbufz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcllurc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeognva.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2icahliku.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wucvouyr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkmxrjg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjiccdr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2docuywpt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbiurjy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnfznld.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyuyavf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaxhvbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrjcxqd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nidcvblu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdmgake.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2njkxzgnk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzglvwee.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxveehw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2klsgpvvf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyeweun.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pytbryiq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uskhgkfq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnymoua.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgrwpfu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlaoqgn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rltgxwfv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2fvppehya.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlknsad.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxrzmrv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vopnvsna.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xfinbafb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmqzikm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmobnpty.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeotnzv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaujamzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcmuqgs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2domktfju.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbauori.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjverhl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2isjdbtzn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2usaafhid.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbuqcon.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oacznhfu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2txzyrqbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bosjdtjb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuaigta.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjdabnv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbxnqch.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfpnvsf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzlbmku.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tppxsiuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myxzvqum.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsclncts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2midkliog.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hsocvoja.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzxigby.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxdpqxp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmiusse.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxzftfg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxigrdd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2atarzsbc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhbbrmn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xscxtprr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpictxg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaibdow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hglrylmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eltvrwpd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgygcixa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mooivzmd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2veywyent.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyscfzxz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbgbaiu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cazxrrhs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxtawpa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2eshyuiqf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzsxzll.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrasvyx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcywdzs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yyndztfk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbukutur.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyxcsuc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xznjsfsv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wyexjmby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2txjnnjvh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zncgpmnp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlbxeun.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2swmjqyar.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrrhylh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqzuyuy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcrotjd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrwcvvh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgqqsri.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvexwke.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpfpruf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmnjwgz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2weicwrxn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcntzwj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2knofggue.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdtanp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtfwryn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nlubqigf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tetdcssc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2silaiqkd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcjnwfu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlastarn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ceimxodt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqnlhdg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nanxmezi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fniewlkv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qbymnqje.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qghepiwi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdvpaxr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpspszp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xonehkcs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nknudpfu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjewkoak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lcelrlip.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmhapol.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijopkuir.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtgfvsu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2botyvdlb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kquinruq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcscsrb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hebqmnru.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmabzen.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrwtwdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rknanvwg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2umwerrol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhadhbj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeinpvt.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwmpqof.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxtuzxy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwhzwbl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rihrkswp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcpkjag.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjsjktb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfdzlou.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbsgzu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeexbld.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2txsmeema.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvepogv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiugtujx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzkctnb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbdlneg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpeikih.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhebzwy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjokbrf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbitehbv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kptgxbif.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmcfiob.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfveeome.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyzmrgw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovogcsvo.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmffzmv.html


<!-- 参考信息 -->