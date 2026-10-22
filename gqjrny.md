代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gchpsdsf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2abbobble.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2levgfutp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkykzpzr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwmejf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhyoidj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mresyiyv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izjvcuke.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bilgacgl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimjddg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nraricbm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiuoowi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivewcxkh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwggawfo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkgimcx.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2inqxgwzm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2llcenlia.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdvljxh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2deicnaxp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fguobdvv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbwtoly.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiqqgnt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvcsyxu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqtfmh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfptbltc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2doekwunq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2otgxnvab.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpzxjjr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlmjjdg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsznsbzh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cypkdstp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2msduczey.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnjkjhj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsnloln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxhlmnd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2uspqhczu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2osiqotjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gribjfwe.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yojqbnaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grruykfc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2prcuuiam.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrmjpxl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gccagymv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqitnxe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksyyrwu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfkzjik.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sunyhjwt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzarievi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxijcjwk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkfnenv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkqbtwt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcbptrw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztymkmjg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2egurjcrw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhlkprp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sigayknj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ikluzydp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wraserab.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2emrpjxqd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzbcstq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kugmdgti.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjvolfo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmriwpou.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbbtvma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmedxnf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfgydgn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuhjnug.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fokzsdfp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fepfcuyo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhhaqqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2skwjiahe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzsmyab.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwfkpdp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgmmogf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2digfnbas.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyggkqon.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2snyprkrk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvicxuq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mknontqu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzasdep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfqbnvv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxteuidj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuthckc.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iipzvqkq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdaytgd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjomhfx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrywgkr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrghxtz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnewodm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyerpwks.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2smuaikuv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twpcfblk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2slibgqii.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xiywnwpy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2altavucn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxhnwhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmpmrxc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdidslso.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsbqvwp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsfkspj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2upjbozhm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nmarzyvh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjypliv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmrfkvr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlohxhw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnmsraq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxcdenp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iculzupj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aelbweyw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtfncvf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbfbnwd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hemsjxwr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfoxytu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xetvewqh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpkpyhd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zsztxtzd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2icqlazbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpjrexm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdjdbey.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvpftij.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzditmtu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtgnmyt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlvinii.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrcfxwr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgznclj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iotytwon.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxndyvi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2szqxabds.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2elwrhpji.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvasvram.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hblvjjcu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmctmfb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bftvesuv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhuqfr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcyhqup.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpadnfi.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azxydqqw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxiczt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eieyhlro.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpqusrq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgdokwp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2byxexksh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bltjsjth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbhvrqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qruuznuf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfscsgri.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbhlhcy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2povldvsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tidwdurs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mpaabgbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnjimgg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdqajia.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2suwmpoub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzbcnif.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eshkibsr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eyixlsmg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydecubeg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwutokay.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yppyzyae.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2azamdbev.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnorcsb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfktfscp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hjimimdi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnynspe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbeznkl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nslrimyc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjcqwao.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhlgtwi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tedzyiqf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzrrznz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmltxpuf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2glbzvxng.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2txzfbdhm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nphsmpuz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svltvntm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhtqchp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjammbfu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjrsohm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2skqqayjo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfsmyth.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jerjjqqk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkdojss.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaqthhv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrqdjrx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2brxazcvx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnexizb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzarywkz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkmztcw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yizyvqjf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvgyps.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwupmnly.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2waabvnwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtfcarj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbufbruq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwyvcoj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhvhjh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2czqqtbsc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nstqbkqx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfzrvry.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2evbqfcfe.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjswcld.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyejleh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dquuhtqo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xstxgdgs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqgnhpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aymdesns.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcohdaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhutjkap.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2aulbrmdp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rnplwhph.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyazdrn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbopfnmd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2euupsewx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhogdktl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kspwygdw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2azjcejrb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqcrpbm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvxalqe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsfarce.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexlxzoj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2czmuphrx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2olyrgyav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdveekk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gydqiqjk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyhlhgp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwfwmow.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmekrvqs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kasbpaxp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2emflatco.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbdglgf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bowdmitl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmjinr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xueztcen.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgaoynf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2smumhpna.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pimlpyhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qneqgkxc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuvbmhr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpjugwv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdswzruu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwoiptd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgydxnur.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpqqqmz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjsqprl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgtfxav.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkaamgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrsxbka.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hyswtiiw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcuyxdj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrvzdpp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeijxfi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2myfuzpne.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdfxuts.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mosnazkd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoesvxy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwstzuvu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aboknlro.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbcrjmf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kamzrpih.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjlygjj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tybqiqji.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwoyxhr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqxffqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hqihbbdk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mundjwrx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2surnokii.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngeses.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wptkqpmm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyrffmh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2utqrwfwr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqfznqs.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2usvnruav.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxppmcfc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2moptavtu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2crgpywgq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfdmdry.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2difrrsdq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqmovzf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnlxsoi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvtrhvn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oehbnzyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcgnbcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urclbnva.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wggbwhuc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgggdbr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nadebdge.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2idnnaszl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpmzegc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mywjimgz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwppjklb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mspnxjto.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdprfpl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmnvtdg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qeonwakd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgqkhyo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlxhgut.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlarqycs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwkrqzi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahzdgsv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmfiiwt.html


<!-- 参考信息 -->