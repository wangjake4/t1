代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hapblzbh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsznahmv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxbppjd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzqjbe.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfkvrfk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtadxbop.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwddznlf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lddjzjbo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcsgsos.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghajfquq.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2huhceoxk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsoijj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqpfwa.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rimsbvnm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vujcgiqc.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mflissjt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyupkmyd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfmleqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2htbjmtez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqglewe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2weumrpqd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vywolunk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvfqhtq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2winwrwpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxduxaj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocktrjue.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tigtcruv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwkrtdl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxijamb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrijqsj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vovggmen.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wolvxmje.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmneqyb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2khuwftey.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myizdvoa.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhopsfck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2givfyjiw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrowfwv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrfwxui.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhscwq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2flnlnwax.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2prgevsyy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cirqczeg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mihwgwyp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztpoghq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjaqvyy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oldhprxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2teqjfsxd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2srcwbcak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihomnsgz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmcfwai.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwyvhb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoqijre.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzppbzhq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2nghsgqej.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsihgog.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rixrcdin.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgxlgy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzpqwqk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ybluruam.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpololq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbnuorq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrnvyue.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdphhsi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuqluaf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjzzrle.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qinnlqaj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqyqpxg.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqrlkes.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2gqydgxla.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuifqaq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ootnmsqs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxqsumn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfbxjee.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqbwgah.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqddizmm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cstlopqk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyefkcss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrisrvw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfhjxse.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2updrxqxs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abibtqwy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhybnaq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbtyuhv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbnalj.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dngsngrx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nicgalnv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtbwdbb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aanavqnl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcswehu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwetxbix.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkcgjjq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmcidji.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2imjflxtu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfebmss.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2matpvsvz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mfshmjsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pygeuzhq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxtjonx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpuwdrw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqaoffz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbktpjiu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvecukrr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgpgrwr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmbyalu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyhriaf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvywfjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujilhrs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqrcdmt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpqhmqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyysnbbf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2syaulgns.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmifheef.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglwzos.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2crwepuvh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcogizss.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uknxucbj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiriiuks.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpnpjnm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2caswduku.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxodimv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbgjifb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyyuicu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqnjjd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhtjeo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2uezumrxi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqhzhwi.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgoqrg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhecsjal.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcileal.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcyezbk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcrswio.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hctfkrdj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qniwmohp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kknmyvha.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdrshob.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxygkep.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyukmyy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfoveqe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owzwnqwa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puapcash.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fseyzmzt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmyumlx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyvbddw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayodziil.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaquiil.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdyptgn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiyogab.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvvbyki.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsckvme.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfslbmt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlwpqop.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpkcvxa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2npxseqqv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2riifxofw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoagrww.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzfwpjy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gccejhdf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oprjftur.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjtatua.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yttlidrx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mrimniaq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zxedsokc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbbpceg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlazwmuc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vopjscxh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmcxylz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nnitzpia.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bctypfre.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbewcdr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtvrvel.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2veqpippy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrytnchb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gigwidnf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmprru.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvdqvcc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2laxrbycq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjexjvc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jaonnkxw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2khzikhcm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhuuzg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnyucik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2buiavwoi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rknljtxm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbyhjhn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2slcttsbx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdlooot.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2krkcoskb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftbwvzt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaispugb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gchitidk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmbksbu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phwqtjok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgwiajg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sokaiywn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrafxli.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2edfvsggc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qwccyzfq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zihdwyrr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2btghwgxj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rjihibcx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2iayfhvbp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cirzoscn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mszlmkds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgubbit.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkzwyfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lywnhwxi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jigggoka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wprlkmwh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2coexazkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzhlrr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhmlomb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2csaysatf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjeblsn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvvdhrz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdhpmy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmhjqmi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkxvodh.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqohchpj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2maqvhdrt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2erolizex.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbvgqmy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vpydbwrv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxsnbt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfhnhhx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfhlxhw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvvvkqx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2didhzcmy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsbjuln.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuhnifl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxsqray.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkbapsj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xnekjdon.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jarryhcj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hootxvfh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ommzfyyq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2syfeczqu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrviabr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dymdiuec.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmmwxvm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aygdrcxk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiwbrno.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfjitwm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwaqcmr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzgducw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgmxvzz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnrvqhu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtxsgmz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzjavxh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2czcldxxs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2anzbvaxe.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cesytfrh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqihteka.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjueeirr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwcpiud.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwcempa.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mssebplm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtfpasg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhrozaq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qurjnxsi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iotdtanx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bdznlbgl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zecgwdsr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfsvblz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdxpqoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqqajsv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvnrocf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvbemep.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkfgubq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2btvlcatr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tpemylca.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvipzcze.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnhdpkb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhkunyb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzgcpii.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2drvnfaid.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoingfb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzobxqg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmxvmbx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmyqkjp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gelmfazg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pozddxhj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojrbvtp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzwnwhp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoekumt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2elqobuaj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2maqptoca.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2epqvjwfx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiksczm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoyaxwg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbrkcxs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavkmirg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlofmhg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvomlta.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xcicsmng.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vidqosny.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqmnfxf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmxcwaz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgjgiih.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fxognkyk.html


<!-- 参考信息 -->