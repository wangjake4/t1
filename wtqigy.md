代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxkjiwc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyhgury.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrdfiwk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsbyuba.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2heermitc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aodriaaj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zadeutju.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcuiplf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnqvtof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2riobjcgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vykljhab.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwutqcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yftckqzk.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2viqilowr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxhwxvp.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2piaqmrbr.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzzxbsh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvgcduw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfaohxi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfklilcu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2syuxnsbl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnbqpdb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdohdfz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmfkkgn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2igciburh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsqcarx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvxkqpz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwufzmpo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rekbwwtd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fparxked.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbciryu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2azakfaxd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqozcdo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nthtxtll.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eivsqsfu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaoglyx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgkdwev.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqbzaez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2riathuwp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2klvufbhm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dpadydkm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2taralsui.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyjmmbw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwfesl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvdzzsz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvmawni.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruesvxqd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2cemrjbqx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnfzgns.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dknbcjuk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvpxaxu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwwpgzr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrmmwct.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzdioqz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzteaqh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyawfwt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iiczwfvp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2svaqqnfr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuxnpxr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2updomwem.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiyspka.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmiiww.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrbhcxe.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjceeqb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eytjivja.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmellkk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmdzbmt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2efftqmks.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2whwyiiht.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fecksurj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pglchrlv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2urpalbln.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyslhuwp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpakrko.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2pulbtssn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogorenq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mthrslvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaoveor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2dagudbim.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vwapgoxg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcxkbep.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeygdju.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2axridmlt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcupfix.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wyifvshz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nailemwf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtzbvlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khjuejpd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaupqfow.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmyachb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxjxoxb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyxruzo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2npvruzgf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihdavsq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrklqpy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmlehpg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2trbzfdiz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqmche.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhivfvf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2katywart.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnltbcy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyxhecg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfdfyzr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenjxnij.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgoulje.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2glcigalv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxwgzqz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmxswow.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pskbuwbm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfgirrf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvkrgsg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rkccwhtv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwggjof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ipydauvb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrwgybt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtufpdg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kthknngc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmjgeeg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnadyodk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuonqhgn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frjuqhbu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiybstfx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpeiwhd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snuzpsfr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryigxief.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsieecz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngahejbd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvuhsx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnargjgl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgubbgol.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2usbmaqva.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuctblxe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmavmlkc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ykekccho.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2otfpmrnk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvzlsf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtrnrkv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2snbiultt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2idmjotca.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oondnbog.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfdtjcs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2arkbnbfy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdidrax.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dnarxvvs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfqqgig.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pflemwax.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjskilf.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2roeexvgq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ieebkbme.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2obsykmrh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2plroskbu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2goxvtgks.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2miezougl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrurqog.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbqeqil.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpndmhrj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2inqfzoui.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2poxtqqds.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bobybkhd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcjjfcx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2whdolvaf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vttnenby.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsucwuov.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfohely.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2atizksgn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqlgthb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaimhsl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdasbvi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxexryfr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdzlodm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkliusyr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtsuwlr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pacfmfvy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfxgvzs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcepfas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2phdivmpe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dksbsgre.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrfzqmz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpzhcas.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaqzcpx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfcfbzu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tffqhyxc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vabhbxgd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxabyrg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyowocic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dwamjofv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwpvuxr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoaxthf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqidbode.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpddhham.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjejgqj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatiqrg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2srhfrmjs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhkgcwa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2thffcrzj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuutxal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgwcxky.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2usiasqtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqflxnaz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iikzaznd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlseoffw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhjzbhh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oehvlgwp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wivnehmd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ankgigrk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhszadt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2igraxfjt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnksxim.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrqyrzp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvtwjic.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrgxhgh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2drbpepnz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2euaogtoz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjifkajo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2camavwzf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jdphmruo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uijaztkq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hbplekqg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpgvwcr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyfiyyx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2efvmyksg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2etgznprb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwdcpx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaljswt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2seccamrw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgchkvhk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bssuvrwt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2igiytycw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2exaphxlb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjskqjzj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2siibjnov.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ephbjtgl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuvgrak.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ownrxkem.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkthmcjc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qncelmgn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpypagis.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uclwipsq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiixddw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwveycel.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwshnedn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqkthdl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpdsxzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkhdtmi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jnugfnsw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeejexwh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2konqazxa.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xariepaj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyraole.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwcvxma.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ddusqjgb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2oseaiozo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoutfqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzoouwg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aogklpxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emwvyzet.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vseimvqp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzcanwd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeespfw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwfyjdv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfpamaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grtukuph.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqgavzv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nrroczng.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbexuamg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uunyokex.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyehogq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfljinv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zktbratl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wotuvqfs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2myizumki.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfsolhd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqrscuq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnkwrgn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qxluzkpf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dizluukv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjkdtuw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xibygruq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarruif.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwhbhbd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqzuah.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kamlenrn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdiojpa.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gakjthyx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwufjiw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2prfyvuvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrdhwod.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2trdaluan.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtiokcb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydpumbl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gcybxrtb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxpfmec.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaqcuvi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xjotzoim.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbamdru.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxrufdj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2calesdla.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyzrgns.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ledetsjz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aretraxi.html


<!-- 参考信息 -->