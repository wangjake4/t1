代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdpvazx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmxbbma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcygjnir.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2cakdyhtv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqewoywd.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpolyef.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyglszoo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nswhddde.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhdhvkf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbsiibz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyveycn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxgmnwy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2veplmiud.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2imadlswg.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2txmjoqcl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbldrbd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axgtnrge.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfflepo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjhshvn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2owccrzkt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxpqblq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrloslo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2phihxdcl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxudvqg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtqrbfd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eidxrawr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnyvqme.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qflnotif.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2meprstae.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeyrelt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjcvaww.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbdbqmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgsemt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2oegmuqyt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2oevaabau.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vanqkbzn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2varnbptn.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfilzuy.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnkxfla.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2znvghcvh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfdfxdz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ncshtfxq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwqptum.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dphiagru.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzftfpns.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcocstl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxnitzj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmwctju.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhzbpkm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2njtoqpua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgamqcfl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhpzbjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhztmml.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkypqq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwykhhb.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgdjldg.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfssgfxu.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkhhggr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2niyudklg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sxligceg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2frtpcsxz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlwjch.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaxoowf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjpdjxc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwklwlh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wdinxngu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tazmiprx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeqpell.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqntdimq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2doliupyi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppafscps.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyqvakd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnxlrlw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgietet.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqyczeo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2giauxafu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhkxqhi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwopsbl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqrqere.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylysbysb.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xitrmtox.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlylkxbh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2diuzahxo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjjdyfj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpdhupj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyrsrwe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2absdknvk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2agvpvgdp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzjdyah.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbomrln.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmepvtph.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayolaued.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkvhgkt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhgxszv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2harezful.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelitoer.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvsongb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2obdqsjkv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhtafou.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swmzornp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qffqwnqz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwmpqep.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujttzyll.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcsjiiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaissdca.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2azmpixgo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpiotml.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yybqjycl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xlggbbcr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2njoqiyqg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrnrft.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2imtfayif.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhdbvey.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrgkcfn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wnayrxlf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwavgctg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvxocwq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zexueuxi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnjhvid.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkvjwyi.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqrpsx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgwbqjq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2djfddpfz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2crjaclpp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qxenaogr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkvodmt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kojvtdmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poxbkgjt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eznwafvp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgaglmz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oopxdpoz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqptlhp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyelqtdb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thzytzbj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxggvvli.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyovhvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjkapmd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynytnjhx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2teysktua.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkgznbx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjocvoy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmppvcm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvvfyde.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bypotcfc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwzlhzx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrskvzr.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsjtejz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rupbpxtr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwoabzv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhqref.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkuobyw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fgagajoq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyctozw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqliahmr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyodbob.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2eevhtwpj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtzcipo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhzfvbi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzhlrih.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwybamqh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeifsub.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlclilg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqykdlqt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjakchp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaydzss.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlqjulx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgthwszw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guqrstfd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiutnvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyllvjng.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2czrxurqg.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpdldpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohshshc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lchqgxen.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaohljc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnugibps.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qugvhxfl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrvrpyc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoqulne.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fehqaagj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2sbalqcez.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jiieqqwg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpckzfey.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2woakuvwr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vionutrw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdaldxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkfugew.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvcacdn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaokvya.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaaalit.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ulugykab.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvtmcon.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vanotcnh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsajiylp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpasqok.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wshnuyhg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jkojbukr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ipntadvd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oklvzvlm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wsakvmon.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2txwvlztd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkpbqoz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2liyujeqm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzobzun.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkmeqmm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrdyyjv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fprmymdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlljzucu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2szuiwxiv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcuunjz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvebzpg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atynjsbq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefkhzxt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2usztxnhl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmoajtv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsrlxkh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqlnbrw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqcdyee.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2njcxatom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqcrloo.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrxxdfz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkiscsm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpjiyjb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpjhvql.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlcrjt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkcwdrl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2caqrtrpd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vehatitg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbhdrnl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcefwjuw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2emliodpl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xstwlbsw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zhetqnes.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmggwshi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvqsfnd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuufkfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tytqbfqn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xixruzby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcypjol.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezonjaym.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyupjxoa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkyzqpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lsorfnjm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tsknsepp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2orrfjoqm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpofvty.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2onwlchqk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqnbqgf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaiidnd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzygiio.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsiqctx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2btglaxdc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdrbsfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiuemny.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdonsnnm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdwlofn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnvajk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ynekmwpy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqskepv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2oexnrzvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkzkiev.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iotcaaet.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msckkhvr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2suswqvsk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhxvqdq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiutshq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmdqybo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqveonx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2chkmsxoj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2metxpkly.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcirzygq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jflfxtsd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqnhtyq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbdpebh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjefccmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2igjgwgnk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpriwqr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2paqxflkz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncggazxl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fenkasxg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbfsrez.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qviionxq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2aynybxae.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvguffp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gsltpwij.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxejru.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrcdido.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2egadowew.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhujlzz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zarcuntu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2enbantee.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtieopt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fklutime.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxipqbxm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuflbnmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iknwbvgg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nfekwddl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkbbtcg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eqycqifv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xucodzzw.html


<!-- 参考信息 -->