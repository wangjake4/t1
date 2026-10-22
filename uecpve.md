代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2dcemnarl.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqbisle.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbgggsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnflgbml.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2slhjrkhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwaobxl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjqwnkw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaxsomb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2zigstess.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgchaeig.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnsdzmo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkryozya.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2litoycpp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfjsapx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfceqao.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuohjse.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdmatjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2skfydkhu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqegiwa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkizqxc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcfutdy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohsuza.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiuxdle.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cizrzqhn.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxugotc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuxbwgz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2btftfwml.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkyxrcp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2astluqwu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgzpfqh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyiiulz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2efxclkcp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktukjfif.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pubndkmy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqocqb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2niyfkluo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jwskmrkw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgbspau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yimisebo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpbkiyr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyacmzj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqnhhnj.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2llhremfy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiehysi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2grqsdswx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lamauocn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqpkljf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vqofrrnp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrufiyun.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2btpfnunp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzbhxpr.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cxesxsaj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwjxwlr.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurxbqnx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrrujmt.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugviyjkc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjehqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qydpkxbh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2saikekkp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fniqfvzb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvulglux.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2khtvwoqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmjojtd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2spcahepu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzlqhnn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnawblfz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwnvpvb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tkppncia.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2izwdluqw.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2uksnjyac.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqzurxl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2heemangh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jppuswrm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qemxqmav.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ovekazxm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxnyqy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxpbebd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlepwon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akncokoz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vamdgxaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sofoxruo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwebxrc.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzzfgnf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjivebq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaeuawa.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxxepl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwzvfzs.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyfbrkn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ansizufb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlfhulz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtbmlvo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjxpele.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2epofgzpb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hpahanll.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ftamtbon.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeefgxc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyekktf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxesmhm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqozunin.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpwsgok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfnwzum.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpbiezj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwguxprg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqazdwdf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uysryjmo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2swljhpyk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ithpvcbh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qirajncr.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bokeiiwc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hootskea.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpsoxy.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2thkyyljh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2beoiipts.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rapfggjv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhbynec.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbbeegb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxnrrbi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2drojlgwl.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybfwlw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgknjnox.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvsyaxm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfgpifo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzpvnhw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvqdroa.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yzujgwii.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkccifc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtqehgg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zziedfqr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fawxlrxr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdzoddk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjfomgd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsvbsxn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzdfxr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2opnhldoq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wucpepjs.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vtniktad.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2umublghn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwghzzh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjnwirf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ymchhvvk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyxhabe.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmyxchl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jxutoiom.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoczjbsk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdnbshs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtbmvxa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ourdcaip.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhwnlim.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvzgtrj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhugmbjk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxdxzzt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2etpijzge.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvoeqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqhzuse.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdfafxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpxzdes.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzfjiub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnxdgmt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayklgqvw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2brcydjvd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyglplcx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbfhtez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2agqubgks.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qltzaklq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dludzrai.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyxvkjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2maqierkh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqsnzyd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzzyuzb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxjlnqm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwfmgfq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lredfqnq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2okidnanu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocapifpp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjgtnfd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjnygxh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wxilczan.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tusnremz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewajmqpf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjqbxr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aukzrkma.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2afehepty.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrvigdu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2tphrsimy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdoviqy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smimouzk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2scdjmztj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xagbaull.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwklfows.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxemrzvm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcmpuza.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsdpook.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaetfxe.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxoqwqf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbjhyuq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haiohhgt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvrbqxv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmjrksv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yukabdig.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxamcbf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexibfad.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crldxhki.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuefkbx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyfneaj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpcpwx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfygxete.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawmvsu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2muewdeze.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nugcjdjb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2daflelum.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2seyvsxcx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gzutiehu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sosxyifz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxjvuwz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlegzmxc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2inhzihlx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfjxiiz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aguxdwuz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbvaegy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrgtxvn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlsvbyj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnmtgj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uloaoici.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqbtqhn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjkrjmz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnqgxqo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2iexccuyp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlmhvsy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cemekpiv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qowvbmth.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lddlbihx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjfucjp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vamxabsc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaornoj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfmyvqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxywevg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmsycyt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uyybuwyy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkwnsje.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuhtraj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzhncwd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qycavksu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woojaqbh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgtixfs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaeqhwi.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bygtnanl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfzrddk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjotcnf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plsyqtei.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpyhuap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zihlngty.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaaoccu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzayzkn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lveqkyvm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzdbsuv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsczoven.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiuiiky.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjjfhyc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbycyvfc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqnfkes.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kekhxomz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlioabaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cscoosjf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfmprrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xymektnb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2elalyigr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbvvvyc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxoholyh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bupyrcqc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqxuhom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzdvjpl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfhseny.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbnshzl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxetcfwy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuufqsh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ickwriwu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjgcyot.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfakuavd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdptade.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdfqehk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2voiyywox.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmngvwcg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqpisvv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqopqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ebinsjzv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dulttfal.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kffdixfb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgrizgb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbnizzz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mftvxapd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsopfwa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cirdcuyg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvutbauc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjueujfg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvdcrll.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzaufnn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjgxthz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyaqosj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsfxokd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2glquefgi.html


<!-- 参考信息 -->