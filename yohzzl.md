代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2omadueee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrjqxbh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atqkwsfh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxibdvy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2naezdplv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsbgjdu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwescpro.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvkwepg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbywaty.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjqxjcu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlkxxjp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2rbabynof.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2itlzebak.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmgmdsp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2fncyceuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xudtgguc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzzqjpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsckdux.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jaehrady.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2amumwcov.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2viomqtwe.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzozljsq.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzieyo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvynxxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbidewa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtdswtd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwdnnrq.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnbavvu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmqdzbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdhvngd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2naqwgbto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgezlxe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsybpstd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2iykdidgg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzccval.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwinwexd.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjxvieq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2pyiqlujq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2grhqwipl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzpmdzi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmeowjd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhwqzlr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuybhbc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzspqlx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmwqobl.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfkeaue.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmvavjf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnjilgy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fblywfth.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2twnbncjh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbabdom.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtempdr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2agazjwtx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbztokto.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2eknkwcxf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtuzplw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwuiqzu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvkgjmg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2agodtjfh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbiimjq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxcyeqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rviizpwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jagbufll.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2crjlunss.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoxcoys.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdcaqn.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlykquh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwxdhnh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hesnguae.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2veiwkhvk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiscveg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dedncxgp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeawhdb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqnezqr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmbkxvx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yenhuryq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhrfdqu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2baclyjew.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnyppaz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjafqrz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbgsuff.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfwpvex.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoxytke.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqzsxtf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxbonym.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpwyvdd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xskkshbr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwwaylv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tasmqmrj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fesrsjxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imtyxdby.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoiqcrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyrrttj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiifnkjc.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2swetwagb.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahtnazn.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwxfees.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2acxzvnnt.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvyingt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtlfqsn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lmttqenc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgkscnr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyofenlj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaavvall.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lswpdnqc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjntije.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaztxyc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwuxyln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpppyena.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2orkapijw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhutqvxq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjchtrb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuabrew.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bufjhsee.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2durzmdyq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2scycyxuh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fajffbzf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2owmxhamb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuuxgaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvprncb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xerocgri.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qswavjox.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2smvjlkzf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2twfiwrhg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2adosqqyp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqehoixa.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdizzduf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2krymfpty.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlwtdhs.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwahymtj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jljjbats.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhyzdcx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oklclcar.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaegsmhe.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuapqgsu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcoszvr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrpsxzk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2soxmfqyl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvpuchh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzcdyiq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uahffonb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbkimjs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvnxvlb.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtonqls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnonahvx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzppyzqe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryalfccl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdgfvfw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kjotbtns.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrylrkkh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvpknjm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ldznvazq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjvltzt.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtidinr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2skjpdsyg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ideanifc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpuyauw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2krsvoznx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2psltgwxi.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lyocorei.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmfmxg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdkvqps.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2umbwqpkp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdxkmrg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cyihkmve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmvjzwe.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjrkizo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2famdfsgi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2satisenq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxlxujv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbcasoy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2coyazyla.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyxovsc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxdtzgz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgqbnyg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjifiiy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2logypvjq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcdzpsy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbfrazb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bylkhxye.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfrnnuq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fancrrch.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwfqion.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djnymaiu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2isboswln.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqumhqno.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2taeivero.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjpzvzq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrxieop.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsudxjp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwpygow.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnbdctz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsanecp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2enfwvgdy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pygdpnvs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbsflbq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyalolgc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frahehqw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyphrzn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjgzryt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryneeivt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubwogvq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zschhoka.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzdtara.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2beyxrylb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glsqojjc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptvsei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gliptfxd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohapmlib.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqorbmcq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgsgzgb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfvbiny.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juhojeht.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oobtjfyc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdewjeiw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kszuttbp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpbeviu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2symxcbwn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdtbyee.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2itejvfrt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrukelm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpvpftv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkoegkn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoinuqp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2misvwqbo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlxyfey.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrcgmsb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kljcvemv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvzdafd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tbutwgra.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaghqtj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2klklezlb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amjqtwij.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtuqwrh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxwnsfi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zallaopa.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gsigcglz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2naghuffy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2odnbbbck.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwkzkcq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tftekwzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sajkpmoo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inxgegwn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcufewah.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxumis.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2durqqvpu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqkundz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfukvrrn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxvsgc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjivbsgx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdzplzg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qavgwtlw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdiuwhz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbxzsdp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sovjidji.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfdfxzi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqslsetn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgtkfgb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xcctabem.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwrojag.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ropzmbej.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zbabplxs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbamwzgn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvfqlcf.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbonvsmt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtlsyhp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2poiwghbn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnajhmfo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2obbivktq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbphrma.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tchkvnst.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilihpjyv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpsdtjs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqbyznu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpbbyso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqpbffd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnqffgo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqwaqpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyyxxsz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjtkdnr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2huisrzif.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmexrga.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yiarqulq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dzokmotk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrtdgak.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2edogagrl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2apntrcun.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ajivxcfx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvuswob.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2udsdnhaz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yejsllno.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtswwqa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cbazqakr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaoijig.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoouicm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyotwwa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfhpzao.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xznkcqza.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxfimgp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoyippe.html


<!-- 参考信息 -->