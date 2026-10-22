代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvblsuxx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhycigri.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivywgwkp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkqedjf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbbpdcf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyghzlz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnxvvgw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqxocjc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyplijh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kroorwdt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fikfrlwn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxuuzys.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2peowtrsy.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwzqzdo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2peyabdeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjsqrfb.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdraxhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnrbdsw.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgthsbk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvyhigg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2aadwxwty.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqibqyv.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyizfiik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwwdini.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdfchu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkcsctv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwapmugn.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wanxvjmg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iofjniut.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjsgtdz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2clztefvj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jngfqbpm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2klgaxdmo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2klxziqge.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzdxmtk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zidbfkbz.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2jywohqco.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqathts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayldsnya.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbgtrfq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2etxxikds.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cykynqef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnplsok.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjysjudh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqmvndz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhplxne.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosnkrdz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hogqzjsh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2khhjmvse.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcghltgj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvxrolw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2usddqveo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibauknmz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvatmuw.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecovklia.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmleppv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzgrtim.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqnjskl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhdhqnq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvlxpfn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wixaknci.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtmcdon.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhlajpk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaplorv.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2txamejaj.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyihsl.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzqbpim.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijircyag.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2caoadjdn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdddwgm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlogpdnm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ueveeglg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gatdcxgl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaekmgp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkghiibd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcxvnmg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgompgn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nreqysty.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2umegeyox.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdncpwc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemoqqo.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqbmiih.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtueytx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzngyiuu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jykfbmrd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmorrtsc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmxglak.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkarubg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcueabr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zynoutvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkmdqzg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2owedlkae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luwzthip.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcchfsz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2acolojfu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2svqzgnnc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyvhyym.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxmdpha.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaqroav.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yonwisgw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsywdng.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylygljzc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzzkdfy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2aasburyr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvqhfk.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2khziwgox.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2atrsxsej.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eknqnkji.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcqjzam.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aihllqof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sefltqzj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqpgikr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhphljsg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqukewa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sriuhrmw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqitxrmn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fupssvis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqhszjp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpprgfl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrncfxo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iavoxhmf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmwoufb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfgoeim.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aixyxgao.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2peyugxma.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyievfhg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qffbilqn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lumwythf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhghlrj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2owtyaeif.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhokzekk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vndfenig.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhchnakt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsmqrcf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthpdjrz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thxzlmtb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbnkkxq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxzjhaz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgbtohv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zftklqwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2txxaduwd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfpxkvr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwoxzhl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecapdrsx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfixjoc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2slxkmwhx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfjqpie.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2eahemfha.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoetdrf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uaijnrbi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhiphzz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhspqve.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2stittkuv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kerihfxa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nortjkvo.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2aflpfttg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeodafp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwovfhur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pznifssm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrztcdn.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2aarpjtuv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdmyvhn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2iunxolkm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qobeodix.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgmzxdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akhlauug.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yybscadh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzgfpe.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yunjkegb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxlqntx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sprenvuj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2afycgxxy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzokrfwe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqudhwqg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttobqxbo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsvxtwo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2geequiqk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjtuntc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwxyxyo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrbyfbt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmawqq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2acmvwvmb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cachffya.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmzpsyi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrbmxli.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ramncijw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2exqpewzl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zephptsu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2parsyiwv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oltgkvwi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mugudnhx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2szsomakp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaeerkm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2llafrkhu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfmzyy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhqykae.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvsrqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwosrojc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2usdojgwu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2egppkblm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckumzvel.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jztzeupi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzmybrz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcgmobv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzieexk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsikytfy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzfwzc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zurewrbn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbjluqy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqakxgjv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yomleuln.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxojxcpj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwqmmpv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phzcljro.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrppgsm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbshtyrv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhgbwbo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgtdmr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gohgwcjy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uebmbzjr.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sayaargo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2opctware.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2leyrehgh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2radznztf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgkvii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjogdyrm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2heofcqfy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rnioofgf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vtewnqqn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2scjlnnnt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvhhot.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnguvpp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfdjsyt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfpaegv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2avvyinow.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoqzcfw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmpoorw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zoothjbd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xxclkipz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sinjptrh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzizbnuo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnthdawv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owkjcmwt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouksaljo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2serkzpsz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rakeljkt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyeioop.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqweckj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeowolo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcchlmmv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2thipngmp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgjegav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2axuyuskq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iognkztk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfppbcp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlyazhc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbbcxrt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbkxorm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgxdwjm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgwbggx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diuzskir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuptbzfo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkptcl.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcwinzm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnevypl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2oijenzyb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lagdbtvg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rclxaclf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfvpfor.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuukcalf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiwpjbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfyuzji.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rnodbvby.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hafzjyma.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxjndqp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyuljrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoldnqx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdkiphz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhwdnhd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2irwrwffk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxxegxn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmuegsz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yiriwjbi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbgiqhd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2osvqybeg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmvvheb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxmhmif.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qyekyjwe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgwxztp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfqtnix.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpxunla.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiazbzv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnmmija.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnoyytx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2alqrronp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lxupndcs.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yghtxpps.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaqqpor.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qylxxmwv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2trkobhpi.html


<!-- 参考信息 -->