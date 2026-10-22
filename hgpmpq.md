代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2aazbylpr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsiueqv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrenzam.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjptyrg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2solsrnqw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnbpqpy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzirpxjp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfadono.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoyjevq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2iotwherq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtmcmvj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkrurad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeuxmzk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pddmdhrh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2yskcnopd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfankysa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sirkhlwg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuzyjmq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2taozprid.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2agsujpnu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfepoila.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hhamyloz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfybyvi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlujqro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoincucn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iytxgsdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxezuvfe.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gfommfgq.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2exdufeoa.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2atvnkvuw.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2plqdugcd.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzyoete.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eolxrtkh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvjiwwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgppqmxt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2spmtlalc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aznqifiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrqhujl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqresxsl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxstrzy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmelokb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2chzswuze.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2oqezonrs.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqsxwhw.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxavjdk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2eozwhvgl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2jznzhimq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvoywmn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yucnfrfa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wictqxsh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmwgxiv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2atmnvzke.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafgszuc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kztvudvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnedpzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrdtqjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guikurvw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmunmhza.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmjyjye.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kikjghcu.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paptslxw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lflrqoqi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyzsjis.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sjglthse.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vfksvuwg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fridbuan.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gchazcax.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwlbcxx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjivoaoj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqvpxhg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jphuwrpq.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2slnrrwwb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqweuyx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2twligigq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzerkad.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrsdvhe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahqpupl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfwpsnx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrxuzmf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2odiuchza.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tedgfzbj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tivwfiao.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2tviqhoks.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2effaeqfa.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hwujddxr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyrsnvy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gzigoauz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcncuun.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxzcfcm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouavclyg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjodtvw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdmeomy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2toaxbolg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjvtdkx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrhyhqt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2umebkddy.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaokrbbe.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umgmpieh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nergwsap.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbghyab.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdksfgtb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xzekpegz.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2czpuxirt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tliysptv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzjocjm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsowyelf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsnhubz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtfnesq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sevzvyjd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfndegw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvrezvi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vsresxyp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yumcozpx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxmhhly.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzvihxt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2aifllqit.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjosfovh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuwpvug.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2eguxugbj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2blhubwsv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hdksfsol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yasvgpvq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkybmcr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jeitmlvu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2spgijyay.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bssjkpto.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ourznqsx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjddjwy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjfxuvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiizdxq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zuikclwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nscltwrn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tieesmcj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrabpia.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyqpswy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iciwdqru.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2raxbgwwb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtorknip.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xikqlqql.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqpfuvn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrmwalb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bktojyym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2naqpgdmc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktogiqhz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthwrhcm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoegeui.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvksvmsf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmulidxu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeytfer.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zieghqiu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqzvyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvadrkg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvgvxzo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqkzcmh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2thgkmnlq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeltcht.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2icgfbmip.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2grsqwsuv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjerngx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfqgbnd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppwjxtr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvbkjxy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiljdfc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeqrvob.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhxydcp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2leydolia.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjcxlk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzebmqd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooynwvkc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikkvyg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfvdafd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpmdbqf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbziiffz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctigynuw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnrydlw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuctwfgc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mygqxwlj.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcukflb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgzivv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpledce.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpcjikq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxrrhq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qsinytfb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2irezdnyw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhhpoid.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgxiizo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2awxaicma.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2oaisohqu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lpllmsih.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgwkpsw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdeejkm.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hpffadtg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeqtmmo.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2agskfzil.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oclbgbvj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzvuaav.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfxgmvl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqmrgol.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sejqdpvh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixczebga.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxywrav.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcwfvcm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuxduld.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkbnur.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2earfdunz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iehdheuq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kukcethp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkvsmkr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2scskicgz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydksvmqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2owzstzxc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jiotskfg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kamaajsn.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2llxcyjli.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzwhvzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxilrx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mweqlpdd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2resnqyyd.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuluuluv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjhqcqu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlogioox.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqrqodj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyoaslp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphrumx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzcvtff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pufhctxq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgzkihj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2calexbqt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnalghmj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ivscfvxq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iwteigwg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uicocfpp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibirwh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdnnrli.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xznngtuc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsylndw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfefjlm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2omvabtls.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpysifk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kqieujle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psrkvcni.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qkigpklu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdywdyx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2drfcgshb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsskrqf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2peszvjab.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfvbdhk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kusvvdeg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyuvbdn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmxzuua.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fidamxil.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdkbthn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rsltkoym.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrqmztg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxnuxo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gndvzzjb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2puefjmpw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mijfsvys.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsbijee.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxnqvot.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xyashvns.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzhyxpy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyeqqbj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxgsmfw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yezoshte.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrcyitx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjalysj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2veyogkql.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inslosrw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtleedp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cddwshti.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2durmblge.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuecdcz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaopjssn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcqtntv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqiuotz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvqetet.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbpltlv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otmywjyy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2edptrjdr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmobqg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tlexlmmv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljminec.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2elgiqyom.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2toysdmnb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfutuhj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsxmeld.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uonoiwiw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nuakapwg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lptqgvxe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyaerfc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yvztnbff.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2chbxfvzq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tebjhodg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2knegjako.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2efmfvvov.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwfujyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbrmqk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdertlg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etlaxsqr.html


<!-- 参考信息 -->