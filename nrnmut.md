代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tciveyqx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pomxtyns.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2awgigsvz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsjhggd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlijxzw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjvcxog.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzgmcud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrrvddz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbhqvwr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuysclf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lymfxrze.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzqyxbj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzciukh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjthhdso.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jicbjpye.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nhptzvrb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdandrvc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dutvwucv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jyowumwi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiovzvl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeachcw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsbsyli.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nremkehp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpkevaj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjutthl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jilrueto.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaarrym.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzttbev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqadjay.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2owptvmvk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjsxowy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2leubydrn.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvwvjbu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnorkga.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijroelzv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dilyybzm.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwbechp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hykrkoxr.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wiksbarw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dtucvzlg.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevtlxg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcfflpe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2axlsjdpz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2elxrdmur.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnjedpi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dldmslzh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsyuhpx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuhylfq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtovwzgu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvisuynw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edurhkyy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2urviecbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfdojzo.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wufkkfoe.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwytcsd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2poocwcga.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrgaal.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncennljx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2haktvufu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqceiyj.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrzfblv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoumtswl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plekomab.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyqkkuy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2chwlqjlv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xlggrtdn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tuerfeex.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtirmypv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuudllg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2szvspcfc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuekmsou.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2owzpyngr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbqmool.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbqelav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmefuho.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsfvfmp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnswcwxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2quwbwpzu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbqahse.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjpvzrw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgxwnhm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2haeiwkkq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2oicgygxr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfylhbhl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oznmdhpz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxncblsu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxxjtac.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2duvrxvpu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuoromk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fchafzxr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbnxwn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxikdur.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwroxxn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2womxsnns.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeskjga.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clyvraqt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2egwhhhwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjudkpv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aanmfijj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pemwdgyt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoirixpb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptriwysq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqiiivn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibspiwsd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrefqiog.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeaciqm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcxbyhx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bweegkhy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvbadwt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjuhhds.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2njethfdi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iazhrcvm.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtlzluc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqqlbjg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2bexoszdb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyakyhc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2roygwafz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzmlanv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgvvhfe.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmikkmf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bnykjbhc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsdllku.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2plylfasv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfmbwjf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ceildpcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fflxbgaq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gezazgcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdakglj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjffthbo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbecnapz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvycztdc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavhbuvq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aunrfbso.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzqunlp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbueixae.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2elezzics.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhtkqsz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiltbsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxqnael.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyrmiuw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frrnuyjn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxujier.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuceatg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrpuugv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jrctvmsx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbctbpqy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2hucdychw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nflzpstt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbotcds.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qacyhchu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2usoxqhkp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2senduvwh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2adojkkzz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhoogkx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qddnoply.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvezwkfi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idlrbqid.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aotytkgf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvebvab.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xccodkqc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuchpjz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqommgpw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtvauxs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oprphdcf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2kocvjjkl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2utlqdjua.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnjwsos.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdktucbp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlvbcsu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrxnxml.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqxkuy.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdwjouv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qheukibd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhvxlvt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuuosnl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mboxrpht.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcbohhh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2foglilhu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsvufwy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxooksm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2olbtekue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjdbeqa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbgwtmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2whdzmmxa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fkusmrwx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rigrytcj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbidwxt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfnzetu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjakcdd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kknjoalr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfrfauh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvriszwf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lduxdvju.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxisbgu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdsgllx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynethqhk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2juqnhkic.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2otsmrxov.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rdulqfvn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyzrczq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaectdnu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iteujcpj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuxujcw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aglzbair.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pkftijeh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiignri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrroued.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfekcty.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylefltiw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhytfbcx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzqhwni.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uawnofqm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjxokpc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrrwkce.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uompcbap.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokmdrbb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhvecdv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldyyapx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2swaszgjr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkuoqzd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiyejgn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fnixvdcf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zipiznvv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cucjwusd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2itlxsans.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2utvmgqvm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfikft.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2readnsig.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ascmogmp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbvkjjk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdknlwpt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxbpujy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sbygxsxo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwnbvju.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2unsimokk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2usldwdvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxvtivg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2baajeexm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiewbpi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxavrku.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcawkfjr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcwxgda.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2crqsmmep.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cxefqzvr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuguwbd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2muuwjyvx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2djsotvof.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfplnsd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uvexcyoi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfepnlgy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pjktavmb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhezejv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kldgkeui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlclsfy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbzyhtj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2efvusard.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfpuicq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmreodj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wbufnphm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2evlqzqtt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhsspjz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zczoftcs.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiqlwnc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjkjkjo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drowqoyy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeplobca.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkyzbxz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmonacuf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2becdmmnv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2misawpjc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagylmdm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeagyjl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dswzxzfv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkbcxhe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asmzskoz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mppuuddp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglthpkh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgbavtp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxitjvze.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uplchhzj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdvibuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kprydxkf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpcyatz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aahwghqn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoevfrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaolplg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwdqvuy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2trgsrgpb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnkqwod.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtbwdsg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxlgnn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2smgsphnk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdlvipk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfberolu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvhhdgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvbvqwb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hismhbom.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2aujtzvsh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mqomskso.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxxulnw.html


<!-- 参考信息 -->