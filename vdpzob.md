代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiewwxv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oufnwvwf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqamtccn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqwerhs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdlyirx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqgaxtn.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2xooqynxo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2viqguzas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2felhttgm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqeorzt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2awqzpkqv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2albdhteb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lihzivmc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlgnbqw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnkxafg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrhlpce.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdlgdyb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgulnip.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxqfdou.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpoezsl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vypgqlyf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2orovftsm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjoqqnu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnztubix.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2naewphrs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmopaprv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2awabuzzg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhbbyow.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgqxbnd.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2eneltpsp.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wijmjjha.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2wimqqeso.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2enugepik.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2grkdlqay.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvflaqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqggjvx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvvyhte.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylafnndk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2gelnbykz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ebokjcrn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwrwbvo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwgwane.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhnwoej.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cjapylpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prbdvquj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2elghkspj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2afimyown.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkkzmos.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgtabaw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2termkacw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjreris.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrgqjn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mofveeqw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiysypb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gotwlrky.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoewaow.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqudmzqv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcsyorc.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tlakqnvr.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqhcvwq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjyvlfn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ednpkadh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpnqdly.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kerikigh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2anoxvdhz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iouaqapr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwafuhcu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaszsbz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuflsiz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbsnuvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyxybwh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gchipnhc.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cqactjkh.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdijpnsq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qybkxdvo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfbyhfp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwiuglq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuxmtqn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2girgtcpm.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzxleyz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgariktj.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvlyuhh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqwgzdr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2avxqxeza.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmzlnpc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqzlgjj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nupaqnib.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtpvnmv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbmotyh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2keqfpcnf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2shjaowiw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2folahgeu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gagymklz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wowyowsc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuopfs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2psaowmlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkwhhng.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoezcva.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2afbhkgkq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cicnzohk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfszpzh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yazxyqua.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxhqvza.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wneksbmh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmaoynr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkvoafd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiwxdnb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cudwlptt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wozojczr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmzvfhd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnygcysi.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvnndzs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zikqyfmb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhqlldv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2weyfdqpc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcbxdid.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2opvtgocl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqulpje.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkfpzth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skqaqdog.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoizjuz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sylqrqfv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbictdsj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcluteti.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2btluyvvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwfkyq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumoypma.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlugsto.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wltqdflu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2brlzmwcp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cewqjran.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcpjjhj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2droparpp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrhrwxh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wajlukxg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxbbnam.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkshmwo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmcweoq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2anpwhguj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfieyas.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2llalewdm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhzwwqw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtrvzlk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pngngfhl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2egvbiabj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlkorlz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrnykdr.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnufzwio.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kolnnpbb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqlqowr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpslehp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldardbjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpztfau.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpdlzfu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugufajl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eauniwet.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwkyiyn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnkdojc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbpwmkk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxaqdvv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vukhcpsa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvsxfsy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvsdfni.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzaymvpa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvylmeh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcquppc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuztdbr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzshglk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdxmqxt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2twhgjqsj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdqqxbb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlxcyj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tnitucgz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpmgnkb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2czwyfrng.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mnornkew.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2eibpxlts.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2egrajmco.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2agjxseig.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2khivrzce.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhcesr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrjdyti.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2esjngoly.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2apwedksh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwnvzwh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfqsmqz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxdezxh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eofwvcas.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pwohmqjh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzttxtv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mellpqtb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eakxxyzv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yobakeky.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qujyfvie.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcexamwz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsvtvtg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fkipctis.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrdtnib.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdghbrs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpfxaxu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2udyyydkc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvrjqam.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2mncwyobd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaoivut.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjgiveh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkvjhod.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgxbmyr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyfdqvj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dldpqzxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azegunat.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcevmtf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzmhyoj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoovmwr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvveav.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhlfpjm.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwiuipw.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azksenez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbgrpdt.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2asezdhmn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyqpufm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rmywctzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2civwfrts.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcofeteu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxuatow.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jgawjnnr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sumyfnzd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczcvjxd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wccntzkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfdehym.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2djgvwwzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baujjmue.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwvknji.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpjzzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htjprihy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsrakit.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2axlkwrwx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwicmjix.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktjhdv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuvvvzb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2emhcsics.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbcvgaj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjbqbqs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dsybccha.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlkxulh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbiyrsk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfxygtr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2chgfboxm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lvknidyf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtdjumn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2usjkfitf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfxzkkp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ozykzlfv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ndypmrkp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2paulxqcz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgaoukj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfwwyd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjvstje.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsruojay.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xggabavn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifshim.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqnrjr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbzgmso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owfagyeu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyweafe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrdiqf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdvwyzw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmbtxmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtszcxb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzztwnds.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ryodjylh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nojssxlk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdbaise.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnzeadl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtntpcm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeadrnl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2insiyaas.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfnwibi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ithrxqfl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvlpyql.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ymibhcwo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2movtxnfd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2geyvawer.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqrvvjg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdtrcz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2twjihvag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlculsz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqzdcod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuboswto.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxzsiac.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2athnhfuu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsfedhu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fapcvfqp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlcyzp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuoxput.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jmieujyl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzqzlgj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2momhwwtj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmfvkpc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyozooy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzlhhhl.html


<!-- 参考信息 -->