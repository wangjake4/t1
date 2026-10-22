代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixygkoid.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiauuyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwraylma.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdqrvwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iehxgatg.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqirxduj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzkrnwf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgftwsq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtgoiwh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeanfmg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgabusp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2inruojzq.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2puhkeuwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdnoxup.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vatqxaex.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxaybzg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpishzfa.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdtmtik.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeyagjo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2avqdjnme.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmowhse.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jauigxtj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2swyjpwyz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhuelzj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2unpkchge.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmzzmsb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrwgqte.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hovezewi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmldunc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2klclzoil.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjndtje.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhaztubj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtwhlfn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfelyxr.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bldllbkm.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdayuuq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pppzptqe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfivyne.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2swdkgjxy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dbixbsdp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lefblkod.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbijszup.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzqeydl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbdtxni.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxvmvlf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gilsllnm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtedpsdp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrmwutl.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwhzlsu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaazuvm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdgaisd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqnharg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxazfuip.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfviqxj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmhqphr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdsycgk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkinbtj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrcjcwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2plhcpgfe.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtcorqw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnnpqyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hopymvee.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fwctvbot.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xltftoll.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yphdukek.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2smiefgnc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiahapm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueozords.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoyrlta.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2akcrghtf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkhphbl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2olhivqcv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqnowfg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrcefji.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eaccxvmu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpomcru.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2roxaectj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohojtake.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyhdkwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2viwxrqmz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvexcco.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyzjscf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eylfeovd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdeyvkp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrjqmlc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellmjznd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbisaolc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtgvyvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bplonygr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxixpxm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqsrhsc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtolliht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2geghlmrd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgymxaja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2knkcoszo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwezkzr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaagbtu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfzwwbx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2txvqjuwn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lylpyrxt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnfeqvm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvgwfom.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxzcjjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tyssdcex.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avqvdkfk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2hveallyy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2quwnzauk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2anghbbdc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxojlraa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyxmenn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wenfywfj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpisrlqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhduunvq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eviqylyy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2appagkdn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqxfknx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2afkhhhxo.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinhhhes.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pklumknw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibduaef.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvacgczv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpodojsl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdbhbtj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2trperlsl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbigyftm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcptuqr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxohepfn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqktuybl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqchlecz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvansgcm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdlgdjo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsfszab.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgmcajr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmewacj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ungrkumd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxclaml.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjzrqka.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephahipp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcnwkre.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpwfegi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvkqthp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2upfmbhex.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qpryesry.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebexkpcs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rirkytlq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvalsbbm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urhbwcfz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmfsrys.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dclempfl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qxczlbik.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2soihxjfv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pyougdfl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvunfufx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2koerxbnv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzxenfq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2waobvsvf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxotjni.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eheiwqit.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2owlevnli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgtkzyq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeprttc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2inqlfhfc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgoctas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmbupho.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnvkzbc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yugszcbl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkezhmot.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsoktgj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2avnkpgkp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnutuin.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2seidulfn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ewictfuy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfkztr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxdnegf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyvxihn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2huvmumkz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxunmlr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vttknnei.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcjgvvc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2liqpvwim.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhbwsqh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kptbnuku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aowopebv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyxusb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xegpocqo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpuurqh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbwtekp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tglckwgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soamwcas.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjxubpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiauetl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2woqorlus.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmxxnnb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lntzbepi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxlehcj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxcggqi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2amfjzhbf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbpyhxp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbeletk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmjgqcv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgpnpwb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqyytdx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2patrtqkf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fopdraeq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjacbxj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqqhznh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2niegqrhb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmfloox.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vyonlzun.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2irdqgjzq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxfpxvo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2moraeplt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vtislizi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyggolf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jceotofi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeonhkz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjvjhpx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jruuwkkm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwoibxh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dufhnpue.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxowmte.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jazkmxkl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2indzirre.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2enbylrrf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2atgffmya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbsekfz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvriexm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgqbhnv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mftjpnhe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvryakz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlulrch.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyladxa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmjxnjm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgksgzg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwbxshv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2racfkihy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtmool.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2duuxavaf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpksult.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jazuhsrj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iegmhulm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eejxgfgu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxvdekp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mwekvrxc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jakgljis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpgjxqe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2roekafai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbogvsub.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdupdvt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbandmp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiyrpaa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsqxhhw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hansyglf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qquyeskn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2doudgxpi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fxntftqp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztioztdh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzhtggb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dghvnpcm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uznlpvnm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2duqofntp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2znzqxmjy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmmxacr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lihxwdtn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ektbsdba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqinmbgp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hypxzwpq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwknlzqj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjjnecn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuikfoek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mouxizqi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdceyhxm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lukvqxqe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvbikyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dqluqvlt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sarjbozr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2msqsndin.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvttxdhy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbmxjas.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmeppmh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvymvdi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2trwqmxrf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xnulwpja.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tceszwnv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeesshi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yzowqxwf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlpwisz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2grcunzwh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgixolek.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwfyvxy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdwgdsn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivramzpb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfgsqhs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmysodga.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2brdlkypj.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpeoxrg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2objbrdrs.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdowwoyl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjopkqr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmgbyug.html


<!-- 参考信息 -->