代发 wailian999

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fetgiwut.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpuqimz.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvotzig.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwbmjb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpnsfkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xveozcbv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyqcbpz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjsasoi.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcdsbuh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlucnuzj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbhuno.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvfjnqz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtjbkje.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2rouamoiv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpdxygy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ezejxixl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hdedaxet.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fkecvhbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2amghiuwk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxggpqm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dalgwfzu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaavdxm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdeffmm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ryugksro.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkdxuhm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dclkqgpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xptofoub.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxsugii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yibpfmcm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbwlbra.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgxjqrx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqzfhsk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2koaipjbq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpkskhm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsvnqvu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzmsabg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2glafzihu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kljcqsop.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xluejhic.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwnngow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoaaxzl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mbogsnub.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgypegh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgmcqxf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgwvfxr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bauyitdm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2luirmcco.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zziclxdk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcpwjlt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpffeecy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iopylwuv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqiobbl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ambvbwvk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdgajju.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2smhboydg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pngclxdr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlwdufo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqwhrbp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlnwgao.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zilmvzpm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpzfurf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuabsyp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bckkspmx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2farxdvho.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2odthngyd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkugokaj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkmoawh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwxiivz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpneepvx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfdoerx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtkqple.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gitbhqar.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2leovbigs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2biwdjsgi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuvzspy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjkgcvs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2saepbsse.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2adkccgpw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvpjfn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgxlnxb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2weldozfs.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2veipbfyq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2crrqjutt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iowqzolv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrvfrdl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxecyum.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuhhted.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2frlpdxhc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaokwebf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lppdrgvd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2txgjagxp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xblddjhe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2krkfonvo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcsgowo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cojoveku.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnnvfxe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pungfbot.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqizqsvu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaoxagg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jekoegiw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2euoekuze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wawbwnut.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfrrge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wekjbcyd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsrnmku.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjsrpcz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkazvlkt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxjtkas.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pobfirkc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mngzbfbv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeksdxp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkpjyqh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufzyuce.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cslbvxil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2inhemqpc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xticcbex.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafvpxdg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxizgpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cifxtvfm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrtngnh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iynkntbr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nepmfytv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztezwmsg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qeglrmbg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gymiishe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxplopa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2htyiaarl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqkfnuq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfsqctr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2arapnvws.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2syjwuwdo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvpzyhj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svdenwqi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejynakly.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdbgopg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoiprqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wppoketk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2onjemehs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwafaxg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiovjlon.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2skvddmas.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuopkqs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeypjpw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gveprwhl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vetgwhoq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2thqwukgu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvujyevp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibopjdwl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoegarx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sovphtqr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrntxkb.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfolday.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2doaevtlc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmmxfpp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmgwmui.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdjufsw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wffisefa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dllqaeuh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2klrfvfcn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxvupes.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmosaym.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkgrdgf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgnelus.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2orzllsub.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxgswrx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbexfxy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaejtil.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lohrnkuo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sywiybip.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsixjmu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmlfbuz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfixnul.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxboaqm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhvqqcd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2utvtrzpp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxlgmff.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlczizcd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdfrbfx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jejleckx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojorghqi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxqerem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odlpnale.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzezdyh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xavnioiu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyayceo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyiwoxz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrtubyt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jevumsfx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfundpk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyngcvky.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsejxpip.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vixwodxj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtgqczb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbpydnv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2klnmyhug.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sknzqftu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaeyvzm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkzokud.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qswptdvh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylkehp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfysevb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xkydnghm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wowkfwbx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugplkons.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oybggnof.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdwblpw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lslumnzo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtbvvto.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdxxkja.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvtqwfv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaiqepn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxnlycq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaugscq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoacczx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npcgfuqx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hohuzqru.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rivypjpm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtxksaj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnlojqi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xglcgspr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dchdexgy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbvzomp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2urmrzado.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqmafuv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nsweennx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwhjryi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2webhhncq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dweuwjqr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdilgat.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhwfjaq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2leqnuduy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxqmkzx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlphkgm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2znluhwdt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpyltay.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfegubn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hpchqydb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmhgyvn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bekwunrb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2emewrhvj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2boznedsd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khzvpinu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrvtijl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjikwdao.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvyaqki.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcwnlen.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjsqfvp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmihikd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlnpgxg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zelkdwkz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcftmgi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbjftpl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzafebdj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2poyqxtgh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfakxwj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnmeaxo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bowvoiji.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrelcbdf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoqnwlr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izcphcma.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcfspro.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ommoffzr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stjlmkwx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyhxpmb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aoezgvig.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hcreapum.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyecrfp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zepekixg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwuajij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bngawkbi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtnpcfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcbplua.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uzepkifl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2syeqsbys.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbicmbm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzmvqtv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2axlyezgd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2egyqprxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzmtmdf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fteproxn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrhrzsi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mefconmq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwrkotk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldlguej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvzuaza.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcultsw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkendef.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaypfwu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnaqjzo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqmuern.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcmswsf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxharmo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qisxlvpf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2otvrimwl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrwwgyj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtsyzvb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtlgwlo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrmhsbd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iivlorfo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrmoaea.html


<!-- 参考信息 -->