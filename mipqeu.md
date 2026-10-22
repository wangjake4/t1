代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sylukfcv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxgsfbd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tegkjoct.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxkgayx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxkdbho.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnsqszs.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxiigyd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qookzluc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtmydml.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvjsdqp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwymxke.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2arocmcte.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqtwsyc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wejbhonz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uepguebo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2plsapdzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiryobm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxexbzdw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwbesil.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fndnfpwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqhbrej.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgogeqb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ptviqltj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrmpaqi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2edoxkmmi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2alrkzgff.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwlaqjq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fojswgjt.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjyquwf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2weiektzs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfafqtk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqwjivi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxojfqxx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrrnzuq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2waynpope.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvpsydd.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftevgivg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcpoony.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbwwwtv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfmgedt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyofpgn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2soxovxef.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abehwyhe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpozmye.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkjvvdp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcixoba.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaqgfip.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iupmfzbz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfuaaif.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsarsxk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tybstydh.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bexzptpk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2izxzdzzl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2byrloojc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2axpqslsv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vdceewko.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibppcknc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2arzigcyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxxmyzt.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzugkwp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2farxstvc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjezufyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ludboxdf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rojfvpnh.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzapdqp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2iojehlhz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbqrpgn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxeekbe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2oyymwvuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vipqnwxa.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkzzkgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oujumybo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxurgvuo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwsksah.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vokjfwsh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dodecdhw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrpwfri.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2apmvwtyg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2onjfzrsh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdinlfhd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzlwaza.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2nimpxxxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hskpsogy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tifreywc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvmyzy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apuxmugr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkhwmjt.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jistnpil.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbxeeds.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2giltttno.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgunkyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gibgjmoa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2sbilquib.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gldigfxe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2thancrzh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrooyw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qreppgpd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tniwluor.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmtwwu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkatmir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qctsvmab.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uonafvoe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaogtoon.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyobshee.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2syifoulr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2enoociny.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyragytb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edesnbey.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2emkifscc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2asovhqdx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcmrsfi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuuxxah.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roucwfrp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpqwttr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmcikur.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chiysmop.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzflrcnb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2twkhughj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wffqpcmg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2taiyczzx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmhsatv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gntistym.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlbqzpb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhobxnk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvtcqvx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqjlssk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmxteom.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfmttgj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2femdssaf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eezjhoms.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pugcvvzz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjqwlsj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2grrrfdrq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcfnpsh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbnbvlm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbgvxdj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zafszcdu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sszrcwou.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjzhkrc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xttknzbf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqebcjz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvklpqh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbcjjpt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kukwnpbt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpywqo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2swjwjqhj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtmmtmb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bltdieqx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sifasmdq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyvgtam.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuiktqc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2osaovvzv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2treweupk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2emvrgrbl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyhbirp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzladvve.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvriexvu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkzglej.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otpivpke.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2operibzc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctgclxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtpoaqy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pvipohge.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uoejarxb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sofcjmqv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2woyznxka.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2slqabocy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fglseqhf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmvxmfu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bizmyzjz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtmjzyo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oojsihhk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfrurru.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcibyqny.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2edpgpvgj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqvinsn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dobwebvh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2govbfigg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnywmsm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaokkux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2encqttjg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yoelgtez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afrsfwpd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iyusnzug.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mizhbsjb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eusaupbp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qzasupjq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tynhmzgj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdbfiqz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtioiut.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeawpgt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2eurcoohj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2crlsybpb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrpvzjv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zomusnep.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iojtmiev.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umcwviah.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsabnciq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sphwoiob.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjagdvz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbkdpko.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoxvtzg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aargffqo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxljcez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2urakzhps.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2blpyeyfc.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbcwyws.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkofir.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mipbllmi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpdujap.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nksjlbcs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaziqdsd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgvbfym.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvmjhtu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clodbhvr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbqpcla.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rdedxwpt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kagbbymm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhzntzz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwxpocp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsqjnvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2btblepnm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdympeyn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzjiysf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpfzbht.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtzryps.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbelsgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqxyrov.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaairhy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcnbldc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiptagle.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2umvgmvpz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eohctgng.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtyzeus.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjxmbtm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yucspixv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjczslk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xayofwqp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tciypjkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyhvqty.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nagjrwig.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2midjlczw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ueaodenf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbplceht.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhzssbj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfsyywd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtnsuxl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2amgszuie.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrrpmxq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqgesdu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyenoqv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfaxqwg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zntfqnje.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkpjis.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hztmbffi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsqruwn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwgsvda.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqdulwd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytitunis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjwodwu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoenxhro.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpahlqji.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxanaaff.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2myrafcsg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqscbqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmgsmkh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pdthtjrn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2twujmymo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvjqnqy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzkikfc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdamsnt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkukav.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kttnqysl.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiawvmj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2phryagcf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2diuzqlqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oenswovb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrfqsue.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvtwsrc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjzeszf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcsgpsp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2luwjrssu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdfqbwb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrjzijn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtayhgr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmfohbx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2onfncdyc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgiqodi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyggxgm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhevzgv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpamria.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydljiaji.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuiokfx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkayjvf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ksilgejc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xbscpmyi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbreavee.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvzpbqj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcsrxyn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdfapcd.html


<!-- 参考信息 -->