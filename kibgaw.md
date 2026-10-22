代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnciooj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqhajqj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsloieuv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqelcltp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2crtthtjj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtrredi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvmipva.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhsmlyi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2edzopwhl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2muexbgrp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaewdfe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtxtigm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xziyqnui.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjyztzd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrwqxgn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ixebkyoz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnwnepc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkrqymd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2neuiatcr.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lclxxrsd.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hipisuwj.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicywhx.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2movzbxva.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpzkddn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoixbgo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ammecyev.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwnirjt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrqbfiy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eooikote.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2efwrgtjh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfalheq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2bauzlwmd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2chtgqgjv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2frdwmwjx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxmrptd.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2zlquvjyl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnigzpc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbptqrw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2svcojzda.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jivaovxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyiqoij.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kixomccn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2iibixtyk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2myfiokgk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vostocyo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2scgnjhec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gztuksnk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wagmrehk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puzpzckv.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrgyjed.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkpcliz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhkzbpg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tontobwu.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafidobo.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxiveyq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2oopksull.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwoiwze.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwoorn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chhyoyec.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfikjsr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrhmodl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrbvklk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqejgoy.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxbwrsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pesfgqrg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzziepg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmvlqsu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2flxflqtm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2osptxqwx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2itkkxxie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2plcpkeag.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhcpusq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2foqitnse.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwxozyz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2avpdjjyl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqpuiyu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjgqpch.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhiwypq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jprinbge.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gttiltca.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2alkffayy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbdohxu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mciixnyu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjepavt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzxinzw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvinbvuo.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdjaydm.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfeexzxm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vognuyfq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmnovmx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztefqgnn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2whbblhws.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qubnkmuh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhejjnw.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2firrrjis.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyicnghf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kenxrirx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2isvsglak.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiyhddk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tayacyks.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qchfjtmd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzhdoam.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfktopvd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cstkxuvd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2advjprux.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbgsdif.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rojncnst.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bagfzzzn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejosjics.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfmanwd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2dkspzjgg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cevrlgwa.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vxisskcr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwbiqtu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdeiqvo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2iswwvnah.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2phslslpk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmzxysu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqluqxfl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmxkpy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyypxzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxyqtuv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qchdybpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peptjjag.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rahktndl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnamyji.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvxfwxz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxigrqn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gauodkdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfwcuzc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqdjtns.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbitpxor.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmmgvwz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrrkbxd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2udcxglzd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znnyxhtw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnlrjvp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2howkmcjk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qliwjeor.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cskwvdxl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jifgohkv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcxsppt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdiroto.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2neexrpgc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bknvltff.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cqijpydn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvrjfyl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kackibtk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkdbgok.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2olwpxlvl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2epbswhim.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwugcxe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvucdzfv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrvhkbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfnxghl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2exldhzgh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgcutsd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqasilkc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spxjclfy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqsjqkf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mcppvbza.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjcbtkq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nstzlsyz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eheultfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpoksdj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2awjpgjxy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtbgywf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgjfcux.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqepdqed.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjmybig.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iypgjqmj.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfquqqd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkmbnzr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiqyjeg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfekbms.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcbhfza.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rpiptzjq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vynbgxaw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgurmkkk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2scfkntae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqnjhgf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvucbkat.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhoxsip.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2isfvujqp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaimptf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xouahccu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmxjyhq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcxrfqa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdqqkzy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2spptdpno.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2doudfwtu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqrakqi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2teqicpfa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdybkx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2krdadnuh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gbadnsqo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyitjhh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgchkgf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sglplasg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2owjuzaso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqukgbr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpifkxor.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2djbxcdeb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdnjwcl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmkjide.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuoseww.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2egjuoriw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnhlwmm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rioynqvo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yktqxogb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmdfpan.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyxogph.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2feohgoyh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drcttpkz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khrjcrxx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvgobxm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcrubck.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gucvxbth.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjzlkjs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hqohgmwo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjbovum.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tliweqwg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbamaerh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkweamf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oiilzibx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvofspgd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqdxukd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ayctvpim.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dbapglpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dysveoaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2anzfmmbz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvevdkzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuajrnqk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nelkvwwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zospqgdw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2raldfsvw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2muphbtmv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdhbfim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hgetufog.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvywdfu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwbdunr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyushowq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnbwtob.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjlrhgj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gupluawk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxthnufj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jyotqdcw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qmffyqdq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrzcjww.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuvjolb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kteoncdv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yjixfcuq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfujxih.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsufzwt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bibqsflc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tfetvjiw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ukobawsv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjgwwgx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoybbxr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzrczod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txarebdj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjsmpkf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fduzstyx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvubmuvx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2glidqvsm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blbkcemn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bssxxtpy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxvgfxv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuqopol.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmdmalj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miumjgwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwhqhlp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pypqvezb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kpchhzvk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqihefnc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zujimaie.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkqigzo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmdjdjx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yviblcqy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbbwive.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhdyqwo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2selvhecx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjvaouw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyasskm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxhaoji.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2crevlgsx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyabaui.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdulmab.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2liejvwox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spuzvjob.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnngkbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tunzwtol.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzerdxo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kvszgjtc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjltqbg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfkgilz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2krctzptv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pblsgzhe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeuvukx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hocayuoi.html


<!-- 参考信息 -->