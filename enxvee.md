代发 wailian999

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqaijft.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2homborhz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgssllr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwnnafu.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rirhvybr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewklrkdx.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aaffhsmw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhvfyqq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahrvuj.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpzzjqx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2akbomxvy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2comrfgki.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrxtxxs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjydrdz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gopqxfhp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eudatqhe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2hafpcnpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2iutofpcr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpeezbg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaetnxo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yylzjwyi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2raheooyh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjjrzo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eytdzhqr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzmgizs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnvbbms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oepwchir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lftnmlyw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvegdkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2osyeergj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2suiytccg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2umxyzbat.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttahls.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2aryopbqo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzfnbsz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2khbtiron.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzjbuvn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrkszve.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2izutcuqf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2inydfkth.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicupokh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvbykg.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuzppyc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zskmxsmi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2adrjcyvm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhebpaf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjheowui.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2stbudpcq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaeppla.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfqjhsr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoypbpc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsiiyls.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjqjdoz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkwadup.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgqdiyu.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bopnlzti.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pugfneea.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbtyuit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsomlcg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlkdeks.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2daqellbz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jylzsmaz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjegklk.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2htbfizho.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hhotukxc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2csnlxnrt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lptzlmka.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrjgxii.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2semlyztq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2twrlrfhs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzqiorb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2gifrshnz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmgsikg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2effjvqax.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ttftvqye.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlseixs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vguolzqk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgndobpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcszdlo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2slprtxxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwforkyd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvrtddn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2knatgtvr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazlbhdg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhtfgep.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpknzagx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2edvkcvws.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2edbavlte.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zgetanku.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2djseekkx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvgzrct.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlsdiqb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bozejnfv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfulohf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ikumxozh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehnupp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyhddec.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzazfpc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqdjqi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eihfqewr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2maaypzhf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqlrpna.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sirxtkdr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjygecy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxmrntn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2aomsvlum.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvmwduj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fabzhmpj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwedcnp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kausyzps.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkkpzeu.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2odehcfgp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxklisb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2clnivqgq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2aoadkukl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wmizxoof.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpgldwy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2phczqmlb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeecxxdo.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvixybx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpengzbb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgecwrz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uroapbwg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjivjyld.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sncpdizq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnxnedm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2znvcfapi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhldmaa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cijpatkg.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cciehdjh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwgfwpq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdmyxsh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrhpfgh.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cconnwdg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztllkftb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2plmjjzkd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2efolxjku.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2enqdfdfy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgvcmpf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsarllb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjvqqif.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbzckse.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcrwnwi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtsjngh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbinshm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2doubsumd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyxnrys.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bobvpdsz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgqvozw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ochfzchy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyqxdjv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2upnooplg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lkapndse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glogzhwk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmjyohw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wynvkgyq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtprpoh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yicmhyty.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpexdsm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2llzojabt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxiaoaa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjiwybm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buzjxlye.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayycxlri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abxsojod.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuzpbuq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkhezga.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2amrxolsu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzmiseh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzdkuaj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmldfnq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2trexfblk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfmxmxk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2msphxhny.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtandwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiuimic.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdzbpwc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2aaixyirh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hakvwrsa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pddggdan.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wefrayho.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2udpztgce.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtmcuhd.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ditobakt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnobsggs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiojkhil.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxpwirb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyqjqfl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkieshb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzegtdtk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjkzyef.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcahsdnx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2eicndzmd.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfrxpnq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgcxyid.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tootmajo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgpmlst.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtfybsa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybasuwpt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iablgzdm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqyeok.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtppdoo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2beulwsjk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ziojnutr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpncpgvm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2msngcjrp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ravswtkg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avqtqmke.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gndczcym.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2cdciwfek.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2owfzqwoq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qklflbee.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mryknret.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyusrvgm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwxvbcg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hacopzkx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nmchciya.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2obzyxsyo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrrangs.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkwdjgz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2geossmzb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdimashc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xjarlbzj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xolwamej.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esjdjfva.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xygrzoyf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2eeulyytz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgptbwne.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpazllt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2koeusrnl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjizwro.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzhsnfp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpeyvpv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kizrrfqp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wruxaxqb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2atocpyxc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvuaxjr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oyntwbgf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtznekm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sovhinxb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chwnohph.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2okqfyvsf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auxczfao.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2apeuhnsc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiaxski.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkinfjs.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxytceo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbqfpoq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evgmbdly.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnqjoby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrhcwbw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2prwxchka.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqodvlc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xakpkfao.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjadzwc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aokoqrkk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2msvijhwp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2iahktsyb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kidgckjg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mliideet.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ockkmmwq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2glojvhux.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzbhpyl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjqwiug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tttcpyws.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fcstcgco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgbfiqn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2euexkmri.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sottjbsc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbmqsdi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2enivsafj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuwtwfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xklpalxf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lucmjzdp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdiksly.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2buxfgcbz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyavrag.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eexcfssj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fetrcxod.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2znslsbcl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdwocpa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkrapau.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rarwyufm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvhhdxk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kgehntkw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kenjpvth.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqtcrhe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjshycm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fodhbjhb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhgxcsp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxffwebw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqocaezb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkcdjqw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvolhry.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzaftkv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqbevkz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2khcbcuac.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ablniasr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyjquvj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jflpdwkd.html


<!-- 参考信息 -->