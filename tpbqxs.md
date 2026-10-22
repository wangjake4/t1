代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2puywefqw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbfliza.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2txsliqyj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnnfeah.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlltuxnz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdczpxb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaeusbc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiskhzw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxbdwzv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwxezmr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2achttkqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jznnvuac.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ggamqnnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlaoywj.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2erejwqjn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbqlbdg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoadmrd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycjlujb.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrcykzc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmblwib.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiiycej.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkbxuqz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxdtbwg.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2moavnijh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2aklsywjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2edoiydlo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oiadceyv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hafpgaoi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbnnzhb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkvoevq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2broxygic.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdunsxt.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2drptmxkh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qutgsjiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmgqgln.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2htoaujxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nklnsnny.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaiessp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2liakjfdf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlragsz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2haonfjil.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2lastloei.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2djreiunt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jauxrioo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2epcagmag.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbxqspo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxdfxtt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjbvomk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgphycey.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhjtrwi.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rudvlhjk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pivexduj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpwecpx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfpivv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzvlpbp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvvulgv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwvbjro.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbnnmot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2deapvjts.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2drovdkdc.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqyxjvx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfwrynr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjqttcz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cunqlnbo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wynwptll.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vczbpdsq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxkyhcm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxtgjcw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhowssj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbrnful.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflxeapv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hlibaucq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzvjhca.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2lclgirqt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tiobeuni.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2suzrtonx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2chtiefhu.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ufznlbcv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ouksohec.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsjroys.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbqazhu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnklqalt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwsqnil.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dirimcmp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpxjwca.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgigjwsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrtprfm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfnfroc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpkalxm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enzbgbur.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2arilewgu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprymagm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pifuktvb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfrikwq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2igwejzbi.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dufhyecj.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2huifredw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpcalhg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tftlevaa.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hixxvhwa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuxrvwj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2asbarwev.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cigyjupr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmiobst.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqxcynl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2clkotden.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfsqhkq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgfowwt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmretpm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwnlcmc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2eninkdpz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2poqoctmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2einvcnup.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaiyfgl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uknaorlf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2osxwdsfj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nowhawrd.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmndopa.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kuosdyon.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcemidx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2odrnajty.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaumagk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwlwffc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tktuepgz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2suwsqpsk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvqmikp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eujnlfwt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zokqkqnj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpuanxt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frpnxqey.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aalbrfod.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxpfhwf.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrzhvwn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2aucvxcbv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2juniwsfo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwaihnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwirkyga.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxriadsj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqmjfgz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sheqqqpg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2muntdnxh.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvklqtqa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiikqvx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpehovc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uemtmmbx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwubfpd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jiffvoxg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2edbxwjef.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubigzwjm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoclvws.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbdhghn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kglvccql.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tuevsmah.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjvtvxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pteudnyn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlsquan.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxekcky.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbvpagv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcekoos.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vbphsmee.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkkzubo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvdpgux.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gshdadbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zetmexvp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaspaar.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dafavnsk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqurrpe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnovpkb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqadyev.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dssucvxe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epodzejp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqvflhn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pasgipnc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjxesij.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2chelbhpd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeysrws.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjregfj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkcbums.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcxdojg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrmwamw.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvgzmad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkqjogp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgscacgn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmvdyaa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2yfymiceq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2utwnzrmm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgalqvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2khlyomot.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnnqtsy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmjnnyc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dnflieoo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2grycmcti.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2upoiovut.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfuympg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfeukwi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oicdlaea.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlrarhi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cheamdlc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzjxhnh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2edyzzbno.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhkdakx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvxpadn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bieoeoer.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuypwxuw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lysdupyn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbudpcft.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2waofdhww.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznjqpws.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzcgqnd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwijwiar.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2prjiyvbf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlehnpwz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqtzlnq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhohrbs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbnhwyz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ddajlawf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2uozwbluq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmvymcm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdcnhom.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2sevmvavt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpmbgfq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuuraqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkfcrnc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzzlvsc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pswadnsz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkuxhfu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqwfjny.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2akjdumzx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtthcnl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnvkrrh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2novfnrms.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkczgycg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2exynsltj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2btwugujo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdzjhni.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mvawdaii.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbodaryu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2umozevjz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjxigkz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rifluloj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nuixifmf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acifsggu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ayecvhpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acimvtsc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvzljhp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2taotfbqg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpowfma.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qslzftrv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nopaspez.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjeqymc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuonqtzr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhhalqx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvxdihq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diqfwugy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drfvtzkl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ayysfadc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhmyfez.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wegsofgq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2blyvzgma.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpkujfy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yipdvfdj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nnikhtsa.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuczude.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2epvffbcu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqkidcs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaofyqu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hljcmfat.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yszydnzl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2njbazycn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqkqyye.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrxsiaq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbtpyau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sezylhql.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyinnwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfanqwl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzvfrxm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbtpjgb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrclsfz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2srittcoh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjrpusi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nshzkmfw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfgbhvb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfecwrb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqsthek.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bolewsdn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxtshdd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhjujp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2obsmhjoj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2olnqceri.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdmfses.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbuobmf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gunfckmk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgvndkr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeiaqcv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lajsqczd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tlujuxbj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xamshxpm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2viqgccmw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cunjxbph.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pslraonq.html


<!-- 参考信息 -->