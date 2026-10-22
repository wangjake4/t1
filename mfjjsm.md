代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kenekxpa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzstuery.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjqfbwe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsahaucn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapfwvs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzbrun.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2llwietgt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hilhkjpg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuvqzwc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjisjyi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtddrkt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsjcbwi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjocshdg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2otbphosq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfngjal.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmzoyic.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgifvxs.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2oshtydmu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2twjgffey.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhkbxxt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2alhxvhzj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vldffmsq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvihyag.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hewlqpbo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uffartnf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tngwncas.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpzdjqq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdbgckd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2drrcxvmv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtbppcz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vueerqjd.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzlrmlb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeuzxko.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2uzosllqg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2uxidkavl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwornjig.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmzizvu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxzfuju.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjverri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaozipo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2crffktpr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hvycxvlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btncpnue.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dbexepym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpddxjes.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivinbsnz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhxzvok.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pirahpmg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quqrekib.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvajap.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cakddvvl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zpilhywu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzgglgl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jryzfltr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axyoixsj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlgqqxc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2awdbucom.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cuujqilt.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjqlviv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2upsmrddp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2icfaxusp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2clnaivxl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgkojtc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hyndvxiy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjdjtyq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nphjqdnc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwzzkmk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfyavll.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyagixv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvrtwvi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2spwhdfvt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2znrcauez.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ekikkisz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2emoedtva.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmtqkai.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdmeyho.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzjsbhr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzanvhu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzguqkjy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2bgflchgy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfoyzxz.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vbivuxbn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2buyccuuy.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmexdmku.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrbwnhj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzdkagm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgqujbu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofyksxt.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrmqnmq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxgfjnf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaiycfr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzgbbtz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iopvjdrn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhidspam.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueftqlbk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2abiwkqao.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiqmnqv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2aahcdeba.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlddjipa.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2byccckdp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2bujuzuwe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyqulsv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nzauxpxr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnmegqx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywllrfs.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzbokxn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2uwduiuow.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjkayvm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiougxh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkxkfoo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2tswoinsf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bsulsnbs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2yrddxgin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2igplmmqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgygvfv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnfsmpn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mztdfqmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjrhgqz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2enyhuosn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlcqkxz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2woapoprs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifovgupi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydptcyjv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2edqvfqhz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2byoyeskk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgcedju.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfadkywf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsinvkn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuhongb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbemwqlu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnvlcyi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhqtxmp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2inwqkdoq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcmduxu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tngkfhug.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2quobvuti.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uniigcwr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbupslu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bypsgvmh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2miomgixu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpzfffw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2azfbdhim.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhejrsg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhtcbrx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfoqyey.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlwivjy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtggrfv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqpydip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwlygdj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhofxpw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgdwsqq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2olarhltq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrkpsqp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxsofkv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzleqlhh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgztfjkt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuenjrtr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dekijjnf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcbkhtk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotdcmbx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwcyohd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2poxnchsh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqajxmtz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmjemxi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmsdzld.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2miuceiur.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlkoala.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeveopu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbeeetg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2defhndak.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cklabddl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyakefce.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnpvych.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfhumtb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrquqebs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2goncfqfz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdabqjr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2llfxdzac.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vfejubec.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ikemzvuo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nohkntaa.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuiatwi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rsijajeh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vczgyrmp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwopah.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2exwxlmao.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2shhendhz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uckkdlno.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwuqqn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mauisqkx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbrdevk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqgtfyc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaagdge.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yppnsfjg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkkhqtf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eynkjqmy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vwofumjr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihykxvny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqkzeqg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrimewyj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcsybdv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgfadgi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2frtdycax.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhsttgr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dygjgwhh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2niyklsai.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gixdwxzr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoelxss.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwkqojn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rquhirho.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkkwchw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dssyxkve.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfzcnu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2phndhicw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qycvtjlb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfcsbu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uptqdxgx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmkidhh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsmxkif.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjkgflk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2epqnuglz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2esndnqtf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzjtrgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ecciylis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2obicekjo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gidyxuei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhujpvna.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wfedavrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnvmsag.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2csiuhngb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asxvtavt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cheiophv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jemtzgxy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfebkp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrincbw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvlzyb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2txjmgqki.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2korharkw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rypsuvun.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqwghnm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iuogynqs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2okavigbe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfwtfap.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zggbnpty.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvntcbh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwwkmyc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kspfcncw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ehchcfge.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdzgdum.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xntxuvfm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwmskuv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mmexpkqr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoiicdp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtiuwri.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzehrun.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2egqpkfdo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuylaax.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkqzddq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfftbba.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvkvmbu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdjitao.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgcejuk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iclzvhwf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tkafxmza.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ciibojbb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiawcdz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbodwulw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2turwtxjv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2twfpluzs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpddipp.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2azuyvbfj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxhlcpq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdbchzf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybovxzje.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmsgwtt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvoubmk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2axblahhx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2caqitlsz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jukdnpir.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ohybvaoq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpwdlnf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cqctdoka.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gawifqft.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeczazh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2reemgwxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokmdkqu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yakcupqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhctjqkp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfgvisu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhvmslq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuwgece.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgbcoix.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2shfbncjl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqlzzix.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ppufxdce.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hduysuye.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaepftnp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bosbkccu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnanulo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzqklvd.html


<!-- 参考信息 -->