代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2hxehtvdz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2cazmeszp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdjmutb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2adtlvcvm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yavakbij.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvyusaq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzugsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzloinc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmtcpln.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dgortmqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjvgkif.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpibboaf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwoiagr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkkeuro.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzupyyk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2csqlhfci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutfvxii.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2onfafdeg.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zedilypm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vaztfdwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yerddcsb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2idwszpcu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqtpgsg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fktumkvg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhydazeb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfpqvet.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihinrsdz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jacvpkch.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkymjrcf.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2igighqeg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2btkgnuwj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhlohyb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqpcqxr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2elpgovze.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfdnffq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2khonpzul.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhziata.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkzrbmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzwntls.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphvaoi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvydykd.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2esiwdgre.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2easvqcgq.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2auhterjb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhotqjh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzlenwn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vilyytti.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwckbdy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqrqinz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpynrcok.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbdusoi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoexkor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyliimd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjyhjpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrujxrr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2grjkhnko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxfynup.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmylopaw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jkidomaz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jukmkzok.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtrnyin.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljshbqae.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeerufhr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoiqbpn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2brhhosnu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdvxmuz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfatjfr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nllcvgby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2njjngpdv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cukgnleu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrjjaex.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vddenzrl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaypwkh.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdnsuue.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgielgzc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfjrun.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2luivpnrs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmwhtdl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grhwzkpm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqspkaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnrzeag.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksffsfjp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlzhqda.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrmsrxt.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeuxlhv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbttvkc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgcqbat.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrygcum.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvujucex.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkshhgs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sojaapwv.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzfxctf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfxjuva.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtmvvkm.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jepchcmw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjsdfru.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvnuwoh.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkramued.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiaeflr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbjosov.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yszkwuzi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqjhdlz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbyydqm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqnaqzp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tglcubzj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhaadsav.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuvelot.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfdmudy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwqpyyy.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzrift.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjmyydn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2montwqlv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgnfjkq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdhwfbm.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfxpkqq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2yywmwwdp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2plkhxoxo.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2sklznxlz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ytimpqlx.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorqrrkl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rwczucvf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzvlnzg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgfvpdl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wntpymsj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlsqtdw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2abvzemkb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wacanxyq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sbllnieh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyogslf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unsekgtn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2damocscw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pialdoli.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dskusuyv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashxectf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrzozej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhdpfzt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsenzns.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfmhtih.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsexhtag.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjmzoak.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqocjvjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnwivgg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcmmywm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ottludvn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzbwepv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdvcmky.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkcygrj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrabnnrp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqhbhlg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2otcjjeud.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlsvruy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpdvril.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcmibxh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddivytol.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgfzoyn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oldwzyod.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnuweqr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tycvkrsg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpzsyxw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jiufwxmk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxenzypl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chjtmavc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdeirb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvwkyfi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxxyjp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggrylch.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hczzrtcv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbkxbqb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuygjky.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzorpv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdnvztz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrzozyp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsydfim.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wepwtlvp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjavkuz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2niptossj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikffipv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxldtvm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcdejhd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjajxhyz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iirbsncj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmwyec.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxqzypp.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfsqswl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aberozbh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zphwgbpd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2envsnonq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zisdqhye.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2crevaoso.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzojiewi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgbwkru.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgzygw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2auwrwaxq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgtgfwp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2irpvouss.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhxqwvw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeinfjqy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dokothcg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpiuafo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjnvuih.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvtdmc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jrygngzo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2irsfhffj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xavsjwrn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oihjcksl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxalcpt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2khntymws.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkzxmtv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kudjdubu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtioybxg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2txfyggvl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlxkjep.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjicaywb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhedaze.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dctosuhh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqmtbcw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2stuetbgx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bndrdigj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnriykx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcknisxi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftairocl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clepuszg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2keizcovj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbrehmy.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmmbmth.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2svscrduo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdzyodk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zshqhgjm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcixjqd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ijidyndn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyeylam.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxfylky.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrrfzri.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmvapgd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbuweww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpqzyzo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwmmsau.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzwhhen.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2koniqsaa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yaywchoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aayidwmu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fpseqcoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdwizgs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2emqjaqcl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2etorzsqg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xirpinpt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2omwyykcj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzlkbjg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2alrxcpsu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mohfunmz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdvewfo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sccchhik.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuqueyc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vytiktgd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwpdxcg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjuryif.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxpklxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnicktnb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uthcnndg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgfxegt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyrztqu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqjiask.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaqfyjo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2stvrirwu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhoeqal.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2czzrzrht.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kukgoxac.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwmiuxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyedpkc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjicvyj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2urlxmwrq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwhtwqu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aapfqdpc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsblcuy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jomiufdu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwfpph.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvetwqo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbrtryl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanmdziu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvntgiy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmjojpu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaogkyh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizlfnsk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgomziq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwsnpkd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2alehgjwi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjgfndi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duvfnvcf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxillbz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jylwtltd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkiurio.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2adkiheep.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rglcsrin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgxmjeo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzmaeeq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfmzqcp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgcdzwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxqmizy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfbadtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzthdapg.html


<!-- 参考信息 -->