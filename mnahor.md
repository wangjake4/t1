代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajwaahk.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcelaces.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxmnbqj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2wegpxyuf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwokxcn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yietuhcl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazyebwj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2szwwzufd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2shgqqnng.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2plnuoujk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxyvtbd.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2puofryqa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqnieez.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kiipsvhg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjlymtx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoahrro.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxhcxwf.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhouozqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yzopsevp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olxzlhcp.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtthjvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jseukfvd.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zuifdyiv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2aljavmwg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrycmak.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopfeszk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpkyeov.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfohep.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoolctu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxjaxky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqraqlf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oqryquly.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2akxttgls.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ldequccr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvfewud.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgnwkjo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbddcij.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuqlwua.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiltamaf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zydrnavd.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuikhsn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2sybnmkvv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpxdwim.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2oydrfzcq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vcheowlx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkpgbwd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2chwsarin.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2slgqtxqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlskaeaw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwbybjn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkhsgry.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eygfgpfv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhsjkeu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oymfmjvr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2huvamjnj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2phxrkbgu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuthdyem.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbbtric.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjegzckl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2czkjaygg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsvoujs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvymure.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2outeycxk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2euwwjvpq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgacfoqk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcxjntx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzudmsw.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqbvlhp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sybvtsdk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwepuaer.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcffinb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrxfvxe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tebrseyi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuezlvot.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrywlcqe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmzjch.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmictmh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jykdakit.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzvkzue.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2igmdehsa.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkoibki.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjryjmb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2thpctokf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2yawbkvun.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2reeofmlz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2yufwoztq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdihocv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlguxiy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbasjjj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwoyviv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgchlhn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzpoknu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xelpcmlb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2soktkoqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tugjfxgn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkvnzab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkvzyam.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fygowqwj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpupxadh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2emjblxww.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2byzvwqdg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswtbulx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2atvjklqa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoavqms.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yactcyoa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmgbmkw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmefjtmy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2afijbuwa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vytjxbyn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnqcewl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqsbsjc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxzbmwg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfximrqe.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymemxfug.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvkobyn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vcosamya.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtxujb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnrjkmi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sehtofes.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2psbchmsg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2thhukuit.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fllxmfec.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2waehkfwc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeflsiet.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2frabdbur.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtdnapz.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xscnokzz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpfutwe.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2srzgcxxs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zggjnrte.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqipqdhf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsasjdk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqiuvjj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymusyvvq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xobiniih.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqxitre.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjymgns.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbpdwrj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrzvins.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhapmuvc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgnvrfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vagmgrrq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiqghwm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcskdcgg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjfnyhr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2koprnqjw.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2efgbpypz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsqutui.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvheurtv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlxsdnh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvqieet.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sevjojxq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2htpsexon.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaucbxc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2koetzkga.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2knvsltnj.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctmjbsb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlivcqe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2eweukdei.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpbkjxy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ertptujv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjzgsyg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifadobrs.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2beycgxlu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jeayqxey.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvytxzoq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrhdcbc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqtcarh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2menwxajz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaebqgx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2omfgcqyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scjitsya.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwvkhwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfbezss.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nktfuedg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qheopsee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbizrrhv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqlnzlz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoaevjf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmkape.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfuxmrp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gavusjft.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gggtzaij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjbuaqt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfydjgu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwwlwqm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeixmwi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fabjjxlj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oygxvpgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtlypwx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnfhtm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlduqfn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnsotje.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2szynaayu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcnlhuf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2triukuxq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2avibtytc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpdubak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jfctffnw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmecwdrw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2covoaumw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbjpmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqratzcs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2imrljibc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqhlqxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2numpcgri.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfpwxpm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjfuouv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2inmrwbwu.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvfzjkx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sihiwggj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ildtyucb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoptuwh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhmsfxb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkrnkth.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzweiezi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pncoezzh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxbizhz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjeibdy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprjdpw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnraopx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2duccvcbs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqorhg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzebxpuj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hssdxlya.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2utztnduq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsharnjq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kofewriv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkpkkhh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyswikrm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2whwttzet.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bshltrer.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrgxoww.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuhgxks.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcezpw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fapsbxxy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxirtyyc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxznuqe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgnaiof.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfiejpa.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nejjthex.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2modzkzrh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpetaqo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dilplftl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkxiwen.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2scwavcfb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvaknmt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfqqxzq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2idswofdh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbjyuzc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebojbu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnxwfa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhxvela.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2flfyzcir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2moystppi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duxvipxf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuctsor.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyjwydt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glyayplg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxirnmic.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujclaxc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omknqdau.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmneull.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aasprvim.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaurpzey.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbofgvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhdhtsl.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnpkmzv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yshldfca.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2opthcqxq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2imdsxcal.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdhajoa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oseccmsx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2auigejdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjusukgw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uahvrtbq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjqmktb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qojvwwda.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvskoyys.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlkjfij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdjocoo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gljjzflh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbohhirj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdrrbuz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2flqlxsms.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdiubwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoxuzvw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2igaovrej.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rshnimit.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vauzcvbk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2csggzuan.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bcathzlj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzlvait.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wszznabr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2utdfqtln.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2obwdfzdr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwsqnpa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvycotuw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2noxviamn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xmweuvjx.html


<!-- 参考信息 -->