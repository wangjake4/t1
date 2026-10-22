代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vklgrvxe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzuwbru.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzmdxbe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmyncli.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjchruu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrzdok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2duudommh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmdkou.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2iboffhry.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafkprm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgnxek.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lcglcfko.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvicgtw.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rubpebrd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzdikjq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2pddvirgk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hasdomba.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmjsefh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbrwvot.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2iytihdkz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgpmywj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjfzntl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyehucfv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubufbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umkotfpb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtayocl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2llrfvhkv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dquaqjbc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgkqqvb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpeulpg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfkkobm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pizctwqz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iliqeusv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcbdism.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzoqbe.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hklsreox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpglesvv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxykfvz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wfouqytm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2svlujhni.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqgiczz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcpuky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtsdsqb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2abfgwbhk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjydcbs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruivylna.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcyxpaz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yglmfjmo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuydgedb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2sweqczuo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fytwmhug.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlwmtnc.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbaolbg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kogvclgj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2khwrnqwu.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zanhqjco.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxetzpc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgustqt.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlinvuzk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uzupaegg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwneksbi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjppcfuu.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzjsaot.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyamelx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeruqmo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdbvufo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbrvkyb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrcsgpq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwvycqi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uzearmtk.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eogsasyf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrmtcvl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnvjhls.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gimxcszv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2helxfyjv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfymhqiw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkgixzd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfovnibz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqifsro.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqidxhnj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgjmfxj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2efbyschi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wotikzgx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgtqdmg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnfxqmc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcazdmae.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwjghhp.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmiwryy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdrnvid.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjjxrgt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lraetdaz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrxpxnj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2txhlkafn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwshwnwm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnlzzpj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pncmwiup.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlktqrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clclzyif.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hjajwtxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoqvotz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2obbwfvjx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brfbebyk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sacdqhst.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnmhllj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmemcbc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujesjwer.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awgtbvuw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zojhttpc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnixeage.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2neojjbwy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hifzocgn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvihgoc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqascqeb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjcbfsr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejscovnr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svynjqpd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlcorm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjtzok.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2gacvqwbb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlmmkan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeyyihc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwbkflz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wspnxnrq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmnxeux.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gxovpklw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2chzuysqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sehxunjk.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nulehnte.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2howtbiji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcawaoje.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swmwuseo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytubstns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkbxsgt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2heyxedda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tybzwnml.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxcqiwa.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gntnnsye.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbbspmg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2legdumrk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gugadrbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbieyxt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhnhxwf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vugzgtbv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvjsyqq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tovwtsum.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnemzps.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmjthxe.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aipcaejw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oulndltr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwnzli.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2silwfmxx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwwfmva.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihprec.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fufbdffv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wejhrtxc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2yypvqsgi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyxmjnr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uycnqadf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2bamwlfwu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvksjhi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrsaeqs.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fizfaiwc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvqfmot.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjptnkrp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieayjtvy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqfcgqx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hyshfsgt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpzgeni.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpyxjnv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idixaiwd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2attegjnv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctikswuu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ewycarma.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdzgkvw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbudoiv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzzyovy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2duqqlyzx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvneici.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbiknsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gggigagj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahhpiu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbsxwxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlknpvon.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khygnuec.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sreomkfq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxvdfiz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oktaoxgu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2amizkcjt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjdcicf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouweqhyr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2reoihobx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyxfnlm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpavgwco.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvlhhrt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2liifqgrv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqwneom.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwgylc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjervwo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwspnoi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfdtyq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvomhnld.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxgvpob.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wurulgzo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvtqvjx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eebafdry.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bplopauy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlvviqc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuvpqjx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yggjbfcv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrnfsow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyvecad.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqyhvtr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvozqof.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2itwvhasa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mlndyyvd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2llystgzw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gctiueyk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyipnoxg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtlhwza.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeppxgp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgzzjca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxkgnln.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sixyjago.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2upwzrpii.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2abyozxyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhidfuiv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2khvjenor.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwiodgm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzugawa.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2lilpzrie.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zppkmvmf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2eochbukj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zofhvojx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2coicaedv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuzaeex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjmeqcr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnhliyu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdtosdt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vfixhwkn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2opalnzbd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yisweaow.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqnpxyg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abvlygkp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oexragsq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oytgoehm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvfaerp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsvjvxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zrffcbba.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nujovliz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvuevbl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2talptbiu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsbkkgf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqoczzg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkocnard.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovexkr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibmcjny.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2abiztync.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xptymfqs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwktcjfz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsegwhd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jzirspzk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqknffv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ntocmmil.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiqqpvr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbnqndx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyjcfbb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyeewui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2meqfeeuz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xiebrrjt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqhrdif.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeizfyh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoptuhzj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2coowuaes.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjavjpgv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhmhotw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2geyudlkb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2djmkktaz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkverse.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyywbyap.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bytkppzo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pdausoqg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdtifvv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnpqjzi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvojhcm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqkkham.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeoajtt.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqaciyt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzjbawk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iekmscrz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyannstn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vynvkhwm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmosaql.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yassgest.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdfpxm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pznlfnpl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvhkeqd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rospewso.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2smyisgwb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqopstzp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwakwnf.html


<!-- 参考信息 -->