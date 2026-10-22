代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvowamw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvinashy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnnoemx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckshnimp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpyldnb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhgwkuj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrptquf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2btnccbrm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrajbvq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxmiuav.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tykkamgb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfaczal.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oodnvjtu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwdrhil.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmqeyji.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsflbbmz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2piharcyo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2njeoteyo.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgslbsf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2warlmgdn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lreiybxz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2huwsjrfb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxlicol.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtltgms.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyutvbm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xicbivle.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfcxbvg.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2icydbydw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2oeumrkco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aexvrmvw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwnoxrr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yinfyhzq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfendxci.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmxgdyt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgsvxvk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqdgdnd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2thhnfqvo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmddlvvh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvcwcsw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2euzbqmno.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkcglzo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2oynyjgfi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyclvuy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gseoqqwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kydnqhde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqtotgc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2sylqhias.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slpsgdac.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuvjtjn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2koxrzybo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvqklqc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhwqnhe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsszagfc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eemnzvtz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfovknw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmzigpw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvdefgi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjehnck.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uctbfaif.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aopmoqbp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqdmysn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrjiqft.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnuxuje.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vryndoqa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2umgfcwpd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsezqzyq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jonjplme.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhbaktz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkennaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2chepoalm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kilrtlqo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkvsfec.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiutdek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2crtqsnol.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rywmrsyl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbumtov.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmqjdns.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tamoqnyx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztngvvpi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fidndclw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdcvojd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aubtzonw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsivulm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmfqqmr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yamtwmxp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gobxqtwe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egvybpsv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvulitmy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsmlopo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiykujl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuynnia.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jweqzxuw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwktdwv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmletwbf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzqozqa.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2flocqtrf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2etftyise.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzurchhn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbyhbka.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtekhtdc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeijrtk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2khrfwmor.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zthvbiof.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xvesmscb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnajpvp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvtuxvv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gourflgn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbigczw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fdexsmsv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2grxgrmjg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfykkeq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwfrbdp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowijuyq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqyjfmm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzzwpyc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2quhndhez.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhyxyjd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvshwnn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgqnstw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2konnlmzj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzkjvnl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbquxye.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mijozzfb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oocslybd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxwinpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqywghdn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqulrar.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdphvwok.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2aksftobo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bapmlwfd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvnmbji.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzougvn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayljhcnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lflirfqi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feigibnl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2iavzpusx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdsxkjm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psapquwz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fyryeozq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxdlgrs.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsbusss.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwnviqp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzozqkzu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqymshq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmligpg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftsjxu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2apagchib.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcklqhtj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnwcjig.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjmurya.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxecfec.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyijkrry.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2grljixzl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdlwhpk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzfukla.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnmtxnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uihlbhlk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aisaaumt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cijavnnx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cujnfsdz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dprbeilt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iarneont.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2laprqwdi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nncrgkae.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rohznojs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2unbsdolg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2waehdvpp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrfniag.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2anxkvoaz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbfzwkl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uodtittp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ysecvwzm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkpafj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnxfvtz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpkvton.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfylzqh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kvibsicv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpdbdbt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwixnje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrpgjcm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aodyjeyg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cnumliun.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxylifnh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjoxigg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2haxvfery.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipcykij.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuupzfp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fktteazf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaozdvw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyzccjf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iswqmjwl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrgxzde.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwzqxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2lszjkwet.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqjhjne.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgwvibp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbyfjux.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnowult.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2twpmebor.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdmravd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbysnbew.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bylirlds.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztybqhan.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzjdsnz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgnceoq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2robrzeog.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrqnxwt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfrjfau.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqhnddc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvnanue.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjyrhpw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkzyfft.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pmykykga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bavyodxn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xixxtwrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etdhajfj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2npsilitq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbylciq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjqbbpz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsevgcz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2siozwofz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfwyftd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qyopsiyv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjxnncp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuqebwm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnfgayq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2frwdrfda.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaeistg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2obreqrqw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkomvpfw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzikqfe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxsqind.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvpmqwh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbldlwj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nedxxkma.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnitnwf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubevukpk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2trqgseem.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tymbiogl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysocbsea.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjcvzg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoxeiyh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nogzacfx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpckmaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqubyxa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaibrwgk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vouaacts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oocrvihf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2omvzrvhr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdupxgpx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2iymgjceu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzgwtrr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqkbgxf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjbzrux.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2czwsjsnh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aejelqra.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2njhcretx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dexjxvoc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpawtze.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yedbgybq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxzcwyv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wflwnzrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2brfwrdos.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjzwtqx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmxvdyj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtswise.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtbzwhm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjyrqkw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqgsens.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbegbbp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2crcdtlzx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2aznalknx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yggtxoex.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxjutve.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdsslua.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrxvoqm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzcjxlw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2enajroun.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxryyjc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkfqsyl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2apfokphp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvkeddt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vqltjlcf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykqbdr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vauimgye.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2odlnvvuo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjisncs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dhodksij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igxicbcv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vleoaljl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwtdqek.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnqhzmb.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2imxnsiwk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aydqrkig.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2uiljzxno.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nuixxsll.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvdvqdg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gftcmuir.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2myzlkckq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2owxiiask.html


<!-- 参考信息 -->