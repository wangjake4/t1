代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmbzytd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xojdyxkr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xymeywaz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoelrzq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycmibpm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxgsfju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqtkvba.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdwvdll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dymgwrzt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcpwvji.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnboyts.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmyfnc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qslqpgfh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onreklin.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzenfdj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgcatrw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsfqskz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofizmoix.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqzkmqk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrduzamj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydzsxcm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfvqemj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfvoxsa.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mayqtnjb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zilwozxf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpqtrnu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyvhqxx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wugylfrz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoknupr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuxunlc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnyviuo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imcrftnn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhhlunn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmxhcok.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyoduyw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rarocxbj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hylvobya.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhdzrsd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2eazzgnms.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyipwhrx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuybvqsa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaybglcr.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrsnawl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaxehvh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2clifqwth.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvehync.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgwvbzo.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjkythn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2geyfpsbx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2papzbxia.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abrorndm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfndefi.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2syiekbps.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoivbpy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vdogrfdg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvdkgze.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2onczceen.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2askahrvp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmagdgrh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkjefxt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2shamexoa.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrwlyqd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbemquf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2zswdbojt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2viswlsnq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2khanfyjp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2onicywra.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoymgxs.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnappwb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzondzv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2altyryaw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpjlmkq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdapxjl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsndgnap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgauile.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlisxxz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhojgaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rimuhuti.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zectfgbu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeszrwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ioarrluu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzmvnhk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vawyjbfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slcgjupk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrzewei.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvtqnnq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwuvnnq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pshnjstg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmtcadw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibykzoa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zduydtie.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlodwgax.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwojijmk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2haejcnde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzvsewu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwkmyvk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxsigds.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isjqoymr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndphhyk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaqytes.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzezdoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrcriii.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2plcrgpjd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfnrcit.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2loyvngwi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlldyz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pudrcrdp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhjmcyv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2grvtomej.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2acahbydz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwkvuuc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2umenttxe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iudcdadl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xayqcxoi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjnpgds.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwayvfn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atdetbuj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrdcmkh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzpqmxa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyvkheq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccewcnmc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjbheko.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voevbaod.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvjyjcu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaefaspk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mvznmbgs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2plcydyul.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2syyjxahu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlnhgea.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgyldbp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2idoeeeca.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdppmbi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeumnhz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xatotmhn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgkhdnc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vvybdhtd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiapmyl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sslgzvxn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2xschwmdg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rgadflre.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwxszmq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvplemij.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyuzjiz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2omaigfgl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxeznaf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzrposi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uiprpqqs.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcoifwy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxqqtmz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlilhfgd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jusgthyh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjloijgn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpaomfn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hzysofmu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2efnkumxc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhtzhql.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmdrnyc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnfnnlx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jimzoiee.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnyxzqp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnuuczc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgvhbhi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvsfafm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyxetic.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpotiev.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshdqso.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvajtut.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvgqqhu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnwnqiy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnxmkcw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mremzfgf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdygteyq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjojuele.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgudknl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eujejmpn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ygklwvdw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxlpacp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ranjskbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ropssvis.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwmtohe.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyldofz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdqzxsl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aymhvwpz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmnzmxt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncufjuus.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgvmolx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2okthsoca.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpnvybw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2agoxtwyw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmfhwkc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqbdxpw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbuslkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmecbgcs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlozgdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrigshdc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qbackcpq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqhrvqw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdqsgjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qcchvtif.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbdzmok.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrlwubo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjcvire.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2olgqlwhj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2oivmwkxo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vohpzqpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytonedxr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nuykuyzj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zdogqcoi.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wewyopah.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2byiprjep.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wffpixaf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvsxzmw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2digvwvat.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2llzucvdb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcpeyta.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjnvutw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2opcvjtgr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqvzxqz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnjuxum.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqofcts.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfscpwq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdasnrha.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdbxfcx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjgdtsp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2fajujkcl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiolqks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjnnlxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xncminvg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hawxzkfv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jherhhoh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frqrfnqw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2feruldbp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzrqxkj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2srhtkcne.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kppcoheu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wabzfpwm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaeigie.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2owwomwwt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqkwzae.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjebnkrr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pglrvwgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhlvfgl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtluvnj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqburrx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wteegcxh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqebeth.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkzuyxk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2unpwsanv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfvvvjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwwirow.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2somatbpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txqirwaj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2glxllhfo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2czpnuxiu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kplrcsop.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bapugdap.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrsrjsd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzfazji.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkatfci.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eweekmwi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvvhhmq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfziuzb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzdftfh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmyocmi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuhrgic.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzqnpcx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2plmdsdnm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrheibr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiegiyjs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2shmmkssu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrhtafn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwsccim.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzibar.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqckyha.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxyepk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2shtnrnei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwwgqdr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnvtows.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hyewevgz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurycpx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwjwfpr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzowfypo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmwwgwj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwamev.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvfylrv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrfratf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmnqfip.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxjhqlb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2caanedpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bozmzwhs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcdhtxg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrtlzpf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omljkwnx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsraqae.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcltwxi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2peddrfxn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxxzbsi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qklxwbvf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hizyozog.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ripefgsw.html


<!-- 参考信息 -->