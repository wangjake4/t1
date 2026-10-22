代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldezvyzk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ospyelyy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhgqbbm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynadvh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hehekzzk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dvssraqv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwrvzlv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2sohjzzwi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsjvmep.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2myzetgrq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2gstuieyo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtsciay.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugogvrln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxvzfgf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwjmlkf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuvynve.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqxisze.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gozvcpvo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ognzlntx.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhkbtci.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrbxtxz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdkwamw.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpaugup.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajexayfk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsvudhh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2svoqyymc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnnmaft.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmanevh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiztoyn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmjjbeg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fihpoetm.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrjatpj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2airlfamk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dloukcfs.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2uffryszl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpjnavk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtenyzs.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiwwlpu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2uofxwlgk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjeajda.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjjacqp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwwxseg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbzvztf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2luqbiatc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyoycti.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwokokxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuaydvz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpheooo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjgjdhx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nudvslvp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxizmtg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsqxzig.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvmkdvx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlgfkez.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtkdfln.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlacbcy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhwsiwt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2popetnbq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxbfzkp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zobfrhqq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiwiqdi.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ucklnahm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yaylghvl.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2occatahc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrplriev.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2aptfzjez.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxpytqi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmbbiph.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgpedqp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfdffjo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wclcnsnj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2exoegnko.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeqnhpt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpqypg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vctesfhb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2svctcukk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aemfpage.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyqjyzo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2uglyepmt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlgepti.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2juhkynrx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2esulxnpb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gojnvded.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqlkkra.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2llsghaxc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnffzii.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpcgbgw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejjixxm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgrkamj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkxrdoi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgafxisp.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuerfjdn.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kxanbfiw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiagjwy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lggukmha.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjekepf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hebfymnv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nriygenr.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrwldvs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2txnlekap.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvckjix.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyppnybo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbfwjoi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxddyih.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2catppcop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxtgukf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxxysxi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpjjptt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizebrpd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcccfba.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqyqeio.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2likiithn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaqzhyq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjkdxxe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkxldno.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuujfnd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtbwogk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxetznz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2svrgusay.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxutcxb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrewsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtznfyw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcibtzln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbwmytb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqmhaum.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbykgjzp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eibmywdt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2auowrylj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbtdxxm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaxrqcf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mksdktul.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqxfxyp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhoyyaw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oviitcad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvswuxm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyijymk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdodbxlo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2stztjrkg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmsdvxf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zudbbylo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtuddah.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsybecu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqmuwms.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2imxntiin.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qskqeyrm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfipqmk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkbkgyw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaavcis.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sniezljd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kglepozw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tozbqyqt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2itslgrqs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zojhawst.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdvbakg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgumhviu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgybmks.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grhxggcx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elkiqifz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxnypbl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlerhqu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnykbrl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvotitsq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdamyhmt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkfhncp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvjura.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxmmhyi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvwkdev.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcwubqv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasxfbqn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmzdgfn.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wffacmoe.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzmyxwe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcdzhmi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaornxd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zntpvsij.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqnfnko.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fjegmtig.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2twiwggrz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvwyoku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaepcmk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhkwhn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwausj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2tfezqork.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ompgnkaf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvribcv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2npmmrlmn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlmipom.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbuzgfz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2peiysero.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2usazfoms.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfsyycu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vggphqos.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yoipynjn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zkymxowk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2psubpafb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2inysxvoi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zaascwvm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2loggdesv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xktheipe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2badcrqjf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2teypfmjl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owsxlctx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2slqotmsy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvemdzrd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2auvslple.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlcuikt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmxiuno.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdrqayx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxbdofo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijzpoyd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imephpos.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2uakbwzew.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbwzunw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhimdvv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oioixtet.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpulxqj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzsxgjy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjzduvw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykapza.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvtctrz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlebnyo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyrvxkm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hyivwsna.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmqxeif.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tllmsrwq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkzrwnk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdwziwj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vugxrerc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dwprvsyx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbdwxur.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcxsuay.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzisbfa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvgyqvx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qgezhpnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxusdyeu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpytqho.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzgdhbm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjnzobh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hypbcdot.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zttzuobk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsbddob.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjszzsk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmntjwfy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgivfwo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgvyfdi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nysitufb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2waxtjrsw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2quwaogyq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rsonjbjz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkudrku.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdogiamt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxywhww.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbkech.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtnpmy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jugfhjwq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsvtzoi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2otcxsnyq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxpyuts.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqdlsjb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuubdla.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oodznykh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tleenjkn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmwidtv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlrlxgn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcpuusg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhyfwlz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhaxlvf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxdfgpj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pdffbplw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2arhjtdvp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmfunvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgoaogt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2obynunvu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2slanhndh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvngppvf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsnbycq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vghqpqli.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqqzzyq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2diesujut.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2osxqytju.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkebcwy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2irpoczut.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqyajlx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vrakmvkm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmekoukn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rilbruqz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpgdfmr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsqqewk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyqewxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqhncfk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpqhhed.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgjljcn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qauwrsfk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rnincdjc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoivzqb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwyrbed.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtjrui.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxfptey.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rftheaws.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2itlmuapa.html


<!-- 参考信息 -->