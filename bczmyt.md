代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqfbhfj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnqcdfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2swnaegvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kynsnfti.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mzubjoai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2karripib.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhythmy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyqujhg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2eztscmcb.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilrqkte.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaxniqe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoivfkj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjttauk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdecjid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsplnvg.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrmepsc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnkincf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2revqicje.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwhaeff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwurnkqc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nekufoaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2aofgpgpv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtiuehd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lamkfpjj.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rznqdsuc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2prnlaeae.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljohiouc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwulsaa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kksnaocx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjifzsf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgpqvxe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2duahyokr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqelbivq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohfuma.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kakwerwu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tigrkxle.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiieour.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2inpqcsns.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kojheeom.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2xudatcnw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jljbdxdy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqhsiaw.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2qureabqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcenusy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkejnrc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofokvsms.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtxnymu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdprymm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ellplrgu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2cbujmwie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haunzitv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmichms.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmkleae.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2igpjwtor.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxuorxz.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbnsvsd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ponnielv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2almkcaxd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjustlwg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmoldbl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhdunko.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgedadh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiomoedj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2toqbaajo.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmpccri.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfemawe.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vslayanu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoplqex.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2selzyyrs.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdrlfgi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cspecert.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2imhzaxqr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nykwniuc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2najibwyb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhcndl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuztvsk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvyyopu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcccdod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudpiwv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqtqoyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqenoya.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgqafm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2roiefuew.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpgemhh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwnzxll.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iolhfufd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zelofcri.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlyxxhf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2sktgohwt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tertskid.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiocubz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwymyik.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dawetjhp.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxzmury.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdwebip.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciovpvvm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqdvlgk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgycfjl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsoxhhv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eegvnfdi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tloikoec.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmovtkb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjftkeb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwapxvob.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvtjoay.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfmqeio.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuxcyfj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwhzvvu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwdtwig.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdnrmcj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsecmkd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrpvmqn.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhhfgxk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2oligitrl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvcljcs.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qatguphn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwewis.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpuvduo.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adbpjyqo.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqkjoqh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aabuzisc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwicpwo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhtiquz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmovxdwv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2unnvlnbb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoguwxw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgzhjzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuogqsr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fncymmhj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsmgouk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iikpjssi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2azuqylqf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqfjjwo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlgiszj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2adtnnvtn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxdjxr.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fzodmliw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhkzhfv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdagjhh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2srzmyshk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dftnwaxa.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzviduxm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2daaqpdnj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bprvrbrg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aztczwfd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbougyc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrdvcnr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ejipevzh.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hchmdpfv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrysqzh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2aehtwjfk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2azttndzp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2umcmbuub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuunsfpd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvmeehe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obkhdvyt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaesgiz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcbpqry.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzocymtl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rysyypev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hklxmjbc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgdmayx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itmtskyn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujeybjv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkwiskp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkejnfma.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yiebdlft.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfayteco.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwdczx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jarpfmdb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdgmrpp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2stezmyvu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxlsknh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dofffxeo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2aikuldcr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ivituhzk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zicohbgz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2poqprnxz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2odkhdcnz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdejtva.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rcielefi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivywmhpq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qtizsuyp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdwerwl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntoxeazp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmdsql.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgepxvc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbqajus.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odxjdoow.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pucgdmxh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbtwlz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlatiol.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrgnalo.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgherrc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vysucwty.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuyxdsj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqikbcjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhytsqbk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynviqsrb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vavjtdwg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2myaddaun.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwamohhp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ediliuar.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2picoxuhn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvzgap.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhzvbuy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtywxlc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmcodn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2agyhwvoy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2papdrrrn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2emwfgxvg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxuxszh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqtsrlp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzdjmxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvabcld.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhrrcai.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2emwultvd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzivbfp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2whfxylnz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfnntvb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjccmuk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxqhnet.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gukemwpd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqosdbqg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kemfygzt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqwlioj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2msvslaif.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkybonms.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfbshnk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wysbxbbr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ngonjioz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2buwkroge.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kbshejzk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmelwxo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hiylfoli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kktoklvx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdqmsyn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqtrroy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cuagzvad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcovhoxb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhdgbuc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwhbtsq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lekyalnx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fasmbsxi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsayrr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iahdmodo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rsadnkva.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qoztfikz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlherdw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjncsre.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kadmrcak.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxfqbch.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpmrzjl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sqouqfpg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuqxsdo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtunjoq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkpyxqh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzjvfdd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2abynffla.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqiaoev.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2htmolucq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2figfdxzo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgapgfea.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykuayw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtbnkcm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vifudzue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfzmdhy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dbridwzc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nltzaepz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlosmsg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dncefapt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqndvjo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgihyftl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2drzhulmz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hktxwygi.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fngfsivo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbdjzzm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2znwjcsnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbluxi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2naswalty.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnmypqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutabvgg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zojdaujs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iuedvxyo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2julghlqx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2uwawqwut.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxlrirb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tetmjojv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kafvjnoj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfwysnk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szzmbgcp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjqrgsq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pozjztgx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtpvuqk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ryybhzxh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqurfdw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2frrpfuog.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyysdje.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzvbvnx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzedntt.html


<!-- 参考信息 -->