代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqnuapm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xowbbtsf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2aarhlxqf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdueuypo.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbmqoyz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kepnsaqs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iavupicd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvfgkra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fubgxouh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxnajor.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwopcaq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvswfmq.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzpglny.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmgnuri.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftplubko.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwjxoiu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dhubqent.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdcqtma.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzepint.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyjzftl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdtiybn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzaawju.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfkhcn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfimfnl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkdasrh.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrohenb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlllchl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvhkjhp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdsccy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkcaemt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uahgrwjo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmnbnit.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpttlrsc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2bncuoyho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxbbobn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxovjcy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jezgkarm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngioxbsn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bakbhsap.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmgbxp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzqgdmp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hayiptkv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2icusxxfa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2maxtnodq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tadsaanj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmkrsoz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgerpoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vccurvcj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oujwwifo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvwrckv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgtgfdl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgrfosu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mckltlkm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrbuhrs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oovgcupv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrnkuvo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxscvcz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oggsryrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtkrrvt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrgthmd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqpshmf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhbfhe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqjqwak.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgafoef.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2axfhljuv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjunzen.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2djeofsbe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2galsqxqw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvdijcm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2njfghhgu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrguujim.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2plenlnus.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrjcly.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2cstonzdv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hadizond.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hexxvgaw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeukpqr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2panppumt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcpoegt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2svtlrqvb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsafqsgh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwccgcjz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxguhkip.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwzdlcl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rggtlnar.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kacdaniz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgykbak.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbseqgap.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffaujim.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iplbholv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnvipta.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbmpnny.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqmehlb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyoiqdt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwhoua.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2crwbkhev.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjfeinr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyhxnev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhleqkvh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2msdhobab.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2iviajsuc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxyrjbi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rysunpaw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2atvmgcep.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bwavommy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2esecugjk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsohlnp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2swzcimnf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuzbkuy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rttemfzj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkzgpip.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgmnvtl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwkicrw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wagtdgnu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eugqabrr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxapldy.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghgsab.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiexjyj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttjjwu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkuyvoz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaslfvw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhezntdp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imlowfgg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pupiodoe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rrritwrx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjpvufx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2afhywxuo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwdcefa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyyymqc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwarkkl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2edqhfgzk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2civbbkrb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2imlzatsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwnarux.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrldcsli.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2foftdvas.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwmlxjb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjewhwqx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfwhmpi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2emfhipst.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjumyiir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpngouq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbukcwek.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2spaxhlbc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhqlbfy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxirjra.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpqnkr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbksfmmg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzhbowy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sscxeazc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2osejlyms.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jstoorov.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ltehswkx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yutpttsr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzprbj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiqspae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hffwqbax.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrchqyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rggjawjh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzrilrw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aptrqwne.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nypqoahc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxnuova.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbdfstp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtinkuwo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwscfww.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2emuhmhym.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2blwedkxe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2smecxpsy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxcuvcd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wejszqlt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pcoonoed.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iragvhit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2irlsvbis.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqfzqqj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xutsiryi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hneyaoci.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qscmuvzy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvgjnf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2veqzethd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxnoxph.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwhpshc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxuvfyq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdklbuv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhlpfxo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neshgnmd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zutmwdqs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvlubni.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mihmyjok.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyorhzj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2togbcqdc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2okgsvasa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fedhfqcn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbrhhks.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjemyjpq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxkurbd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jponuqii.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeszcxl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pevivnkw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2erebsygn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zduzkuta.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwueaff.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvrtbir.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gihkpmbp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tvumiopc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2unygqprl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlpesov.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdfauex.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvuaitb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hiejgnst.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyybfnj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqwteyo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kctehqrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvimgwh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvzspqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xssafqvy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlbcska.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxfdrdq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiygmdt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvjmbtf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwqgwhf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjczsise.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2elhworpz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxbmddm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvinrhey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcfztyd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeyxhnr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uusdiiar.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqwlelq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfzuode.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprujkgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tinknqte.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnoiqad.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwnyolc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhczcnsb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdsglum.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tudeywlu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oekmkvhw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpagafj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eonjcmhv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdbrkrb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2elhcakdo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2luzsgsmy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ippwmcku.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrhofbs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfhohqt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsyhzdd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqicdzzc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbmhgen.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugggkgkz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oqipauaz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kddqxkll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fegwbmtz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qngkudku.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2evkioyjv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hheplczd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewomwchs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wimhurgy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqzsfxw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcgdsn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjytmmx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjhhwco.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tlduawyv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apfqosgf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2daxapewm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdggfde.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iegdgevp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmesowc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2otkihyky.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nptqceya.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnarvmu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vyecsxsw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukybsesb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgnqaco.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaaigcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rncdxvcb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cpylqkwa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfpuoro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hotyqpdr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sribtzuw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyotsuwd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzujhxx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2uoncymnm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdjatna.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdditofg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ouftqdfy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vshkfrbz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bqexslbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zidwjytv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjbatun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhawcmm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcsmaeb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsjcucn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjozrlm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2guwvlmhr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsleahv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ukguckki.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvkxvgk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hykpaepu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwqfdby.html


<!-- 参考信息 -->