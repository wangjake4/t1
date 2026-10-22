代发 wailian999

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shyaabyy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdoipgg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqvzuo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxditmgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpnwsls.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2glgruosg.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueradpfv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeklqpiy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkzgota.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkbluoa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlewbbke.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2oefhihjk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2llgpbdji.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjtzjc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xwthobvx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwgqmpd.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlgmjvg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrywxhqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hygpbkzh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwttkfk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xecjkvfu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfykvhv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxgnrtl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bdujjgoj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwbesha.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpyekzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zutdwbqo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2azcahieo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdtvhvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eesdtjfy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnjpzbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbjbmlt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2epqybapw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyrvoip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eixzwqcv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiblnze.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrcgfot.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jimvhkic.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafqtcnm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwkbwgq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eldaqjxa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwmopfk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkpqjst.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egrseytd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyacbrx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyeopfn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2crhdpfgm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejepawo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2omraswcb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aavhjklz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2afvwtkqc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2sagzfbgb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2voqynvos.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfvruhz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfvixdr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2phhmwabw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zycogngk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qenhhwqi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qaedtjlo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjxezwe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzxxrby.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxzxpkf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhvkfby.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgycmbv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2loypupsy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkjrbys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtayfgwd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpoaukh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwznlxm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwimfgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyrmssn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmitdwcf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdpsdkp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjjnqvo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctipnwzu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rphesaxb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrgwibe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txyimafn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqdbeup.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwvxqxv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvlirgf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2udstctkw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhaymon.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2izhiibuk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qjahnyal.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fewfcsgv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ganwrhtd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbqfiko.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrfttno.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktayujie.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljylshbx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kyptqtfi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dytnoyum.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaptolb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cosmmbbf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwzdddm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpheujm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cagqozmn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ffleuzgo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dimfuajr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rfypubfq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjdcltb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuogufm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pwupxaee.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbssjen.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gudrkmsg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwryxbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyxcecv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2amtmzutn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrxkenb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2upjqtuja.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bnftopcu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoqqlja.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csqxdebo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cucsrfjv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxnjekh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlafywe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqelkwgq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujxppm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhbfmgw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdwgiam.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2makrdhrd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfzoub.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iusodwqx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxbvoee.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrbkknd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaopvmu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cirowmlc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbeogqf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bppgkkan.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pxilicmk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tspxdxyz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzlbrkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uewdvzny.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyspaabb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaahgfr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2higxtovl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrlwjb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxwiqeh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrjlisl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxahistj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2omjofytt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wseqdqkj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vnblyqoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpxwuez.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqjcxwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uolzrgbl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaksofd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkecucfg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uetinbee.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghvpnqo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatpokg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxkhbht.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmlhqtw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzbxatc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2citmpbcq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaljlfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzmshmc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoswxqx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nepszhut.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpvqexk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjojxgb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhexeyn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwscncm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pejgbkiy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzioqwe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shuzlmkt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2corqnkkq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wldqakum.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhypeub.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfixbk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwshfqqx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhnnjqy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyooftcw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqtbewj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkicedd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qodbzaza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzbhmnv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbrssf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkgmvnc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oexywwog.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvkpfrt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2emqxjiwk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gahwmjxk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2djpivauf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nelkprdf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkkybxo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagolihw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrewrij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqzxmjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjocemh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qenerszk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgyboff.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsuahuz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrwcptq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdyrrhx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cumzuiir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stwmyyke.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaosekag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfzmgxt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfhvnxk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2iddcmuoz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcljdi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovczgpwm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxndthbz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cssjedni.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2scngievm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2plsytvpl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdwyefn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ackegrhc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlojmqdc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuwnfyp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvoqmxy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjnpazi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2htggiyta.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjofrglf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cknxxogf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwexyae.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2puleikka.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mchslbbe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdmmmqc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgisjjr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiaslfw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2idaijbol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwsmcse.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2msznthnd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2imwamqmj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yxryvegk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2klehszyv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2irgrlswj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gghvgyhe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eoepjyan.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbmnntn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltouajtf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xttvlkcv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xurckpel.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tavonkaj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsntgdn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvxlui.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjzrvie.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpsmhwu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2llpebdou.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpbrnyl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2byftdbna.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2alogljiy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ethjvzst.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cphccfae.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxhzwsq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2quioputp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtaraiz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrhnlsu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brqkvoty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bujearob.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noouztee.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fccnbjxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcsbddz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iimyirjq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2clidsirh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqkmjfx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgpvggt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2epefjfuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxtaqxa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwoenxx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2meuscjyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjbkggb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aktlxwyv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jotsoysp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzrkliy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgydpatj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnbgzca.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwyers.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqldiomq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwxbwgn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqvxutw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqupsab.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2onrmrdld.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjunsx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcbgxiv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoodqrn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbyzqog.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhrpni.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkalmwh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2buvodadi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvwyzib.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2smujcsax.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2shutufxv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfjqlnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2llpmuxvb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdobao.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vikcndmt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzkqktt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqozfkyp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uopcnreu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjncwlvb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2twjmukgk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcxslnk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrlvnzd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrpmqev.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyolvyty.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhhzgat.html


<!-- 参考信息 -->