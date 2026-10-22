代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyiipxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2quwcvhzu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ommajooc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flowazfg.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bzujtjpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlonlxen.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrosukt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexeraj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkgzjzq.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbnnigs.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzlsase.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2omsnuffy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpkpnsy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2wttfpacw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vogqdtbu.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2veqcpxtx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eovwmnmn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2insftmtf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lktcgzks.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkcweoy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbdzxz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcodretq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2aalwkasd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kctojryi.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnheutd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2vehyfyym.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyslyui.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yinagbgk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbrsirz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnjacte.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2balgzvxv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwacqnun.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoquvphs.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2bffcijpv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiixbbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eijubhte.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2daxbleys.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjuhqnj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bszzvpkq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtbvpe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwncmwk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2scvjtatu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvavgbed.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkcfilw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbcxwai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fiorojjh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hbshldoz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cicpgpuf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjdxvzf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zinfiqoa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtlgggw.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmglfwk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjordkqv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2arpkobia.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2juujonqt.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2utrblluj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2woznwoyq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpchirif.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2naetirkg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vatgkxgf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgksdwus.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2gutgasvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxtucpr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oncuwvyu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yejwtpij.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwexqog.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxgywwi.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zhudqthz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjepbhi.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vaveycxw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmkrave.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjxgdck.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzxydjy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iijpysqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2uribwrwp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zagedzow.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzerwkg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xynnofqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxidyel.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfosvjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdlqdyi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uefzheqi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yphyabbg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ordgxeuu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfabvsww.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scefhvnb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgjsfzr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mncxkrsw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtzuivs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxkpwhj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhjcnim.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgopmisf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaivaqhh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpjwbrh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gpigbyma.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nadzbosf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkapcuox.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlxiiuk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcgrym.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmgoqzr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcnmntr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxknvqhr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqptsici.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbztwix.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitbopy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmbbitp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nndvjjds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kblkgnte.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsqpfju.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbedevlh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvqula.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qallhxll.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2faxfcaka.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqnupnl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilngsogs.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jdstenuf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkcegnb.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkqstmq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinwsobu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismxybmt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdrqnft.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tppnpvoq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqxlprq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjrodxk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmwujfp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fexxyjav.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2irwsnndb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhezkkju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycktovuk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbikshe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqcrksr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqhrorr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvznybda.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2asxvxacu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfblxytr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmwhtyg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2wzadubwl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqivorj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gomecgoq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bptcngru.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftcjast.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovblkuwn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhamita.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcrgedf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2crjpuebb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxmpejd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvuiosj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2avgyjisv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyoyurc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfuboao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxiuelt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cfftsqco.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tywvkfmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjxpzyu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnqwcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkwvhhl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdyjpvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilflnods.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxwhpwj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtgqdnx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbtbudd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbmqcrf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvdaywk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnazsxyf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlgjztg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2uonsobcq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbigcdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2auomlmts.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cldykfof.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcurkns.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyusjrm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2amdqmuao.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2teotousf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgasftz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqraksyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wocfjrqn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbcpiln.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2brkisvfz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xjagmbqf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2phumchjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vyallxrt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbscryh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyihcnp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrrnyau.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfupaml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mblmkhfw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgykkfaa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2etdnycyt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuqjfid.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dedwsvdn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bekvpqmk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2autdingg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvatrrfq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ublfcjxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckufeyei.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoaqlre.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgtpzc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghcajh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sksasrmh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlqzuqr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdlikbg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgntxpft.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpixhyeh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgddhyy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhqqxwn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhezcba.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2uxejnjld.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cicxaiec.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkydcgw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdrnong.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmeyjgk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfdusqq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tixisarf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwovoes.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2biufduhr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fiscnubv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dghjzrig.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyclvhr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2svmkdlek.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfbjqyq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekfmcbs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtywdpul.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgplwwgq.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjcjzbl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zgygqrjb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhakhqj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsqlwcz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uepajumy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iisazpnh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pilrrafr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shqamshi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2foyjvfnx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2idxhewee.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyxwstb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnbkfed.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkbhtzs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwbrtdc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeakuoq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhsfgvi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqwgbha.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjducehk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2licayqtn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2funorzis.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwnljqn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbutmseg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oszlwjob.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wovwllyn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2woltxnig.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2palsoxjj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xheenfjm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjitchp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimgdvu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wziswcsd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hqihzhdq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvxaryc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxwkcfs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sovyruyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vufszkmb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wivlqtlq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wndonxbv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2phlqhica.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nndkeari.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2genhsvuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2drxujwtc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbmsxrb.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwnakql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpreafu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmtutyy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhydfpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszynbp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jwojauav.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqltjxo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcgqles.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzyldzs.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsgtwwr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vmesrqcu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mptqzrot.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvafykvf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxudwsh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjqxuem.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxopynw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2limhxvhe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmqclqi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtqiufb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxzzpzg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jrycwift.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhirqxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2adawqrix.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vqiraton.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwmhmat.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcjohiw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqipomw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msikjcik.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyijiav.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rckcggpk.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rztkydas.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uisqaiht.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkyjobh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lguypven.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xgculxhm.html


<!-- 参考信息 -->