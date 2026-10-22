代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuraesy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2eligqbah.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udonvbxu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxfswyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dutacawc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjehrnd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqctggzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2xknvjoiw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhvzaci.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyszmug.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffptmcua.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmmahom.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yupohscg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2snmxrkms.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbeegdf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvouiyxl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhligqxn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpniwbkd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuvggql.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjmwrpb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2opjssimv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsvmvaa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zukwvgqv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2unnpjhlh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsibgtp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zzffbqte.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eirmrfau.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2szxodccl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwfwgsx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbjzxip.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2arasuukw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgucohp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzicstj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaytcmjw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgdyman.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaauupm.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aoobdsur.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sobhbwup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2plptqsan.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2onivycaa.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2klwdohyv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aatdryjj.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxfomvj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkbqafn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjxpxn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhbnpxy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzyitbf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgekmzoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzehtuxq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzplkhz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ailqpuxg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyppnfd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fordxqza.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeuyepz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwslkbnq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2orvbkudg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxuoyo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bozfjoer.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfcylpw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tclkjekf.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphtvshj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsplsrgt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmxnaum.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvizhcvv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbrgybo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuhqrgi.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfraogn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gijhjjvn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2flvccwot.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqfqugn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyumvmn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmgoxdj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrxcqyi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aevwybea.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfsorwl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vwubfcbq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxzrqwj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwllrce.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtnllxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbmxsse.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtxrdzh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2sctelchh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcetlnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxlpafq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yyybbpsm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wojgshpf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtukkut.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cojdephk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsdvudy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsiftry.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyradpt.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrmajic.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2imlihnvt.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kijuhnga.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtlvhbq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbkuzdp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjplnjfz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paurenyh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoaeprs.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkrdace.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmgeidy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpjazxd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lttqeidd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhyklny.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwappqx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeppkuq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cahiqzmp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwetnprj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jifzkgme.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhwowjm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzrbmss.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2owyreahc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkxazhw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzrgsf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkotjhb.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hadurypk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxitdiad.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhtfkwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2droqshgl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkuamxt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvqiczo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxgmobz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulixcnte.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2abojrcxe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cukzxgxa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlkxfuj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jigljrqc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkncjf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tggzurmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmulunfd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2edmroqnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upnexpis.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwowdxid.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiwyjhi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkswxxog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eipkmera.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujezehr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woybedsa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvissxk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfgbeti.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqieizre.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmapvjk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulvgap.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2psidmzhk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjlpvfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxuopx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwkxkhw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomurdwt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxclqlq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sidvqgil.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnmuslk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcfjflo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxorpxl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jurmcqvt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofszmn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vtstojca.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbtygux.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jaizhuwf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fugxgcnl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrzunip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aastinae.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbxfmck.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2synlyvmj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kshjujhq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoybvzo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efkdripe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgtpwwt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugokwtio.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2lludgetc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2adwmlcdg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afivhlsg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwpfmur.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zldvuvrz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkppjrr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhbotns.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbqbadg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhdknor.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfdlbww.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkkuuie.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbwjvat.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htkdefcc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sewnksca.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsopcqdx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkbvwne.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxzvakf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2djployet.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2froikgxz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jrimkibo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2eayljruc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklyehuf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxsvcll.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgnibrk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2thoukptl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xrofpkgp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiuxvti.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gthfzpuy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakmizpz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvvbulc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpxicyc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhpklhn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvenbpc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxgskv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnnlvkx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhgsqwk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuupslfz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaenerx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdvdema.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gugfwdci.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uleodhze.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrrzgfx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxlbhnw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiywzdb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnuqqyd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcbbzih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kodlomeo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jikxgjwc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2arnnrnwt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcvgryf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrayhmt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfqomal.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvtpxxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2birutpmc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyjeuzm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2joqgylkn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyzfbfd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpivgfpz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmdtpxb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvmtrsk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdsxuw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2svgcxnrv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvqbzjc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtngfvsu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntreozra.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcghohpg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2brfnzlqc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fklnbeaf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fkidvdug.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlmlufb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qotbhkmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fotufbft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njesccxi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqrkxvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgrnxeh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xbroyvmr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqgpdfn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lubronsh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyxyuxo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyyzhoi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wygqsvfc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqejcal.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddybqmdc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnuooxo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vabpcywz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcgvpqi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2axbwocst.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2prypepuw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iumvwlno.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gojxtuew.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwndqrn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvoymeg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdehcfv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iutdevzm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pjclvmvw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ambahlts.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2thythezh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyzegmi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouijgert.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2psojjztw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzfwjuk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrxstxe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfetchr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2adubsmzy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiqdmol.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nltcmuly.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhitaqxe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jobrtnmf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzjnjzv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jmagfzhe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgnvfj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2thltsjrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmujogai.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsnswwx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnqhzqo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2allcqpwz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzifwghv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2klhvfwoz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2znmhezef.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvwkwbu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oflpzqzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tulpddko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2balgmzvc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqwmrx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ytybfyel.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2unibfzvt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uemdaqmp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoweeef.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoykiqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrstzcqf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgeiyem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soupwzex.html


<!-- 参考信息 -->