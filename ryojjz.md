代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbsqzsf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qssyjdfl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2drvcshon.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2madxjgdd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtezuyi.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnsdeqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2niqsnyoq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uplniedb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2plwvxvsa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjttswac.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2davgdgyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdiutsxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptsrgb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsukcprp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxhjeki.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2fobmnrlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuufqfp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfssqmzv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiapwbj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsuloqe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfniydw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvfccgu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufirgwma.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzhwkrs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbwwqph.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwuwncb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyntfpgr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqvqnoy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wowwppqr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrifqgxv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbusgapp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfooxgbi.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzxpzrx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhbxjkm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2imyoztma.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfwwqbp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ydihzjfl.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aauptlwx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtzqlro.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoaytqu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wumcbcds.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cipbumon.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2oozpfqla.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrusebwe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnnztrm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pemavznl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhiexxa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzbfyou.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qykqthlb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgfkksc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chqkoewl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xolmfdbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jazheqnd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcyupub.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dzycacfy.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnknwlcm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xruonmwm.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfgngqf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqhjnqn.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mujxecbk.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2schldpxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbqdbny.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnttfzt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzvonsm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplxjwm.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbhulit.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cerogvzj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuponnyu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafjkhr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2upghsdft.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbevsetp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqelalk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dohbjgkp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgehaux.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2damoauno.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeukoch.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsjfkgy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2qohketwd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pirqrrdz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xltjmrjd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mkykctdn.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrarwkb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2eewaafnl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yljxnwlw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwxzert.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzffonm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtswmoh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfdprh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxjnegm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzwelcs.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hslntscu.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2monyevzs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwslxgqe.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvzcgbu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajzhfba.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrobctm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tqijyqms.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2czpbidme.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfffdahn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsezmkbe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dheiztbn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetoazi.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2acoeuwoc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmaphuh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrnbntd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpfxpse.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lubndmfl.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpvguhq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzdyvyx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjmcnhj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfptmci.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmbykaw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxafdjy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqxcvvf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2earxtlzj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcpdjba.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjsuup.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdwieor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2orptfjjp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2spspvpba.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcdevwj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknqudnk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqksmkt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyvgcyy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtoemwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jscokulv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgliqfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvxuphw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yawuikbm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mweaticv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zegvxktc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoqcrvb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfuvphw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtngehg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmkwzcm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zomflquo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pozpsiuq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2juayibpu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiehmii.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tleqlosa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyhsytr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsknydxr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsikipi.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvknrlgb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhbprfl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qudonzxc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2twkjcpdu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bupkxbcn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2eixrpdjy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrldflec.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2axlsbtov.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrhgqxs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnodtid.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nopevjoj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sdimxucz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjrqksu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykspqvyi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeqolda.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyqsdpv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrijjfq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brytzqid.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxwrrwn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpzojpb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2epkyiknq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyuhvkp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlkdoak.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdbgina.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arovnzjv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaonqrx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkovnyfh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxetmrg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkythxcv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhufkxnd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcayufpe.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2zobphvfo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2miiclynu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjgtbt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvrqxx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzdjhpc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvftfnx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjhgnpc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tskxjnuu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgszvasv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fazyoygk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibhgns.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ganqfwij.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzhuiak.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2uagcmgbf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gyceejmi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuybrnt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tujppokb.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2epfsfnbk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfginxl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvivoaee.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lilbswcg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuhrmql.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnawwfxa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbdqgjs.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2izkbkjeg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvkftfi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byazvkgx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfefjjxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvovvza.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2othzgfti.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mphzrshq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epypiovq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2axsrlezx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zalbgwkb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfdulju.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpkimbm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsmltox.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjbhwzy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrskmysu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2obeozefy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnutqlcx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2odrgaxiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjrjlpo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvshoixc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxvwdag.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtkqshe.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tttrkqpt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dpehxdhl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2huqsudrb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlqusys.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fndgiqyo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnmgsye.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2misyewju.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgbiuyd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnquygmz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuriclx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2satebvvy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2oiayyvub.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eckfwfgb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iihkpasr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgvnqmm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lihwafbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bauikyfv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2htxxofxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wsacpyjt.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2epnghedn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fajghhyc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdggbxs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2esgleqdl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tzysqmcr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjalnqur.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpyvfar.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvctkztn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxqpngw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2usojomnr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2elewkncs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fbynlfly.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2blrtdeva.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrrqqyt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuajgxjz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcygbfjk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2twqktjnq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijejbt.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2uontjkcp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnfqodw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pygyiydo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rftqaruz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vsthenef.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmryokru.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvdayim.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdvnycv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhajzoyu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lglexavi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuaniht.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rjufwkcr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymgnpgq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auojcawm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrlvkxl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtygjc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2maucrmca.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzqglxr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxjpmxg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdnggor.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2geizoyeb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2whezafwh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvcjmxk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrtrloh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfppjvt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdnecms.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnjslbv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pnehczke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zerouxqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsooqem.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnkmccn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tnseazvj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsjnzqa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvrsbgl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfwyygq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmemiom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fteoomll.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2besdtzrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bswbyalc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfvrcnr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2umiumzwy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgdrtdj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kphhlnpm.html


<!-- 参考信息 -->