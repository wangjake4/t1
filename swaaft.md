代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgbhmyx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffussqfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaghdcr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsabinw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcggsgb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgznmdo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfyqrci.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwwmbxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxsqeal.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ilycipir.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ijicbewk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpgzihy.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoofdkg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwleclrd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fbghnowu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaoloej.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhoddsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jehebccf.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2knqavaug.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2agfhwdaj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdmevyo.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuuejmy.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzjlczy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbmlxnr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ollgndmm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwmgaph.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngetnmyl.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyzjute.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2aasxalws.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2yxplilsj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlixacb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmtxujk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbectrgs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsrvawc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxpsdgq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2adhygjuh.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrnwqzg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkbtybs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pddjofdf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbcfsi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxihvvz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqsysjo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2kitguvud.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2atpfspif.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbgoheq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vasihvvy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgrlaxs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjdpofj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aolbhfbn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yqblwpyb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcyepwv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhezkhuh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqoxkfs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dskowjjb.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqschjm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2eqotpcty.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjpclal.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2amymzwxy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhbkdlh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2okijybop.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ideybnye.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ziypbcpq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyzgfyr.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iestewmq.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrrqvrv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfbbvfe.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nojuzfhh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrujjgbw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtaxgyb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pafihlyo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeklbwl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2slhhfphv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyvzevo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2okcwroan.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2snwtozba.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2romrjuwy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wxumdpoj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrcuvnz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcdwdrm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqqywtt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hmddzsso.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2iajmcjks.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ffylsouw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwphypjo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2secgucqb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqhtlzj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqfihwx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2icpzitpg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2umpqftkq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbavsooe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btptjiwp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhzikiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bynkjiai.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2reliymuz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhuwtlw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qubbjamb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfdsvxn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifqkbkq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsatvizz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrvxoni.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqhpprd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2isebzsze.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uirqiqyy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pixfczaf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2saysjsfe.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wocvqxab.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kqupcmfg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnwimfl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdelhqk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xtirphiv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftgyyo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eckqaxlf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxhkytm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvtekwy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpxjojc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cghqment.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxltbmze.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdiaolr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jepylhgd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoozjft.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjrmaqr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhewckz.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiipsxt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygslmpzj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2evavnhko.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohouepsh.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtbjdtq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uyysggmp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bufavqlw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2uuflfywd.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqkwjhh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2munfkvsf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaocmwvy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaxnftn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxidzgk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfjwpzy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxlewof.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfngcxa.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlptfucc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnixcywf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzmnyln.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuwcvar.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jafxbkys.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tehntrrv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2plqwfpbc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcsbffx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2agjabsjj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ygishmfg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2aucijfdl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsuymyq.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2obdvonde.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqqaalk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzixlev.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycepwpvx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2viucgzaz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtyhyzv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhttsln.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftutvuqh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfiwqdt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ephhhpin.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iaikumop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgxvrtt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2savqpwdc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsxemvk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrnigtw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiqgntf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhcprpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeinlbs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gswznnse.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2diznjtyt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyewfpbd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbyqriy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjcljws.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2figayosk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcotpam.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhglsox.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtqsxlq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2shatkccl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdjmzyy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjwbqqz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhbshmj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqlrxmc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcmqcco.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgepadul.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khpwisnu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhqjlww.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjcaxft.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rumxgjua.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbzameb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2aaixdeda.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jggcdbqu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2omlnjetu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pthnlcxf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2blmixlqq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpblkbx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2clrkxbzp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcexzbvn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fempltyg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqvbgse.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bztvajyx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvlvgmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gajvukac.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgrydaw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2huexkozx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqzxnmy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrhwzxr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkijyns.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwoixzo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpsktcr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpjtfwr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrxbpnn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oefhmimi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbvafvb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjientyx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uujtbrct.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjswcmc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexdfdg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oajvxykb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzluqrv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2najnzdbp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sxixnugp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwndepd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2awuqcfhz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2gcihgshd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2podvlfpn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvgapsm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadcepp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mnazwffg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzquqnof.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnvzfuk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tehibxsx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkicrrcc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2haptfmen.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlmjzpu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dznvvtqz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owfjtozr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jytceizk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiaebpy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2inkawext.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxlggum.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrhxlqf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlqqtiu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjvalsm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvvtmkf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sdautamr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwysgcvv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tblllxxc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2okzaljyh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhlixtm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wffalhev.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzkiphp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpgdllj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2giexgosy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2duggsjiw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnovqla.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcelbzpi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyxvqhl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkvkul.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxgrzrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wwicwpge.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhnpmob.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmiwknu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rytperee.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yibqbiaq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jswbwbod.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuqwohm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxditsw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvyuzjg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsefvdwi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2orcktpec.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoprvsg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjomlh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsqgnsg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnjxuey.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnhpwej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oipuidoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eegvbgkm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ymogxpyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcfczje.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvchxk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmkljzi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtbxghx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lesvghot.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjbtwky.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqwrqia.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyxyjqt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkixytyz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ittxfkub.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2utlqupqq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbjpede.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxpmiqa.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoinogo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgydxov.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2glaiycqa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yphjgadc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfandbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bhievedt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yacnmbqc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhrlhsk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nobddlvl.html


<!-- 参考信息 -->