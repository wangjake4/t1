代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxrjfsv.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2attvomzv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkvubip.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaoakgt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rssvapuw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvjhdte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrgwiac.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkonxlsw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmioxtlc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvucslhu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2nipxoina.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrgoixy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsdvatv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hagxpqhl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsecxgu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhocomw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2newkvksi.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgovwlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjnerwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjvgymw.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oruwuipq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gryalijw.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpsgryl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxsywxk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzbncbm.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhietojk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2stenrjea.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2txjgehmr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkakncyd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvutmzrt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzthepbm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyniofr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eiobpdpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdsgayv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgzauwa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiwhosn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2korknanh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaurogj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2yywfpxob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyiixiu.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2isgfoolz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwczqnx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmqazzp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeqvcnt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2amepyqyt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxcahaz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyucnqk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjexhwm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwefizfz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrngji.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlhiixh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2egwdkxqg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgxtqqh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnzkjjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lywkkicy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlovrsn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxnyqho.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxycyyfp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2gttjwoes.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrxfsfh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epxotddu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zemukkae.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvupbla.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2etirssbm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvxhvvu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfiqeet.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mypwkuls.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdxjbzb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdqtuwr.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nniicctp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtidvgd.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gknrokie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtttbhvp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhpnopd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqnxtjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrfzine.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jewnfxwx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lamdqswm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2enzdmsuw.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pndyuxsg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiqvkab.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqzxsrf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjibyyv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uemgxohx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiidhhc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2miwopqao.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhoxqok.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sehczgig.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjilmiil.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oumodzwg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2umizzdif.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2chpaxqfu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2neheajvh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2txppiiqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqdeeuq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkxylqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqgmvag.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omcqrvww.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ongpzfxg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuslojvo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhtjxvh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bganbyfe.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbpxsmd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkavzlmg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2crwxlngq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaowlgk.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mociisru.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsjxgrg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vajphvbw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2uckissfz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgszhkg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2daseaooc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrdzril.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrmvovh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mezajtss.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uzudoxzx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rflioimv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjzgfn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzkqbvs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwrtbec.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjfuntb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mprozwtn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rndegnkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fumebpev.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xkizstro.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfeuwzp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvoohgo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgomacvh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2klztzhcj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vantpwzd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqauxkqd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2sibcmxxk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxubcacc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnhnltt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chsqypjn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyyicaj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoohtcv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyoegky.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawqtsiy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsirssvf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxbder.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wxajcsav.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjpfyev.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqpacyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzeqtiu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jesjjccl.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2skfeytzc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sthxgika.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiposrjq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jklbgqzs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyyjriu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2grwxicbp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2acudfcis.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hszaxfxt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2eukeysna.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mltenoft.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqdmpri.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2porsoyjo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qiradhld.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmfmycx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmpcgko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xihwpcaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeahqni.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxxfzzy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlzkunq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ockgnawx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjngpdqm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcuhrvn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxlpqst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eevnallw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkrmgeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krbkihkz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2exmgxpdq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecayjitz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmsylly.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbskuuo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2omexcvxf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcmmkox.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2disqvpmc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mabskbzc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tksfnydj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mamithrk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2akclhpre.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwsgjr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhfkqmr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lajrrgwa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcsprtq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprtxmnd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwdwzno.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfcjttf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfjeuth.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhorscl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvebvxc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2svnleviu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgsfzjr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqfzffd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xsngufym.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qzasvemj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fodcwftr.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2leophclq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwdiquw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwksgbiz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwvawew.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhmrojk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuecvhpj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fynkolgd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dndiyoqs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iakkzcgq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnleftj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkdqtgi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzjcnqk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxidvgu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxdhcbn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hubifwvh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrrirpw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgbnrfv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lekzenyy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2noszfleg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzrcfsu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasngewb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gypzoyks.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeoupzm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2klxqcyvb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lwypjrkh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifqqvs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2augilsfx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfzvnuy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnpeuoz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqydviv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxieajhj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2bppridub.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjuughk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lrddrljl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqfhocd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfwngna.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2znvozemy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisoopxc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2witkafma.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfafrbsz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qoljbqul.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kccwguyn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wszlbwzs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhywqlz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxausia.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzncioqw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlttjru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqyiwax.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjxvxqr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrewdiq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbosgkj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvxipae.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gugqqlpi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkyecpl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfukjmp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2amizvvia.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iamlqzbp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mayjzpmy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2flnzifip.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiymjlu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwczeit.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2inirjjec.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpcuubs.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjiucr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcsfwzn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzzbxph.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqgzmrl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kgydjfyd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otavcpar.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czttsyev.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyrrjqt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zllffihi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqlgxbe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssykckll.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2isebecsk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlvtykc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvlhkln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbzyfzi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyaeool.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwxnewf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2apmunknc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpmtsbo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aggsgqkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbjidpd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjjeupl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjtzavm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hweolcby.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rubjqbkw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oahcwtbq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcaagzr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qstrdpvv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnjxcuv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dwznaolc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bnleegrr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekhifwn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqmdwjo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqmvsky.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbjszsq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nscaouer.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjpfxue.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtrkdsm.html


<!-- 参考信息 -->