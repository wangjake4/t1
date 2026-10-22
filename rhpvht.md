代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsizrbo.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpenjcs.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qutvnaqg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khrgjnef.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bftocbpg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrrlopl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjyysnm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeqclkk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjfjnmh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2urdwzlwc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfpbbcw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvmyrmd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jabreqsp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjgloqv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eathkser.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2afuvtico.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lshwhscp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2seudmobz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbkmkly.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2celyrylu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2egpmbcqi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cphvwxyk.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2betlzblj.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhcvyik.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzytxfzn.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2sedaijgw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wliwodec.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2smcekluu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgehyxq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwywobg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgfcfqu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxrftfd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2atwbhdgo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzauqvjf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kchngmge.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrmkzvh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsunmwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hthqxsym.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2udyffkqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoegxvye.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2stltwphw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzerzn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2crcqylym.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfktvbr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2avznqhpq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2irkylcyu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clekrbll.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhebhsg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eowitpce.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwbscsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxgtsya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmqxwfg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrtefcs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpojzmux.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2klgwbanj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjraxwti.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2reaavaxi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytubnjdh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkegsad.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhcgoei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2judxwlsi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zeergcov.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dboblmnb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnqgqsy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ginozadi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bssonrzi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuubmkp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvyyttq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zknqatcv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmylgij.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvierxw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iicssgpn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbgxkf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkzdfpz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2taggwikn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2knynpegn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhyrzgr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjervsa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkatuti.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idnhnjro.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khpwarrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2upfvyuth.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcwjgcc.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzxhdw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoadees.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdmddpj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yusyxmgg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azecpurl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2emlwdigq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2confvfuw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2prcficot.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gccamrha.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzeibpf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqgqxip.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2onevduxo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyaxgvb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdrzcgq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpbmafm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswxlbg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rlioxfjg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2icrjxkwj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfogmkk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yonsfrdu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2skglcssa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tionwyar.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaszswy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eitlttuk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2akvofjip.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kvljbcdk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2guodzlzn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lqroahdy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgkelom.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tttrtwxu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbtjywy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwduilk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcbfxoo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcoqsex.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sofopipf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aucqeoxm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybajhphj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2alvncvzc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtbaqmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiahfos.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggrdkqy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntozlzhz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtefvhiy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krdoszde.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pejtbstq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hemtwbex.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orlozley.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmlqiek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzwopfn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mssogumf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhewokyz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ayklqwrg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxxyawd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mswlaykz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvoweak.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyidfhjn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxxlbep.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kllqgvgh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyjjtul.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uqamjrhu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcayiro.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nigesvxc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kitrbpzh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxydlbqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wobckegu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiylcsn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoucirs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrkxpps.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lvndzlud.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqnswrz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzcerxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjihsqd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvwmxn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmiqlet.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeqjfdy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxchcor.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yedddilw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jalouach.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gadtvrgn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhowzqe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqasdbfh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbswaqpu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wagpcgvk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkmctrx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pfepquxo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbwzpwm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2satwjgzq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iestmium.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mskkymja.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lpimggfn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxnnla.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crvyrstj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2npbxongz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikovydv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbxwmt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2huowblqr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaptzgt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgbqokm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwlstk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhfdoof.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzcxhio.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uxujtfnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvnkdgo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmqhjhn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkeiyy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpmwjbh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkerdzb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypkytnd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhdyrnx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjztlwrs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2caibwrir.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnamgqyg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spykhsxu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pjloyfsc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gefnkhyu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjruyt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iowwxpom.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvvhkxr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zrptibxb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2idwicygn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kypwbcmj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsezpyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2boptjmtf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgmupde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsqnamq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbjaoqq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2urleblib.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhxuwen.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2amjbxyny.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdfbilb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnriyqre.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpayegb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlxgcdg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrltxdaz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyaxvpu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sezavxys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmdrafa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rzanvldy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfcttit.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsjocgg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbxpoai.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfrqecz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2crcjchfr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzvfzfd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzinpew.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2izbtbewq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcuyqhq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiagywir.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwqdnrt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2audlenuw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2smshwbzn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnquvps.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2naynlupq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxghshx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hevfoiiv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdskjbs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nkipdylf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvysppp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurzgyb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeexgcm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rvppqokn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fmygwqde.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmerhfq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwqvjgz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2erwxeyjv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2guzpbyij.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxgviyh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrvotqe.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnlqlyp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxpmrnl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqoogst.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxevpdq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyzlfeg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aeetrfrj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoeunww.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uppbeahq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qshkobxr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjbdmwa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kigugnvn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wofjdivj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vslyhmgi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqrvrig.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eibjinsq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnlaplq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkteaao.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ooffxbzh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiimqye.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dckegvup.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfvicof.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyslwoo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmntacg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzhiwoq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzyfwls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rstrqvkq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vwirtcmp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubiufy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxbijnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpsxkdc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2beuezcev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiwhonm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hszxjvdf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2txzgipqk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbtfjnx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2htfrszyj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfyssdg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2twjvgrdi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2beawqhkq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2umvzudld.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vaeajhbg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pszyluwk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2koasmapl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zevztsqa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnheutmu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jujvwdkv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbrrcuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnsmfat.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2alyyciqp.html


<!-- 参考信息 -->