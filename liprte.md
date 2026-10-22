代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2shbrappz.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxlzgnh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsulyqh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2txmwirhr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xykhiipz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqsnbzh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sizlqopq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahilnnqd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcgzkld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvznyaz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2yowuqazv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoexdorf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2munnfmzh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxqwgiu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjxgvml.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmgrmzu.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2juanlzkc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewjticg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyxyarv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfouyljq.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2afandisb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tachhcsa.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrgrtzd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqycleg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2nidnlolc.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrahelhr.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2otzyvriw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wycqdbls.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjxpnag.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2oujqmihv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcayjrnn.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbkuham.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbfuoxl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gmltohxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjhmfty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvptfqb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cckcmbhz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2gripgrol.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtylqip.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qetcxqqz.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2htlngbrt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2dewqknci.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyecmdf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2owiftjpi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2jovriuka.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuluoyd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lppvkyku.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwgtxoi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmilgjvh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dltyplxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdyqaz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiwjdqf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgdswys.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2truwfbsj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqlugqs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzizwqsy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrcyujj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgbuwkd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2capskvmz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxgkgml.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmtnupr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2htvpyqon.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnvyqne.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkwaobp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osceqctq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2riqahcip.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjjilmh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2umajftyl.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2quqqkfbl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeblqgi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybrwma.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbdtnvn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2azakkzoo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbtguvx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtusgibd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxywyylz.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2crhvnlys.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnygphdk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzyfbyd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2djwgjcsz.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxmesfz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvhpvmo.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ibglhsox.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ogornmmj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2itmvengq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2onkbntvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2yitsdwld.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jljucltv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2carftyln.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkceugfb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hocylkrz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtamclz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2njpcpwia.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2suelydvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lktauior.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yerrvubv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfosivhv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkofkcfv.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyenoiw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2agpelbnq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdaodvj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2checxspb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gplepety.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lpatqwxz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gdalpuxp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2swvkanox.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axyaottg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbidpgay.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vckgrlbx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dpofqmyw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjpocub.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2whhekxwu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2laymjbjg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfhyjck.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmbigkn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcrymur.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgopozcv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjdqkoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2stgcsdfm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiruqqn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnyyyad.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2sljnszyq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2scjrpqts.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2alibalvv.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iqypflwa.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuiglbg.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhpoyzf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wohkrtna.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2omucwslx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wezhrnwz.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fypfbdvd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqfgfru.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeoliug.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yyremgfk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2puneugsf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qchpivaz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqassba.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlkqodj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uutyhrad.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhwalkm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akxjzfto.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vpilzfoz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmlaoeh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwpmaff.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeotsxmw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2boqefihb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhfrirf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iswllxpu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzzqppv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuvjsya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlwaxpo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhgnbeq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjgphua.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2douyhfzp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2peedofwk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyolrdv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqodxlz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kclxpvcg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpmqkfh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsugyiu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuceuym.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmverteo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ceosipkw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lobajalk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqhwgzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2aigpoybp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhvqmsz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbylngg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hokqzcyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruixkiqc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbqjqwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2idibbwrl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2svgncvll.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaojjrse.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnzfmpd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzioqn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2alnwzrnf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qncstzzo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgnucy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rosbgrwo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlqxzpg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2csnpzscn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcplaxbq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qglgcsht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonkkoxk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfggank.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkyywii.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmewnzi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2udinyxsd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxobcahl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wswgfgjc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiimlpp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfwnvke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuojnzw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zghacnvn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lozimsgc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jjthkeiy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2eggickcg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuuezyv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xamnulzp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbidth.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsvmnce.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jubfymuc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzgpoqk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psmdmkrc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhayzxt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoqqjer.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbycfnv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtfvlhj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopupxil.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfduhcrz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqdkkup.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlhsmii.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxabbop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mislhlbs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbbswds.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifmtndk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqbfyra.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xnasgrka.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgucoeho.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2djbrtvjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2evofwajo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgtearw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvygzfo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhqonfy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfgrkwv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtftcdvn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2efyrctra.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbnogif.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvsbllj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjwwnpp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwuetnt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvesgt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vghwirxf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xeysnxic.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2anbkpdqr.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swqrrboh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgvpetd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xlithxow.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ngclfssl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbkmecg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkphoctp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qqslkxsr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pidcwzan.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ueddhxrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2muxymxti.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmbfatl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmietyc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rgygcejd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfqyawp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqqllmc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2agbwnhdc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkmnfuh.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeeprev.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrrizvd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuppxsbl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsunhkzz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqsxhnj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaudcihe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkessln.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifvpinj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hofktpfg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bckptlkp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpgsawi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuywkuc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2btrhauck.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eevzsaub.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bfagcbdh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqdbupr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fmohuquc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zupepjjw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iljcpcgy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmuzvtk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eodwhhss.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkkoyqu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iomnfizc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpokbpc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwipblqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2feiicidb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qofyvjve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2marlomob.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfppjls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtispfz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljamqipf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajieifub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtifawgr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqejscl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2imxcvhgx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cljzntzz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2utksrbxt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzoumd.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pwopdllw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdlxwvj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnpaodf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtbduzx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2asxiadsx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fozdmvch.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfjqjyy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nngiejiw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wnydzknm.html


<!-- 参考信息 -->