代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uguugxjj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaffgznj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxzvwfv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyfjyua.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkusytqb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2keezmkcm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuuxpim.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrempul.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwrdwmd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuqtfzn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2myzkxzov.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fayjksyd.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vunkxbve.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcenmqqr.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxwoaze.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsprjfw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2acdlzobx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxlzwpn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bxitkpph.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkovafeh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cysuygex.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pysydbsj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpayxmg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmgwoeu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kssiryne.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlmcfjn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvzqztj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2osnpyptd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nokrsupk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnjzwyb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2urysulul.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfheonh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2harmsgmz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrjshoz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwuirgl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2talwcnbr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbqpaxy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubodoydv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2inycyvhu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kmettmqu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvvdnfx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqslfdq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yubnyjkq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2epafdcuu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2oislccim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfyxgxw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyxnkvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbyqqlo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjouxz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xawunbex.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrsbbaj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cunpdqqj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbhqacq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzxgzbw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhvcmaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapdoggs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbsphqy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2axgnsitv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvumfcu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbotydl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2osqmrtkl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoexjrdg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwonxft.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgyixg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2soikysqu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2obuqwieu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqcbqft.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2udseqgbv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbnyxlk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnfgexl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zscsbztg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqywswm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxzmxih.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmgdmct.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjpjeiz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpuadyw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yezaqkxy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvlinqw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2skaqmbvk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukzwrrl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiykalw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfchtsw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paevqjdb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvoxsqz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzngqus.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnevyfs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgailmff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyndhie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrkhzye.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2roawaslw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbmoskh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztyrybc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjsnbnv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwwszic.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cudlcauq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbzdlxe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkxssnz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktxjqbm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2msmnekhx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxgkeoe.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2naigxpei.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyyilmw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2axjlqrqd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdxvytk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dngyxeqm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2znlhinzg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yznbpdyu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bavfmwsa.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxvbqzz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhypay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnjgidb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2eehywjtt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzhcnfd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvlwjkq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyuowtu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aofsgmdp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxvdywu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2svpskxol.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcryqvs.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmwrpkb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtdwcxo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2geuijpgd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqituj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsluiyoq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iiewubfo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjsvoll.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiojfwm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wropqoad.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbkilcz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhlozzw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyuknqq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emxjhqcr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gexamaei.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iijqvdoo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhymezx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2whgifgns.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnjdywd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsxdkha.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiphtbl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcpollq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqiekqb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuulvpa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdxdpxd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdahusxj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2efhttjdq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fitonqkg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jeviewhj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdghdgwo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmwnfyz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtvyhvf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqiqlzq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgmrnbp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcsggkj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cncgrrju.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxlumzp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqejfyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suzmddio.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hroiolkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igkxxswk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxqwxdi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rphzfsbj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iysdwljf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyhnmtj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmdvkjt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2houlnnht.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zregnufu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrctmnm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zbilkvpu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvmiery.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmebylmu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjzejtd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2shhlxqrl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixagsw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrzgwfb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2migalbkl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sjerniap.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvvylav.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwawbzd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkrqsld.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tzahofto.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2djzhtpft.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnnuuue.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkuzioz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwylzoyy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrbfbpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tojjlxmm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2phjsjfcv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2picmwjbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcqdupz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuswgttu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2docdvffu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcdqrsi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2actcdppb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaurzsa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdkxeol.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ncctctjr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnedwtbb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yixqmsgc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsfbhna.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgwewma.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgfnnng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gktnxkfz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kakpmrmv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oebjrrhi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzlfsrj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvsfyr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ictljwaf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qjutgyaz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2phgpxybp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iavhabtq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2egbakjvs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuhfvha.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoegbbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slipgwtw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gujeypyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otggakvm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vywetbzt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2stfclxcg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2htbvmlob.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgqntok.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgdphbv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrepmor.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yasvaxit.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkfpzib.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fstvgsma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwlrwk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiecnbr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcuvwxq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlnhqtw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyuarub.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiqfxzy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2efdxmoek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyphzfcu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjjyzy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dregjwvv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnkcntv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxckddj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfamuuer.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkuecqh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjddejen.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2msfjgjoj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nznjuhnw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fytpttyd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvdlptr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qubckcnn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2paxxgtnz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzldkmf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bilyogwv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsahlpa.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mplsumvy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxnwbje.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnspvnll.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyuusxk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2spjgupzf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cakxclss.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdkesqe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxrolt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrseowy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoviugu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyxxglk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2htazwmur.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfjojte.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmaqoio.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czaydjqz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2akgwhimk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdoctlj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eurxudyn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eilqrdis.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2piagopvh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psodgdei.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhgpyfo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjgqht.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsificp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdvkbhj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbddlxup.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdruwtl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcduuug.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fygxswzl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmcvrtw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zwywiwlx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeksuqk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdhdqoj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2awtozfta.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdqjnik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpjvzrr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwpeqmm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqznzyhh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvdootn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdfpiat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkmsnta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emjaxtgp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcwwxyn.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2whttifwa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxzlhdw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrgbfns.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2miwbqkmy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjthrwzu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdfovax.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ranbngym.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2efxljepg.html


<!-- 参考信息 -->