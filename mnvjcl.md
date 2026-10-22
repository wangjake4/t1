代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hycuhele.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqqyvdn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwsyoiw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwakoie.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzxreza.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2opewgcio.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtlzuqj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nizqhvqp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqkpfvs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hawotttn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuiqkpp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecijuzcf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2oplglxxx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2shlnhxdk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2liefdfcg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgzkgwi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sveolute.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vseljgqn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzneinam.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmmznwa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cepupzms.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcrmefy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjpovca.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhogluqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2apbcxzkf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2panurcnl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tldiarla.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoyrdak.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omknifij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xgimcoto.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvjsxnp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzpptin.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqhpnuh.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwarztpp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gicshlnp.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwutggi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfztkrvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmzqng.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wozzkckj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurnjmc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtebmjy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrjqmzz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwhsnrh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uomngfpk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2basgmurh.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2igxkltpz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wobxpmjr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2plhlnjxf.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsobvzc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wqczttby.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2acjlyprb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mufrwvxw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcsptdv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhirogm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2spskmxnd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsilmbe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxzdodk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oszdswwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiihxni.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kczgeouu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2panseizi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzzhbgj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqrvgyu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2uukecrfi.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwbxgbl.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycocqyof.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2recjnmlt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkiwlgh.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsfyejz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpkbbdw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krdgpucd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftclazsx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnvueqd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgmpaij.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxvwhhs.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrowxld.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcxoczu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sctrfayi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnphkad.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2aniziryx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcuefdy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhatuez.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vngbeilh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzwxbzj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsseagku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaroate.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2medwfhej.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnbarip.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tntmqyvu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zapaaxae.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcswfap.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoaniki.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiaikqj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyetcic.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbsozyo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwykmze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tblclevd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpjodqa.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzphlydr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlwsvvh.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoiwlhm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmikdqna.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxolqox.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaurvzqj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdwnfya.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsftsej.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2icpymfup.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnffdhx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxoyjj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mboonihg.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qffjjaxx.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2acpzorjh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2katpxogw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsevjhw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2swepjczr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkxbmej.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqzggid.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2naxptfcc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2aanbbtwx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjtplpy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gomkfkqp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdwazzs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjguey.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmasmev.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oymcafqh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fthpdkcz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrrdxzp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rkobreif.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sgopicaq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzxricu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeinkae.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qktxknkz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2czrmxdbr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvryrwt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2byjejwgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcuxalh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjckvt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmnyyg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kttcnmrf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eossmpxl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtqdhny.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvwofho.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2abforjfz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgoeddu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmkenh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sggzlmzf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uifujbep.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xghouygt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzjuocu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlubhnxj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckcjvn.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eteqaqgs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoitzft.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfehptof.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhccbrcu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dudmgfre.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsxevpf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvjixjk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnjksxh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cexucusk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vzednfie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2abtjuvpk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaoxxcg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2istrftma.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqmpidg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kybytvpm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hskvpwnr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bffhzchn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbuyyvo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgwosae.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmmksxt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2klwfmxin.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwnorck.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwzepuo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icqfgiyu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgynlquo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimimqqy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkloitj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djhuczts.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nceucpbv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znektqyf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwlpozc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hifqelbe.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xanizlkg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjgteaz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpjyixd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2exkmussj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nitqlhta.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2owbbrcnh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oyubzsir.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2adfjspaz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jiooeijv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxdlobe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gepmyurb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwqueds.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrziimi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrtlfho.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2glmpdlxl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjlxaqj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2niulyggw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhmyhva.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2eazndoyy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czneehbf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oegkcine.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cuozplgj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtrgftf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjylfjb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxibuem.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2paiaqqfr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlkjugb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevsucv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwjrwko.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2klshwbcz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2brileojw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmpknkl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbxkjhv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2chsgbfas.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhcbalw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeunfeb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaibjqxg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmvguba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnceqgj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vupwtham.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zamfsdaz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2snqbafkb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwcgafa.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzexbbg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dpohouxi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqhqndo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfveqepq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmpmrhx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoclqyq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhfwefy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2havyjhfd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjtjogz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cftlbnrv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrzwqjm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2anmhedlp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkssnsvj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgyudxq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzyyyuf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhntomh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrhqcis.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwfxruw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfydyiem.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vssuehom.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvltxun.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjsnxbx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cggfhsni.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfxpqzv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jxopvudv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hykqhwtf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sszkxcsm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywasdcgp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qniruzmp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvbcipp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nzeeospn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqeyejw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vlogzqao.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2csovxelg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyiuysy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqzjbtg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2clnjjhod.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcnwetw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kozirrgx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqgwdjx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xiytgtwr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dgicgflk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgdkbfj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2szpntkvk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzjqdhe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzukgeei.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bseikgmg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaygkbx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqtrupu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryweakms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmnpiky.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwufdnf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbyqiqy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovymmgdc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvyjsyw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2prngtkak.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumnypgb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yzutimzh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmafpsjl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnophty.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2loylenwd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbcmijx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtijuwag.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxbxkpk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyoqsbs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzghefv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2thpnyygj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fykfnrwg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclhvyk.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuojbxu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2izjmssvb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvjeveh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2behtndog.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxivpli.html


<!-- 参考信息 -->