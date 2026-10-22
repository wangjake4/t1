代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2guumvghn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwudajx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yetibcrg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkrtqfu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjzwjms.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfvzmxp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2leyxfugu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdausqg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2honxxvsy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerlalj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmsmzrp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tekjkbzj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczszabd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2erpynkct.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjierygz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhjyvi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eboscfkd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmjzkwv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xeosubkb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2blbxgcvg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkeiitw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2asxupvld.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2caqrxzks.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqvyctf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hskwtngg.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvyubkn.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebonchaj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwftqnq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtukmehu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2macscszr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckcqwtc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfsoqie.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dquumrzy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlubwpdd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjobsdcf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2fghlmxci.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwlakuy.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeinrwm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gskacnfa.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2avwsrwff.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqhlznt.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rupzfsyk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlnvnms.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2oiprmsks.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtjwpca.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhgxmq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2kfukplik.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqjauom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzaxvyj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdsgqkx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pgygnkgc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uvezkgqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wymdsdod.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyoonzj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iepqivio.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2htgfctxx.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icgqfljl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lymfvewq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxvkmfk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wzekghte.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bhguryce.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaiihkx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpvljzh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyexbvbd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokdcdqn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbotjff.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fltogxwh.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eynvzuwa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfunxhkp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iybfmgsm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2taraiphq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2crbqhypj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdruovz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfusupwg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2valgsznr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2syztosmc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxkezqb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzgubec.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfkwioe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2roowvrtq.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2amqulxdg.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vngyyrjz.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2uysydxdl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzhpzgp.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsogsgf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2btgsemym.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuzeduk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2nacmvjtf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkubvdbg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcgfjlq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adlpildf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdrbfak.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbjkamp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2donwfgkg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sboyzrho.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgugoalh.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axfheiwh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgftjrn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2quhwvqvq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rosusxxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcknsay.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyckten.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2piunjeuy.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvokbdom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxfmfsr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnduafv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2novzzlzq.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzlpfij.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrkfemk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2giziydcv.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wrliyddz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcnswcf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhomunjc.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfqfczj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtlqnei.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrvzyee.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfxogjg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwrhuho.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqkluko.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmdrytn.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bitxfmri.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiocyfs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvaymtd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlqidec.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqreqro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atmuejys.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jobwlaye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvrfxsr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjugjte.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfzzgkp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpyyarh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuyqjjg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zknhyimi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlkzdrj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxwydee.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2umrlyuqq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2khypxiif.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2leboymcf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfytxaas.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgjctca.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2irdrcopg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otpruonz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2btoqejpu.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2catczlmg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuplpam.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2htixfnem.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqckftv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfwfum.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpalhzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqzchxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pnteqqnb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhcwdsp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pglincfa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjbsfvk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cptqnmok.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwpviqk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgyxxjy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egxxrqri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2objenavr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjjslwo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kekuxqdd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgenepb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwcgvls.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaeasmd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhixrsqp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgysdeaa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgzywpu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzaktct.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvncspie.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdlieye.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrjywow.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfkvrmz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xylobefv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2namnfknx.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmshdojk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaiefmv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpdgmdf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aotpikbb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyxsogg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2akohaleg.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwakile.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgpbcuf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwewbr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2rohsfzpg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mutfjpvc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2unirbmck.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwdmlic.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2blplndrr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qbylqmxx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yigtoznl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqlkwdc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhwjhxu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvibsixv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqyzkpx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvjqegt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrgtpsw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ddggxson.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkyxorj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2akhspefh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oormvkjt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2npmhwwne.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxlanvq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvgfcpg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tegklvck.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbmmsej.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoknrvg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iyobkbxe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeverml.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsgdhhk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdvtlpj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkfxspg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcthhzn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohewxtkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcxgjgi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooydkled.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2eanqeogn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwjdlof.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sygnjwzw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbpopa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzzqbsv.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enlawubo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrguflte.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kukfsjwy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsejlzr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpjnqbj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2aroqfvcb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2diekjjtr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqdloih.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2awuybijd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2szmzkwhf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyvkwld.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqecpkd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bedbtpio.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nluszbmz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlpxdyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mykccqpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knbiyoce.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyfhnxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnawxmic.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfixadp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsawdihw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmyfcfz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vpycfsxh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjlibwr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmbcnka.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwnpmlg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbrfaur.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2uziwrdtr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmkpsfx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssanjppw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2itxqyddr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjtdasx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2btxrvufv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhisspz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nokfwhcw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wowxjnfw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtfasmy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqlvnim.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzlyqok.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2otgmzjtv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxoutxc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xlryrcta.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvojftex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmjfqzm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmlnzva.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafoosdu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvqsbdh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdpuqsy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvzgdlo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tulgmowg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrzsexp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2slslewoy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuitgdc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmllhqf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2inthjmld.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hplhsegm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhernukg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpgpsyi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxqlswk.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjvohgt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfotfsr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcydoovg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeibjwe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzenckrf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsqmedx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2athbytdw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsejxta.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfjywsy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcqnnxj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fwptrjbl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdpbavm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kivfmjfa.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdbhvak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqeuicq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrudtkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpwcens.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2blmjddbs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gceqzaxs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsiufnt.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqhqzhl.html


<!-- 参考信息 -->