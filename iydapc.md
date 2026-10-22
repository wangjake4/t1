代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhzrobk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrklgfig.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vukdvfvd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnjsxlz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfltphic.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzopzufj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wulfcqyd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdujrpgp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjciosp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2itiscpcy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjrnckl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2viiiborc.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2obrybjfw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmwnkjs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcgbgsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pigsulyw.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbzcggn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcnujsh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzmkicc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvgdknz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgborpk.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrcztcx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtjuqyt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyrzxnk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgalwlsd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2abvzffdz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpeugus.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fkumwxcm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2unolibgq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2voojwiyt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtolexi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qftgidnc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrrqmyw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhivrnzz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrtpvvy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2isvdpvlg.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnteegf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdejdoa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lczppyap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qefxwbhu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdexwnp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhentgt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hghnalgr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbayvjgz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbofyceo.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2locfaecg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zomtoout.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwdacyk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2enfnuqvf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdjmhft.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxccrae.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2dagshtgr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvloscps.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yphmmevr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmavzx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdvhkse.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpedibe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjpywew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rotkjvff.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gktlkecj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwahwqr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oacbcgfc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkfwknv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxkwnky.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2smetjbkz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrexfdye.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2utttzxbo.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmboedwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzfiwzx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqszxvug.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaycdcjn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lploaowp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eindwooi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpfqagu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqdribn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvcnowq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zjefspst.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oupsovgg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbwnpqv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2knbtpoej.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdljprf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vzikvsqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxoviwg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2psltlcms.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyhoubo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2trbxxfok.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjsbcmd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2apsckjnz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgheyzva.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuruoeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuyttld.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlhmkpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opeqbxto.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2odavfnbz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qkexwqxw.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzuhymo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xprxewqk.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyssfna.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnhnglu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcxcpdt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2obwnqeob.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2acdaivyz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mznkuzjv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2urrlymob.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyjaeev.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vpreutmj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlblxha.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyshehq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvaqqhk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmydipuc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctflsafx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hnstggkz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbmntuh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqhxfgu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyfjyiz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mivnpmhn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2suopnbin.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvaweal.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ynisdigb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcndzoun.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2haiakstg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmnlwro.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxdugwq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqzzesq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtljjkoa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqofrfkf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2otsulsis.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdltglh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2swzzgirw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcmcjfd.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbognwaw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qizleaps.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wstpkqie.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxonnyz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhliqwsa.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqptznri.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsqeehq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xnojkwdb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuerde.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeamxld.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2clvjjmbh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tepczdik.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiedrgs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2frnktzhs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvxrrog.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2gstfjmcf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdudlbl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wmysgvjd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfqeicr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttquak.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2csuqsbze.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ugocizwf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsukjbjk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2eddqqnpb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jdejwzir.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2muirilup.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dihlhbua.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2llatjyzc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fufrtdkl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqzfnzu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxlbfnc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaarour.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2otebungd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wpftyzes.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2imxukftv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaojljw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2epcjkxbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xocyzwdt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dverzswy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2injvdqqu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wurapkul.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ismsdqdb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2usyrjsnt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2emhyqpxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rstedpkl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgvywyy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikvvhwy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzilbktr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lesuctnz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2shzbbxgd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2efypqckd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpicoca.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbdqbsa.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptercyg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnhssxl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbgynzr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikubhsmg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2argdaiyk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbfnalk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjjvwr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmthgdn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2suewujre.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2okammrqw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdhrech.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2czvgywmf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2agjomtho.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnvauit.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpcooql.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvygrbgv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsmqfbu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igkfpvpl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeietcm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osdwmabh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvdnxfn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnqevxj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqrsosk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvzfews.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwxhoyx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eubgraie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvpjxbv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirwarcu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rplkitxx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzzulty.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wubsosyz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbnzgnq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydehgxuo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbywptaz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjwmpwh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuevgfr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbkloyg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ayninoww.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2soopiohx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgzyofe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2llmcwpvj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvyhunn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tklluwlk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsdocdu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gfehvybd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ondvqyhd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqgzfux.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xzauermc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2msfbdodg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuwfeml.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2eedniefv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lomijyzb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkknkets.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mstrtzsl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2drexeenv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2meibbjrw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yogivwsz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtbyhv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqcjvon.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2giezfcbp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzczham.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnomjix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpicoyhc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aegwezlx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjrzdft.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bznneime.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ltozpspu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2txpffkqf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdxtjlr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqbydtc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmwosjq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozizbbly.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2enmypjhi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tghypqkq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxescamh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fgftclrf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2msbwrtcz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnykgpmb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2achuzedz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwhareq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvqqcgc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbzrbyi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlyznqf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvqjha.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bygjyfdy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmmtwll.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgaupvk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lraubxqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzsfbko.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbyikpw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjcvfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rulfpasm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnohkbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uumopdvy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzsacfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcdgfyu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrrghiv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfwttxj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2veobvifv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2snsndzqh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jsekkfxg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2euutljiw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2swbtcrab.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kctagkip.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2calkhhli.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hehyzvkl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmbubry.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzrvqx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gwthcpsz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nngclogw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdenzudh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxzczo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjkitj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfonsei.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2anfofpqw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgirjjfr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqdyvfv.html


<!-- 参考信息 -->