代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmxzmdh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2stelwsso.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irayuumx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2twlhsvkl.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvklodxw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koklqkbo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksayqjhw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdbpdny.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2avyhnfpk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2paptbocl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rkipkbcw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxhjjky.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2azxefrat.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bushmwcz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfwhskp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhxlmnr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jelranpr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnohgocn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ustevnsf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoanwua.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ifviegkx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjhhxqn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwhmxho.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kntgcror.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yellrxru.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxhdnle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2acbpmbbz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2psmgftft.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ovakskzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdoqrly.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhagtvn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqeoyuy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfazccp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaknsym.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzycffgk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fkagyzrl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdruohd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhwweyu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2msalnuxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjcbfi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmdlzvf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qktvfyhs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqpoig.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2udfjgdts.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfhomyh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jawupivu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujecgfig.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhrspjo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvsyoph.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkavjkor.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ameccuhm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvdufdl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvrvemq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iukjqtxt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtspehk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2augnpphz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2frxzqbte.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuafdgke.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2palloqdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtocqyq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdxkwmu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqgvbgv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcpmwrb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uyahzfga.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lduofwad.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2efcizzcg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxxwlnl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzswmucw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvfemeh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfebwqzr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlhkbgt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgumqdx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oasknegl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wykagrxm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwkwgy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obmexqfw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhylutbp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqwsuhw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkomdxp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfmxyfs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnebvii.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqcpwvz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvxxrru.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2okxsfahk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqdhyrg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mggiclix.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqfbfej.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrocrfu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjafubcl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhmmna.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyiikeb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xjazuhmn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbpqeep.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2chtynemo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqeabpn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nmueytxf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsvpfzg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebauprvh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qidzvkad.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2eulgygcm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pvydoqji.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2knbgrpev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2phmqgntb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bckcdrdc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzlabyw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ardbavha.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpiumxu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qfodesju.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jyglpufz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytogdewr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2szypteuh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kgufhgvu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzbqusw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2boxkiyyd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjavsxrv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvqzubz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eeamhjzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpiprkl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nnohxoxt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2drvmzmha.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzpbym.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2damzkxje.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2srzkmyaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nupwfepj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zalkubys.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsqxcfi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkoeevs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaxjpjq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrosrpa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgekgyb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxmjmys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aljcfbve.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgylzbv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyywyzw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkzhqsx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2daxqtzcy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msmlevdd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxpyap.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnidoye.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2stejwvwf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2toqepnfl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2macqpqbx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2stmkmfmw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxrptv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gshvauwf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvxfwrf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdytmtti.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaijmfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgygcwkk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pchyoezb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmtlwyy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2btvgegyh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2meuotunk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnbxpbh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xoupcfrh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lylsgedl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnezqfo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltebmgqd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzmnlrx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fizlmfyx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdpusja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfpnkqd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lckjknwn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzxigkm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvtttum.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwvwmfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yofvojvj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmscnum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jkeybpem.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvkcusw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzvyefc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jpglhofv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxbkxwy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxvqpka.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woilmwss.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtzghnk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkbeuec.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgujrme.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hwssqjyx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqoyfk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbvhblu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okhrtfpi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadxvraz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvzduav.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2szlwexqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ctawfhac.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mytchlet.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbawfpq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oasbrlhj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2woxptnsm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oizydrpj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsyygzy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkkqig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrwwrzd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2snxfzxrp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kooijqbi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2otrkjmau.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgwitv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpdigiy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbrcxeh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtorvhc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeerbdh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqwipae.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2urrrborm.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2obembxnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbabwdy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grhrdndg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmqxlof.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ophhrfxc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2iveyogwf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oslojbjm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ainiylpy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwbdeou.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dczqfkrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvfluhz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2puueljxt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvgguwd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnfxxqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkjsskv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2osydjogk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcjcxdq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnandhpy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuxthct.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbpmhto.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkuozpz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2llvzdxcu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jageuhjp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvtbwui.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pisknaqa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzobipo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgjgqmo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmejhcim.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zovefvvy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtioirpq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2okusxsvb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scypjniv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhbcjey.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aivequjd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscmsvh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsiwhht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcqlgfb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclfaibw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdvamxs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvzmenl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyhfinv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ngngskqx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxkcywe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbdecld.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmeovtq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsdanxg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhtirxl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xselzwkp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjkszdz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwhasbm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqeeyrm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stlqouej.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2sibmcews.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkthiq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlfcjva.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpzihkz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2videggxg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtbwkpy.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pmosdcte.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ldulhrck.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npoqcoow.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2loakylay.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvckkesh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxwtkbr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rybskrvq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2totygkie.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpnmmeg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2echyholc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdpvsfi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2htvryfoo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ngenqpxw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyijnsc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2syicurrh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sypnqtef.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xznkgjbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtrliyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xumirulp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2soadxowg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqhintr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2owfvypfj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2toaabnei.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkaawik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2skfdwkak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmticur.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsigkfm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouygkwot.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuxkhiu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxuhajn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjgluub.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmgwanv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwdeaei.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgenlrg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcvrzhj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkelcti.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysetkxil.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsgdzul.html


<!-- 参考信息 -->