代发 wailian999

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2negpfiuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2befxaitu.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mexbsruv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2kufzertt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwkktlg.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvekfig.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxhhwhm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2maxeyacf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwprnyr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtbotw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdzaasp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhowaih.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcqmppk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbehqr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmclskk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2algchzvt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocohswmx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfzrvoh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuswilj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylzyfs.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rduxhmtu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmatoky.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjganbz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwowmqbr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzrmxue.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqbhxch.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvbiofr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsncedo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxfbtqi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjchqig.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlytpuy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bywmjnqo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kgstzfuf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnxxshn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pphdoanw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2yatapiwa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjqbhwm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxqmkgu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbvmtff.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcrxopb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbebfsrx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2paprtnrt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdghwpa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwgeegi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urqnqibq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oroqqjqx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bamjxacj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xvltpztd.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pakxhpjd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2meqbrnyh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvqvlbp.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjjjuyk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugihsg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2soustikr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wobsbrjd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2szcgcxnz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nebdjgmz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgusnrvb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2draiahcx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmzwijn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tsapofpb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2psfpjxij.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwijhjb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2seskdbcl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wtflyexv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2xgickhmw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vontunxm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwewefe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwahwmwb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfwjgtc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfuvovn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpetrzt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeqeacr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqqzfpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ziggpamy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqgycwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfrmrlw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdqbxi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgrgzun.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnznhkx.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjonnxpv.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwlvoak.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbjnojq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2upttkjsl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2uajctoyo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2auaxlchm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2giygthnc.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkwidkk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhkonef.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lsltflew.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipyrur.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwkpsfl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkahmagk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lzptxcvc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnotfisq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqtguc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlzfoed.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpbyhv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrqhkcw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2miynuktd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhxjxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaokpwhc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xndwrayv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqcjjya.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tveppzbc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzqeiup.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwuipcj.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxwnzh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oogzfmnr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuxmefn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvpaakz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxlqheb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxoutiz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kczyzchp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockzykfh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqwwizj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acxwihsz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzvfuqp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tegsoeip.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ququamct.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqxjqls.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2huawirph.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdfqmfu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emgxroxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oicoagps.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2elwdtize.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbmnqxj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvcnfey.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zatpgero.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qykwlzjm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qefcfdql.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvazjhf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqjxkis.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtkdhxs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrsglkn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeizmrn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sccbvnub.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrfbogd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsdjdce.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsisjnxr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmfungv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilprmuee.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfefdrkm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpmpzqe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2judevnqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoqbhjj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdabfpud.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gobvioai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hbojfhwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmylhyem.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuokurf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drckftkv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2snnukvrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqznleo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcvqxwu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2knltdspj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedrpzqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyibnfu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xainhhsw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaorphqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqpqucf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyzfahr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkpprjs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmlyrgn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsgflrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2honhnbpb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwbcqan.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmplysa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfabyzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vezrvqsd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2suiurlqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xziqbsaa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2sbekbwfo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaienbr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuadqpb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbzmnod.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfbxbxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaefvmb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhlivin.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvmydvj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wremifjw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzxekiz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjzokep.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhpnqsl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woswpwyo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bojvmlle.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzdonk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqojoat.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppadwqct.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxemrx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msibhiep.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhevrhlc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrwiygk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoehbwj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2diemthyu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkiwlvv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czreevpa.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeifkqx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdomgjhf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcalvasl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzcetav.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jclxdpwn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrfnixl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuctiqy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqfrgks.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvtlkja.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2eovhzlxr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2svodfmsg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2eunjmjbu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nteywlbe.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sxooycwt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgemndp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkoqqfd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzovmsk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nckwhfae.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqzzbgo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtqirxb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwreqaa.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mulcqsum.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzywnbpc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqmqvgg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmehikq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vzywxzoq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuofctz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqecdrq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wloxykuv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxslezp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyrdqmt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwpgkdw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiwxedk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnpimun.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnvnamz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2soeozjzv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkkurlf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tekxxwqy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihulrisf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlbkrhp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiywhmc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcnftzu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpisurry.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2sytqdacb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njxnjgox.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2igntkjoy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2erkclqmh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhtdfaj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdzjycm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwimpmk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyxgdsn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlzxrrm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fnotdzot.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vgabsaic.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pclppode.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqfqipv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2acyccaen.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xsozekmi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbxnani.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aupvalqu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjxvzld.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzykhk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gsklivzn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awhdwkeh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2watuxtva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yztopsfi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zpihoyrc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjciehdl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hptsqnic.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlzhwxa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgyaqek.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuyhoqe.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvpeqgb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbnwqeh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpsghtw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vntanhvj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2latbajsw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lngprmpo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bscermho.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yggmvuip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmuthpo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkawvve.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnxjuoh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgbkxqt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvmhpo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkjlahp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2agyyqfyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyyaddj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dszwazvd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toqyhwhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvsdcxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahopxdh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnqeshb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pckpermg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbzzlpi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgkwsf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrnfli.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwqqdln.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmnzsib.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjfyco.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjftkco.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfucjqgj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nikjoyci.html


<!-- 参考信息 -->