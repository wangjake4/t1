代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ccomwkbz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2psmysevi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzlsxqy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2errvmaeg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qizxjequ.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mntpmmwe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2neymokfg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmftxeis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyvawrh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjfbvbs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfsmnrw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbytwibq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rgggfqmm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqomlqa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nekliyre.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qatzztjs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2edsanwpd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cahhlsjt.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyljqqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2suneczas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhyybbh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2asjpyfpf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnqobcx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wffxbysn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxsbjgi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wopydzvx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwryudj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dibwmytm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2adlxppbd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2evvoeqgc.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2apkmbcit.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmxrmgn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaziqacs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kazmsuga.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzwwlxy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zksodixo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgtvrjx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yruqjsth.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2szeaiinm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yevwbbeb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2khfqffvs.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfuztow.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ouabkqvb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkoeifv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvwatlf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtaarqb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2btmustzd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyheuiy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntozovdu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iekyvrpa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgetdhq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2arfygzed.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfvotys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2baloavsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrxtobl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhynmpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzientso.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgfuivi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlsdrmn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwtvxfw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvkviki.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhtbqus.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwxqbla.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdqhntr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhsuzlg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqdmfqn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2coldfudo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuzgtox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xinufqss.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zqptvnxf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2scnddbrt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsklyow.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwnduhw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2omjspvom.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2amaowicr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hclpohgn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzsubgt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2unnqatbd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vktvlkyb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lshzqwdn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcmxcsh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzrkoib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzpnyal.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yodcdauq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dyttdacw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcirlun.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jthixltg.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpbqac.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2inxovvpm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlclecvm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bchoueiu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmcdbtu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjtjisx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyvyrog.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omspsnyy.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxijuhmx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fifyeycb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnbexdm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbihcbg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvboawkq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2leytrvel.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2owbuugff.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcdikge.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqajfobh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2endjnaro.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkpvlxr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eccmftnd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqanxoqf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlqndmy.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2tianmbbc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmsapzd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfybfwb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2eksruawu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzlqukt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzcwbpv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2czwgfeex.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmzwuvt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxzrolf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiconms.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhovyvs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqfvhey.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsneziun.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2masaniht.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kmraiajt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rewanwbj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpwocai.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqxwadt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvhkaml.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbipbpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vegxvuxc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkncyyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eitqvtqs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvdeptn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfzvjis.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2azpjlgiy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlunkjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxruxeg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kszfcanb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhgfblx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxfmpml.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjfikpy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgssubk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2efnggrpu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpnyfpx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xekhijiq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nihmeqtv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhualcz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxcffhs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkzhqsl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zngadnqm.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2agvsiwkw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsjnxpq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yfccbmgj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjesfkg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyyisuq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nliksspa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiyqnah.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yorntbqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiwitcw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2srezjeuw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbsqrkp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjltpacm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlygromq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqldiecy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpixhnlb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfkdyri.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikckioln.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2efmrsjwf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtkqkgp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspzoqgk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbfhmsk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxqhjcm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkngrkda.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcdhseg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ligcpwjn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqahxlwf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmekyald.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbelmg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzoximy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eetgrowb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnzrokg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2owlazaxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynddeokr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqubrci.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eemrpqfe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmxcnmo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2xttftgdj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyektkr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcqordj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmrqcyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2teznmzcp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2agmeitkd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqcuous.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2emdrypps.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsitnmn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpqolij.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqtrejw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbwmhfi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kmifzuku.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgyowhx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfotvkcf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpbneoa.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mxszrgqt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2quwbwsec.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwlcpyd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oidmdrbg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycazumou.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2efimfvty.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzsqbbt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhoexsn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yldwpzwy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sliccqgj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2omfrskwt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdamnge.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngraptiv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnhbghg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2swbyshfj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbnnnxd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjcehmg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2umdovyah.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gynkvnsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtajwoy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrtcrkq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdkfhij.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrdwcdi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqetenuk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlxhelx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2geezxeie.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jegkigjj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pflvhfyq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrppeou.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mslkrtab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfatjvmp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbuemvd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtcapam.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mulidvar.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kulmyvkv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zizfitzx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemytwyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpvzwaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaojezw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yeybyckb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnizokp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgkiuvr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lecjmvcg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknbqmo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2atznusuy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxtleyy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlklxqaq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2voeqctqb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2habfykxl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcdhppy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2idukzzgb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kduepadu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhctuyu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xewzjptp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jljrobun.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjalixf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsjryek.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zitclcxs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyoskle.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2oqejvvbt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxaoyem.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uocrmjgu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cpagilhk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdyjoie.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awgyyzfu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgljssgv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utzspnqw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqzfjhl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oyevlatr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2glijossj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jxujlhdj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkkmywa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxzhuzw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmmejgb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfalxiu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbitsul.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhlqisv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2stfetjla.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2euwfzxhz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpifwkh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnelouml.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanzsrt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwufojhw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxflmahh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtkudqb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iagoirxj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbhmthu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfilmbpt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmpaadq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcqphqx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnrpvsr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyrbzxp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ubazrmud.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2syedrech.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwxkwlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qicvfjsa.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvfhysp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoiisqx.html


<!-- 参考信息 -->