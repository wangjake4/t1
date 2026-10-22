代发 wailian999

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupsyulm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlgfgyh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aomywsxh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtkxstj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kdupgfnj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2egsdthvu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyundlu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiafkcnn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rspbbxii.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2twdewftn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vknstmnq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtadnpw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtarqgwk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2csnbnaux.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrhoolj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwqkbby.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpcpee.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kpayibea.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pssuoqyc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2eatwhucf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwltnpb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2oivcwqcp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2iowayjzu.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oawkpzlr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtvolzq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kamxwbui.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwycptkf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fksjeoic.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2imcrnsla.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeoqxkk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxpppof.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeamyyd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegjfoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkkcipt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tktdhhnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cheunukv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdndgmro.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfwvgtm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcchswkh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxflkdn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjlqjio.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqchgry.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuprtcc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuixourz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujfmlst.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gktmoxzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fskicjdf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cykmqqvf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfwnkcp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxesjhk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbakbas.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvzhwo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vavsjqzz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdvcolm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwbvuov.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2heymvlmf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkakqam.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgilkdj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gibnqqfv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkxznup.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ainllmpe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2sakeygxn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kidqeqsl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwsxmuf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbfmbnp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbklwxd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfsgudi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtisjdd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eflinhpt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjeksjv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcacewxt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxknuwp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkudzat.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzwqez.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaorkwaf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjmtszc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjhdtqk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzswwjhf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bosgmulx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhrhrxh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbdeagx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgynzujj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbqgcwi.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhtealv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlmamqd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsehxehv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhioffs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uypvjjzz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrvskje.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqdoqna.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wngbywcy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uypaewul.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rsolthqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsossruf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tmydhpky.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhtylns.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhkhcgj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnvwqfq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gejwksut.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2odhrblkc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwjoaui.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhejhdgw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tedlthpy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgjhzge.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drncxkxq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyznklux.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzpqmxa.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbzobuk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuiywmo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2npljvcqm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnfraiw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvhxtso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mgybjiyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ophbmcri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nflhcmjt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzveabes.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rutvqwrl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2esnpcozr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrkyttx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwznrgt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrrqkzd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2agojrvaw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elefpmoz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqigjinw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gipihyri.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcpweil.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqaddcn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtecjqg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uipdszxd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxcevww.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iszsrdyu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgwgaah.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iromhmpt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvdqqnk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2snhqftej.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyncndwf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfvyial.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhyyyrp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwtxzki.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwboests.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2igesynfr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sapflxlt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoxmjyl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pedrwxod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmndtsr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhbxyxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbcgdp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkfyibs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoalief.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnytxpup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yuowerna.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjpjqpo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2invcaifx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuopwun.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtweyfij.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cyunlern.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2efozkfje.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivusrfb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvngzjm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2feekrrou.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgpnrm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltngfb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpxcvnp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bsczxyhk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2snyfofuj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2latlisia.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgisedqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkazbth.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyqyopr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbsmrkg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdskbcxa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiumtro.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azqzbcnx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzbanai.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqytzrk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2txegqfxk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsnjflm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuiegdk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngtwmtq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2erebvzqg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxcpabq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2chdwrgvx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwmyrsf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxsyhhp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2phoavkft.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2htjhsuxq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggfidpz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpnssru.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeokhodb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbuzcae.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdbyqzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrdshre.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzgvgsg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2utmiaeum.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaschte.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uiskpnuj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hiexxfxt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmirkej.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ftybqtnm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2okubugpr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkwwwme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxhrjib.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrzsypi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbbyoml.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzklvqr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2velzluzr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2njmjjkxg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvotkghk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqurgali.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfshlgm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwsjlyp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyakdfg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvearxug.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ggayjdqw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekppsxgi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyavksgk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2elvokioe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrtyjec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqndigi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlnggcs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhaclb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlqzjhn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cusuacxb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcphxvzq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgsmizn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bogtghcg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrrbpge.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzovxwc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iykerujt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhdcpjh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2otyjlqld.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdrrztb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbgqnkm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2thchjirk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxscchh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtpopnc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ferwpdon.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnvgjcl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2skhnogio.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxusiis.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bouzyzin.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkcoafx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2usuyujwt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lalwbwyt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxmognc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2svpuohwk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywbfisd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlhxnqi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ccopheim.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqnuump.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jvietpwd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwajhaxq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2deewugwh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoegswf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjdsxrd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvoqsra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzyywyp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxkjpta.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqjghvl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lraofsdw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdbpjnf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqvrdwv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkeegoa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrnbkxk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtturfk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjgsnnz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aqynburj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrctirz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammsxwuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhltscq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjghkjf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2homoslcq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsbaqpz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gupngjni.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrikwjv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ixytsaum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oprseoyb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuywhssr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygujwxlv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjkobbr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hxixjsye.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjddtqz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wipuzfsy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhuhxyv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aauegvbq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2djdkgfag.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tryxblyh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhglhz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjskbsx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2orsyhrxc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzlebyn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2htyaccvn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgscdeut.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvodatqt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2geayfosa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvscuukw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjzligd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gztkqiea.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ospxogov.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2riixdbbq.html


<!-- 参考信息 -->