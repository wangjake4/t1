代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqohozun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbweeqqi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2rburtayh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwphumbl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2sevgvfka.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxmmynr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpoycmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lftqnxxy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2luecyedu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbgrmw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqonditq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcelqpmq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlbzvbh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2scwzfzwh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aougwxsq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjjifuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqzbbaj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qegvpzvx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuejwhz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2obfvxfim.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2muauyslx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfidkmmh.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jygpofdy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2plpvrzor.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oebdrkga.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2swhplhfq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qukvezdp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpleupd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rygtrfbp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhjdzhd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2djcujahw.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2udysoprj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjcfmdx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawhrjxi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxfmgjw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2elpimnyp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrreucnz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjqlcxa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2koipqadi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgayjolu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqgnmdv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2diqzcemr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjndylqp.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvczxuv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2usffmnjl.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnxeiqs.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2saugxugy.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fowdjger.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2sqipsbpg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wsisrdpo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfnbwhz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufslkqqz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sngvqcie.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2biuigjtz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnwfllr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbpbvcz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfytxcrm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuryznp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdrctpg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbteqha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmlfrev.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzxtooi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vshmzvtm.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2suvwqicc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnevgzt.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpnroyn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtylfzz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fknxqvel.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2psllipxf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtswebm.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyjttbx.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmxzlpq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjutpgb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ustdkdhx.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzdukkm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxsbeme.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpfklwg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrajhty.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckmodn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrkcmxu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoixnmx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivozso.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkogfcd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrkbyyk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjqlgdj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdshdics.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtozaww.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcjndp.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eoracpbr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwtmgz.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfecwuai.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwoglhh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftckkwvk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahipsv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgyblvh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgubglk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmqdalb.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqjlem.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evflwnyb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrppgioh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjllzdej.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbcjimc.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2huxefirn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzilxjdo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcveseu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjomejf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnmcmoo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2purpkmid.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlfzksb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmyevon.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrazfim.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcotznu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyejebn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmstzsu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsfbzhb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2pidyjulp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2dftavxwf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2batxyknh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2piizzmbh.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qlotesig.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkieaeh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2evpsqrkq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyxzxir.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxfebsb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxbngnz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfuoexu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqqlqf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2edwkjcrv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2exbfkmzv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqrdfic.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hguuampd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2aianznar.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjiuuff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxdahhn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrfhgrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iatqihbc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uijnzqxb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lypmftph.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2saauzjre.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaceksvb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzkkief.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eovvfdwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrcdsks.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyzqsmx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bycanjcx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2doehfylw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhxefth.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iupqkhvx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxhzube.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2feciwwal.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnxakbp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnmqduo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrxjdzo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfayhysp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hevmnkgu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuyuqxf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2usefbogu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mklptfmy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoltvwy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgyhlbx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkzzjsv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjrvdp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bmonodaw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlaaxwo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlvnapl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gphldxno.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkujpmrc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzceewmi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eadrtntv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaojswe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwvqnpx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxonmuh.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2caaoqkqq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxgrlee.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzxivaa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txhpmzly.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejgfpay.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2evrxxvdy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2prgrljmd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scbribgv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zunvyhbf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiqvjbb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxgxbae.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbuiajw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvddsiw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlqgjmo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2agnovcct.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxzadel.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gfutxuss.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wezctftr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hotcbouc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fbigmefr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfktdgi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmxqdo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2abhcarbd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2usjxkakt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2itmzmzth.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2skiiinmj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzscnpi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sumapxbe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybpgnvi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2sptniqve.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevsyuy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsloqzd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkkedc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvxyjik.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdtabdo.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lfunosbv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpssuajw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xttgeuoo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzkzhyo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uksmfwjf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gonrgvuc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcprwyfg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkxxpyd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjooewbt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmutiiru.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stkvzqpa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxhykwq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlhwocs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gykfnwow.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfazabwq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zijcsyxi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2esrvutmt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymykbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqytotb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2celpprde.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqtbozb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2noqiaexw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrrnwui.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2knszpbqo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbppwsvm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtcxynx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnxuygs.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2othondmm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rquebbif.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsleupng.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yblhnvkc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbvfdtp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pgabrjds.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2duqlsxph.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdtapgr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brrxejvy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuryzta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onxfhbnc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgccnok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cospixit.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnqwjxa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2igeetlru.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvunvxqd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkuchre.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzxejnb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzpshwn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2voykcgml.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkkwegl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qfobobeb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkzufsg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdsqiok.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbwnefx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ehklxlxc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmvbmnc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qobjrylp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2eukigeyl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zahaszli.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcvwvlv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxgzmrx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdsvqag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhejgyl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgrdilf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjecqiv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqeuyor.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aieaehrj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjoovxf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbosooju.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jlecttcm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zorznfje.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pdefbsyy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qihyumjs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfjhyth.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vibjylqh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmiiofh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2luibvrps.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaiooxm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lrctlktv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfnnyrq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bxczsvgx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2twurmziy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvercudr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqcmpni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajccssvl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2knrjgzjm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnchhqwo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjfnvpd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpmglly.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2puymbado.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sndabfkd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrhtepa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aajkclvs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxauxjq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rigakwnk.html


<!-- 参考信息 -->