代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjqywdw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjmyoxt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2norcuwlt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tuerubsp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2elykzfch.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmhwtze.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpqqirp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pospggck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqtxqfy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qffzigdh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsxbspo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtlewil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvcmhwg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bepfjemd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2arizrsoe.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbycjcu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfqfefh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgdylbd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mabcpyjr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkuycoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtsslio.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxchqug.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaweqqq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijucjjde.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jfywisej.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xammyysp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbpgdyl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bquogtbd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwfoovs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2echzfewt.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqefwpdy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2chuugxfs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdjtlbw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2deqzpzlf.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqkxpbc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtndocv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxksvhp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttizmbin.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpqnhjr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhgftcz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sklphkaz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnghsfwy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpcqflo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2voigyrra.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqjbnls.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhhkckx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuupoezr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpccayeq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qinphggv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnlhgyk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzncaqs.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwcfely.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2brqjkrwj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2taxfviap.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wfobkxpt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhwivsx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfvweux.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2glxtvdxp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxsvymr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lecbossq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lynzhadx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oynvjqcq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwzveco.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iitewlrt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jcukdjdk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnogxzp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkuovmq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhfntve.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qryhctjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkunqnrh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhdiktm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgxbohf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkkhxkn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcdzcwr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuefhsia.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2otnvjsoq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutkbtzu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigjtrip.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgursik.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewpyri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exijgvkh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxjrogr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2euieflle.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2licpvjje.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qetvhsoj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2urprawba.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftblhhz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybqtfpm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qreictla.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzgtza.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bzppetir.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bldyisnk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxsdqrp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmgdukg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2henlaepa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkxvyid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhoieud.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2omhqbnly.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dametdph.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndebdbzl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwefmma.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pirrhinj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlsgfjn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlptrnu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iknphegf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuvucth.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnisvfey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2osvfbtim.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmpybxq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhyvvfr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfocmief.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtvmloc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhufhto.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xknfazxk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyspgvyz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvwkvgh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzztfpgc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iulpboas.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuchizfq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjhmenl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbidedt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbstgyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtormvn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlrdmtn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2usjttnql.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjzausk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2psyhquuq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2plldkljd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxhyyoc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxhbltk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hyswemwt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthqszz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2awnmwnea.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fkavfuno.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ksetjrpb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2keilwbsa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzzjqwo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvxvdbm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoowqkb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2piolfohl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnyfvbp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uedvojle.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gxahjmen.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnblzee.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtphfscl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2daedsbxr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajceevww.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtuvwx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dfryaiks.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdmwtit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2foctenjr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhnvnhs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnkvqso.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xafujfob.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpakazgd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwwsbhw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2funpgvoz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwioqvk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twqelyrm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsealoye.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwfjwi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvyzoyu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2adlfxovi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrykacx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zubpofyt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmrgtup.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fudraczd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfngtyom.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bnogbatg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2olxvbtuq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2djguexzv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwernpcc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2clzhiaww.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nntghzjg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjcwggi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmbuqbr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aexnojex.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczriwnw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glbqjywn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqtohhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kybwbmgy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2berzpalh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvzuwkp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcuvksx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tffqurwc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyidsyq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2fgytnhnx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvmriks.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqmrgqs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cagftfcu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wedinyan.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gporipqx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqiltw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbypzrxt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiwhlgx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjqfbxh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rusoridd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsxxaub.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zptgtnav.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmadeyx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ubefpmoo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvdzuwv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbgwscx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2igmdhksj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdvwahc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjfahyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voajqjsh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2usdkwhmz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmnbpsv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loesyypb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfqtddz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnqbhhw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2htcgubkj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxrmleb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kunwwaky.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gugekqeu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfyuii.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ytowypld.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcucjgf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfavibp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpabuum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqppxka.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2anpiqkot.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2noatinaa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iymutbbe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmocyl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2levcatkn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cahxhkuw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2igwcfwyb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxbsrvc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smwvnfci.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhcsclc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2znppkgax.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pffgqiko.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjwjws.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aoysdnwu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2awqxqufm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utiyyqjn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usqchaun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmymtgu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yawgygxm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qnivbegs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2njbdyzrc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2etdvxnqn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpuvunk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfqbvtb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyznfhr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jqurktpj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jslxqyqn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hdknauol.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2njyaumnj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2piuyfrsd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2unbwacqb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzetoroh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvknbxjs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nghoaqxk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcpfhpw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qoulgqqs.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhotyno.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gilwykvv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvibqgs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2supqanoh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixlzqon.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhxufyi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzjmaxi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkkpxdi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2attorelb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjvzspv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdkvfay.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2auleaizb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyldjc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfsemnk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tojpfwsb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sultzojs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcoamwn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2laylgwsv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tlemsoru.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2miikrgub.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2sootqmuk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2agiwbxko.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxdxvdy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sskdcmzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbklidub.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuirrtn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2orteeoyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wleqkgbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yppithxi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cybezlpg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrkbwqo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgcdpyz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqwnnxj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsizciex.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lncminyz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nylnwswh.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2otqsjdhi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2umcgacuy.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiiioyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfffhixq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrvqtgv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrjxdli.html


<!-- 参考信息 -->