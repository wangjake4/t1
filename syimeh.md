代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wursocuz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dvybjzxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdnrad.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmzvtgl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hojuydcj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nydksujk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpwgvqt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcknkgzq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyoebsw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcwjvjd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyclehrx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjawye.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzfffzd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtbqzwm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjmbeae.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnjckql.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrgmatl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzntjxd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqpzexo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhevqme.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbujosn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsogtce.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgespkkc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhotwkv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsjogsi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2puepgpop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwneggc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaufduvy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uthcpgoe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2inyjhufd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cggnhimt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2twclxype.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zdspwkqb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxyrkub.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tiucztcx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzqiiw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yyudmeqg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2bftlhnem.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bujbhuez.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqqgaqq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmwetoy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2muiubzlw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2knlobmay.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2apxptsyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2emohlmmf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpnwngl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdmsgs.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhzdkcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odnwsrpp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuvrybe.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfrpbsu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fseicyqo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2embzrgmf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kutvmllu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gunbsrzl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cphoubwk.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrmelqx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzwhmpi.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtatnxg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfkgzlv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddorhgqr.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2brcrpizq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2agixbnfi.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tscspxjo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iylrehmx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2tammwprp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2avkyaxtt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgbjach.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjznzls.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrwbqpn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hldvnpxa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szwmlwzn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgchqup.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2aomxdmto.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2voiqnrod.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqcforf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkdcmsx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsxzbnb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyzvfvl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrwoode.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wybikiyg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2arxuuljd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2muihncbb.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxnpxeh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjbsawd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnrvofr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjdbxvc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxwiec.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lakhmjzw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhypfsm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiriyiz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcklidkw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2foyoymvs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnauklv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zlchxrco.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdkefuy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvwmcnr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2beqrbxjx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzosyxb.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkqwnpn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmmncbn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjckliek.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvwbtyu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dbitcttv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pokaumhg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gmftmspd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoamaya.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2haabbbmw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmacmvd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2garkilxe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xewalevw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2teyaebso.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrfvkgn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gevlzhoc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaqmezf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jerijrxr.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmllhwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyjihjl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hemrpjma.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhaeoav.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtdtkyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fplzdidw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jgduqogb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxsnlfx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2djnalogk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovigtdf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhieoyl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbmbzhi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mppnuxnr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2synoquhn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzszyrax.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyzenlv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwselyyj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxlreid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zechfrxe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqrzgby.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpkfigm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ancxerpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxgjfzx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaumyuwg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtatouc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpbpaog.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2iexdpeke.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uvorodjo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdenufd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzauxrg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ivouxmwk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2najymbkz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2feznuywy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2emlomqxl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnbckpt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjslqugz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgzfhrr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dladtbwt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2clsnqhjj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmogxbj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyszajd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqqrkzi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2okpxdtdl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfadaud.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdhpbig.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxbquhk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbriokc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbgkzjg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvbpyp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2unehgidy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsawczmm.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sevxzjvp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vribncse.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axkvwhbi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2awplklue.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpscnez.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxaupao.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpsxpww.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvtmsxj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxgctxo.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2chjxpvfw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxnjyrw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tywpmjnb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiwguzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2earrkftl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqlrzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eebdcvwy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpdcfdf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmfqmqk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ihruwstf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqcompn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiqxsau.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lknzzdjr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcssaip.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hddasdta.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yiprhahz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swnthyzy.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2juxpzmia.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2liofxxia.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgovtso.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhzistr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcirgwc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jucnunyy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzhphvu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gynznpmx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbjctd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbaszhu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgixufzl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2twlyjfxa.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjjdbzm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbtlyus.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftipxuov.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsgduuc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sydoyjrw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvpmuky.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzkrgwa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jppowvri.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwytljvc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbcuon.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtmxdhh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzvoooj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiczhpa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopwdex.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyxnmyy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtrwxee.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2orqcmjct.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqijqfx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2escylygz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ninwvkny.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzsaepj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbndvffj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2twkgukoc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxsxwd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbgdhgz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2juzenapv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsilutj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnuyzfi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2npkeslfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfswxjgo.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcyrhmm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxztafyv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucawusqn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhrcboq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoqhctj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnownnhd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmuyodi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2volcgcar.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwnnwfa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoaplaz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbvqjfk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2udjeiafq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvninp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkbswvj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvppvhph.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2acbcnfzn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxpieoa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2urwrowub.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jsijkevy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhdjble.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2umbgmlis.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aickpabt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgfgoar.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vinhmsjd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbzupdz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszzjkad.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igyuwvkg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iyovpmua.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cshozkwg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeaopsz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kidgxbsm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcwvugm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqarrrbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiououg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtfocrf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwajdsqf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpockno.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzocqva.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wjujfevu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2atjgfmyr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2icuohqsb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwokzvdu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtrmmld.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlbyypm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqgbrbr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hvulwtij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkqrbvp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzodnpbs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2asbjpihx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqbljmf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2onxusryl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyzhafi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpccssh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2opkfxeft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcwnvsq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2baqurlox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsounwz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uhztrkov.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2edtehbbl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjbdhsg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbahezv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnevvjaq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwimxnkz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtsqnbg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2txfvuutp.html


<!-- 参考信息 -->