代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgdopzm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2oziwzyee.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xngeubac.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtddfbg.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxrwkak.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2naqpmudy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2spvsweno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeqnckd.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2doyyxvcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgctxyhm.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbiamqy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jibllptn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2usaijxou.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2waeczgvg.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xixsxkfe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eeskukvm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2foejjsgk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqwyojt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrnxbiw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtoktnl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrtwqxb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2thfmguxh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzywbanx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zenswlmd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiowvzb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtboicaa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzevztgh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbzzgnz.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ophdxmou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnyswzr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnvjpaj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xywmvgdo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaqsbwm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2iceekosf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cquebacw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2weieunqx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2amhtfkqy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhplwrl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkayvhh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjudaxug.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyktyqj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuonuyk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oehvqufc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lktlgrfm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxjtmfc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkfdfyz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqloinzg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkgzwlt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhajeyj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bxutqavl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnuaham.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqkratj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cogtwvrt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyrnzbq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuimjq.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2etvkusqo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tybmtxtu.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmimswx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gegomsbe.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nacchzmt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpbmlwl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfckogr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtafyap.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2liogdwvr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oiizsyox.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvgnbcg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqichnva.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvjrnxg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsdlhfu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqzdya.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfsbaen.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2akxnrnbl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eopolwfi.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyydcqf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxegusi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuwaeqh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoygjip.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubecbhfs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zjptssli.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rjchizyi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblvquc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvcevhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgebcbf.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iovvlrzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lexvvami.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsgpqmr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxqfntg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyitbnsr.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzxdnkl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwugadea.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzncbwym.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnacrv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zzippjvh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sitwkayl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcszakel.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcygcmsl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlplltxk.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tqupkuoe.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2piximjge.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvcpeuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkruogw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyjkkxv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcpuomx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mpizekzc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uclthnwm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2idkkhlzo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvgnwbv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgpknlo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpyefmr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2cznobqav.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxwobbc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiysggh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjnijuk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yroeifne.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ambftpqr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pktrglgx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyydgiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcvcuvs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eocbbfil.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgiyeor.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qognupun.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2urgruggx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwuilgk.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxhprdw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkshygw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtuwfpo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmkyend.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hawrpoel.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xboauxvv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgogbfa.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bbquktcp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthqiegz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmecinh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uznlivaq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvnkjpv.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptimjuvh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bipmgpeu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lutvbtwb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtsbawr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2twlcqdps.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyszgwg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btilcaye.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyuhuax.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pznbhola.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnnxzwz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeyehon.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2isocojme.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2olbeulob.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2slxuselm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhztfnfj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhttwfo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvvupja.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnkffnh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgbmhv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cytyrqsy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpeslsh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxuparj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpiufah.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwxcqxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umjglyjs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmrgdkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otknkozi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dystkjam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2trramnva.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2buvwrovt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yududnrk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagoisii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlahkwcd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iobuvyyd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtahospd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsskqkl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwfbugx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iustxbsx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwwgzec.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwntceb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnutktzz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqjylmy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vltqsdvu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcstdts.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2otesgddz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2asiuxido.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkzdcqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mowqkjpk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ncocnzen.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nctinrle.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxconvg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkxatax.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzolhatd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjcbiox.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaahmllu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyesaknl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzacbehk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnbuach.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjurgyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpuosvb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnqywvk.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqsbknn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrrdtap.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbqlkgu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khzxzfin.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcmrqcp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cylrnjzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqdrgxu.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2floieged.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiiwmml.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyejxebi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoxlcnn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqzpqtx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwioykcw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqrakgw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcfskrs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dooqtqql.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2amvagpfr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtlgvef.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2isatvyqr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdlxvqm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pfggjwvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2riezijah.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdlfdmc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpbikjx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2owygzykg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dltwnvad.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtjqxnr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2iknjpsep.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvicokg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrjwjjt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ellsijez.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uskrjwmz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdqirrp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfeqxoy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnripbj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2abpomsny.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcedoxol.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoeevhg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zinmrqib.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcjiohk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfpdjsw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbmpbvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjmkjou.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2upnhygnh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgdtyqv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgzjqbo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxnhfle.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhedrzx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vogewmok.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykiazka.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jegxkehe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejizrln.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuozmwtp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlthply.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffavcwwa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mznivlnn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iurnxikv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxmlznk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtjlbpw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xupgawnv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhogfet.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2clhrxbbr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2durwrmiy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfazbrn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvdyteb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgkgaow.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xkapcfmu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoydrwf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmnevwu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkkblv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2agrmscoq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lagcxgdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkarkxvg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrdahk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzcovrl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gytoweou.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfotahz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqabpcw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2avfkjgxi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtvdryi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aisyhihc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgeleiw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtguxjy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmygxgx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaewhho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaqqwkg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2izvhubzk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mltxyuha.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqjzjv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyvcnbj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtytusyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpewuz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2egzfmgbw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2upkjafap.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhdwawq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2obmdtysa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2errrylfy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vscbixyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvjlgpd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2huxtphwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvebczin.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhofmmrt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2spkdnecu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxzspdq.html


<!-- 参考信息 -->