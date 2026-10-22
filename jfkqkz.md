代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyajrxx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2crehrgyq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjctgus.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgugipt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkmtefx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2atzkjrfn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbprepdp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkyglfm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uminhcrn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2madzwaqr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnppjwa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnisnja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjudqcyk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqhkief.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjtxext.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxqphwe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxrgcrh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2goacbvio.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2icpchfew.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpdeulq.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2elupblqa.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvqaokx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlboadae.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrorilt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcdhyba.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfeosum.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzmjbei.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vliinepf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2awjiwcui.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2whaffref.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2behymzci.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjwxsks.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfnprff.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqaidsf.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hytndhjf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qmngjxpw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgmhzix.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkkfgjm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2izwwyded.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkhpzkx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bodyizyi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpvpai.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2iuulacxf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vxziqiog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygprskym.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xefyoarv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vggxpzft.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcslmxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqhccup.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfmfrtl.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2piecrjsa.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2otsnencg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgyzxqh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeguleii.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kurnxbyw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvjkkzl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mckxuskx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdhnrcs.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvmjhxp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dleunscu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbrdstd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vinzsfnr.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sduiljga.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xauplkzm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqavizq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzgypuw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoyufki.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qjswhezd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnysxdme.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2akwqxoeo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyuyygj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2titpwimc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbahadbx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmjcdjq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoafkoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tghmudnu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrucdlo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlajchp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2odkscblb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcookgu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnngueu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2evazeomv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dremdwul.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqfgaii.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2khpzejes.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxjsdkm.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbzoprh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoliciv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2crvgxkfy.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swkuumax.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpvdim.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvfjuwy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2imrfhoab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrplwth.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2udmuvrxj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyocwgp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwknbwn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxzrsdo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgggfgqk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uulfxnpw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2imcykebn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2izdbybpy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcolbmey.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ienzngpt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxrlanb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxqxhrt.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvvywvx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2owoymjjn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpcihgf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rojkagvp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2dcweyjmg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmodsgu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ggohtxww.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dazsgepw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nezsrxgn.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2futkdmxa.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrbitln.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gubiqctk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyczytq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bmccdwpp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ahngiiuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtmrmic.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxsxdtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgtuaci.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeeliql.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvshyzj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tirhkcvd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tetaavjv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciaaojp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfusgkg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtrgjbk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsyqirn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxbnowa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsywbyhk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2giaekcow.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pduiscdy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzznsbfs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nenewzce.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuzmxem.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddghsmxr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdqejpr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gazznidq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvijkzb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2djtipyuk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ualulsvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2loxkejsi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mekjtsxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2clfyhodk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrtjaxm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2fykfzjkx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2scxohipt.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkrgwpz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2grlvlguw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utxilkip.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uinrffme.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2isfeubig.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edbasbjg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoodpjn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaopcox.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwgmwys.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xekqlmxe.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kshgcezg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roxkblfa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alljbulp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmujrdwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgwbokm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2voxxhegp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbwagog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbwmkdd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2shuwcbsd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaxzbie.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwfqdgr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeblpfkw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdefakwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2veapbvoj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ocijcvbu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bomlahou.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvourbv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjsjdkq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2aflgwmbj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lidkvbkb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2womqrzri.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjhtkm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfzpnjq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcymghb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2uryiuwpn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pndkjqlw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rotaptso.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwjcmpd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsfkdfu.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hneujrks.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgfgnqg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zagdctay.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaatnec.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjhwzky.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sknxrzqi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejvept.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwckpdmg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkymkwio.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szppggad.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vjofwnaa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtugystw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlixbgn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlnkhpp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpirgnua.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qdigaesa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhzivje.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggcpnms.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lurfvogd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2spczneiv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxdsalk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbfduhi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgepmazq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctiavsi.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbdvbnf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqxykkj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxqogqc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dflfzqpq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2seiacdtc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gttccghd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjpuyzr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjduysi.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdhophr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeudeen.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gyciwnvz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2oieszhoa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaopejq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpgzpte.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgjcyqy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdldfuqk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfmqnka.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2byguolzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcynmavt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2szlbqcdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvwwov.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjyskgn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqskmvv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhylogla.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dtudvvtd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fngqista.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfqtxhj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2taurfydp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxdjsc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxqipu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2etwxczgt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqscoqc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpjfhvd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2evlumzxc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mswzonbi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqrkafw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tuonkkmx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yubjeyeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lhblyblr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrxoobl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhpqbkk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaooxkt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgrcgpv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2acqkeevi.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoggvdh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2njfuhpyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpsxwhe.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gimojiwo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaknand.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgworjhd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jakjyodu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcjkuul.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcguqttu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeoikel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2azgwwkxw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrahjl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtshawx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpqeirp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmuscdl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwubiiv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2psnemjjn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2caqcabfs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmeunay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbdbpwf.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2angbluye.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvidhur.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wqddmwwu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuexxwk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yavaerss.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnbbghd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpayokc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvlkrds.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2frbslorr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2njyawcyz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cjffoqgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhrsfuv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yibgjiac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ludprcwm.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwppnst.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmafrky.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqbxipa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2udfbrcav.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvewqovj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpqrvcl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2poomzhas.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fkilbpqv.html


<!-- 参考信息 -->