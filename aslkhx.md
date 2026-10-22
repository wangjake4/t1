代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcqrnug.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2aztkqdns.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbxofbo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbqizhf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgetywcx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zchgazfr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgpdnp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxgwgqi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2waevifws.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2giduxbnr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdsdfaj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjybvotl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbkotcs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2njixmqrd.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2srdvvaai.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwkzuuk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbesaaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2peicndle.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2eznubcrd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgkcofz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vppffcqy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlfbhoi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yiujwvxl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvwevkt.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnbpgnz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iakaunpe.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxysins.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2byjjbkns.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwmjvhm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfgdjlb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvlvqaz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjvmun.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wznynvzb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkmtwqn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrfhpee.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oiayesgw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vvifilyh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2puqqlyad.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeiowan.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dplwdpsl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2eprhkouf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qausvvny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2yaprizsd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkruzmkd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqzbdre.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcejmqtq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2yiojsfhw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kyswfilc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouovmdxg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwilrhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alhupoko.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ahotpzdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nafpgwqi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oojcbisg.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tszwczgr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourcyurv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzfikqh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpccuzvh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eczsiwew.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbonnvf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdailvo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoknfsh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgqqovr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cedwutuz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbemzxlh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2urotbsdl.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gpavvdds.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnnpgth.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2asagbehn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2grznkble.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzktcnbl.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wdusravx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdyhttu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzunztt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2upqnuwfb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlunqnzd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkkkotu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnottfmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rldhibvw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwtgcps.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmcxadk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cizianvu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrimknp.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdzpqpl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2szjcqepg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hodnrgwk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwdbrod.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pckanyri.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2spsftqmr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjflxsk.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipecdrqw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiicjor.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsrqbgi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvegbhtn.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbrxsmc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxwxrvm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbszhdt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmhsigd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoazxpq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbzbnmx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dikkjeyr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yihuongo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2frqqndvi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2leluwzxu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2edxoubcj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2eevxfpxw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2edcholfx.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2byjzpbjk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xahekkyo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jahzkmvj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzbpckw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqezeap.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjdgbur.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2msotiesq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnombpq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2arxqorwx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2latizjmd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhzgqzf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdqhdjr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2twbghdkz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfytmnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2igksrwyc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjouwpxl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wphxykgb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnqousz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czlrcmxe.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfsjcfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smxxbhtr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfnrzqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgysxopx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuztuvqb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iszgawqu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpwwcpg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cahalplo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgddpvlr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2yricibxo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjneyjat.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfzlvmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnierzco.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnmznvd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dihgvmwb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skbanmlm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoypfqxa.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzhmqwo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pfihcdav.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eleyjsyc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuhilnz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pclrelrd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pdinsddr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlpywpy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzgqynm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2psmiylzw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxcfdwd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnqnobh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcxrjlw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qimfffzx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfcnlfe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzpyugi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxawcxu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiukiqt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sphaxbbb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2stbzazsp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqifpf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvavvmx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdrczop.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpnmwtq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hihewpgp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxufdpt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbwelsa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gotixcuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aztfhqxb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmmvdrq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sspbwewc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yttwiydu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcnphrq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxclaa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzplxsxk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zegommhu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgmjqud.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bqprwwfq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tyengblz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwqppdg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmdmvmk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2htneuoxf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2brvhhivq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyzaofq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwssawa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnopocx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpwczsq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2szynnnxy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cncvuklz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdatyszp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpscbrlx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2movjgneq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kfksjklg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azoqcybr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sseidcjn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xgudpgnr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorsgzb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjnpced.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpdslfi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbfwcuk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtkehm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtgsuq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vbucbspo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkwjeli.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcgbzbi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2roacuvjd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jicyhpxs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgyxynv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdevtrfl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjzmspm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwvcfw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mypbxgcc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seozrrvv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtoyxxg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wddcvueu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhqamr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vozzfkoo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2intuwryf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixgorj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjxswgy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbogtuas.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkdwoft.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2preeamva.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdpoayy.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oewkmipy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcfpwnp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxpasuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eizpzucj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uojziuwq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmqghwu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rndnvygs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nblcyykb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrqfhib.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnmauuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkejafod.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2byncyvgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agmeokoh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuwiznm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcucpjc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjctwqel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wckjxpno.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qlemiinz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrofsfv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqutfii.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiwwhme.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdlevst.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjcxjzt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzwtuhf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cuadanwf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ulllggfw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dwysqsms.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvysuoy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsemsdq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xqadtkik.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrpjgyt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cofyayjd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpoqyag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2stmrcvvm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgugsla.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqlzocl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldbevv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2acyzvono.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atgqwcth.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbpgofz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwwyxja.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2coljuwjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cikasyet.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfysvv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdhtfsy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwmpyzn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvttaha.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vycqvbjl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnysgkka.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrhuaql.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2itufxfvx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimgmmw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugossefc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqlqiwi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eakznphu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtmhedl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtenkcg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmljawz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmmkxdf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtnkbji.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbvevae.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kxunzoir.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdsavtm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eyollylz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoikjzu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tbacalda.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hyarfgzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2weslnjuz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mujwpmwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqsrerb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2motcohws.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nirgcjtm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqhvloa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bszraemy.html


<!-- 参考信息 -->