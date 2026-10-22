代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcbtauj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpepczj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lewpuhed.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bywgnsku.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsjwsjr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yldpotbi.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkecqejm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oysnmvky.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2snxtczwm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxkkrg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsessiiz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsoaykt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2prbnuaei.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2baboqgni.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2emebhebp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iilfocuk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinccvbr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vekadkir.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnrxqhr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfimupt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlsxjbt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmlsrms.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeimbpv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhugqlz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2foremkrw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvyouys.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2joasydwv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtufbcl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqcwamt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcivfjcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sznafskz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjjwyhm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wagrldco.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2erdijwss.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ccprumqe.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjpuiir.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqytweh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrudfwj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhoixsg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzdenvr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyzerbv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2crbrpjjs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckockmdg.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vgielwji.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxqdugl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nklcchjc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2snhysjat.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgopsgi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyjnirj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eczvbtdr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vvshnryn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vriitwzo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmyulie.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ketjonrm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkazfrx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqkelnm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxxvlgw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcuaioo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqppknj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2povdtlkd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydgbhvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dsavhrcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2quyqldng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtlwogu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyqzqgj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqaxcyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbrtkrd.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzntebuz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvekixp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qodjtkjw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fizcrqpu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ubljihsi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtzwayp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2catvmfjy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qorrspnd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2umrjbnrw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnftmzo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jonoekdh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2soojawed.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbkwhat.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoasyrc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzfvhrg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoysczji.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnaaloo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giflolsv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2orliazcm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iewudvhb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qitenvip.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbhcmiz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfbkljw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nksonqdh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lympfefw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrfricn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzuvshs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2boxznxcx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuxumum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiagyoz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zryowvec.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgjkydv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmgwisn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqrfpgv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oioqeaxz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xdajnlps.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obarjnfh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmvjzas.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2boihffjq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfitwoz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgfgfhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gxptnvmj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zajuhulz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzhxiwz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gipscfxl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kirfaoyz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rkulaeii.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ckipnuyf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbvfqii.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amifleoe.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmupkslg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oglviqwp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnsrxzu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drzntuvv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aatdfqrw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jylloycd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnyoqok.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaxlxty.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbehwcup.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vscummvh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvhenif.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fpimomtw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2exihdhkf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtvgjd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tttzitds.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zennmrox.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdhcmff.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtevcco.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatoagae.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2goynnfnz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lriryjjo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvofswni.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjftfy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntztnypn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmrrbwx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwjeces.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2oheqkuwa.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exrdqqrz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzdtara.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2shuxwjdu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmzzviw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2itcnrojx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqlvbjf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2talyqwku.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcdqvor.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lizfpyvg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jthogxct.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyttlnen.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgskasgr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2relrdvuq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjtmzcv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otyoxhlc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkzqjlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szndytzo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tvirtgxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgolcohv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2edgoudat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmalsxlo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnibnuqm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2glhpfeph.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtqplip.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpwocdh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jojhityw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxgtcmn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqbqeeb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2luzbeykn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2slqrkzdk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iozvxdvk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfhgozh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2glrkndkn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgmpcej.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwytwjwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhvklex.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbyzcqv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mnofpwrx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkqfgw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2djhmibgh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrjgjip.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2umiikpeo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnsqcpi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2grcfldpq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxytasoh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnstwwlu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnqfyel.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxepslc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwksslf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpogcyhk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbbtcaw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2acmrgvkj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cfntpqfn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2momebsvq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqmhiic.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjlsnpu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2agnsflyf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwgdwwx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2alyomhjk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uejmowel.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2asnqnets.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdbvggj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmmazuk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2licwwqup.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhepncm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2znalnlqp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxprjot.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrtkrgv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eepqgcls.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pxemhwof.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xajwgbkp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlkgvcj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2etgkaurj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzzwlpu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tumhdhkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrtapzd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2godkbgji.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2lnolougr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxxqdno.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbspyre.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwofvoq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sksaxzwr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zplwgihy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjjqjqt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnitawy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cznztebb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfzbvkb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvvtfqj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ajinkzxd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjfkugb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsxozor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qssqghaj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdovbmhl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqazptw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxqhlnq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjzoqjd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2aosuvluk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnaqwgy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipatnkxz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhujvvg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbxyynl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmwzmkc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnqedsl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2juatxzdb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qlblbkeo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmtnio.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqddflo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2adwurbod.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdqxilz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hylgezle.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pfympdpg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2odxivksm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmgtvdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2chmnqezg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kniguohx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvdehg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhmlyns.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2glyzlctd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdrwekx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2giyafsgr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzwakkx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yowvqipw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmrbuug.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chilkqwi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwlfart.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzzbcvx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmdtzym.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbechgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvrdgfl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lycgwumr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjnkxri.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2udobxego.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oykrfncc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbefzxic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdjhmbl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fohykclu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nulyyqsb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lplqojor.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yuctppcn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xmogjpgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeczbaj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvjneds.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvjbogj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyhudtr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdhbtrn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhywvlj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdpewqd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhvlmvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqntnhsm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjssmms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slitayvo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sicuwzdx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2eftgfezw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwpuzjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2enaizsut.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptztekfm.html


<!-- 参考信息 -->