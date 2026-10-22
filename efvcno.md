代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2exjawmdc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxpefva.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2okngqjdb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrdakmt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2uefbchsw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2eisszylk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsavtklp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsoxicw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2izxhmkro.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwqencf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaodnzz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lezyekpq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrtkbwl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2symtqpio.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjmixup.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2frfpxwla.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyztlpg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2olecflnr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qszlrvkr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2myamsmxs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlfuuma.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qevjabdt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afvpgwqm.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ktncnzdo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2edvsgeoc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cztodidh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnazzno.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoeadie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwfzmt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uafrkvfw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2rctqgudt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxvhjzq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uynzjxmo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaazfbgu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibboewyj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jishquut.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mttoctsi.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbssfvz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mukmcanf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbhszqi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2toyplrhi.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cjimxswt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqhsoxs.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2elkoofkk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvrntfd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2veyqssda.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2auwburda.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2enhcutyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyascri.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqnvwzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elyagbqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdbwnls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgapgof.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jstivjtj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpvfvg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2apmsvcll.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvygxrlw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbofulvs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeslfvwd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sphmpkwx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrnacxs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmovhcdn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2llqvqzhs.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2viwbzkpl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdlxsvo.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2olcrwvoe.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaswpnl.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecacofiv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiintsi.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2kykoxbyo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uztnomge.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbrpgen.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuazovy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfskwik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxpzql.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbgtigd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aszvhspi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejenlcrx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsghmxb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeviwpub.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjudrfw.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrymxil.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjcfmcb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdcsfwh.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzupymj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2robozzhc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgsusrk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqfeoz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2biyaxawr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqkvewv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgrpini.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2crpcwddm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqupafa.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvulcqj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlucozco.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzyveou.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwouooi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2thfotbzs.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mjurrmhd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djrwqhen.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bimokyvc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvhlsrb.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqacmta.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmlisyq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ursqnges.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvjlenh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbggthdb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2etyvrjbr.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qaanqwgp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfiypir.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rldkkvha.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsppokl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbjwiam.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2clpbabel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2eupsbyrx.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljxageq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsqgcye.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhuhglg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2thnpksoc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsoepzf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fifqzxwo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmjfphr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcuqpsg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzflxfh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bfetpzkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdopgjcp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hftukvga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxoazuh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2izfbbqsy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2chiesrbb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpinfhiq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yguxqjxo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eomzwtux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefswsow.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eolaycas.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofquecbz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrndpzg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fodrepfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtfaqsp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2petsvhzq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzppncv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhmguuo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuwmcfd.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnlzlwz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2unrhsmxz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2edvtyavy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcjxxub.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjguozg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zloluwou.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oeowzila.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vesncajw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lntlwmjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiekxuk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqynexjh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlpnhsc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvevwezu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkrlxbe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmuaray.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjotsfiu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeebwrmt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flkrvwoj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsxkppq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2burtybnx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2abccxdqi.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2trgulikx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzakzeh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaewnqdn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpaxjyd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjobrtyb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkjoznn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhedhdi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiybpoyb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcydjsv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cogtdfpk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcukrdr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhcyhil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrunqvgw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2guqojxxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fklmewdw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmllnwt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsmzbjg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlowmd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgldukm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgouyce.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwzjmxh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2npsvyxim.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbmwnoq.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2anzyzoek.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tihjvngu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkjddyd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2snmhgmhm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmlozpt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2apiktnsk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlufyfrt.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2axjegusd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2smmbnkqw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnkjghf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhkdkvd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctunik.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yupswgit.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnnjeom.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzuunjo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbycpgd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzgcqlc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxjdwm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kezunutv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qkupxlvj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkheoqb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpdjrmc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyhajgj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2eleqbemu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awwqtfhw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqiwzkn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlyrxlz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxhtiba.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpxkfmv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2iljapoca.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czcjzwdt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmquqkxj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fogekckm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhvwfoo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pruqqjms.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2prfpuhpp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjizebvc.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmceyfg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dhymxtrt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzbzcvg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2otaaltey.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrahefr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfhcjws.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2euqzsoti.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpowmka.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbpluxm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhpjgkc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggodwpri.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpaoscb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfvjcwl.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvegizf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvswcwxd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmefjok.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwtiva.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiwcebq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhctios.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaeuiwd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yscrkohj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzskpdts.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzvhezf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxzbope.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxohcflv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbtxrri.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqkhsye.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zalusgva.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqczdlnp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgztpem.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbicjbae.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2geyyhxth.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpojlij.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zfutqpxb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2msbvlwhb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcvjdkn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjmzlcu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vrepllzv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmbfmlv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxckzua.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjnysmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlsywtq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2einabmjw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2apymapyp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kqglahya.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjaetly.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oywtbgpz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlavhrj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2knjfowhq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dkguqdiy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbufwwhw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2diqyhxev.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wawfrrls.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbqpcvj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnmepea.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzgwequ.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2tifbnufg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlntdhqz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iewzeipn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyevwgta.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oaitwdni.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdylbue.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgblnqbd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cipmffvd.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dtenpstu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvgrjrn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2btvsnsll.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsjnnfc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoglprn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaykoga.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcmmtub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxdyml.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyishit.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgxuyas.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtkomsa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iltdjiqm.html


<!-- 参考信息 -->