代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uroliyhh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2diokjbdy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gexamvbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2izhqogta.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhefxpq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzlbnnm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2sikqqknt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2afwjdcli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xedlkfwm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2giolesek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iyygrbjn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxtmtnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqouccij.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzayybti.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgiacng.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqenbceo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqrjwfo.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quehhfbc.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlqhjpf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdylggf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2owlqnxpl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmbfqkc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smwueaji.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qibsgtsj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2txysymdg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dygdtjvb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wkheszqr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rodesiol.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvqeoyv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgzrodr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bphvfirw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vufuqfgd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtmvhdk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2unnxrodv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhfdhz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppixgevi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeguniy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtrbpfv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfvftcz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2anwqjjir.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnzlndb.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjkqomd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2segsssmf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdmjwam.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdpkrjn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcjchsy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufevdzqt.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaautac.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaifqdc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2extjjjau.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cihuywhs.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aojrnnqx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucarjhqg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrpwwsn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhawnxya.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpskkaye.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjywlntm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2subxpfbf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kllfibod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjtuewp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tizrspnh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzezgqb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nphjatbf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dugbnyps.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2svnlwdum.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2roinmuur.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfjqdcz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrswenv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrnbowm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvirghj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wqouhblc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ncozdhnp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwaaijy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dysysbdw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hngvviex.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpfwlbs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxwaagr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnutgvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2froojbwa.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2klespwfp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2krcilowp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbtyuzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmubjd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pxripbxo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2djiztlrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuxffbg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgnprxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdrrszr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjumiogk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzhpzvr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcdrlro.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bumafzdx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bboalkwv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2juprwagq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjbcrve.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2busilvan.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoehfdhs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkczodiw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejusrdis.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nedicpys.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevulgz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dasrhvnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2trynzgba.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssltavn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcbvpsn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hukhhvhf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqcfdoz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqsidse.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkintom.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdaikse.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhaupqfx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dugpshch.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdssncp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2guczyvsn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrhudut.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjrozce.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzntxsft.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgtblgy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aelfzlzp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfnpjm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgihsee.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpwkmjz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyhnlqt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdruuiyj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2meifbqwf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdhntby.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cozjzvsv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhnjvmq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrcnwfi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlalyohs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vggzgfcn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwztxel.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtqmyna.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prfmguos.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcovoqht.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2moufgpzs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gritbznb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cehiysad.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rogadkjz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lquuhhmq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljwmhj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgkvtye.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlmxwfl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pbovtixh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2atnknvvf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffysicmw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2asanydcm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ooscdhtr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ieduzjlg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pbskkpqn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmuouoc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2neuqfnvd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tflyohmq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzrmjir.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpwsvdf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtpqbgc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnykavum.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdwhrjk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jejybcxx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2minaagwl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbuphwc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtklmady.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2javuzovn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnixjff.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmnjthh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cipflvru.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ezogmueo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2edbruakh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uolknwhs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wspngwdf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfkzvnm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocibqecq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuyivog.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kycjyakn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srwmxneu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbutofi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqfvxve.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxuoqwg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpzmmis.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsuhpvt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdasikpe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjthbmxd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjenfbcx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhrqsqm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zovwxrje.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrmobgi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcgdli.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2afesnvlq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvlwywa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyegokg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2smqrzqao.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfdjoyl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tvafrezo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydtqxyg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrvbedj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pjonlarn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpehvyxy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbcappr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwujmyxm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wiicvpke.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2goiksweb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcwkpra.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eezckull.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kiekpink.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiswanlq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2eszesnkc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lssbairy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmokgiik.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vghaktjl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtazzvy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gspsucfw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmssbgz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2owefgzzw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgidets.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2neszvvrn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcmegoe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghctsa.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxivlii.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdppysbx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nphuidch.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfqvsp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2djenpbfj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqvfwev.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqullggb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyflbbnx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewutrbnd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2osnggyhn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyupkmt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlfghqp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnklkeg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcijvth.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lssodicq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2njriwyco.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxiqpcy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbguefj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2smzjvdwx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdpljum.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2famtxgoh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxiaryz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuqnud.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhhntco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzrhgfg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wytsovpx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyojycsg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jrngeouk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2strkeirc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2robpquci.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejhhwr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmyblfs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mrllzxkk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2umwxyrcv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfbgghb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tvumozgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lscxcwof.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfliawfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ousgrhvq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2obtefktm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mribscnc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2shortkpd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wquqcjal.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwbyivb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2myxjnchr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxtjnti.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dhscsjwb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwckiaao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqttgvc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyivzowx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjryzzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gfawypxw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpwzhqr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwvedb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnswhnx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshtxhxf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpfrrx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvxagqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qambienx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzzwkwv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bywiygpn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfdrrph.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbzwir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2crqebhei.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2khhctrqy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnxtdyg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmkmjks.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mioknswv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgztgko.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uaulzmgy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wisqgfej.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqhzni.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvzpgxs.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbnoznd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oizbhzfs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yxejhtus.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrqogsw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsrgkdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gajdfygm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxiccg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxebjvf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpynfks.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ipirxocd.html


<!-- 参考信息 -->