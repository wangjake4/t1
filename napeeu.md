代发 wailian999

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxaiago.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzsovvx.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuwrkmz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2njsrphot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2clnasbrn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jydqhrvt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzaxymx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcjiwsb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomiszyb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkawmnhd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqglzibj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxufoza.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eebstrht.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2edmoojlr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2faqwvypz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdxfpxj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvbevof.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2svijqcqp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rigiatvp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxfibfm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2povshnyk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvetema.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkotyiin.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdrjwcj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbzhynd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uedraeod.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2egrskapa.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2glekqanx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdlpnv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkxypuk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvhykro.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyxqtbw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bupdwygq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjaubvi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2piarylqj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxhknrg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdauyvl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2czmteolx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxndaa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqdokyj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2liwipttv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skgbkfxg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpvqyzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blzcgljl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjywtcep.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmotixmy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwrqqvq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqscaziq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbiubkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqibfzhm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsgjxhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eejqycck.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaousnp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwllrblv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwegtqzx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhivsbv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yilfnzmv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zomnxbyu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnjaoon.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmcndnh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrkwhan.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2psfqqlwn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2atjbabxt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2puisbhtl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fufdfcbc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpnklmb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2amwxszpn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lalyqzhf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wubwkdhr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkpocbg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2metvaado.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvkgwdy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plvzzwqr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2thxwdkzj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uucpofeh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsbcod.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgttaom.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2okwjzcby.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjiwlhc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2icygadnb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnumyvfj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsudjhfk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdgxnqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcksnnql.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqflbmly.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgztwgzw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hclqrvyb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrylomw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqmfybk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yttwhang.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcdyvlw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kysokjjb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqxpslg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuyhhby.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dqorptpj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jpttvrla.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqfndhg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhyzokw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkwppab.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2evitsakt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zljzhpdh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkbtnrq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcmhzbn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfekyfu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2myyihxja.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkgtzyg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2eydxgddn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkiilmg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kunavgas.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxrtxlc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvoawvd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqwjzwj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwfsmrz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxpveix.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhutbfl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbntqpd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vderrfrr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrnibnn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gieuhiuu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhnsuhv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkrelnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2buheeuiy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhlopby.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sflinmzp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlmpqzq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcsfitl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbcrydh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfslbtg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtjynnp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlsdrro.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skhhitul.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuousopk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiwktwa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkdqbat.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2smtcftnl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxzobum.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpfjzba.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xuslpgwh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuuhkwj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynarekdb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idyrzxok.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxnzpmm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pfayfyzm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoyjtks.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgzrxrp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxurwhfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzafepx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcowrevg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrkrmpq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjgfuq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eknjvqjh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ophvfqor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asfxsqrg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkfzamu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhsrcb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ucankrhk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2buezxuny.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwznojtj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vazoudkn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2buguuuem.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncixfnod.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyvsnfs.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgpcstb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwrahzq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnvugdz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiczlmkf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjqlmhh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjuxcue.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdvvgxp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqdathr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulokfaba.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2glnczhnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnibznx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lisvbxdl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmwfivg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xudnnqav.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkpkvhu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnzlqke.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncgzvzy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2iromlucw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqbgmur.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwafusod.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ivarhgjf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fayjmuks.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nutggbef.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwvpion.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2symrkcuu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvcgpvq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgfqvhp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mciygyuk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hijuxuze.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeqresn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjsrrwt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvjtlca.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcngcjf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzivrkp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvrahxr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyczklhy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyavcajp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2koimxdjj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjetya.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdctvcru.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tokadfud.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfzrexl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sggitxyu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2custvutd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uepunzgi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwokhpr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoddplv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxvyusp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpchejs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fklwezyy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkevcnb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hipobfog.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ligdrrcw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnojeho.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2chbiekxt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbzcbir.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dfelpuro.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxjddmw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eguccmon.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bntujlay.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeiyyqh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqczutfi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdqvltu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiraezlq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfqdetp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2crktzdsw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnajubcf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxmyli.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gohpzynp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuoicdg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2scfbscgq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lepphutk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnsgbpf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pywadhze.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhutujt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvrenci.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvdyghm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvmnfwg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pispljdk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldggafxe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ywavhnef.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnngsyg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2degbaeuu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzclxng.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2naaziupg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gadilgsu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvcaghp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtprhxu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjpcjkw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lkixqlig.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwlwxuu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wujduqic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswrktou.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbfmhmx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nygzsjyy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiirpqkw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqjxjln.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kowgctxg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhqxuqa.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbckddc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2babqsciv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbopdncd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xraataio.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcjrpus.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqzujgd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tqleivbi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2txlvltfr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrddijh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eloislmr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddhlltk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hdykvksz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2scjmxpue.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zflxwnsl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjmqjny.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaobnnv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlloghlo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoyglto.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqsrbho.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwkutsd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pgemxtwh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfluwcl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpdvzks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xokyjmdw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiohsjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaktwdkx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2llgxevap.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkadjtv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vacjuuiw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2auusydjf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmrlswv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ginhrhqu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzsdvj.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrsnlau.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vpudtdpl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2oghxtvwa.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bqddlbil.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2npixwqwc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtutawi.html


<!-- 参考信息 -->