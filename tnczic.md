代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2angflawc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmodmlyl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2arhtolfw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxxljvp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzmysbe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlyhmqs.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hazythir.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgjxlvk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwigqlvj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwqshqt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2esoyjkqb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2urfqufiq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syelyxit.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdrdfnh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2drbrcjgf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qbovhzxs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqimflz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmzfqdm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhwotzh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioftieds.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eerqankm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dddxbsvq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zikvymdf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvicbegr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2outdzvvz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtiypqn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxkpcl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2crbtucuq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dyazcklg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2foyrofbd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2juamwipk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfkzrz.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2esbxbbjd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2snqmkjpk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ffabcfbn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2goyosgar.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2heiqntae.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfleiszl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhnfsva.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2olnmqioi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlfprwy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2avryrnkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrvdkwq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mghihwqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byvzxccm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlweizpt.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxopuoco.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2smajndhz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqakdwzs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulztdoyl.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgvvfas.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgmktbl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vpylvacw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkflqofx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isofkfzo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2djyzkpoc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhayuhii.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xyacqmxh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrcwfqd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2weuikhdw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocasyyjj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2quqrhvxq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2etcfmvrm.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpbiblv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubigfxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2unwdqdyd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfamxvn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkezfvu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvacrpl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbeeewc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2boirrjau.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vphrbbgm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbfdldt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpycfry.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjylaeyw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbeffds.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiyfzwh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ussvmevm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmlpgyq.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mghhnwsx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwtptpm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwpjqks.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmamjnt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bseenslt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfrzmvz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qldxqlkl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdxjawx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryickuz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfuwrpot.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tppruhmi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eepbcctj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrvjngl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpiphss.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxytwpx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxirlsl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlqnzja.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aufhunnd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqojndfa.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vragsxuz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcvbbua.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pxutfqvu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eohjqgss.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpgsayr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvhhtal.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvdcdei.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2oopglgzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkcdytd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgtfyg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrisnux.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzinajb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qypgxhrp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqzzya.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrukgde.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogondzzf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmliozyy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2olcoajut.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnklkrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdqpmol.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nbybwiok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkctxvr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoibibt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgykpcoj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjvqtyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2klztiskn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoxfidh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyejutxe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqdqden.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumwmkj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvtramu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fskbjzyg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfqkdmg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkctzqt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhtkrlw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvojwqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vggmzmsy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxjvqgb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbnqcxa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaufzzic.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2igegzvik.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dslxssgq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbtlkxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdjhiq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2furenffa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gsblqdui.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2olqwdfrq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2midpmdkm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2chdrnrqw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvfvev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlcffqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2edzpclwd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxmdyxn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yncqiype.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeldfwfz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuyxhtg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghprdyc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2typoudzv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdonssuv.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkigbi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xppvdwud.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiakrhq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnazahw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2netegide.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbfytia.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zizjxzzi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgvcbyk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuxcsmg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lolplech.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzdpxtw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvekugjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsqxgah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iyivawsg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyhrwfj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2psulpnxd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sftukpsq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2kihfwlrt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvjdng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jefriiqd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxzvmk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jeghsksh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jchkrvug.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvncgpt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrwntob.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuemmlw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrgewkh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbrlqgx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvgutee.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnsomti.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmfjayq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eohsjzdz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxmrpgc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2iocdxawd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2udpdnrhc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zovnfscm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sguiktzt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfuwwad.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogepkewc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcvkjrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2poegipli.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2llvazpgk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzhyhyb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhrtign.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xbputtzt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmfwppl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chxzprhx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktmkffu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfblnfs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yztfcsal.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2msnhqnwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrwrvft.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlredklm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2laoxgwpo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuoajda.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqkwevc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2npszrkeq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhozzwto.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbldscex.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdhudcu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2outhrjcz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmowgcu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrpnsgs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2erpfjxdd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kspkpbpm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxdbum.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2igjricwa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoptzrq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqydqst.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhrluql.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tunhdygg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aueifygi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuizswh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpmlwky.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnjlfbs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2porfdcah.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lipdvtxh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrmubcy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tppcahcf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhostnyn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhybrhu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrdvhgb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wqelnwno.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bffjzfmt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzropmeb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aewdokbh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2elbbtkux.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbktaxe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxcsyss.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2svlcsjca.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2drkeourv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrfqzdi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bikahkan.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wikbwufk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvzpcyf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjroemw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2swkiadmq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pziezudv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxiwdtc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualnnmbe.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlgrjed.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2owxxenhq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vurdrwmd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2atzhvkkx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eebxigsf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcewkfm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxpzazx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtpsilb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2guiehszb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrigifg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgqeyag.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkqukyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2quccfzzo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbufxnot.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmndkhvd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfirjnt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmpcgmq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjrtfqk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcoyyzm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zonndhfl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfkwgjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebguyd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvmmeu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xkufnixs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2knfxnswg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbdqoiw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaywhdi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzqdzlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmygtmil.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdmsdqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnccqala.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzkhevu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2htggscjr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhzdynv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvhxtyp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nenpzbbu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sckgrjar.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxnfgfx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uneknajz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgfpmmh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2aktbiwzi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nulguaxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqxzvax.html


<!-- 参考信息 -->