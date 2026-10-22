代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpofklpn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqiottg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaoujrd.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tunqxkry.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuznrwg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2votzvxku.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rybodmmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtaavck.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbesqay.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2njaxmhyx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmcbkkt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdeftgu.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gsympnvu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxopmxn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyygtgp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gwofedlj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxrzkqw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbexhqgl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2krkmauqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfnkgpv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnijdvq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2nhomsqdy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ralhxnjo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2noixgcjy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fystijrd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhypeet.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdzlllf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2laatdqii.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2uidpyylf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmrgbhf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2twgmpusp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2kyddlcir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aolwbjcr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qiffrxry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnouoph.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlmhll.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onakylic.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2waeigldt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlcdbfk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kiswuugi.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kobjqdyx.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtyjtcf.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtcgfrd.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2izvrkkaz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmeqvkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuxubhh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2wopfhzbl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbuxetu.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhslplv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2djmocaig.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwslffrn.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnrisgq.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yadkvoqa.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbehwcki.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlobsji.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vktrtpar.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2kcarghib.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2eliofske.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2saggrpdi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhoasfm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uujgpsob.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdgkxue.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnerfrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxgygxk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlsfbjx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qefyozut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eliuumzb.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrqmuly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kruyyydy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmrjvpw.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tgglmriv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2yupmhcah.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourxefgs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjddqne.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpvwgds.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2epifljti.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wermfsgv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfalgyn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2monhfebm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbbyvwx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaqqojw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zddfxrav.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2axwkbest.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjsofrw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufufrfji.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2gntubdgd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxymlbd.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wsloafpx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snymneqf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cczteuqn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2henqcpis.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oahglgyu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfjofeb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhsbrgv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmmoygn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvmfiyh.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mcktttyy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzvkqsw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcjaotn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoqgxxq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvexpmg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijylzpee.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2isviwvel.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmryuhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnpyzag.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvnsor.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aflupuqp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fubfuyhc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqvzejl.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjgtlfg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqannmu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vltkluig.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wueobptf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dbklsjan.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgpvzbz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhbsjp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcgpowf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcedbfn.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyqntdw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjleerdy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bflokxia.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iithmxkg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwxatlf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwtpvcd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfdxpkq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lujolvpy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jfllreaq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrnnwft.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwleyej.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsdwntu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhnvktq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyokklmz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjoqszm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqeivbt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrdjsxp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjaezeg.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sjthluto.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlbtozw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtenvl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2szrqbfee.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2msjchejt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwolpmn.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxpulgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbscyqz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2otlcpuxy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gptagbyx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zptyimtg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjayupfj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxlzzhm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbomwzmg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vegvdndq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgglldfr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeplvhks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlcbrav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhibzrj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtsdtzf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewgizax.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzdhsme.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdagaiwe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wimwyybo.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjpbfxb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgjbtuk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2obnjrzyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zorhwgsi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jkifnmxd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2htoabfzr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpqxpet.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vipcnyzl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmhhhjt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjfzvpx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxjlfs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2wybansqq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcbpghy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kukwgtri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaansvy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvrvxut.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielewvml.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwrvtdy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlzxjc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzfguxt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkwmtjn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkexamhe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uztfccbd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxtqhcr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tawxfohu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2plepzqny.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxovkuy.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbugfcx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awrnbyuf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfdzwuw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhuhmiw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rucnjaga.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoidtpg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2excgqrpk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqaxlgq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbotcset.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2atueatee.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdywtmo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxnychi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkolbqq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gpasvwoy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwazeiie.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgexack.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2domvxzgy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkvbfaw.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2faneezkj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpwwwmt.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bthmmvzd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2revbvmqx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2oydrabyv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jraecbxg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwrbtpp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hugbwrrf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrihwkk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dijvcvcd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swlmnjtt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuntxlc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeenoqgr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlhsaqf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2agktxagw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2galjaxjc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stvtumad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dkotklgt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gphvqqqy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkdftrw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2apczpdri.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2piohykhi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqwdgvx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvrgiyj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnftazbr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxuqwel.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxisndlr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ousmscdt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oidpuxuq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jekzmplb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2nldpcdqv.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awhwbxce.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kphpbvfr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzkymot.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbccatyq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omtmfovz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2uoolkwjk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzglnom.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoaueju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2otmuayuo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2saittkay.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmnxbka.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuuzthz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2icapubip.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2asdjupza.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gebcrqvf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxdpyds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkxhtof.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiorgnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evnndcgq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlqajvb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2spgwivrp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgbjzpn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdcgiua.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sholecsf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2phguliqy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dierrnog.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazckkrk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lebjzbzd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcblelz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdaktty.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2edzxppez.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpivnps.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkibrqn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsstgmo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2feziqlvg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2twjsjjtd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdqsssf.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxfggcf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxelhkq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsxtqaq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2imogxwno.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nypuclfh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiybzik.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvfkopp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfgqjvi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibnfxxe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkfkogx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxbtsoo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2blyhpvno.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aequbilk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzmjkrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpgomao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ocusxjda.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2umqjjsis.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qujbavqz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2anyhekak.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2crpnziyg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwwihqw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpwawsm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcojjpe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqxfzzc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2sslhiosp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2niffsfmz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstwxobc.html


<!-- 参考信息 -->