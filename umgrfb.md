代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpwfhiv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tkejblyk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixnuloj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlhuzgg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdyijmp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xslavmyp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2agvtipaf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgshaisq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkbanhh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtyizqu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfcbmyz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdluowb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eocxkhvm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bltqbzan.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwogxzc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qijhypsq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqsekxl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqjrjsf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxubtfej.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2erobesqq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnatqzi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlcapyj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxzfse.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2zibvjzwo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mitrqdcp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2roipgwee.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvcyodz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqsfppg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhgeqs.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejokrfkg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojynnunb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgqpehn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpoumdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmrmzg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyufmsv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wddsgyfs.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnqodca.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvymblt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2haxxntvq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ojycxzcc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2avupulhk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxnpvgk.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnjzlyv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlsohlx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmlgfcp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nxesuzib.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdvegeh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmydtxt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwptribp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhnvxqg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ieprkmzw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2epkojugx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpctisw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdwnwgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nieirihu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjvvomp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vafrxklu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sehestxw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tscfljgv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqpxvuk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkbchme.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcwfgye.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtwsuem.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrtrqgs.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2aliytmrw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiuelcc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpysptux.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gezytdoj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhdvith.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2glargmwe.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2unjijhdg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwegrvwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2khrhnqfk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyepsuuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2voaibidk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2chfezmlx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrthlkrw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlvasxy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmeqnrd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kufoiyae.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yedgbubf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsdpavm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyjdmwx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyhgfdd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jdemvhng.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbsdsjj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqrlbrd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnphplmr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsxfrmb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwjvizi.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lslervcq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnqpjof.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2illqzipb.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2waszqima.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmczeihq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2udtqshcr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfqtqiq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnhkwkg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fynqavqf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyuomcg.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2agckpiem.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmipdbf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkaawsy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xywmcble.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcluyirb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yksojudl.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaysfhv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxhhneu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyejqmzk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgwzlnw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzxbugz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkrmcmj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjzllph.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oshrmyxh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxpygow.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfjpguv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lotsvxke.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvwiggx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hffxeqxh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaaxfgb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pixsdcaz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfovoznx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvkjgzt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmfifex.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjlepmh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbehqbr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2alisjddw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hszjpfxs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwgvgue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtnmajq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnojalzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcmlrkx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkmgcko.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngykhlsj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxvijpn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbfhxdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2caruajxk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygxsuou.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazpxkod.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yepspkcu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnficnll.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaczrlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnltybvq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwygfli.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oifoayqu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxtuxki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2noagckbw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtofnpuq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbjonlj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbyhlzt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2moabdanl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnzfvqv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zourgqgl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xpegqizf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnleejxq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcnhjgy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpomuxx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yppbvucx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhxrsrq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mffhrkbn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtegsbz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeibksfn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xojiozmi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxujsbbx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2veahaadz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2twefohkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrgzmmx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvtmrsb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2orncpkhd.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgyyjin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfxzvaq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkvnshg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sleikzwr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxrmkpg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuafmyv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucmobdv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxctdkjx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwikjscy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2klrhpoii.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmchvhdq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2myjeqscd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzonedu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsuwjyj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbeovpm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzwndla.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsbtgkh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjliykxv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kadorttu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rpckxyit.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsrucmi.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rradwfde.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ludydomc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrvdijh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmwplxu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxcqyaa.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzlakoy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexpxvjp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxijkpm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifshvmma.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dahcyita.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uoodnfpd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqeggoq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvxekan.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuujpva.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxreuln.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmczwwu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzmjzgi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcplzdye.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2phmdrznl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtsnxky.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkimhud.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaebtvnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2komfiyeq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgzjabz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlefelj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xerkcgfz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgybkjw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvdencl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcmtotd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhbiabp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjzyrsm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epvoxdfx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgqgosk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxsfbuc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiepjvvc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhgyzas.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpbfiqs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrvvejb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvsqqdz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjbxhko.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bitjfjza.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyhiktf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsqrwxo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdtvoxi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2injbxcuj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sditdofv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmuyoyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdophhso.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnfjas.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2igjwvfjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kavawjft.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjjpbiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxqpyaf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vyihxumk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzttzpbr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvivlysp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvmwzku.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zunngfue.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiljcrjy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyoczaa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpgogsf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyuaszh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qvosogmr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkihplkr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvchxoj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2emzozuqk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uthlhqyi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2txdeqhsf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2alirlurf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2aemgoujy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wnskwqhy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2avoxftjk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bswhrwsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqktzhb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2umvvxpwj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkrrnhe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtlnfgk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxfpcrg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inroesyh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvglkkt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cltbmscq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfglbunz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvfaou.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukphpus.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvikvknk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qztkakyt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2drtnrltp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkhecwp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezmjope.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2loengcey.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2grrhlwel.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vdluuatz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjoxgyi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dszqykvr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hromqzcf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyygrmq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhciadf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czzueetw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rylfcpmv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wucaahnt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyiahkh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ryimigun.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vallckzd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ficcgvnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lomwienn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bfizlgyx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxncvuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmmqkpr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wazaqatq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtfyeeg.html


<!-- 参考信息 -->