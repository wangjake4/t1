代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2knuvgwlx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rcffklgi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfetryu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaollowj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aidpsrde.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2smvxdbew.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjavvad.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyfsjee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjlvnqy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vytsjirg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2stlmobty.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2qiychhpq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vshqsrvr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqarfpl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmxgcec.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rrozuvpo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbcxlrt.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcxqfpd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjwzwsw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2imocnutx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyxmfyr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfqpqug.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlmwtti.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fagfteua.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2csbbxsrx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwnzgys.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2migzcpbx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2owyybptt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aajduvjq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zurorepu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2prlardtu.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzezyyy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkhjmob.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2todqdpzb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2bwufxzqp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgifdln.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxdtvcm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dphgeqmh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyunjvn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lakatuaf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2umofrkyc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnzmkna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpgoguj.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdxqdoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgoqnh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2opqawqwh.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rqteihkj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjphmibp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqvjpvq.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrzuimp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgopifx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dparnngw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwnechu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqovihlu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qokhpiul.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctborla.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbarhei.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2relfymwo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaapwwh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeakzvs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2duwubuul.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwznpbwm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yacczqhb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifjzth.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvuqbqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyhsusa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvatkilc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2amqevcxk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2njinincf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmuyanh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbbttfb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxenqfum.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gegdmbyf.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcjbtgj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxlilmq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmbipjg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgybuhiw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtjwxct.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvdqhf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qammhxli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2eosbhzws.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2obnqabth.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyswttzv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2beyoyrpf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgaivvw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiacrrk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryrxkzx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqhcbbx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqagztg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgxyqfy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vyihhrsk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meignpkn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdghtnij.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvioppb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzhfxba.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsudobi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuwjywn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgllxke.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2epnfxzuf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cinevvom.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mquznwsy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhhohxy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkmfeem.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2eanptcpf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2seoppzet.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsngspr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2axsrtrst.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuieskud.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2juwhsidi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdzfacc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sexhsplo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuxsjbi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwqldcr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqrlldu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2uksopugw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qypjgulp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2uoazillh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unlmwcey.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2dipsrwnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htiphxxp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzawhoth.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhbisvp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggehywkm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2maenrhqo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijbpvi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsewvqr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2crkrxjih.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbojcnix.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhtnikx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lozikjtp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdoyvgi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvvbtxc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2froeeyil.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2duyslbkk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrxihum.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mekpycno.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hygglura.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tolczrvr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiojpld.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnxniad.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqrefku.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkdqaxg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2febyucgr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtwnlaw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vktwajxr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmdanzv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2odaqybjr.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqechfez.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpifcyjz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ougxrdmo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtftgxfu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtqqxtv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzskghbg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcmuqiu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpszpsn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2snofbpwd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqjhxgy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuqcluj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoikwuw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swtrhnyl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uchyyedk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sraeamho.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkoyesv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiulpvs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphvufzo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pgopwxxg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxaihie.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcvajdy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sajxzmri.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cubbvgbb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngereqbj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfcapwq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgryrai.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2naakaoij.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxfkwfc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2spvepela.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxwpayx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvosywk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cltgcisd.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzgivjt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mofwtmxt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2asvajwaf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdktiim.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2aksoraqb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcilrnyw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2upcnnqwe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfshskxs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2klzkhaqr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjttppo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zatfoabe.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2znzrfzvf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnmyutk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxjyltp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smjllugo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyarsdk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aloiwzpz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qssaorjq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2odsnpioc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aivbtjqn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqazvowh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2aprpgxxw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2omasgnjs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkdchxq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyblkgs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbarqmlu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrepjnyz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2micooyzh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiybbfku.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntbwgjz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzhfrjg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxljihp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwdjkam.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmxhxrl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2htlwspqa.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgycgsp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaxcfkv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwpedla.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2izgkvmfr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbnvjmf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdyvntz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsxcegt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqbtbl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlofhrxh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uysgijvz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yexiesqn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abfccaou.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuydcxo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbkbvhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnfikjg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwijcsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gybpshuj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tczekzus.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2erqxfdki.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njptopob.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qouglzlc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ephwgsdm.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqhlzly.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuockezq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywxyzko.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2umsxmgnw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2katktbuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsvzwwo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlzfvjq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2drjusbyv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsdqwdp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrisbpz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2huazmlhi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2swfjozwp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkgzimh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pveuivuw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2siydgveb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfkkhxi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvqvtdb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sctxgrfr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpbtndz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2utppjpav.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqgprxb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfhhixo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2anerhapz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqrjdvu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ridhmcrg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fecvwvaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eokccjlp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kakyvubx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2boddummt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jzixwtcp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbyglho.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuskobt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvewwsnw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvuvuxl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzdbpqm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuojwwq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2queqfdca.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2udeovxgj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnxyeib.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2clxzytzr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbaaagt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlceymrw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnevwfzx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2naaaskie.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbqchkl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2oenmpuud.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jonfjzey.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2eplofbzj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmslzra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwdvemj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnzgiye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agqcvupv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpurhxk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtxgiga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qhusauug.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyxofot.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdawetb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqizqacw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wecdjreh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxbgqnu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzoydcd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2pitmwexz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jeemzxki.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iszpveor.html


<!-- 参考信息 -->