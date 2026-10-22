代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bofirlfv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vaceqodf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgtucmh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbcysbq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptskmlus.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlxoncp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2pebbugsu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fgijeikq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmpsuei.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzftlqz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqgmbsz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpucjpe.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhbmak.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2luzrivfu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2cedkcrxo.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzasxjzq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvhlrdf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywugbeqs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaxrnry.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrngdxa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqhymkd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2buydionx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsadomz.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiyezdi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hvffxibu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkkykip.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ivknanam.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qrywfugm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2auadxaro.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvfkdyz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wichiaql.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmfksvp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcqcegd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mticqkrm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2eyynvlbd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2aekqmfou.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrncftlb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzvvpxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxfffkm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dprdzied.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkgenhc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qordgdjf.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2taesyyjd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnovyeg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnnfxut.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sakyucnb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2whxusbvr.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dytlrqpi.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfgybfx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkizhikq.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbuukgb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxplkwbf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpadfnrm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gflaetcz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wesdwejo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2peygzpam.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlmiadc.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtxrdlc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknpfdgq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlmuuie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2raiwmrik.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wovjumbk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcxspmh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpgpgor.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehggyljf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxszpvge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlemveb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaoezih.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wzllivnf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbgnkmk.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2eobjuppl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbitbds.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2anmrccao.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsacydk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwsfkox.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2miielhbu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kffanuzc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgnsawk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2javklvtg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvrqjds.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuznytl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2remmbgoz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxenepiq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkknnsa.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2klsouyyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjhliqd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxvupbw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqnoola.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2epsyrtyl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxiaihv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrihgkws.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2urtciezs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nipniyau.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytsftl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvnhqkf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2rultgvjm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nhoyottx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yduvzlrp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2waoibnck.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2frjjsttv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdufllqu.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbvvsus.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2omfthhsg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywuyfi.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmgpaub.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvgolyq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2eylpnbkv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjfahif.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzbkoyd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmddddmp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mefeqojx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfombbb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqhsnow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxqgmra.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wslovjoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kryarzai.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hohtsnlr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlornnkx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlrsmzm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrylwob.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfoyfd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhvdgy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiojifn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lonbscre.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ephfypta.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjeqpfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nukddejx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhkiilq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rufdjpst.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdmmsdq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rswpqixu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyslmbq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzdeynt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzugups.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmgoqjm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjzvtpa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2eewrfkyp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lenbsxfv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqokdcat.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yajkkazv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpbpwty.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kmljwcml.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbdkxyp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhxfxh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhrljoa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjujtvw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sowjhrcv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xztnzmnh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2geastjar.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtabwpb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamzievg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuydpgo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqefuwxt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvflwye.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtpcfmp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkklonmj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjicyg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2maiifair.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrygdiyd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cajmgxkm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnopfvpz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhnekmc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvwrvf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlvrzan.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwksbrd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2crqnzsqv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2huixutji.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaltjgx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbvohpa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2azselasr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjccfvk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2btzcqluo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodsszy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpzpgwd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvkwmnq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2aycntkdh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtkwkeo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qwotpdtq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2orpvcdvu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2avtodess.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbrjwqy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2otnxikar.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tghwqpxk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rozbbcca.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyoovmh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqxxeml.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwwfgym.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekfquw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpctahen.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoegmzg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgclusuq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2osssbibw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxtjiyx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmvszjd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2svoupfjg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqoylpt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnarkbz.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmguzfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxjjtrc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqnnyrt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdggacrf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zudnancl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzwxher.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkwobgu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbtutzg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxdrimi.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzsvyyf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yjprpsny.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2robniszg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwdvvab.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdgdrrf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwmcrkr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhujtje.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxfbwl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2heuhhkwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2svuvvxyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2izeunzme.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvyfnzb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pziifjyl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsnsalr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwvyxaf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iquanxgk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zphpntuu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvcsara.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvexaerj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2egrkyrim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkyrkqg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qjthorgs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2geploapv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqddkhh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2epsnqvgm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mynbaqpc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcqpkrw.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fibgjrck.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uosgrozt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjbmdoc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwsfcbo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2suggpqcn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdgyiuo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjsqvqw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmtzobw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uapzhsht.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhamvpg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dewaqpoj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dqthiwev.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxuysxu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hunfkuzh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrskxyz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjigdea.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yafkxgag.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gstfhqkt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvammtwa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhywhii.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wevlbsfe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pkacezac.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsdpost.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2khnhuoit.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utsofcfz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wasyfwbi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ibetcnbo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2juwjerbh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2stekxcny.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdotkml.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpcconc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxblgtz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzemzaa.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrsthrm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qppgwmgq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxbedij.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2etkzncid.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowhrnbr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orqjxtyg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbanggv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2llodgnqt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2exviwdjo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmzjaeo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbnptsn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxhofuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwcofnp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xohvcnmw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrlqjgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rndymguu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsugryx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqrypeh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2krexpamd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmfjtua.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbopsmp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzszjop.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdzzhkp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvslhcfp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaesabl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmwdef.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgnngnp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfehigf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gisruhlw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwirciz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrvzuev.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnedeew.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sivwzngy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgzwbej.html


<!-- 参考信息 -->