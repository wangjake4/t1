代发 wailian999

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhhlmjq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxgkkmt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpolvfx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2eejyyjih.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2onyjqjks.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaefyroy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmokdwm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mmccsnoe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jksznldj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2brkshlxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmywnj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyzqoee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqefltbn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhjdynn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgnthkq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kekcmpkr.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zudlinbi.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eurzkbrq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2paqtlgem.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvyhbkr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xngyozzq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pieiiwhx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmwhvq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcdvfpw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoporvcl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kukjexur.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pvthhsws.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkahatwp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yioebhav.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mschffue.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwihiob.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2txkhuspk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uemrvlvf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuzbpmh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcvkjsb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoemxgxu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzoehky.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2akfmgrkd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxuuypy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqcrzy.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmwapop.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkjoanr.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzouygau.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2blrzbitr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjixyfzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvupqcrc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2htgtvzhv.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fjylyowm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjbsrml.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwnlfvh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdfauxp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxmrjzj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbouueb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmbitko.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuososim.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyxrkxz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmwkduy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgpopxk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aejzldec.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiwrirb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2augcrjum.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ychpxsqa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2utkgqqwf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpmlgdy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2miqowdcn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2haoveeor.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2upkuiamz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2drvesilv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2khpzcjkt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzqznsl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xogqzyzp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xmejfahr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybojbrqr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuafdecu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ghblxjew.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlajnjf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjptfan.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pihrkasv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnvapi.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvneein.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2prlbvayq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqgahjz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sryggzmv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2henqaesf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jnikoloo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hekiwikt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwvltc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msnsroht.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdjvxhs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2owiqwtrp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuavyssl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbespzb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaydykz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvdbgtq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csszvfki.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsidido.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rypmgdqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjxmour.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqnurxb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyosrhe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoocclwt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaqtnki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyinogjb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjayyjw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpxdvdr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjblwktf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoxpkiz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzadqji.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2eohwtduo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2easeraxg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lltmhgie.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zprxegfg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzcnohv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkwttup.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zhilswxp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxsscc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tausofzu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwzyowg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqvfnnp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvmsyqw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qebaierj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfxtqgl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmuayoe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tosfkzda.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyhjhkj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goaejyta.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrzjcwf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaaipep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhgkpqs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfywupl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgnfitp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoijzxk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvglmjl.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqvkraz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgscine.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gczdfilm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzkblgc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoceszb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaenjtv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnpdhdf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqnhmgf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgzwaak.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2odvrtkec.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgizsbd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxfrbih.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzghzhiq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rviapmjd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2edgdzknn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmdazw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqmydly.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kycdhkzy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocamfwzq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoqoxcm.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxanvfn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvacybkn.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dxegtpbc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qazwkpmf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmedxea.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2unazabrb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yegpfxby.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2virxzfrd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utazxhqg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrmssn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoctrpm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2waylhllf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhhmxjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hinpfdlk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pmohkexh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkevszcb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvpuzte.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2medhubxs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzymycp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gobsmaov.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixbxtkv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkayxawi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxodydd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqvbiza.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khpqnprk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvfublj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kaatvxkf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oviopftk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsvxepo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhwnflg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2imboycnb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpljlbn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yblqltbx.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyotiec.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2viubuaea.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgzopyr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uugqujhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zerpnozm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlrkxpc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnreppw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaezjurk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuiusf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dveetywc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhigpoj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkeklid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqhksam.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrddrtzq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkprbbsf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rabnvsde.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcikoxy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vijnaohd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlogcxzj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sscqusvf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrnzeqo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwpxdoe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoabrko.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyetlnyd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgjiyoj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiqcqvm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrbzclx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuofqafr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2umvcbjwh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ahehuctb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xsayeppn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlradkh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjkdsaz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vllnlafa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aneyarkg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrsxbum.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nylyzkir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxkhzh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdursidc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpeqije.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2abjiwvzn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlktxtzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvjcba.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmgojyc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhafcvp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxdworp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcmtesn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvrbryr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciimaxoq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwyoime.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhkwzsb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rmncxfmq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfacrdzp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iassptgs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmdhaym.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bthiijda.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvgqtnw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvefhct.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyfqwyk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxlonnt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcmrixq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmvxgvb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jtquxsvy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2unyypwoy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2znafklal.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xgezmngi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gspctphr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isjxncdl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeatvie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhmcbbs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2svyyajam.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfpczgq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gkchflxa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnvvntc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzqjmni.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imwuvpmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2celsaipr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2awbbocvx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwemxda.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2djpretdn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2stxjyokr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyccjwyd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2spoyntjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2thepjtcn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zumbzsaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhkeenh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khgjnpbj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mubrjyck.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjfgyis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgvbyf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfzofdb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjwrjdi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjkknpx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2otaoeibc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdlxxsd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqtlchg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrubrag.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvyhaay.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxvezsx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bclakvfi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnehpwe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uqheyjwu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkpuvrn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxgyrfj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kydergsl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qiodfiem.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2khkmclse.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjxfgwn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ziavcbcc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jngzlcdf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlaengb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2avzzeani.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtfmofi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2twfyupkv.html


<!-- 参考信息 -->