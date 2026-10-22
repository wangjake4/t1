代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjevmjj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxogbfn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgyczje.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwygcbr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxvrzzf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwmyhpw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2keauwxhc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2bspsyspl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxqrfzx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2awbemdzi.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmayvwpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vwricbdz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fifhmmpw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsxyoqq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kctxjdez.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfdhssb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxbkjgx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2aegwoxsz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uovaqkoj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fryfmhkw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlmbpwk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekbyrxf.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzgkfcr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uififkji.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaqnqce.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiqwkxk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtaezhc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2krnlwcea.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qttlwuug.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkheogf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfezynd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptjnpn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhmaytp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxifhijd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xoowexxv.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmeqzjk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvschd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsrrvbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tksrqjxl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2covfjvsj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmtdhtx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyhtszh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbemvgh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2obwvbipx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdautvcg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2brafpgwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zswzadcl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpmffpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmrldzg.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tljdknmn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlbnrql.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxofvyj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhyhore.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxngltz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxbtazx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcocdtr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfxbgwc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2arqxrfpe.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otoosvqa.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhocbxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrklrmq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2krabdabc.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpsjsqw.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjcpwi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2otonvyfw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2gelqyhdy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndfmkb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsocaly.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpfjtl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2satzjqlx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oedqjzdy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppldhzby.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmouculn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbrwggw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeiaxqn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuibnhc.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jumcnsrz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxfzjrd.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdumthkn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlltdmz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uegxmgar.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzhubpp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2apnuohmx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzesio.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwpccig.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yghvobil.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bobbtqap.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsopkqf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uidqdwzy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiudoww.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtiwptu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzlhpqo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mahdmzuv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvhbsso.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkqqlnh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxawnmcb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhosqdet.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ektmrhiv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2muwnxrcg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2leprxoey.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfyyryc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtlbusu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzimarci.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sebpanij.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbgkrpx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yydyjfmp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvimxwa.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyniylq.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2alvpkyaz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2weyjcfbq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsilttf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pldaejdz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mmswkrlp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2doqqhnkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiqjayz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ivndzfdw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwimjzy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwzdwls.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lykjxwgc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdnysri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvzcetf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iljuwlwb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hecyigug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cppvcwlg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsjxzfk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpixfg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bliirdal.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsgpjbl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkalama.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvzcbjk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnluhwth.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhmccgc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvacgmkd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqaefzm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoglyyu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2smyqujnr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdlyqod.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmdmuim.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2urozfxxp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkpmfyn.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2huhedwba.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxziyckh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2oahhjzez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjxufud.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hufpzisa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cztyimei.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xymfbfwj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkkqxxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzloizt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2urcylmyj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2citrypox.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbwapa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqjnmgw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdkzpfy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2whexhwbx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmvqnpg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2molzrfhg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnikcbhu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pskccnmw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvagdlq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvkmrbm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyhzamh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnhegom.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kudpjeuu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unphrjij.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfrhcl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpciwlf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wslgejkn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slumpwsf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urmhzhpx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwtimbu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzkiyyr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2itltseav.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjkjiug.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mzndcchk.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqstgsw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwhdfcp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvitomxm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzddvtge.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nfacijxx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcldshc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdszexs.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeqohvi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iniswwmv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkksnzi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkpjtge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bmevlnis.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2coyrdimf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbjzilj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwlowtd.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuwlnzt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qovbdnwn.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2peyetypx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuwhmjt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2udbsrmos.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtigcjyw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inlbkoxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrqbkou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yosihdbs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdlazht.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wwstltfs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrkmtqw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxobefe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urvuhyki.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxolmnk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzixczm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnqtfib.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkimkwm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tethrezf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkorlxx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lndigwdh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoqwjvj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvouhdh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqvqbyn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwuyxiv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqwcrkr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlomved.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxqsnvb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2woaantyy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfafwhp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdpoamn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2myqhjrhf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2utzotgkj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgsnzqb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2awicgdck.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgutazm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jmebpkej.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgciqvx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2elbtlsit.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahfejkj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmavetfk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2buslgmrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtaefys.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2akfxphdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjisnir.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2azhqrbih.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbqnoko.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjqayqz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vaadhbod.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jevzlvax.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuyvspw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgcrpij.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbalyrit.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2amuhgfua.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cceiwsbj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdlgmwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wkllcfue.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrxbmvk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfoozdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdthtmn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2slaamisw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyrtafd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2odrsjzew.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrunvpq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pendjvkw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwgevzn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2najjejeh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwfklxq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrhrkoq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvfyikx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgqlqah.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxagacsi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oacmjyis.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaekdqj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwficyb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gohkdlbb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otnbxkxe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oovhyiyw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqzzvqn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsuihxx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2radevjdr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2emmcqucw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pllrmwoa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2knnyfqvu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaheoyq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljykwlz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnojsln.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsidokc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbrezin.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeudevn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwlxkij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhaphod.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2koomfzmx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nmadnjgd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rltrqvqu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzrfuop.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gsghxetg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmcmalg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wzemovpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubunvcnu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ioreydbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgcjuoj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgwcfyr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdikjf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2btiyhisg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqerszu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuadohch.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfenptky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphcqih.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhmoyxs.html


<!-- 参考信息 -->