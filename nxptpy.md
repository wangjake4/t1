代发 wailian999

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mncqetys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qowpfhfe.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2grseskzx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmeyryh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfgphuk.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkdrfre.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2szqdbdmc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ohemzcuo.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtwmwsl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2eeufuwaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hntglluk.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eviwmaao.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjqwftf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2oamdkyhx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2siehybva.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dbceuobi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2eydetyvf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxgdbb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2abjkrbsh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfdumkq.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2idztwdpf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ykootpgv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgihney.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ymumbvhd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2svkoytti.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oheevdvy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2noblqbrx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2yizcdxmp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrbjxcg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2timqseec.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkhvdj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwszrax.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqhgunh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqnqscf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeimhusf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lodnhgsl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayquqaak.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpscawu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgycjpxx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsmhbiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnrqdrh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2avxykbsj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2shaucmyp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2lnugymux.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xoasezqi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhtxmgt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxhxyew.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sopgwfkn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfponocw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcedhlub.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrqgmsi.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzzhskg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaarxkv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcvgpd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcmfkr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnjzmhw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrulpizr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvoppir.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2awqlqkao.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2snfxlxpn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kltxomeg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wobbdiff.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkiohkc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2geyfmjfx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vpllsgyy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gfibteem.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ycidpwxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsphnvi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgseknqq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jglmkhlk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmgxrzf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvrpvau.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmkeptn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xexxytqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axauhyck.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mvllxxkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqdkjs.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezabwtgo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrbfhm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfffqzcv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khsmbyvu.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxhvdfj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjpztjz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuiihn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdrlmfb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxgoefw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqvafqm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2msdwzfuh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlsutzq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mizggwea.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsgugqr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2enyatvsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2welvwwcb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqhxvys.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2znvhstda.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hqncjcgz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoqkqwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsrthxq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcrudpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkekjah.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcycenr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2esdjpipf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcgqflg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxfotyn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rvieyumn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hypeajbz.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mobvsulc.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2navehfbv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsacgyqa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2shzatfwj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2esdtmjjh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjjitdh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2twuueigb.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrrfzdk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtkrcor.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkiaioa.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeycvqaz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuvfnzx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2labfrcqw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcccblod.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuxusfe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfvsnbx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmdhrup.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvgieml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpzvaei.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2luewzhlo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqblsrhz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aesdqvyx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqimkvdo.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnilnin.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gquocijn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mmotcvjv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnhdwss.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcxprun.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzxvazr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gpphmmxg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2poeouphy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtpnolv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2syqjazms.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwwaukq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyaezdm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgajzzgo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihznjafr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxdkqno.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrqsusm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdkmasn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkmatnn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmlupvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2owipavpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2subksbpx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2npbgcumb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhugvlt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqdyqqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2obvzpnxr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoxaixt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcxtkfo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqibuvc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrieltn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pybstvkj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmdazcn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqliojb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmprbeem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaicmchc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtepslk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2reaoouvy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dioxtnhd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrrwfd.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2msfootww.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwakrzj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iogcfdsy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wozirfmv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoldyee.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwesdiu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tclwbmwg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtgfvkd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mirravui.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmxpdyg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzezfmu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kieuyyuj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqioivnt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tatidsdz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acawehug.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnepvti.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjqsvzv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aerozglj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qscerntc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvkuozi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwjwpmm.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqeqife.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2teoggeag.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralxdbjd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkblnnzn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyetpazn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdhlpsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kihpnlho.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfakkcc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqvoitu.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2grxbgobr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdfrwje.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkrmcwo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpsmzhm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcckejv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuxmjud.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auqszxnv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xmocejtx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zilvissm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjqbqa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbbvjoj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxtpfxq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2obtgvftv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfvnab.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ogawbyfk.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2epdinlmc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqheljc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zigmsqmb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhelfxom.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnacsiq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xadmugcq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkmhyo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwtaass.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xronnooe.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2phogkvoo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jckiukwt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pigpsrpu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzfwgxk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbivjkvf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zrglxsgu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoqniko.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rtecioen.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgppjqe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbgkyys.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aflhmgik.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wogzrjbl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgcdkhe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaqpnte.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoghpkiu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqqyrun.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdppldv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimlgdgl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2stoeqowd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlkuksd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsmremn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yesciwja.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgvzzm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmqkqbx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jinxtqna.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fegvrwer.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpwlkmp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swrkfxwb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwgksyi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxxvibo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzwivkw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bclzzveu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wltptmjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjlhbgm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmdpmhk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmtlwnk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiaixjs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dililuoi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ogidxoqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zenmjiwh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bgipuuko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uygmpwgx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnvuvrl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsabwdpn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jopyxkjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpipzla.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmolauc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfizzvgo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2aazwhzlm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaegccm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2harlllfv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2repfzigu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggauhdpm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vfctsskv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jcenhbol.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuaavnp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrvuxvx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jnntvbvc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcueedh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucqtmb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2woexpbkw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kobpcacx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrbzqbl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzzzjpl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2epwuixck.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtmream.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2afchmbgr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2splyjqxj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emrbukgy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcnzvna.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkkjjm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdhvdka.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fitkajfo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2naqmzyxp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2umofgeir.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lncyuyvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2iydjigtp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbdyzcn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pykunzqx.html


<!-- 参考信息 -->