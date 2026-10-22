代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqajntxu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgoqhzr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjcninf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzuoigd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2meronpcg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2belabepw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnztuznw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yicjnvib.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmcwqet.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxqygfv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gevpecco.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2citulnmo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoyjsls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbkjsux.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhlcxng.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ovptfygb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuslcht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2csgytodz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hxadnofi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoldoar.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miehlmpu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mynpqafy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dduoxtaz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jxryovqr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fitfjzhc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lknoipxd.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnmpsgp.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzzakps.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlynpfzv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaadrijm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezikiwuu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2keitopan.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iigqvxxq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2siaptkcz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmpezzg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2thyazstl.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpllsse.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2kynkkrsh.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bahihpqz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjgeict.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgbdfmk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2djruqkma.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkcgspr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnercsl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjpwldr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrgnvpu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dbebkgzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2zeglkrqa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwknpvt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwrfqxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpawyhf.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eemjhize.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjavsqn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2avuejunw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqdtaqv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhpfocb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpketrmk.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuolyjg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2keivwfqa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2shtofqma.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtyyqwq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kammyaqx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2napycqbk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgbzlaf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfylgttx.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvjzyie.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2swakphlp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xikyjuho.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yegzqutz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgcfuia.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmpwbxl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjlwknb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrhniro.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtcjkzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmrftmn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2venhuxez.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmmvnts.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdwwpau.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgvsxva.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhyjrmn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ucejvtpx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsrmxal.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wcexutzl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeyardx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2udjtwofq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxpsaea.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqblup.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rzttcena.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzozlel.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcukobu.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qejevvwg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrpnbnc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdotlvts.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gemakkwb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2prddszxr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxdfnct.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuzmwwe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhkhyje.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2optuvrom.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zasoniqq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcflkae.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyorwao.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvdpmnq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcwxvoi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iricxvqp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2idvincvp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkalvojv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bofzaswt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsfeesa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bupfbzif.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zglelbzt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmtmds.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2achjnwpr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqytkwc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxoypm.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcmyriz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2srzxuxck.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtcgtzc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2insfpbgc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iptneimz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ayffjyxs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sintfdbg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cubsoltq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbpcttu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ffubipor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwrfitf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrppwat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nthilwuu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzyfcck.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2poaanadl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzwkyx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwxoiyu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbauhody.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaonnhdd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspxaxmm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2owyeerre.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqoewea.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhmmxja.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsfzdcn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rghdzzld.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcgwfsi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsdoijj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxpgpsz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbdhlgv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hshlhbca.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2biaqrmjs.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppygklrb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2buoeirno.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2iahwrunc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2odqyhjfv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pzronlmi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2miccdwsc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzccyvy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rshrixns.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2webaiwir.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjotcy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpziaaz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rricwbiy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqprxxhx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2noejvlto.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2omiiosli.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjrdutl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jemgmlzd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmkwrjr.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2iiltxklw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzvnitq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjdjldn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwubeseu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdqfhs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxohnnv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2utgjtmbi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hezcesab.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbjlnuj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhmqssv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cazuuoli.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2elsdkiqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmkikhl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuqefyi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpxrnbg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mfymsndg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2igkuuiib.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2luynrncj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsiwtvk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvcjrfx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2swlsqdaw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmedqeg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhpeqks.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2aggaksfb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2oaakbcbo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2thojsvga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yasbhpio.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2whkdagxp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2osgvnoqq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfrxeai.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjzqqsa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2karywggu.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqsukta.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2leageseo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2knvvtieg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxcpgqp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxulxfv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxjtxot.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpixpxpb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyulazcx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hczjncfv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2unieymoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rovkliwv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zivtujme.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypksudxa.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqlcrek.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnhbphw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2squsvhfj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2koxrivdm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkztgixc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gewerrou.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehljniv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqchqhr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjnbdfa.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jctudoql.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qweprduj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgpadlr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjokpxar.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2urjsiksb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoaelid.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2juhvqsai.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdobpwe.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpwimqm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwvnjof.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oipusjyj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxwwdco.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vidudbcn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fumszwav.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eafqzadd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2scazeenb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkvncia.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2abqluoyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2loixjaim.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmvzatl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zouylwfo.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2adagrmsx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mazvfutp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjaqny.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kifyazmw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mduresbv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjqfmlg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdohplp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpwuswc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2vsemgivp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xhizdctm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzttudky.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2butlbulf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiswykf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hvabkflb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2omrmbhel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzffslzm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2teilhqkq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuhzuox.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdypuia.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhvabxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2juxskqwa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsodhhe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ldarbwnv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfhhmbb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbpkrh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcanfdu.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2getrdjgo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsdbrvo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iycfrhjq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hxghbmuz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afeahyrk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxgbwnt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrtoljs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2unkspbqz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tagwufqz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpwvvxx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaliefz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavphdb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgenqxd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbggwimm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbamepwc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvfqiur.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnnlyax.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2toizvako.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashztaro.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2izumaegb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiunsig.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgizdwa.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fnppukko.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhlvdzo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhwcbic.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fqykauyy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2erdhnljc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbapzlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cecpadkt.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smuvurif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqrwueg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrnqrid.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bsabhnuc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2luboghqs.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uadbiajm.html


<!-- 参考信息 -->