代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2hebmyftv.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxksaujq.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezprmwlp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zougghry.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnabzmcc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiynjgl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskgwivq.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgoxiej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2cycfddau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcpznvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeicxkn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bptuikdv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfvmhlp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgfmjyg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixvscwt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrucefk.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmnzora.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2bpheiwis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkyuazt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgupase.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwqpqux.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgophlft.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfadqwbv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2woihpwdt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcanluj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgdqgyy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnadslgh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozipidpm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oujitedw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyvtuxf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2liumgege.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2udprslyl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwexvgdu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavbwnsy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsawgzec.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2oznoknrv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxihtpo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rusbsmzc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljneqhpg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pegjxges.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgzhkvn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkneawi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxycfgq.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhbturg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkncvqxd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2znrtjgvb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcyljrr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2euwnylbb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqejncqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhrzhww.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjbhqub.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2taxzjhvw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dfabnikh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvsdtxw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcudgwx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxgvoqh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnemcrf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcizycrg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgtqnun.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnqrtoa.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2llxcuuad.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2muacbauw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2daxciari.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygonbchn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2khthjvti.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhdyvik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kcahuqyc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhloqyq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdhkspk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gziwjlcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgdtgo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjcheno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaftggl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2glezqmxi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmizpqwn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoifwhz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yossyidc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwdxpjw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2myesqqpj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlzfjca.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2hisbtvwm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2airxaumq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vabgmvqg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdzrfnj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldtoipu.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cunwjyfw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdkuztz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofitezel.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlflekzi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqzzpsw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqabemhb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2finrzpdd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbllihtk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeppict.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gotdpdoj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwenihhc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmgynjt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yirivdtv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjthjhx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqntkzu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2scugvpbf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2syoymytw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpsizin.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwxxwpx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxlktaw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmosxpxj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiuolno.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjhyikc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ochswxyp.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmxuchv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrmjvbi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyniogwc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcpucel.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftegtdmq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cetneeng.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkmurgd.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubvfws.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2sygmsswd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mearzxce.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utowhtka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzmosep.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwhrudp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxrlfq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnupbadm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpricom.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jombsunr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqahyit.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmtyvoq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vglqokvi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cscbmgqf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bkotjnbq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2llqwkxji.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfizesrh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qznxowyp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqqdgao.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuekbgzw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxgxqol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwewckrq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cakotoao.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2axvbgeea.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjhyech.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2elvsnmwr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oanbbnqn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnbzsab.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrsuhcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrkpopz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ginorasi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhsnmye.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykygibwk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsvtobr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxjlamf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nphelece.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqellt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjwxfnc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeagdgat.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2niejrjgz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmxywge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqqynlx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwvuiqs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lelotdpc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuqphwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2drpwgbtt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxshztyj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2syljfepu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jipkycmn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhykkyyq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtqoxux.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrocgzc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbxmzrz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2affmudha.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgxhuso.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iovpcqwh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbciyro.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jiikhtht.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfcvgba.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgeajay.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpercwny.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjnibc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbjzkkz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodnevg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdecoyr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2diwkhowc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyawhth.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yutsigcj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wieiwvpq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oynoqeua.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpdmfvx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wojpswho.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zatzddva.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzyrxqm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkholpjl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjhzhwi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eacoorco.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhyqon.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaxuxpg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmupmwn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wodmhsww.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjqitgo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hhomfjtv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjfttxd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvxnsui.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvlukre.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbomlmfy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2owglspna.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbecqdt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczxjjch.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2opijeevr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2eoifzinf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fblzlamb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2txthoyhh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2behybpng.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2usqrhgiw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmniayuh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwcgsky.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wijvndwf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuusehi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rncgtzfw.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idnwmgez.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2apgcabyq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dokowxvl.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2crphnilt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qprywqhz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dznnmriq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbuyobj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aoklqtuk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqvtamv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mkghzotm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2motfdvqs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vomnnise.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvdqsvc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhrqiz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orjktbqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxzcmmi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzsznue.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xivobktd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmwrdkm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlgqhkq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcahtbt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqdfzn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2skgwcjvx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cddxrzua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsfsrch.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nflpqthi.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zyitzrqv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdkepit.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2scfkazob.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pfddssne.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrmbgrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqxylcm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhljrlp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvaxfkk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2trbbwpha.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zquuukoh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vecqwnyd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xblqgorf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlfphpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nooxiacw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2axwhvqij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grdslzwh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqakwrs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gssprwvw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbdchsk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ianfnpfx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmzdxlw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvbwbdl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2getmpday.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsolspt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2diyrdrnz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pihttvxu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaegkjl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2treycvox.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2elooeinh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pwicrror.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtgljwn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wavurstp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfzgtnk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfksdfb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzonbsm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsudejs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gsftmwtd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cobjuati.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2upyjrfsu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjppaui.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cliewhxu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgekrfgl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evjiocae.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2knhngmko.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdekghm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zfengrni.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdandupr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpunnfr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bisflidd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2svtccquv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmzzput.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkedrryj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2okxvpgzp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iekqdqmr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzhsqfg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtylqtyh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjqjrdx.html


<!-- 参考信息 -->