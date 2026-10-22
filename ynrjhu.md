代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2exafadme.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwogyhl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmlqfbv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2autvqnpj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdegrcmq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsslzwkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhwxubv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dvljptox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmxnaw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cskkkdfa.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wacidnnw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrilamir.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2moulnxco.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuricwq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvymkdmz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhtnbug.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhpnfnt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsfxply.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2astopqeu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dshypsaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmputzup.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoaqmye.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqgoonx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2issvngbt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiilyri.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnlgvny.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2diiwkrki.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkkewkl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dosaaxne.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fijvsdmn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdspxwfk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iznohyrj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpptyncp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xutqatuc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdyvxbm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkmjvdo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lbndocxv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyygphwe.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqizwlig.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzlbmrb.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdfsvwn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjmtwd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwvlryq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuugesn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzdvpoy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsincytc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyxdppw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxitsyx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqrkerh.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2htaauags.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfxoaao.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmmkann.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfmkjy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2htdxsqwt.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ffawdijp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkikahkr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqrrghy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2odygmbum.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2buqdibal.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrthksuv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtcibqo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2exrfrdsw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2poyahtep.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sbydfjmt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2onlelnoc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzfagby.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwmjnhf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2viyynlqu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yshqtcvt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvazltfg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2dsojweep.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvfuzrd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tcncpouw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggidpfxj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdoibos.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrbzjjs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uquovnga.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgenljkb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmilftpt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vqapvxjq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2uowaunze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqesuvc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmlrwep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsudodz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfohvypc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuggzww.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcauyom.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaqfnli.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2owltphzu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfwbfon.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmxfhnc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkqrygm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2olkgungj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvikyuxe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcqmkjg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxnipl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2enoczjch.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmbiigm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqtuysu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jokbdzkk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yznzizel.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzoxfnk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2daxjbbuu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjpxzzw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2thtgmetm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmgoznx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kobignjb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cctdhuuy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdwhmwr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsqoxtd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpkyznc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmhukej.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvyqndb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apnegnsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2atruuueu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpxggm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pizroehn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcnnrfx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bauqgjlx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqvljfi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2avyvcyke.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dttntcsx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yafspdzf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spzgeemp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcjkcaq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxpqtpx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbuztig.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbgxelc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvifipz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inaebbdz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2srlfjqxh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qemlzqvs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibokscmx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvgfiog.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaxstsk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdjijnl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtmlugl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2shigzbso.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhicvbsp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uefyvxyv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rmitolqv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qimoxwro.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvxrbpk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeujoby.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2guuembgi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2sstkxlni.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcnzewp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmhmdhj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfmswwh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqhgupy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdlltds.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxvhowt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2enbcwvex.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2syjdsmbr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fryfkljz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwthovo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjmsjgj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bttvcpxz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziinnwxk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2toezltke.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycjwux.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtajwosj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xuljkamh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2woxnfuuj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfileur.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgapxfl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2apoxvasm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfefsyd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eobfmvar.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rreieats.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sosaujqr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyfbwkg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxbnfrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiowcld.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyoaezo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlcpwdy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlfbmhn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbuzvrb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nacbzbdf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2klcheojz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcxiuma.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2teiycjsj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrjwbbj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdpwyjo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpngyeun.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsctuglv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2smjshjnw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nejxocni.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyqrdjq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtpclvz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyfyqcp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlfnary.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slfwwfbt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfndrnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roqhzthr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rlavmjjx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxayhz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkrnmwx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uovxxzsy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lhadgiyl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhacxwge.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2oikmgfso.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfjrrvw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcgofaf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzkueuw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsalkgvr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjdaubv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2icasvypb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2glmutcvq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsqqzlj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2chnxmrki.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fsreoboq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsimzqd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnebgrw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjhbmtg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoydfyv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oonpjcnu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2emyaishy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmefhjsl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipezrauq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pylcjzgz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkuhvew.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyudofj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiheiapl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vykqluio.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwlxpjo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfkmbgh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2keibaber.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxwfxgn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxdmyod.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeizrec.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgehxah.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2naklpmsg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sthvjlqp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxdntgu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjcgam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hudoadhq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mulshrgx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjyznyc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlltwex.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaoigoh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2obrjtezm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqubdwhf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhprtbp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmlhcca.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ooniszzl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2siosvkxq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxzhsci.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vhclscvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdzzofw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrelvlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcczpvh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2baoezrmv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvkcba.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fqojrdpx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2heynfghp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uatxfesn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsswekn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2azhgyozs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vvygmhci.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtocxk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2trbetcbu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2onpmyzdq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkghdkr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2muhwkcvf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdefqkk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2siwvsxvw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvwteph.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfwydhf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nduiijln.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fghsycvn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2prfbblnh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zngsajsh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2krbjseuu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkvomwo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pegxpugh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qaniuuab.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbknmcg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uogedxmg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoojhbd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bshthtel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrrxncy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmlcqid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdenujb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhrzkwn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuozatr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ayszpqbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwncajq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2joznoooh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fsilnjss.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2etdzdoic.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkhrdsq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpmdppd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cfylifmv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywpoxan.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2whxaunfl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqbdqsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fisuestk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfyrmmz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvrycor.html


<!-- 参考信息 -->