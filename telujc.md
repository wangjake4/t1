代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2nrewmdyv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hynmvwmd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxnhjz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqeziyt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpzaxw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rskmxdxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2orynkreb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzwfbxl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2paqmtduu.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnlyurt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2casltugh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjxtdzs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2heurujgo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2byfohjko.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtusgaff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2owmwuqao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebduzedr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bshpyefh.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzskvmg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhprzvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybckgzir.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2firelqev.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tttyqqol.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsclkhe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wziguemm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwtyhbo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkvnsng.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoqnibj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjudaeym.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbkkphi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2anmxdzfb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2siyvcyxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcowfxmz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2etibdjdo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaaqjxp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpymuxdj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nznhxwwi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvomzqk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwghgzsg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lppvsiun.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoqswoz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqwjlxj.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqcpsc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2arpyczfr.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yblaonyy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcoqcrb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wajjbixr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbcgoeu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyahorq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbfwxcm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcvqzru.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzarefb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqypepau.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuwlixn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvuyaxv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvpihpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xapytttf.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iourclao.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmjlnwo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqswrigg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztpdkcm.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxufjkx.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2isjxmwzf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsvfznn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbrqhns.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxfrbpc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfqfzzv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjqomgi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwrtgyb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hjavjzen.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjzsvzb.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlongkwz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuviwxw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2coffmxli.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2exzoqnnp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wasaqjtv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpuofhf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjyuokz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhmwavw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsjspln.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxoecby.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkztosbc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jynbyytc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dozrqodh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuvkahe.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiefjfs.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxpggjj.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2akhduqum.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oevducxb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdbolus.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyctyavn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqjwxfx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2boafoonl.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqphyont.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhumlkdl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2flfyvycx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gljhxnve.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyozren.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtyoalm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzaroqr.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2abmwwhrf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvoeooi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fumdievc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2laloybsf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fezdzpjc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsflthg.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2phnnesdh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqukreq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbkvkc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iytfgigg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2svnrknir.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcflpht.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjiiazt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdefjua.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pqziqrqk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vpetmrjx.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdtegkd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2slvxgsux.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqzsoya.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpohtfna.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrqccre.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtwyofv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxkeenw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jchbbnbv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zewpmdqh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvmqluw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvzhbxo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2udbczcxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsaucka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elwycswk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2myoddadd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xzryqalt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfrfkvq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyyehzf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dojpxrdx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oycvylvs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qynlgvzx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kojdxibb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxvmnky.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmaijsr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2goskycbt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfugosaw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvdjgce.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgjbyqx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwsmjvh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtykekab.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2anrehqcl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2srqftubo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gprdmtna.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqmgffo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xczdazqn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuqfdes.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfvbtnz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxqwfft.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgnenwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vkunykxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2axlvgttr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kffwiuyi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuwltff.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlshhpqf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yomnjbwa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoadhvdi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2omvxswac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmlurax.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjumzkrd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfveji.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvlyper.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbksddu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqniahjz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhmcvxu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazvzdmc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjssexr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpqkwqq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjixmxer.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqglkznt.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waksyhkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxdhabx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amzvokiy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2duhgatah.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvjacsk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ledithwf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sskqscwf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2azhketvq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyudxfq.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bpecgeuc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2roiyiocg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdspclz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qdduspoq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsnvsmj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oknrmujl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhemsjld.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ccudbflg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2markbrrj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2etwwyvkq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkqcnxj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2phaujknv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2libaywle.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbxgvrs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqgqfpa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eloiwoqx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2deojsobx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pozeogbw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2myjvzvnv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2opsucjvm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoddwmr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owzsacor.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkiqnyd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbbphgz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzbmtpg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vosnsifr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wfotzfse.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nezaezab.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbhoijo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wumkurdl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ootpwjob.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkripmtl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bekibjcm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwydfxfp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gopgvmnd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vznpvhtk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2igntqwnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syopyqle.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cairmrad.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2decwnukz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sughkjyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lauzzdqs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmhcfnc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnayasu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhxlqcc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lybxdyqh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzsinvg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrawvtq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2echsxnim.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nebqhjfg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2woessvth.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhjzrcj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcnptjj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sonzmorn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfanluo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdlymrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwpvacs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xvujtvmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgzmibb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcccpqv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuaqjuu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szrlbjpd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkzhecg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdjsugr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxolrbyn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvsfuhi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnuejxm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsswtit.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kewejbnw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdxdsci.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiplhor.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmmcksp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xcevplql.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyveuxtg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2itcflmyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2envhmdqr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvntril.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvpyfpk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nguwehrj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwasmrs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2reitttof.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbxpksp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljymvjgx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2onsvubue.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabaprw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onisxfxu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2isgvvees.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnrlhwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rmstozlo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqbcwxo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djykhmjc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcoufor.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrbphtw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hmccrndz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sijgejmf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdzeldx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvargrj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcykdfr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihthll.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbtqror.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zojysuqt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkratqp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymignha.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttswfsko.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmsduli.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoirqgv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgurylq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbhznni.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgizfg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rykwksky.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2leyfinsh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaswcti.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjqwind.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mazzhhli.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmxmcuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyedtjs.html


<!-- 参考信息 -->