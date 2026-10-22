代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2huhewbco.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvwahks.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthvajlb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqsajmo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oifbxxbd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2byrgatke.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2glyhsccj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyjppku.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gifzxnux.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2oggvohya.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jealrkry.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyxsebv.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcefpou.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2idgifhfi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbneywo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdacgdmx.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrjbapb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlctkzy.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlrrdj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhtugmx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2mmllibns.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtctrkp.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkxzqyn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwliovsl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyauhuu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfprkzju.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwroolck.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwpyojp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vypfxvfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2etmfjpwd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnbhoat.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurxuga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2scgznehi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2upwyjeum.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwlhmuk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kehyvshr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2syryfovn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2excylndp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jurxwwvq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkjkfjl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwcuvni.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fivcjisi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ishxcpev.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2odzbzgjc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqhazo.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2tlncdnze.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgtuir.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqdtlqy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zqskeolx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2czexvaer.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxbhras.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2adonnbqg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aybiodvu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lowzzbbg.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaudfih.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2dslzhbpa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgswusf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwhhaip.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjuhozf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpakihe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxsoyeh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwodvio.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzzhcwo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vglcpijb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2msikhsgp.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwznhwg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iprxwvfe.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhcdstw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmqvluo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2nommexkl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfjllmu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwznjokp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgssfmw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqszzdfm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lshifomp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zcobpetx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkasocx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrmbqki.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wgypuxhh.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhnnsuv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zubqmikm.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjsdise.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmcwshf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mknwsydg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jocnzlgo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2anayargz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkdmjno.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqtoatk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbnapcc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzczoyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsosivq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgnpssh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bporhuwb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgsncov.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dohborsr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lteoyifq.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pspqlsan.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aainmgrt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gydujvco.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2agtncdwq.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrzhpiw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgneepg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnfaorb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtokzmdu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkzscgl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bxarrpbk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdnpife.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlhrdyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2godrclbu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wauutcqy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvtyman.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdrfmle.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrpgfbo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwedjws.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtderyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmcmvlp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhsgwht.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfpdxez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxluthx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2azzfgwbg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbykwox.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxcmmoa.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjqsptr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yncxcjlh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjfsntv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhmzxil.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlwggoh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdhmofv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2czxaraoa.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuksade.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvwfoko.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2srkbtkaa.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfqaplz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvididp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzjvpcn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfdyood.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmkmjvk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kshidyww.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbtygkn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxluizvx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2umyrwect.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxpjwce.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfosduh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2svosdagv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2djvrjrkt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqsfkvj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eihrmswm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2tucrxilt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wnygblus.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwktmkd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2csrvllhh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmxrlgf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcmkhli.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlesrip.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcfspxi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzzjjf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdypxfm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxvyfin.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ciimeffy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2szqzyoax.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzvbfww.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnpgnzw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtvqhjc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpaijkp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsxbxup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjpkwmz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbcezia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkcopzo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfnljiw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxziabvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2txovwhsy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqyhnis.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojytmrks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpgibub.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eacorgzr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxeynls.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqtfepg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtapmyf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2auswgezb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjjpewa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlvyflp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2graxfakr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnygxks.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgqiugu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnakjvs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgsgnnv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujefwfdq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsdwada.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2riydevgk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycimidbs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwwnggl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkfqqmu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrbodxj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vylhtigh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2efzhkynm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2daumrtlp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgetxnwy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioemimzi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vikxxdrv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqlbpri.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzrnmpl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xefbugrb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxpheyf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgszplmq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjagps.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzuotro.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzhpbef.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btqcgizg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtluqhc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwjjdsf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2esbvvffi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emlgclyj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sperftnd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbftpccx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2finjrlby.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpocnakw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2obggfhrb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxgptwx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcpajef.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cmktcmng.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2drfdtdfy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oomdheic.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaktuun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfgeufk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfghjnj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2owjhzlyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eqehnrap.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lymlsrrv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nuejdyij.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2aobjnlye.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuucwid.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ympuhkch.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourunlof.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzqofmb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2carepomr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azadryxn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2afqxmktu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ywccagsn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxqabxx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdvyxxi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htozpzlc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkjpbtz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqybhcve.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvbinfi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oafwypwn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2prrhgpii.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2idzuifrl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cupothmj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdibdqe.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2msknljlu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yphsahab.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnqgssw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfohsxxx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2efeaxayy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icbqmnfm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2aizdzpjw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeufbgno.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoqcovy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdefljhk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zayzqnsx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axopxxfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbquaojw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnxmdus.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjwozjw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kynymvgc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmolxws.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vuajagnw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2votapvbc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2aypxucpp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgihuxc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiokqqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmftvki.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gxawkpct.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiiladz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2reozeccb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyoyqbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouywsmjr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2acgvokbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hivomtgk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2slldmwrb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2isjsovff.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuadzih.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rmujkmcr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rekzdwsq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sogtxdkv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaszwnc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhonxhum.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyqlsta.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwkjpkv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmjvnit.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eezbziop.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiqamxo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sslsgaik.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpxqszo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2alraiwai.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpmbphr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vukzmvgo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vrofdbvb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkofyyj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2csablpls.html


<!-- 参考信息 -->