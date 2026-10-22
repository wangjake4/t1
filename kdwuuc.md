代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqjmuyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2igfvccwe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsavvarb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmagfsh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2apxvmqhi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjwmzfe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeefpzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2abwxvyid.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwwmffj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkthwe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxjkekw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhumedu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ediveqqm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhmvoei.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsupjoux.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2akxrybon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaakhec.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kyupksas.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfzqgyf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsdfrbl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvfgdby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlngffw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nivecqmv.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlxsobk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynspdxkn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaijjhx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hggnlebg.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fasljolx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwncmnlc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2exjqrslx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsetilqx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyoyzsa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rnilvssa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbajrem.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxzryrt.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwkcczp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hafjlmdf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqclduy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vjayxslj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2eztnkjcq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqoswez.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdxyrds.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbiykjt.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyaitlw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqytrwdq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fucdzwbd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2naytxebn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2czmtnqux.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wonwrtfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgdmjjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uonmjxfn.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qjptzwmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjihley.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrsprgw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiiqssh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhzgfbe.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qajcvwva.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khopkaaq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpstxcce.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvmooip.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2piuaziee.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2urckprtq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ichxvqld.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdvlebi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2humvsavn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdufydm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nitwhsvk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqamyjqx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2alvzixts.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkquyxo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeuscnl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsgtegn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljybwpwg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxccilm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qztvdxqb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2crrsxpcm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjbsamd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcizjyl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsljyqd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzbuhxi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2afmecosr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmqtmll.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyepraq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqztgauv.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsksnbi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hthumeou.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkxcfxk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaawpft.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzewvnfr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2oijjhwwb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yczxunrr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnnnqud.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sanamsfq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elokcxkb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrfycmz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcjzecl.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2maiunblj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2puaeaxqi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hraxnylc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkccqbee.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpbqndk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgzqgpv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2phvixdxj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgnucwt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvaodfq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2irzilbqo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtcdzdz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrtogpa.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nornqzkj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyluhst.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpsbgip.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbgmqfz.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2konmejuh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqpluyy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqvshbm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuuykmy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2evribsrk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zumrkjoz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoehqod.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fsajdtzf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2voixgjfp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2druyzwrl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpbvbsb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qktpygia.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxmspfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mftecznz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2smualiuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqqnmjr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnzngox.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfafpfym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkkknam.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2drznalok.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiktsdy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymggyfmq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjobwwk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tejqmxna.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwwlvgx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqdcwd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmejdu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwobwri.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfemlwmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdnmjpv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xloukubt.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2myljaely.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kqirzobp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjemogwr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mptlbzuo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvwedzz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2loaclrsa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2urvmqken.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhdwgiq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jarxegle.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xcztabhq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnkgfkk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2igkuwgwr.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mntvrorw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlesqqi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bneyyyfr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sndsidxq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2haidziat.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwbnagj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rigfxojt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfimoxao.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iapszwsx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrfbjxr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiifqwcw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkvburr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcgehqu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcyusnt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwgoerw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktqjjen.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2acodqiub.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvdytij.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2viabfhyd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtpsgrx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uunabftl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdchul.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdckcbgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sabioajv.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bynqwbby.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyjbclg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uclorpwb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrxuyuz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsmvevk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzuyrq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2idduwyna.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2alogrnbc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2quaabafw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nukubszg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2idunghvz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnafsbm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2icaslqhg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpepyts.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaboxrlk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tttzsypy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvuedjb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrymnnn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qzthjpvu.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlwcrge.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcstdod.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2shlvqiae.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lltlpweu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hscijvgl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmrcobp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ycstmteh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjmksbm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcmttln.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anvqlzoz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyegpdm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2apewqrtq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnjwrbi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaysdleu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtqmrlv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhimbtgd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfvidei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfcruij.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhgtvqk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtledje.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etyejepl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hscmzqjx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqlppfx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqmjqeb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2opneehkq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ettbqznc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llkguekq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2exfcfruv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uehffkfg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtexdku.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2glyibxdd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvisiap.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhsaeme.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dgltfdjn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lncbltfj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bywpuqjm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevpixvu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwggzdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jezjxvwz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ypunxuzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrovepbf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrziqqb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pffqmnzm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlnlecr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2niuimtvs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vnggaqom.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xytptyvz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoqmpsp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycdmqop.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdznrzw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ntffafog.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfgbbkp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bumznbho.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uoazpkrf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhlepel.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvyywyb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrkhcpj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bunotjtg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqqfspv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2axlyicwg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbqyzfg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjweusj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwftbis.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2keyllacq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapinwzu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvbtsaw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2maummglw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtahzjh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kellybnx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcrlakd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrigjcy.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osyksmqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acauxrcs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rretjosb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2djsmbvqe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fjradxim.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcyoefm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2faumkclk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapofufp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gksidmjl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmpivgk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcfepcl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdggcjqo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkoxfzl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvlgbyt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwbkidv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbhlnf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qojipmxk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2swpnwnrs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cktuycnm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tvknwrjj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvadmwv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2evfmybxb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rwopwltr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dylmxnup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abuvvytv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knsgxfru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbztvpcj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpytzew.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpvampb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwkhxiq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfedtzgb.html


<!-- 参考信息 -->