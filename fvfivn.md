代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2kaigfnmd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfowvcr.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaqfdlg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbhdruz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtrgcci.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2komydrvd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yznbvixd.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dgajtjwx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwmnvdv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiajoht.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdmrlms.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qscvzklw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgdybui.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2aucdpbbr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdmshkc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxigoqg.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2pfphaltc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2imlqhsbn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oavkjjuh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgepgjo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvstxyl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcxijyc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdvqhhv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrixyav.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvbmcdx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2wchpviae.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlkxfrp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxveeqlb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzvcfzk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hncvhpoh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhndaeuo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxavrmpw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdxfztj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrcskhn.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrpiyzo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyxcrbv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2puctmppe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xyymxtfy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gfizfayq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2eklpwdrg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyqzruz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bxddspqr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjvfslp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aomuufzp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwwzsju.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2axnevajq.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlnfejv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwquchow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2stmwvjlo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoerfwq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2awiwcwov.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzdpqxe.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2csqbsfwc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqxpzn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgufrvyd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zqptutau.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kpszjowf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqapkeh.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2allqpvnc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2meccjana.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbkpcvy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2unxnckfl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2cehbmvou.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcjmcht.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zehtgkxz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grnxmtxw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rshlaugh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmphdkt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrxmabk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2edmsrrfi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tooheyyw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hncyjuod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckosvcuw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbylwwgl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjmfaqn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2coofniur.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpwonhz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrbivwl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwajzeku.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gaguveqe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2sapqsmyf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuaekhw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqqyses.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhodtrt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrehllg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkfiekk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2oednodyo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaqhdgx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuxwadu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dadjeyys.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2likejesr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxzywu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2roplzqzw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqciboh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkbbdnj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zipmrbpg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwkmynd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bopmjucq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkygncb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfebsgf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzonbve.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppabpxod.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2irmlpcgb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvbccpy.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxrnhwp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbekvibf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeyxcup.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxzaecv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqxkzjd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxjgqqb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuattpq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrtqafa.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxoglwd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpcworp.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osvxfvho.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqplsvxi.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbafesi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2udnyaece.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2asvhwzww.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqnuulg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjnvoot.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkxtst.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdxutyu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsxvrpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpnasjs.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltosupky.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzigpani.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpwdslp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2oojjraod.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuywvig.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zscryfpr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhobtjt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiatvjp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2arpnsdot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qitgzeul.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2offhlzkc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2chlqttgs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnugtzd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vezdjogq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vyofrczm.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlebntm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnypajd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtahpwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxjmdnq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2dzycksny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwuczyg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrnovph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syskfetz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhuoqkm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcstnmvp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2srsqmbrs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrnhgwv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytrikzv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2epcbmzhy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdcxqaf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffngnid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiviodbx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhdmubi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhtqbrq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2usplaekh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2besdcssf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjenrbw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwdxpni.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetpfsnn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2agnfhwpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zskasdmr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2knrtpeih.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzoioky.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbhunjm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmlgtqm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lzscihdn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkqxsyp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhnowto.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2prgegtwa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2olegvjcp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlhxtwe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfqncsm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkftotmo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxtqxxu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzhlcuf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azleuimh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontebtre.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isefooew.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rldavddv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wllftluw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoizaor.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umdeujkx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsssyill.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vczcxcrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcktycge.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgymjyws.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccijqjmr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkrwvnq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spyefgrf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyaskvo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwubywqx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2shzwdumj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyztxsr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsgwtxu.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqfbmxc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcmqzvz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmucblb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2sekujamt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcvshx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2upotshsf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeptxlf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvnjxrb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjzombw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmprbik.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2koxqfcvo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrhxlpg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqdskx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xclhelwj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2quenodqf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2errsvjxp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2msdxoetf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoowefr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2opdirgcx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzzgnyy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dwevtfce.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsltgfb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcslltc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzxbwvd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utgndrxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eryozwuf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjguvvsq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eizxpyva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tugmriey.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjiiqeb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evraurhm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbgchbo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymunqatf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlxbpao.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrjvhul.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hukntnas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2khtowice.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidwcwkt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwyeywp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2enpgsaoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hsijlnco.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpareyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsscweo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2txcdrpmt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2odzifkti.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdwrkxj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjsitbm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nojxwxri.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjqfsgg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2axsjjofy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkcund.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhfwrrh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmavjin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsouesm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjfzrqs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpxtwag.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzsloxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwckorg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jpptahxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfftls.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwqadf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeabffd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2arwlhftt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmfvcyf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2relevded.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvnkkua.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqcclbo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgslzqkw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmenvis.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uewxbcou.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnilkyp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cplzcjyt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iehigtmz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2khjrcivn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqcaqxg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2syljemfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpjigiw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fidgfwuc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpskhva.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjuvypb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2otpqqimt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkhucds.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kufeilji.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bghbnnme.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnjocqx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgxaams.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elruxfzn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxpglpg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cysmqtym.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qebncocm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbighgs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uginydcj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vqubpimi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bipysfpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkthkhj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akbalxyz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zawirzbs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfpwszs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdeudb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewekydvx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlkwseo.html


<!-- 参考信息 -->