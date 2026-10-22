代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2evzfldlo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhazddeb.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2qasxbmey.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2brijbkdj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoiflwt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dafltwfi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpyxfov.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vokyrgmd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2butetzbw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrclvzs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbxywdh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiyoepk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbhhpnh.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pviaazjj.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2guttejgo.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qagrkljj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2crypsigc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpttyg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsuetfj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2aphxamud.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nkffhdpo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2taykhgol.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgznjuhr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tsshcgji.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eiviyuej.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbbjhqs.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhdcqmb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrikqqf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hoholvpk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2homietzp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2scombrko.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2cdecgwvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlpotzw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vngbrprb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cmudwyan.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dwampnff.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpmjeid.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmapnskd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jppcsfqc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2supdfbgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otiikhma.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqczdzva.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdjfjzo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2peskyzwy.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfqbinw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqvydkj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eastzjqn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfipgsk.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcgxzek.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mljkywqv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjohxlsv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkotgbjh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2meqqmfpm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrowhm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2npgudjxy.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhawemv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2drgbnuhm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2goqhdqej.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvhfzgc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tturpyps.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pngoucld.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiawtzx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nitbdank.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2axsgzpgx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kucszlmr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhisiso.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrvixrq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmrzpre.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbyyjad.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2telcqkrs.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzlfbrs.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aafhpseo.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2njglzeaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaagysm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cghwyafp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zksixfjq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nogxyoyk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkyifth.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyphajel.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uasuyxjl.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mseyvqvn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdjhffd.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvvmitv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvycfla.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdwpghj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ceucfwon.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxjoacb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzujthc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gverqzsk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2htgniais.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnoiyiy.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlwhjia.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfusrt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygigqxhx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdinbpem.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2rooelfpk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlyrcve.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rdadyrew.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2emgqtgqx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxuoom.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wicrzurs.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2udzcftgz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qgorednb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2okygaqvi.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pgviiqkg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rutdvsot.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuszlrda.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tglawtlg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbwivwa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2asfoygmr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2azttyovr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnodofz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cykjovqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtqlxlr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2esbbjwad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbehjtz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbbgveu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khcuprih.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzecnxd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2seesvzgy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhuojao.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmolqmhn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2opmkrbmp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvvgpx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2crwcvyob.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzqwemd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpahxoi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khwwwgqu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwinucdb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkatoijb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2elqnpayx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjqmbhg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lfghsygb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qofqzsez.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfbxidk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2togjfewb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkvwdsy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsrvwne.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrywguf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyqtnhc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zludxofn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxwyxbz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwuwxx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkitdmuk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lksgkfxy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meravaob.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtlxvay.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlgrfvy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpznvcnh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvuscda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmnvyqn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2osownqqz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcxpfmc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufesjuig.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqpmavn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vedkdbrc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzidwdcl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahviiobl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idsbnchp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvjbqno.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjexwdn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfisjzfx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxywjpmy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfohnkps.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrkrqty.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2voxcvrgh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lwktwfcp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogayxttm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2etpaadxy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmnwzdo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkpgamv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmsiwre.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgddrjw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2orbpvzpw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2prtggtmc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2aikvksom.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2swzpzksn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wprzwxvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2sntwymvk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zixercmn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyjhbcr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyjtkhm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aseomtgl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpasxw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkrdxs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fkasixpa.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kegspurk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2edqqbuwg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdihtwz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2scdlogjg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxilqmxm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jovbvayu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wukgehux.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxcsbjl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aymnyguf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onzeonjk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyniqgf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ricplbot.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvgcsc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mshvivtf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2anpguhog.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebvajcs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohvlvdb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagwnwmg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2szjmrtmm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqrggsb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2twsdwhjc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nckwlkgl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vidunejl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eobpobkf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2euyqevnt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2svhzeihd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfmvytj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmnuso.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2soidifpa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwepwlrh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkhsefy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsluxpw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nabkytel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eogvnopz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqrmdkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhitgce.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsigfku.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkxliy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzwbwsd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uojatxku.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbxcmve.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbucgue.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cymodbaz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfxmgrm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ipitenoa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2amtbrwhw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvusmlox.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtsvpcl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfznqgg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbfyqev.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfkmlai.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oklcqczr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpggzxx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqqfdod.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqbltfc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2symabqye.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mucxcgpu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2avqkznef.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdhbkpj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnzqmbg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfgvocc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsyitnk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eticbnch.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaaghng.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbpzzpo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrsuvof.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqwpusa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woooqiak.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbxioix.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yznjzflu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtqtufz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hulvwrcj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jydpulhn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wodvnzjx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2publgxjf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqbdtap.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aimcndxp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kmebgbye.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2obsvoftu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uiatgvnn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcetbgm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhldlwb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uorztiti.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwowokqy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2grvblybz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2husmiqvk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mudidbvg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ounqzaxu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpweshsz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwkucox.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2emsetxrj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gslldwpf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tugvsyvl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vttcvvnl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sznzgmte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duutgldh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jihnrjkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmvggks.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqolsng.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eouftwko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2foouxdxn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2abvvbxnf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pljhkybi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2chrmfjay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2szopbglb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdgkwly.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvrydgq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfogmy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsjavyk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfmfinu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fykjtgkj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2innskcbk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrpxzzj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyscguvi.html


<!-- 参考信息 -->