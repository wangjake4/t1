代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrdobob.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgyhzzs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcqobme.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhvuymu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfboofm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yizrdynj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrahsnb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgscooo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcqronn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2smwqonfu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gldorxhz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgzlamc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjusuys.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2yozwaian.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoaagqh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqoijzi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dndnmlpt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffshryhp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznlmez.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2bueyrnwl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkbgihr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvpwufb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbsoqq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hvagvroe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eynnbjav.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvnxzix.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rssaedck.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqkosst.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbjhszc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyxwvmn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaaowrm.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2apvibuqa.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmiweop.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2alryzwzt.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idcxolfa.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhbkrzd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgszwsoy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wktqubjs.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gijtzrmv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2exqgifjg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvltfwvx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfynvys.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzzgfci.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nscscgki.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vknouzwm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhmphrg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqguqkh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qowvhewz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcklvqp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxgsmui.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2biizxrkf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yallvpmr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mtthavjj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaxirjd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cikvsclx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfbbpwu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdypyk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfklaws.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdbveze.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rehifucv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2puscqfod.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmcdpp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpiwyk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwhqjch.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuifvpb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzerfdx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lihfmluk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhupona.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkuoebf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qllahago.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lofcujqt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hogexbcq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxnahps.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqofioq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrcypud.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuuubqu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiuevhj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfhjrfl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjpuout.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvlqzwi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2evrznnbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2orkyaqny.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ygaodsde.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxzbrlw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjrkxxv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zufdumwv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjcakia.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cehljtju.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2djvflrbs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkniewap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2kyppvpmi.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhiozub.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2swijttse.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbrkxjc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vihaplsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2moltxknn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fylhczli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qanltgrj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xhilcrvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yknaolah.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioddaiee.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzoffg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qowpwgwm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2onsdcyod.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tafuhfov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2goczzaok.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlwchh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbfqila.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkpilbt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkqeagf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2senejgev.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuahljj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwioqzo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dttylhba.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdfcljv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqtvrhx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqlhyar.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zniixbjo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwryvso.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uuachdlj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuaclqz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlybpdwx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtaiacm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzsipuo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaqbyem.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeokxmc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvtusd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bauocdqu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemfekna.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjlswlb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqkdlji.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvvqlws.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaifjevz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqwliiw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyoetbv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2udxokuec.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nogywdzu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaazbue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnjdcmj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xftohlmy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiebpcn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtrfmbo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsndagt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nymiijuu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhebzea.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbcfvas.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2odcfrjnj.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2asbyofeb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2slsxhovx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxwywee.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwexmyd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hklpmnyo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxwnuhu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqlzlor.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2itfqauqg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgntjhb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gupzmgwd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfstlkg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2avcuigmn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2czstlzzb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnnhmox.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhhjljo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tytcybxn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hetkxtly.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2euxecnup.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynitbyxx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vgedadpv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmynsdw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtpjrbb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xapxlbtu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhajaid.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eggcwykz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfhrmmy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzhhjve.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oepzeuov.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnmolez.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2slpcjksz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fltintex.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2itxrvmsc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpgdedv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuuyreu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uutefufy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oyserdjy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnhhpna.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgmjtbx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2grjkbvjf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiplqmha.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwphgna.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yndxsvlg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esyvxnnm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oegzdxfs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2podaysnq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgijhbc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsrsefo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxsxvvj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pthixuuq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcznlkuj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uddhodaw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kuibwxuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2urxfsxfz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2velqnxyg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2treiqbjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzhtyup.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2leqovcxu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgsjrnn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqiljtb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otytdhxw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jgosetnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjcoelo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxknwcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoxpzaf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhlchfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zblhgoyf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znscfqqv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2imrreshe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2esxmecsq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmryyalc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvmywhi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmujpfin.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2asnxrwiy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hsltnubn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krbcuevv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtxpwzc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnwfzdr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2avbifekp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vngcexol.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgwfymo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kuchmbfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwgknox.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2djrdewpi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsuiqzn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzyvrrw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsbhgrl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xudqgobv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skcqhwwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjtoket.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klmcdejf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eocatfus.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2msdncceu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxfnkpb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvltnbu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2futsucwt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2watyiikv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmsbezw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mruprdpj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yexijmke.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gznqffhw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2sadrmmsp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpbhvzo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwwuygq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfctkifr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2khghrmml.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhaehix.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiscreru.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstbjsbx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmjtrso.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ombmngty.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhbyqfq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cukckock.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzutnym.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpprfhl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2riwupvrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrlchav.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qjttygos.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hdglfhss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znwzbyyn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdafjadk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsbcclf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vwipjmtx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjynylr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2txdfkfeq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xovijmfi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsutnwz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnypctbl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzpcbtv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwkkgqz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsfdslx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2agkeympg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdhurbk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2prcrlwvg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrgogjs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2watztiec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezrhfyj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqidcfjv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onqzdhpq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtyefhc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nskdmzsi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjwzquo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioetiqji.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2acdzinlb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2twkldduh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2foqihcxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vvapbtxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuflijag.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yasezmkj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2modcrfkj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2udiiuxwm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjlqnqg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoktpzr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgswkgb.html


<!-- 参考信息 -->