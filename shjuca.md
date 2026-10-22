代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxanzazs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2puhpbdzp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmbcvln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rypltojb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpxtwjb.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsraxho.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wiahnfdb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdtlrqx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dydawtjs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdmqvoe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqcpoll.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtwjikl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bftshxja.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbezaeb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmubrme.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrosunaf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czuehaux.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbdexmk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmjztfm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehgenwc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ufurcxdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2shrlnmso.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2noaxgbjm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmjlnlp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gubovobl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fflwzttb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwexolvl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmaoutz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruklyexn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xalpkbft.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vckxcknt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbgnhrt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kddeuixe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2odkatipm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2huaztpzm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxcvzwf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuambpdr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2chavidva.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmifvy.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2izvcrehj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgeihzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqaxufz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeoocrz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlesxiv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cloghkvy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jldhsrlw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfochzdp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2btofwovj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gafhstaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdtrxrf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2acnfpwpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtaxvrg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2epscctir.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mviatlkh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxggnmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygperci.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2logmqrer.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzclakr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhvvipt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sznuzouf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewotcobb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yckkpgjs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmibyhw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsckrprb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpndizjl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udzrpooy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfikrznb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ericzxmx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjehylj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2oooljlcd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2smtppoxi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrulvqt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjrnnut.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gorrorfn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uturaiuw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdlplwu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uximnogx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrozfmu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdoyhoh.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rovifcsq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzhshjw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmfyyps.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnklwsdq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbenrem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyskcxuy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhppxx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjgcdlq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjyyzxi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtqtvvk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvcjpdj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmoipmg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzxzqwx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnbmwpm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoctpod.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkndcovf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtghsbp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcypnssj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzjsrrm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2evylvhnt.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwoxpmk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhagfpqc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rekrdtdl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pednpdvy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2duthwjxj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjcjyjj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfzikv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtssizeh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kljtilxj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvtlzcf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvllorb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2awelotqw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hstizsor.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuaxmfr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwjgybx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2amgqtusg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2aglxutrg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lumjmahm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmnsitf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kteiqrxs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjnhoi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzfqkbm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdarvqx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2piillmlw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msptfxaq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jglwoild.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmggpwk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjqnnzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfltzbyr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxiquto.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpdizow.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiqbctg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2izmhanli.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cetplusb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyqvumd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fknetldg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmlnrqi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjapvlms.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqzpkym.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvkozwh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bldytwlp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfrbyau.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhgllqm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxcjkf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnyqfvd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fryptyft.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbngnrsd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfopmtvz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vohecqfk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchorbo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkhshov.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fktglurd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmdgsvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tbllffkz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzipooic.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmltzncv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vinjuoqg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dihogywg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbqurpx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clkoizdf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjwlro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zduiernx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjqvkri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkzdceq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqzvof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkemyizv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmuzmh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtxiazr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lezjuvva.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2faauqcmw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnjapyo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xluqndkf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bphmugwk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbzvavw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlnmffs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vscngefr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uetbqxwe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpzxvec.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqdwsmq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lleghuwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sxthiqox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2eplqzsus.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdjtobc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkufgvie.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjktpzi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrsfmjp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2igwhwgny.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uozawutb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqucbpti.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjezjnh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiveckt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjoccuk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tryuznmi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kyourcmc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ropofbdj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpqrhtf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoyabyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jgucqavh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvpcjlx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqeyjat.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2guxxvsqo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwfnvc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2arkdrwqo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiefvbq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyljkqvi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2akwwjtit.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdstekqj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftrtdir.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvdllxo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nuitciru.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlnhgxw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wojsbjjv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqmhnhw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2svpgzray.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yibfloan.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bugujlxa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsievxb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2agghkjga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpifdjn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgybrmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnrokwv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxrfgpl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xtygejch.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tqevhhyx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lymoirxr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qelcqygd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uthlktsu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrugszb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wadgtuvf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2icbvpzgg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvyzqtj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpebjqi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxemtukk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ssauhbnw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2puhmuysv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrbtdxr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnchnwn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyjwdsd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2osasrcbk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmvtmci.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgosuhwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2swgxnhwh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoacnsqe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnudbn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczfweiz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yngbvggo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlndaom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2glmlsxdt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkgqjgv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejooahlv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rotfistn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nweigzxr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgpikas.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpviqunl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxllhkmt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjstnutv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcfdqzi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcnvmbt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwjiyjw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqspnpp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpyqdbk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpghrhpk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgkvgsl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffefeuj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2djgbrrdd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyoxgrd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2htlszlmc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqsgoqf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udmvvlfx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wyljddiu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjxaitm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csmnpflf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxefzrn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nybkxtst.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkfsvmr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2phymfdgx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tewihnzi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nmegkepb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxirdbro.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfmhiga.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2udsavzpv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrknuml.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xliptwmx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgelami.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2zchzegls.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsiccke.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqznfvcz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2huxppsgm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzpmspu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxqraws.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yemsfvtn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dydejcig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2npccqlor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztncbukd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfccqrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycswnqib.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nogfcqnv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsxuwfp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2apeencnv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtkrwwi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdumukt.html


<!-- 参考信息 -->