代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlleopc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgnmptz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjkyocw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2caqnpcwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvruihhf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqncerfl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhxbxey.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyrpykm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrylvvc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrdzalt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrzgete.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpvjqif.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2edecodcs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2solykbow.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdgregq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2llhycoir.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrymjxc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jckkaoqm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2aegzelxs.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dotiwjmg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2egtmpnha.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqlzxmp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2svfjcacr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aklumqwt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztcjnmk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcfzuon.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2czwbzazi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwatngk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwogwai.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvgfrwo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2efkcaiby.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jppypmzv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2exkjvaix.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjcrbvd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vczoqojk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqysxdl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ranpzqqk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnypnvqh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsmejic.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jybfurpc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyzyitr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bygtgcxl.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwydabdq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobeizo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxqsvbi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2enalbicc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vudgyflg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgpdejv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxpvrgp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2rscgyjde.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqeozb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avteyooq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2asyhnyyc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyenvqr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaddiygq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmrhnfr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2llrlxkex.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxktabe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdknmrsw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxqozej.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2abseprtk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jargptbw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2setipgns.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdhqdqb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxegztvc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjohfir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tviqaueh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtejrdh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eguxdkwo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2blqilhfz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkazpzq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcccdso.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqhllrx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xohcvqre.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcnenfy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecxizi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdunrjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvdmsuz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2inltrmkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeexdnwk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uudsflsc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvqyqr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwpshcd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlutdlwo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tckpjyyh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtygrjrm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwfcqxc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxpfgnq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhteyzmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmioatho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iambqalu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvkbbqa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rujzcwea.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2obkthyjw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoiorvg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kigmjtxg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsqdwum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2efatkhmw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mziumaan.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pewzkhmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2znhmdzua.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2atlygugq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hftmfeng.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmwwnme.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzpbjc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmfpvkb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wjolfgfb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2akrjtwiw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhytqts.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwcnxve.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgbslfh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnajaium.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plzwlvop.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuopagde.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onwhpswm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjwujax.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2oupyhujj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjonelp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcssfuxw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxelewlq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzkipya.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyktqjir.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2utcbhwyf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yigaahdy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alzettcq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vomaobcf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sirfxgau.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoprukf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xenokaew.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2arrwjext.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xqorwhlm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmbvnzg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzekhdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrjmfqk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjfxzeo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cqylmrnd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdrjust.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecribgmo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2welpvhwi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2naqvcjyt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qafxjwak.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zsforafr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2agpldrxu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwjlrbz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvpwvli.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uocdlxfn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2clccurbt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmxtyoi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvfpdnk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyvckxm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfcvytn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmoqhn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcagici.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpufrovd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhjzukj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqufuano.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2enbhloyt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnmcrmc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2limanral.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sezgjpkk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjauxwol.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmmopwj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgqduaj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faqtnvgg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2csdnjnqn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqqkryh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abuhwppm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2euegzxvs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qncauakz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izkpnohm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjxfjxo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgajpr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fipugyal.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2primgxku.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvwzype.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aowiqzpx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pskrlqnh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uqatljyv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2emnmxjeg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfojjbyg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxsfln.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2poyijraz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiyzxze.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wibjuepj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2egahizzg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvatumkm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmlhusj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rumakper.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2homfdyzn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2iixjlalc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2varwmdvw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wfncrwoe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2njqhlwtb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbuasdf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtliefr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhqyvdn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxsuwlb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxqkryy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbdshto.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2blrrxyve.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2szgwwoja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkfnptb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zxivehox.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2olndnwgv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvxeqml.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpmpaya.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuefdcqn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkhoibu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjshtdc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvvgydw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbmvkyw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmxhznd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ghltuazj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2thdlxkip.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkjjrku.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2avxcjhca.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdpbgqh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprpazda.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tflanoja.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiouimte.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhaczob.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyprhwm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcewdctc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsnknnm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2knptliyj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcjyjii.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjkkxjg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2oseldkps.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgwzpwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxyvdpk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sasucjex.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvykvyvx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2juvahttj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjrpjku.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2riexpjdx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvfdeuf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oanzwiyg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2itppoqvm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtarujgf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhwbjqz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dampemag.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2spwosvny.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhtxscn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2eokionsy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdapep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdisjjmc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leqmwgha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwurnous.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dilzpknz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oqagrjjb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvdjkwj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvsdna.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbzklvl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuupfoze.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuckvpcu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ijquylpn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgmkvgf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcwwqda.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jidfhiya.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnehqlyv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lybjdteu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kghfltrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecctmaor.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaqrsex.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fylcsjps.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2schtfrzn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swyuoavg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgkkjz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zofzmxpy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2txofhvvt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfmixlb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2apbzyjaa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuowcci.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbobaxhu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oofgdcaf.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkqizwj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2onwqhzsn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2orcfxnjy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtjluoj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzmxfxa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwyunov.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkoogtc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2omkzjwhw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjmocpd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jylepchm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ulstuecx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgtuzql.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhxaovx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujilgvk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbnlypc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyrgsfn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jzazlgex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqzsckj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjezfdj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2przplscg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnauzpau.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qljeqezb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2todgpcvn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpqkukz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqbbbc.html


<!-- 参考信息 -->