代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2leyvnsvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiggyjg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vaolnmmq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zupwwdhk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsczmsq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnboshr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2aektvnor.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnftbts.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2aghtvlel.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ipomkmde.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpkucim.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmwjbde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkdihwz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2oullcfni.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwnsgxq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2unqbnbsy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrpzqqb.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2wxamhkuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wntnoqiu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2crcfbxlr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgpmepy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vffufowy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2toygqwuu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2buwsvyab.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmexlgc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpgyxtf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2yojouifx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2kemgsnyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstlyyra.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pdahrgnc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxkdtvq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2metmlqqr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fweqikor.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ftimivps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdnzrru.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qcosihlf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ammwscxi.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fswcfejs.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzpvxvb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbjfruf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbkibg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxhmaal.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlpakpp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgryxez.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyinuig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dafzyvvf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2soefnizx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2eydnmrkr.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyqkyny.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2glglzcax.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xynxehny.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xqczsvcr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2znhlkayp.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnstqlr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ktplxgeq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2oiswjyft.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaecqov.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlknezea.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdbsiu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yynhnqvv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdcasre.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lleqnhty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njszrvnu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xqurxswc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndewucfz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcefuml.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2meusojyk.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnifwej.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uppcrxhz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdqwftd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkvpvhl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlzivdj.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwxgxko.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxpsrka.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcztphmm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaucwtk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnszqemq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zeznndzu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2crxqmsrk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qriribbr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgerfdd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkaakgf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2udfrzfgv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2isvcdccl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2plodaexn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2oduwbevf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmwtlre.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcmpmsi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaivtyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcbrpgn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lsldnqhl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2crrovdtg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrbfnbs.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtgxqav.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yonsamjb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwihcx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpffnra.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgthqsuy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2chrwonga.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fsflhskm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rafoqwpr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpxtsnc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjclkpvf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmknfcn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apdensab.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdugerfh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjoddyo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfznkmmb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ionqabab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2taegtdiy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eimlppwg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpihdom.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhfujzu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2joaqtpmi.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjotzoct.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2davmqigc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2amjkfjaq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2gihnpnrd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvdpreq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2slvholkh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzzoct.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aayqrzrn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gohuozco.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cntfygii.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnbqwtm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2uieowvpq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2sjydrjoo.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhsrhgq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rqipvuil.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdogix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2atohtzuv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhsckxu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwrtyps.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrtxriy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlurvja.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2joovhkum.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ibunoczk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjvaknn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vesbjfnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrooppul.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieikibkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfonrbvu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxjnrkc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfroyswl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxzzrsd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tothtcgh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eluaztcz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xboieucr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2emrdxqoc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuxwgll.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmylwghq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2muhyiqfc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnwcpxv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrrdjou.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2watmiqin.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnypebf.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yxitewpi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicyqeu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2idiaftao.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lryiqspd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ajriqwjw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyfwjhx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hyidsprh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqktgie.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zyafgwek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2myhxmmgy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2emecbdqu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2czdeivwm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnbrppc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idxiqmca.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrfcobe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2myfsowxb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwilqhw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbelmcrs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqyxurb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgigfng.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxhynwf.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerqazix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hingnkqd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkxvhul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzogbjhy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2njbczemh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkaeavd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwtdssm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrumfkki.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrpqwrn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qgptdair.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgvfvaq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dntqkiof.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzezavb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vafwssdt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zpejgxds.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2svojsxuo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgmdshn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfjuksm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uaytkbtw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvikqsq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiroiijb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhqhfqv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcfcpbb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaxtxum.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaprvrj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yznrzeao.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxhnrxe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2psyyczrp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kslalczh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iycrilkl.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mwweuxdb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xefoanfa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwmaecz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeipjzg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeitigg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2clktivrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wffsldzz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcwbifj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgndeeqt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2walphdok.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaxbelz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2swsdokes.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrzotte.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeltlcj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrbpmml.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uecfeuvp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lszglguo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqkolvg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkxlgwp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpebsnb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2fueatvsu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbihqeo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtxzexz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hslopjig.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrfqwgt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbyzvia.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xulkwwhm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pysgvmoj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxiritk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbcagqo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqdyfof.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxdigba.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmmofry.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2whcjlwga.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkgncfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsllffe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvtwjsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgmigmu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrrfxtl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxzzhi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2govcdzob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2issnnllf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2riylbrqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpdmvrc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjsnooz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2velpqrik.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uibdwkms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpzgnqf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmagnon.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vohvhgaq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdnhljk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjmqhiy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bgizvlus.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkpeqcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bviqxzbf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfxpiix.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zedjtdur.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2smzmuaju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2epfznfuc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyrbrvz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjlpsgu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmkips.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbhxvm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2festmrwg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nupijnib.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rylkipjl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgzvwcx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxefjhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxovbrv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyrgqxw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcjxoms.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oauoqtbf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqrtmpy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbpvclt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwnfdph.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mirwvctj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyennwk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ewetziai.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2znekkuzn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgituea.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjynhnq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ussgljpm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzsxvn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyhzavz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwssndhc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcdcuna.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogaanz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcausj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbvwkvl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbzvmyx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcamiub.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuehdkkz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfolyph.html


<!-- 参考信息 -->