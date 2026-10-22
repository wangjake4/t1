代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2oohhmffg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2eopahidj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndirfszr.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cclrmjws.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gemgeazm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlwjrrh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wxffekgh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bshzorla.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzfaood.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2phjnxozb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsnsszv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lphmidqt.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaqhppa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2onhuslbp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agvfywtb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kziavuzr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2oiarxloz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlvtcdx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiigvki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiffcut.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvljqrb.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2aivwtgbl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjamizm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcsehqz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvnivy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxrjrjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvhkxyh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaqopkk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtvhhcc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytntgklq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhstixed.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjxngid.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcmuacd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkddycb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2suiqhdxm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2bknlwyue.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sodnrnje.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqcfmui.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2smllmcsu.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bztigdbs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnsuctx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqieejzd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdumdl.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpwvckf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2imsdgevk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxmplvt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuihljda.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiivyjx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jthpsayi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sheuwuxg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2eviezcfb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2erwjfxxx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhsldvp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpacbok.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyhyeml.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2emkinhsc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaquvtx.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2epkncrcv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2syzjgzru.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvfzsec.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mniorhud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zztkswzt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxdledz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpiyzsc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhtuxht.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2albohzkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmawubcd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nozywuau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skqxhfio.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2weyyxbrz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uncfnpok.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2anmfbthj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzffihz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2snorbfat.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2asetzqhl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmnbybu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2divshrjl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhabcmq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gldvplpz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bspwaluu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqelfaz.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wygsvwfx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2olidualo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvtxbys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmsfbpb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bgazvjxc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgphcqun.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bypjkpkj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyqmxb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxvlma.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2liwhwzwu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfslkrqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjctaafc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywatdrds.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2umjoopvw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcxkatp.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqnysiv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gspavbug.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsvfzbh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyiudkc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kobfpedi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxzbygx.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngepfhjl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2stvbymxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajggczwe.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2armwofde.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvtnqbz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuuxnbp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxfyrou.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuniakk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unvztsbd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsarnyc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdgqxih.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrumoge.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sowfisru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtwrrti.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwrowqr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaamvqe.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbunwrw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhtxzco.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnccsrde.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhhlhyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2widsgypx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvcdkog.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhfhssb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqfiman.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2elicrouu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bwakadyh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbctzfir.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmerzdfs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiqgehs.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdayipl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vcysjtiu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2noufsajs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2oorgpedy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2stkotebg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2edwvfqee.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wadsvxsp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuxghka.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuvqeww.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxyebcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvbhrkd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2keciqnjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2govtclbq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2czrzicii.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvvlgqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcynytf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jahjyynz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjmkkkx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvftamqz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpcgbgp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tozhlcvj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kflwlagh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbxuide.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxnmybj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yapyndmh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtyuedy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtusezjz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpebcedl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwnejre.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuxkhtu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfeqcet.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoieiexm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxnewzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvywzajc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuptebx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2uronvqjo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2drsyrnay.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkhtdpu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqivjze.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlkiyuc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlmlrth.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtfglvt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jifhwsbr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqvnzox.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfbagsl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyzfsag.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcouaxy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyofajy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvjyfz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wesocmif.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwnkokk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brgfjegi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaryqoe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbogqhy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfjolgd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdrbiax.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfajwzam.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhqcssq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afaizcpo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zibctpfd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdvhhaf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwokqmc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2epsihrpc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdoswhl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyjvlyw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoegpbi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kazmpeiq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hghqeyuf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iewvslmm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzzcjne.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpiiivh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2trarvmbt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwbgklh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmoqaeg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2htylgyew.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uejfoszw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbqqzoy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbecljx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2azqwilbg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dutbacbh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbwkpap.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hratbhof.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jugfgknw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhgmpra.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrjljge.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvldkya.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwolxwn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2scmmliud.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2udgipdnj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xezlgpux.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2suwrmofn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hetrstxq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smgmvvah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tludqoph.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoipbtf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxxdoky.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtlojla.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuzkmym.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvxoljf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuqjrrm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dppophks.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gynylcut.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rucanunn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2auqnpngh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mihgherf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqlaafq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvhuarw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rgygzfsn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oizsvuqk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2etwqpqdl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2quezlzst.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgsfvlj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoazhgw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvweek.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixevzvqo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcvelcr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhvhofj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2urypqcuh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcrvmya.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwtspxy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsqsqlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcupoim.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeltoan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbimexaa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2buxvxhka.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqweejxv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hivcmzaq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfosqod.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dweuciix.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhwzpuv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgcvlwy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpepssg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hgalefio.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pnelexob.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jelvenpq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kkapagxk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnliqat.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2smndjeox.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpdeuyx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkpkkfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2srdlylcp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qivfjlkc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cznzhpgk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrngcws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sboxyemm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvncbyh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jujrzjrb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bczuvfhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsziwsog.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxiskit.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bttqmjjh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvnzlyn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gybjnxhg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtqxgyw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnbkpnp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkperhtl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwdnila.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvumfjr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vmidvjpf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmtnjal.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mobzgheb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycncxchq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgigbsv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2debiuasd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkpozdy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpeskro.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2llcywthp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkyrhoe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvbhvcx.html


<!-- 参考信息 -->