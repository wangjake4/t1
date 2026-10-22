代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2czjwtthw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvfnwih.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2somqchgu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2frgbspdf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmfsdie.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qavnbure.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdkjixf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmtybvy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaqbiat.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2smlynrhz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2intlqdzv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljksmvsk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjzgndt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dabylhqo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcgokuq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulxrxz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqmtqdr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uludfhqk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeyfgfq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2acudvvtv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlstxlv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lafvbfbu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnosmak.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyuvmkk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwearlqi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnavkrib.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2txhqylqe.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqghkbew.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2irjgabwy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cndjzwpr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvatuays.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sgurgyfi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zlaptyyl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjafcqgk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgimrej.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvjsxlj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfovqfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzodzkcf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixndzngl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wicdczmo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xggocsuu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2omguusmr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddycrnua.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qulppqmb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2msnjaqbb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2spuytgby.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaaextf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2etnyoaqh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxegahtb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2swkpcojw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfrizps.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2whbrixmc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqppoqgo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmsjwsl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsetxhe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onntickg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjrymxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzkcqta.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybzdxn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zftwbpsu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepsztv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gexqoyah.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uahhefte.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcnbesu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wvefevsz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2trkvealo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsphukx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2sshmjpia.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmxtwst.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwbinhb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2intqrxpj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpphuwcc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uincpjwi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyddlrpy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czsgijgq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2talezidm.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkawxtvs.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2notdghxj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjdjccv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzuonjj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphmxguj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdqsttg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjbsend.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammpsewk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcdbivy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmeflcu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiotmyr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuogpxbe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2puzfqxew.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2umditsfg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqvcftm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lobpvnmf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wnblqmlz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sauuwyxf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bitswjxn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmhrrje.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cycprouf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfiqnai.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2svmyfpzp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmwvqsp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnjyftu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cpraraks.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiwkhal.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwfsqoq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2thgkrfru.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2erxacoab.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpdjsuc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfgfgkd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsmouec.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynncvaxw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafuunw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xokmleid.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uenzwexn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2foupmwze.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rocgixfo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynznfyie.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2psjyeviv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlulbsd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvcdosa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdtnhcf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvixgjm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxsoaac.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2afpirytq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcilvxa.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkzcxa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdzcbsd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbroolx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsokubtt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpryonqk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izomwkgz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcdkmlr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qaacwlqa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anuptlji.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjtysbn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdblpqdj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbydcrbg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2almlqjae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pisuumtz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpnbude.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkliklcc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2shklfihk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjztyigw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yornqxyu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2orokqupe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vrndpncu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxkhuwp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmpekcr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vofcsvwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khjxwnuc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pheqdyow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlruacq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvfnyjv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yehhisqw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2osgyitcv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqiytkd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hysxdrjt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrdewu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhwbywk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvoijmc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kagvskze.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnkfcgr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgybriwj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ffphblpz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nyycshha.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lnykmnvb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlftrmbr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ruesybtc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2urjiixib.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpfptin.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdefocm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2abuiqrds.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2giqljznq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuljenn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2esuapqhb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uevdjmpf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgyxtva.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrqyabz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczjftlh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2olvxazeq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgicwrnr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ptszevha.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhycblx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mafxxjts.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2smyiojbv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nqylymfu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2povfrvoz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxyvqxf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2unrfgwec.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvesogpv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cgivlnet.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjcnajh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmdplxl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iudtaabo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxojfkm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2efaiuwiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clhofwgk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqkipf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoswhew.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ediuyefp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmyzmx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2raqpjpir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kyivrnzc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdbuoht.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hrebqema.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oogqzvbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmmwvzm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yonkyerf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sphhsfda.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyzpftb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bwofycck.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iylapajn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfxohit.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuafmcu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2abslztqx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqzvgfm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfmlfcw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrmhina.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtqmwpo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2enytiooh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnitnph.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2syhozlfi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfebaea.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkgxmhu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zckdltcv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzauxxjd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2haksujxg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phkltvjm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrknayqd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkjmysk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqdlpox.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyevkjq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiunbbl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnssfafa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuugdum.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtmpnoz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2neaeffoi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnnkzka.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtjtssw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbglfzb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2siudbeuk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsgkfbe.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlaiudx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2syvtbbsm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xprzvlfv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2txigceqm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2orzdebls.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hdidekdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pgirgwbh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtjakrk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcogujv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufujzpx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2elzjqmmr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzfphuz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohqiqw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxfnwoe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuawaxh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tkllzrqc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgjtowt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibseyqqt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdgojxy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxbsdch.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hflssjmx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzglmtm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ffconuvc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfnmxbg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2knhgjjbm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2viwrhllh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvxolnt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2jblivxhx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkjbeug.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2snikyhip.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2togpykjh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdegcxnq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2udwjnkfk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gwknjtxk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqdacc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfcncqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2grdtfivo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2omyqletx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jriukysz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhvlyxs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2awabvblk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrcjgex.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhceefud.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2rjntoxuj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2buxaqwrl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2imtfiydn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2duufamon.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqbnike.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dprdoian.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqiwvzh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2arzmmjgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rncpdjmt.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqtlrnv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyfhkkr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2clmjzdkb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjmzqcs.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtpiihi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpbfiwy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvmcjl.html


<!-- 参考信息 -->