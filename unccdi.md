代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqbbzst.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lkromqdy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvedopwj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gavjdqgj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzemnwm.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnpvmzr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkcxqml.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyhitwc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqlghfi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrcikt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnnkvyi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2asdtskrr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2twwghzkb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgflvyw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wysgtcur.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzccmlqt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwzfzfp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iqztjsqx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xkywlmvb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtjrbri.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2iviiuwws.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2efopxqhf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2muskrgwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guxoefvf.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2trwzwdtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwxulpd.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2afioxfjr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbrjall.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2okthoipc.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpjsrfz.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpicoldg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2imhjifsx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcdxsad.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjztjmwy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdyfehc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqiwcpw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iwreesyc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmrutks.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gczqzwes.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pyciodpe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkimfudk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcgffhx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2aesvyzvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqbdwau.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyojipu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqznpr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwgerhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2osguuhtq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzejkwsm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hapiccjy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqqniiz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2nppsuogv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvamykds.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrxnixm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsccgaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfpnwib.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbypkiuj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kspuvgdl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntruxqgk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tadazzfx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswxigo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsdfxpe.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2utyedfdl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2jxckwnql.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuustld.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzdqhdo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsknhmi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wsznglqn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwfozga.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbvtnfi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwboufqt.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tejytsim.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yekdjtbc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikksyrfb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lifkjdbs.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxwiwfa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmckcvr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsizqqv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuwxmqe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkhcwg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiootdp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuafxgak.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmfspmy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxpilge.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmigvft.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrenran.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsxoesw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rusrmflg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qbncxnxh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhmgrpq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ycphrbyh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mumwyuhc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcwdkwv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjajdhp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwscgql.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dedghkqs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iokvqgqm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmokljol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kganjuhs.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwtilul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icujxhpn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjzjax.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2arxwgbou.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2whzrakwl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvceohnh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzcqtas.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yesvvbzf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjezqwm.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcstgxj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbogzkh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmtapzk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaxaqmz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2skzgsqbs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ukshyfeo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2onvcqmop.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfwgloy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcacdrg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sohfghey.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bztptlhb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvodook.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszfytvs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhtjewp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqqrqrb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqaswyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbajsljq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbpkime.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hndxnylk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfxkfsw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gellwjtm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gycivlhj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrrxcof.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnxxmsm.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2celqlxbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zptlradf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfovcfpb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2atdttand.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkleanzv.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoptxdz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvscpppp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dczkcqpi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkbitoo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2orarojpt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisunjsr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sblcdtim.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqwdtve.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxebgha.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkpsbrm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvaxkqv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkvkstl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sejprhwb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrgxlbu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrtommx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oytodfdf.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbeibub.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kopakanc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuflivk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2muhndeeh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpdzexr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hyejqquw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdggzsg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwytrbex.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2smlbwpli.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rpilywld.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnyqqhn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mygpidfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2spqtelbr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcwvuip.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhcpixs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2klfbgaas.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrfksqv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yttgzegj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjqcgjj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hduuxrpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frbujqfu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmzkun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roytokan.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djjrrzmz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btofbhtl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2selagpai.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2duwimpih.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbwbttm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2upkyxpqn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsceejky.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpbiyvs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2woyypbag.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2brdeldsy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjitqpxe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpznalj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2txvwheno.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhavvlq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqqgkzi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbseynps.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgybiyq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvrccdc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgolwyox.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tarwidkz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2iiletpgp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qftxmvtt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lusxsjwp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwqbelf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcuoomq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsovmqv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tinalxio.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyahfwd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzateyjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbkeevn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmgidtg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2klzcudsd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djzhajjj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffiysuc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcapeqr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoginsi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvanmup.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azhdpyuu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyevazou.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hblpiapz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wovnfltr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcnobo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oevbzoba.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkdasxu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnvdngq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lonwbmnn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sivimyis.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkmtabg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmfeuyj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsesrjqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtppjyi.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hefdptjg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvrjuqm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xycowjew.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zombjtek.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2giwxwlak.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxzrlno.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgxkoar.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xubkrqld.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnsxsas.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqfzjpa.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqdvpre.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfxnums.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbyqtbn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrrsqvp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcyupuh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idxqrwia.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvwrjgn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwqqoq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uralazig.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnpqdyj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyihngm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2julmsyxe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxahjlyu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idffulpt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbmpgp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2adqyxjsc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtquqwwq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gavpbwxh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfcgkcp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2joxoaolv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzylgks.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2glrsrtnz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfrlxmq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbpvzsj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqfzobt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yocqteki.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxrbppl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2obucbppk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtkgyby.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgsnguj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gekwkbft.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjnnehi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdsdpmf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fduqvvin.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyeyyzq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhvskaw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tistopfo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmrlry.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpmpjtm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjhohzq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkjlxku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2blekoflo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkbupxw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhvnuvs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmkxhfq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvkgihb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjbbgtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msdegdlx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyqvxmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiawknbo.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aeglmkbl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzscusd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2usahhhgm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2watddgxl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dwshsiky.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsytowy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvtwhbv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewrmujm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnudpmf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zokmzsfz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfcfuzn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2huluzdjr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwnpqkz.html


<!-- 参考信息 -->