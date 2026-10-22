代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfbifpj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoditpp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zclurupo.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uytoozni.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpkmsuj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnijfxpa.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwplfkk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuktqzu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiyucdf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pyngdyfz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzbpmtu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjahejt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jffmethf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjwwwpi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2skizmqwe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2aomsdkwc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yetghbfq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwwjwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ungaxcrj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rajngtux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvserfc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2emdfjffo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjkwblf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmkrtui.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skprskff.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2imzwcclh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzpxdry.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2osbhozfv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pchhhsrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2njvnjjuo.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2egsicvvr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2buraevlb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznkkryj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2noiuemgs.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kgudsqow.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyswmrbg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfmqhid.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzlyomb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2abnntdbu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2alrlvxvi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaqabrr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkgdayk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfvfaol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhkrgul.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmmweab.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvxpcoe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mszcleap.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdfuoqn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zunnqwum.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2orrhbrne.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbakwqw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrhulku.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqoqioj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsggqbb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuykjfuf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwckvax.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gardmixy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jktjqxxf.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfzvspk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mltiscqa.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuqjmgw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhhjkqf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2meeqtzqy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeteews.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2allfudlr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2iuvngppz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprvsbm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2feczfyaa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfxmegn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaptnpf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrroqqh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnclim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgpkkcl.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcxphfc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrllxhn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2rvshlgzm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pccewkoi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2akxtibzd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqtepbn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfcywyy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2elblolcp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2edfhicly.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2oktdsulr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sixmhcwt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdtlixn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlmjxrn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtzqwtk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhpsgsg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fztpehbw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgirsguz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbohtks.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeklaaj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wawpmcvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bblapeak.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbzjkdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhanoid.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qctztnsr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvqitnx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2svssklej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjoiimy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oskwobzz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvakuat.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpxycxn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxqotys.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2grlzmygt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdogmbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnjfbtv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvfcgv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnsbjr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayygqbdt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfmgpul.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhanotrx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqnxmov.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvptxfz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyhujye.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoojike.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkmpwur.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwbcuid.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwoytqt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2icsjiztx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzktjjm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnavukd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhvvrjb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfhqusl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2intfring.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaabhxmk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wthptivl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtlmmln.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edemzovp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhehnao.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzdydzd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlgteqp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzcipgz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpofadxz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eisvinyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrvdowx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbidlzdy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2upjgviqx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxufwzrr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqgttgi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pptaahfr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhdqczf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvgggyr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2krziheln.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lveibnus.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlktlcv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfozuit.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjgohqd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjjujsf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2remfbhdo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxndxq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtfxjvb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2phlivlxr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjrgibh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdbvhpl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fporgkvt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2enwijlkr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nthcdpvo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvdxcsx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzqbbnr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pciesbcu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdbsryo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxwnzyx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvexomyx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zihluexr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2twnliszf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vegibmyf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjanniq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbetckp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeoqtxm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwancs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2svnadtgf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2setvekgj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhrxixu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2esjlzrsc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuvnntt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhprznqg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhuchbd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctydgwpy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzyavyl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ronnvzai.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiihzffr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbynwbo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfpdslt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzejhqq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpstaeak.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjjnlef.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpzdmoc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omwiuksg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2imohkfyz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rutnlrny.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2neqooyum.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjahozez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hlokgkjg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwtukte.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lotmcqld.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2psycmefy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswokpau.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzxgnxy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsjrboj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaentyy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqromruf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocolxyaz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ovprsdfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkukdcn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfwfyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mliqvoal.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eurxmuqm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkjjbjv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2midwdflb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2obsxsfng.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeskahb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjmiguy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjbxikl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdcdtst.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtoujmy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rujcchcw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmuudn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfotemt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkzwfiw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfrevbz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2abtggnml.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhuqgoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2aktfpltb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gchlsicw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mdylivuj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkylikr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2werwtrae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2whsepztk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuhzfgf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xseonrak.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuooncb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsrzkde.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuanxkgy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fniijgsy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwspcszt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnptptk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkekone.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjrgxcd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2swwvxzwj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2katiwjac.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sqimtsrd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvuqqka.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fpseqiiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2crmdvgzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2itonuyoc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcrebyk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwdjyo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhxqgcp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2stpctkcc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwstltw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwenene.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iahygfoo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2trjrwvra.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbtobh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2inlyjrdk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrnntkn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiamqfm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxhskef.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtwbgaw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2atraypuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnxborh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jttryoqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqmlwvv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2laaaapzx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqrwier.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgctkme.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyianlg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjoqouh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvlithx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoflubt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2iogaolvo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2emeltagq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwpfaym.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzxfgzs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbplxtg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qcayftzh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtusqug.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcafndbm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2voltkidq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gudjalez.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxyabhw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtvyhho.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2twpsaiwz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrukmuu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixezxtno.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpzjrwo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvwbcwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2otiaiixl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqniazzd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nuucxcsz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwyxurf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jifvupsy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bprjudiv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhdkplr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bbchtuvw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aivlytfy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xinvxekt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeepnce.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfmwbez.html


<!-- 参考信息 -->