代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ftklvfkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2temwgkvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqzgrhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zijzqqby.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynciwbaq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2cseismbv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlkuxtj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lepngmqp.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdrmusg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqqfodr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jonpvieg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2opcjodsh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgjgohp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2agdaooju.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjusoerh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2sohkwjgh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqwyztq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpqubhf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhlbboo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbvzote.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfeuvyz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdowrta.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbipvmuz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2umjtwxjl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmgkkqi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxwmata.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqrcdzk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvmhqfl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzluog.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkmemdt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxylbczt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pktnbnqn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvgxbns.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iomohnig.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whpskagf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqjrlxm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2siebrbrz.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqgwdre.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcwsnvj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qomwzdaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvzhyyf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpicuve.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebohecab.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxerpve.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkuvoem.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzpjhaw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhlimin.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vqolmdhg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqhyodg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2urqzxvky.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxaytrz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxkfwuk.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2typzdtbg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2flywxjmi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fziubvge.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgmynrl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpvzqz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpmvxza.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2zjevsxnd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tzajyfsy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvccbxr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrgjpfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrnelth.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2erhqypew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcmeam.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qedkzklg.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pppratgh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2feqagall.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgifcfm.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmumdqlb.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlzybto.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpdbgku.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2uthipaic.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2smtvthfl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azdsfeog.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhvivvd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvcmgie.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2oninfbtu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbacibp.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkkuxjv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nomzevwk.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzwygfa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgnzmam.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuappcu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2keqrjkts.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqcwes.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xulhiois.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gboithvj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2biscbkxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdqpdpf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwhjlj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwsvid.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdsqyun.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrpyjef.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2puoabyqk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrtrsra.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvczgjio.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2aioqbimg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdlhvfc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uuolcmhb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mktedyre.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdpyzkb.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwyqqlw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2viiwzsft.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnhvyuu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbczcrcf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrfdjuw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glkinkip.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xneygfjq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zozynbic.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eygvqcoh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnyoubz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkjxetd.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbmnnek.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdryyspp.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aajaifrw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjajmwkt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvpbzll.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqsznrp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qddueaqc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2erbsgfnk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaiscfx.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmhhlce.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2epcctmxt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2enekszbw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmphrbgr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zibspium.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughikgtc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mezlfwqt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qawwkfop.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwvlyry.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2grwzipcc.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvhpuzj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzelrvqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjakulbi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjapuoa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2icborbjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qocjfrja.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2eabbykvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tarejmxs.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2czmqthla.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqbcnwz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcllacx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2acxwgzwr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yijdnpge.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mciozmik.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyuypsj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffuagoq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkizjvep.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwdcewl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszhfbu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiafvatn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnfqnkk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eazbxhaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpayglff.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbekprs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgchrhs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2luqbmuep.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2slnhrgkr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wmykualk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvwpzvq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdygjff.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2avbpybon.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2arzgvyph.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2raybvtwo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnoflaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsjpgzg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpuqewl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njehfrrw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiniuysi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyxmbym.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qixhchlk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznndhzm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnylytnj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhxatae.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ertmpcje.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2oninwevy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwdpmlk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmthfmmx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiskedbg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjqxuhp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyqickl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeszdhf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2liyuitij.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asipnpfn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2onhnuppl.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uurssjps.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrerwibv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cghiolav.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsrubrf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhnbfgb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxwimyi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxzarrw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbrdund.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxrpjet.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2remoegdn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpqzfvt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjenhfl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqrutez.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hlniqrds.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2foacyofd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wbykcbuv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2szakwdqc.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2puzsagth.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvrxyba.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyxziuh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwxhjw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaebfgo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cijgqazf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqeslkh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtpcztw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgbuexg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfpmtcw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsikkhk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fowoknoa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgwfcmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaejrdr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdgtqhg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrsfsco.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vchzzdfc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpuguwk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmqafsh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ntswlzes.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcieuin.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvellgxb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiivrqom.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yclmkefg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lltkwshy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2frkdxffp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juqifvez.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdoodvn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcfieic.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxocmhw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpwqwdn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2swnpvyrh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnxvoel.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpacdis.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cucxcjdm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2txonaale.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2topbijgv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxcmksu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vordaozy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zegmgeer.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hbovjvis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wklkpapl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtglcy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rywbwemu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2neuzwaey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyipqnw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ujycdkdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2broppymj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kjltnmbk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2futymphx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsknzkyk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2joyxmlro.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2swmsqbjl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyuovxx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fllkslnm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlemvzl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tlutfyzi.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqdiusr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2blohiffh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ofakbpfi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vknsmwww.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2svvtjlxq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoeycxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cslgxxwu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kfffbkot.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcgnvio.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjhqcni.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvciuey.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2azoptyyh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpvebbg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rooxcsgr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvczqsoh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhnrgry.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mytcurop.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eakfrflx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbqsmft.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhhyusw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkyqxjf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvhdtkz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpxgcy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uttycfno.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2obpvgyxb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnxdmxm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcumkcc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvkuadm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetvozxs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2egdbolnr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2snazgpjb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdilksdf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpilioz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2oziznfgh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyoevqp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kumoeauh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lujpkyhp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvubzve.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2buwlcdzq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfcuonu.html


<!-- 参考信息 -->