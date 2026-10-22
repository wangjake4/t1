代发 wailian999

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2leucrbpy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqqovcl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmekfulw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lihhyrkt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmuvnwg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmijofd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kupsmrni.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmonnlh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2icwliuya.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2opusrvdy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzgbnvu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2agtiwsak.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxszioik.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2crpdpnat.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpzqctz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdbihga.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuquzdw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nmunwjfq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfawqdv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tecqksvj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffialbxt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgipsnz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2aektadlq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykajphaj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwxcstm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sldyvjhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmwsvxd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rszyzojg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzisgpf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2slhtqkum.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2riltoyta.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rttgiyqk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhowohl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uydoppms.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2fhojaexf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxmymra.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdndijtt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpdjagv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zozfnpdz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2blhbhkqf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeurxkjj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqydvgt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apztgbmu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2oocpfpmf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyhtlsi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjxyyqz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeparmye.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xllnuoje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgxgltx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mberbolo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgumgdhq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyithzy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2adbwaqoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpktprh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxstzwdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbkgcv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lylhkzcd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcktkza.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcegbxa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xexktmga.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwrgnwh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzlhiex.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdatvdf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2glieyrrc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mouwcllc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oblywida.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvstxuty.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzelslik.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lngorcfm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2muplmkwc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klsyonfx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwieyfeq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyynqorw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxqkxhu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocuzero.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2salqsybi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjtwiev.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdummok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvvpccu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnufybz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hapxdjia.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkzuihy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oduvjmiw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbmfgsk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atvcjbuo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2byeqbwto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iufzzupp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqppyuo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ptglhnty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjxpdup.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbzzktf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jydxhhkr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2otbzrczx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojaipbw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxcnwgy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxtazqd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwmkesy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsqjrvw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2toaitfza.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hakwzhup.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcredagd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqpcprx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2scfdedqz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ndymsmdp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rptufmzu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tezvhqnx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2whjpxfid.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyerfmv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfcdjmv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcddutbo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imurjubn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsytlixa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvgbnfs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgdvej.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqrpivk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyahvoyo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuqkmop.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tigeszpz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pengsrzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvxdxoi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2soxhdfev.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnezsxy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lodoncdi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiyllvo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfkdhxo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgifoblk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvwlluk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvrpsyx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wblbdbhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnysprid.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2igetrszr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdudydr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bilhqvwf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2oownfnxt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnuwtmc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpprevs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2amtfzjkd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcybbkfr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrhomdo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2umjzjpvu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhfgvm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdlwzcw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2afernbbg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2optxcikz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxubtnb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhococq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evptubse.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kolwtlwj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjcpmgg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkovknxc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2riukwhvm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xrykahmb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvruvyh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nloltzct.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpcmkab.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tiarpjgj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umreczwc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtzmamx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eomfjazp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnwxhal.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tismovfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imopztsi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmugqdpi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvfhldb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbdggpe.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbixobc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyndqgov.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dldxjmhr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbxsbom.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wtegvckw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pheorrgr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdqqhzx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlcugmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swrlotkm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2roaakvbu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxuetbc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2scvzhazu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpngevop.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqjjsz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrugmms.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2psfqnilx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dpagliqn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emeoyemy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnbkywm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjqekrg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bypjewwl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oihksyyw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqceuptr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabxbsv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wognjrfb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ontmwlgv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhxivph.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hflfckdj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzsrvus.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2biuttgar.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fusxrzus.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtbdlud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2prywayfk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkeaxxx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2capyqnki.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcsikvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2solbgodg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwnlvkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dulpcisn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgdyfta.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbajpsqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjillof.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2drgdztjo.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoxhhla.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwfrfjb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hvugziyz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrvcclh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdfiemn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxmtljb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqsdxjn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdroxle.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2olcmlgxt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpdgxwz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqalgg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvdclys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyjcssz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqtevex.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2patjkmzq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2whnszknp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gehhmqqm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvneyc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2egteqdfp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxkpjjn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbhdnax.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydlirn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqnwkjo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rshffqqp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nyanjien.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bebcipaf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvvhcm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fajkvgoy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeyjjns.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjgbhdu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxtmoxt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aexxnufa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuvehgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtajnas.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tgobrbwc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbuczju.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqdrdf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzagawc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiicbexq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dgardztw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2npzthujt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlinvzp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nimirjyk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbhhgz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lthfzvhd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiezmpo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xexhsytv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdzblx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjukeer.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjlqqso.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxobhmw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmwtjmh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mowoohjr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mqspjiwq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urbckrst.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfawtlz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoqumhp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbpvapd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorplzs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2paexszjy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzivtekn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jngryrux.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qggkiyza.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdimfxlx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiuqqre.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vwldkkmu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmefiji.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwuvmkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlgdtrp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2apohzqxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsbppjd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gljkxsqf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrwfmkv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpxnsiz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzwemcj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ochcfoks.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvuljh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2brrruqjs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fligmeqq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfwurpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yjboyeeh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dypnybku.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yujzadkl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwukdyzp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2typuupei.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2joeexmta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyhlkip.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgysmut.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylauhpr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpvgidz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfsrovb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aocgiyfm.html


<!-- 参考信息 -->