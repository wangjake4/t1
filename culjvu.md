代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhenzep.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2agojbnel.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrliqmz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdjzzxz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2itplowni.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vndnfcwu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgdeagu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqurxbr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbbymb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmbnzzj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlwqupn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeitcaa.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2suttezgv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzyofvu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2emmfywuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrfqndn.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ajezqpfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yveycoas.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqbpwq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzkwwnp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2aeziwzbh.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2taturgje.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrsxpvz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2majfwgfy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2icsapdnw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2deowsnlz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zevxctlr.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fonxvoit.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbbftjm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqqrrjd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ezixxnqg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxrupqt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwnqqbw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2stparizn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbssetf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkshwqj.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2djugstaa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznsbes.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krftpmsd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyzpjqg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaxwmqe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2eojkzvzn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2qovvroaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2irgujbfs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jijxauqy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2peqqfnil.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjadflzq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeymrmyv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yappqqzh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdjnioz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqabcatv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeckjgj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yadbwnfr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgxuvjg.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2yusotcpp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdmakdd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewvrmza.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pkruqtup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfyoovz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoouwrk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljszczhr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpinhzi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2luxupicg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfdovsp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2izdvkfsn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ithoregc.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhkvnfg.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqldzll.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussaywmh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dldletwh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrykxcr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbghlnsr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2invzaava.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zajhghwz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfopeaoe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgqebtw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2calrixrq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hveacujc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2itbzqews.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2karliknw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kfttfwnj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkbkajd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbnylly.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wukjodpb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hacchtik.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2llvidvmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyhcbry.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvnzfvd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqpjjmg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgubpxip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyajfuqb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iotujfbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsktjox.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgurgmwy.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhprgob.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoadzuf.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzspsxz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfpcwav.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bidrsbjg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwhpnt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zybpkhbd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vumiozpe.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emxszgae.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2huaqutor.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnctadh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgnhlek.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2psszcuog.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lchlrvun.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxodjun.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjnhgto.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaxcpkc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jbupebmj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbdtxfx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvjtbtk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nefzygig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gorzvcod.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2heoizozx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mafnejaq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrxtvpo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjdmqvo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqnkmru.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwijpuv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsbwztc.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpilcwuw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdodjny.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbbirqi.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqobpan.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jkblnaar.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnvclqh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrfjoqn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtecfyc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhmhnpn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhyczad.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkkzrwf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhbpeft.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlnjzsq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxouuhlp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jswhwgwu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2udclzjwz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfctshee.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfpoauz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaufhvm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxiuyzs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxlubuf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmqghuq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtegxea.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjakyty.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpxrzgz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ibytvacd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iimodvfv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjwgsve.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvvinrh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxpyvdx.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxoamvo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2sutrnoiq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kypyapmt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rflholiw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qglxnoww.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdxltea.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2atwiypuc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqyxkqy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2otljlilw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fljygxiq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuriyuf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwigumj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eykaccdb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxctqtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xntlxqlz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawjffp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbzjbac.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuistex.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvbabv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wetocsoh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzxrrls.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xypgzhez.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvvsodd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2whmhrqii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqyuvq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnykjaj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsnbenm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnwycsz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzfdbip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnrrzkm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svwafoxt.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpgvwjn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdipdsw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkdnnyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqusoth.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2glnyirex.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2alngguhx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vhleghuy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkbybur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pramxexj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2edbkgjet.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmkzcvm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqyxvs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzttnjoo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykybsnpz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbixisb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhfmrig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgjdlid.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eogoovdh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnirhgco.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewtbbsv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2amiqjrub.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2veciiund.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztoyhog.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxqsmpo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eonnzmjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoodcjuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqdnlzv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqzbcur.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkowlzd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2latsrvxm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnohrpo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2srurwgpa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiueuoji.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2totbhcli.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvixirvn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twglehmr.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyirpsl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jeipncqf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hswfyxgf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hljafhdd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2saxwusim.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgcvngk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hogmrwqa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2faxcfufl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mfehrrsi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2uuogzlug.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yisldaox.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2iocvqanf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcomqxyt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwiebnz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsjxmst.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpxjifq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwtyofa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjuypiu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcuxwdw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2skgjohdc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lucekjsi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcufrfpr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpdzxfd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbtzcab.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbrqusp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfinjeyw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyawxya.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cjerifmg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfghsts.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2alevyiik.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpyxewm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwumvnxx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uamkmysq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvxbgfk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naultlba.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuiibds.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoncktbg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krtkkkny.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jefzvyfe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zolqajwz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrnsspc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbtasfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkmupkg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2myciyxhf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjslvsf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtumoeh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2leatwmqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aulgpbzi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hteqqbzx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2knhclulh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlshtlo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjgoiht.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlvjqiw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrbajiu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrkoxbw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgzmtuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prlponke.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwixjsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmwtegp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkeiouw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sblalljl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mczixygo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnfjqmi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxjsxay.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2khdwvits.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqvvsim.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqlcsan.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfycuae.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwcfaoz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrwngtq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2crpcxojm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ierbyxqm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2asggkpdo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2purjlntm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpzwluz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrlexmd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyonboc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjpskpz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cevraeks.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfpbiyy.html


<!-- 参考信息 -->