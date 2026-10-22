代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rozbvcsf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjieksgs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iivyhzza.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvrzrut.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdmvfvr.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlvalfj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2keklprjv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bhamflnc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtucoqi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2anbmyjut.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2glftfrno.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaszfigm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uynfuagy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgzxwuq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrybzw.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2etynrnqk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtpmoqi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cchbktik.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bizzexvm.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ngumfxzr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnvozae.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqmrhzw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdrhtqu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkhjloh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbklwfzd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtomgflh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2meqyterb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmqpnhn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2txttuauh.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxcpqok.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2oaojlpgr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrdvkhm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwmgrhz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizniov.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2plmdsrhb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfgbzvg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxpvfvh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lubbzcci.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjayapfq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibswojti.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fueonxao.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmabssn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaixpliy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnqpeji.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozojiv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lykzovsf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gditoldj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keapprse.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrjperp.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2seyjkxuw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbmqvgo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zusuwhji.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jllbrbmb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2petsbiod.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2urwihkoj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xepmmegy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dczvdqgf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2faqjvlmm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvoyclm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2oexwtnhv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskntiu.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kucswkef.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lihllozi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jclvaznz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhxivqq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxwxlgq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzwticu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlunwhki.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtbjpcp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwhnbs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnriojk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2eakrqkcy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnuatok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtzxnqf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nggkdufz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlihwnmi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdywrcxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpvivfg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iesgtuvr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyjcqdi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkhlvoc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcygegf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlrzoze.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrssekf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2exswkawt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoraxhd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiaondy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdnstvw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzqamrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsuzlnq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhixfyth.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqzazvg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kjejqibi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkfknls.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2taaanzmg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kxypxyrz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaqcidn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iprdoqdr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzdhaux.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2awigshvm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgfegoe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2syeujifw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdmfsbv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaogbyz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vamzdsve.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swsekona.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2syltvjbv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkjyfgm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqemmny.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbegmmnh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhoxrlz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfdivnx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fedfakta.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvnwpvq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qthqwvhl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdksttz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtefzobo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdxxwo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqudfaj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgjzyuy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyblomn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtrdfnn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2edbrkric.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrdaua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuwwabw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2unbvylsd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2giqywvjs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xenpylmh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zczvxual.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2noxttuke.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cacwqary.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmogwnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsrkrqz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oettwupo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2svmpizju.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ppchakim.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dauecsdk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tnublnah.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mmalsezz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwazbogi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkieuxvb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2helmrapu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoymook.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxejuqcj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drjbvmsl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhleari.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeskuhd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yqptpiuz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eekzmhid.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hltxwuvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lozgpbbf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aeewuupw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ihccshcm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ccukcrpu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pulheczu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyikopx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjufyajj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjpsjed.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gavrxday.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvwupd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaddjgi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fopviafm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xntkylfw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2adzjgiht.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavopweb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqumgda.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhwoguv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kikyucmx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upmnzfer.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhiacay.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2biplzvaa.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjqopjj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kwefyvel.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pygiymry.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzbdime.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrulcygr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbwfhug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eblplusg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wklqhoqw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtfhpor.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfbyrqj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcyklpr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqluhte.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlolgpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiejinjr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvkpazz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjepshdd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyuvngs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywabeqan.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2izamejxb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2baaxyqjt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xivkqerg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2euandjgv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lolgdwtr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefwojhg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjiibnz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rselthzb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2abmcpqym.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2esgfgrjb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdpzbbw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzharhy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yutzdczx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwjknpa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhidxpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gcugnjfl.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfrajzi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mefezyup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrrohcb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bodawefu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdfbbgo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvwfsmt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnyfwj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiumyar.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxyvdyp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hiezqwhv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpmneew.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2engalerc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nitnawau.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkzrkrg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2avqdsmeq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2noeuycyc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfgatu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bedbmgtm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zrapkdzh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnftkmex.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ughbrrxx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zksvomcl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajfltiq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtrgxe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoelzyt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwducxc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoavvaz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wwslepmn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaflnqvr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqyscra.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdlgwez.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvlxvyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jybludgr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeoserd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgthddd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwqfslh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqrtcvp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsonpnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyadctrs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2polnecrs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjfdtlk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2faxipqfu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyezzdib.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcogbfst.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aypxjxhd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzpipyp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlvhsjr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvaosoc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pppzdnlj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gedevezh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2scscwyco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2aozbmfax.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oungobqk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywrfunf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2owtvxdbj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubcxsql.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnlqmea.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhudjgdj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmaelz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyuaxrh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2neiniwok.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnrdhxw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvwjppk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yysxbved.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrudvmr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwqtrtg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqnnsw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwadcysa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiancbg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fixxveva.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkjylwo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jojutbff.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrxfjwa.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgghcfr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnkcwkc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2svtxrlzx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkeybzl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtgiydg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqonngc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfwfbte.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tqswxtei.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagosczn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqxprnd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqpblxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdhoyho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdxcqck.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjmeks.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsvwpkb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awsbjyjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtbltuv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fydfwwah.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sielqttz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zehnzdfc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jokvdufp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhlvxzr.html


<!-- 参考信息 -->