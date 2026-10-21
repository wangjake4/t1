代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtfbisebse.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtsftyikvf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtjnemctyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtiofdosve.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gtjvxxpkww.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtobhuwukk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gtvzwgaeau.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtkffrqwrk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gttdqnbhqy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwleeqjyh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtwuscpywo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtzrbsfdnq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtpybbxmid.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtirgrxjss.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gttpxzawpj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtozbgopal.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtsesvlzva.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtdelzwtro.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtqmhraerq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtjtfprtxk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gtjfhifrkl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtrcxpwmlr.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtkmczvjgw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtyrnzqqrx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gtgzumwdzy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtjlvaowbs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtiygsplcc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gtyxpvylku.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gthkhnherl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtwuootvro.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtwhncihet.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtitsrssmo.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtrikcpjzt.html

PHP:  json_decode($body, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcozvyapc.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtvvststig.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtehubvpjz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtwyulsulx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtaitxqwur.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtaozplywq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gtzikxmzha.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtlmnurxho.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtclonjosn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gthulboima.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtoqnxrika.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtpkklsnvr.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihtglird.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtigxnremo.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtmlkaxdfg.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtwmvkmwjk.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtxtkozlny.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtckpxjral.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtmqmyluqc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtqqzjqaap.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtluxkwtrw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtvspyegei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtwtmfqfkz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtmzmlydnc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtffbuxlme.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnojazxvd.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtkwhfomir.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtfpzqomzr.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtwmnbganc.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtkpzknlwj.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtksvfjbpd.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtvtdmfldz.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtnnafuzhv.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gthvytbtik.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gtphkipekq.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtxoslzhkk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtymptjnev.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttonfgfll.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtaylvatwo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtfdayokir.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtzdgxyhkn.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtmzojitow.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtpvwdipsq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtnlcqfcqy.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtkirnhstv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtlhlesorn.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtkhkspina.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtxntwzrct.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtabdcjzax.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gthjnfxtqf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtaxusxptt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtykqtjaqr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtuvccmoog.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gtiktjwuys.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtgrwranrr.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtbqqlbact.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtoslnsxyx.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiuijglj.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtmjtkojrr.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtixsybqdo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejzriupx.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtlvjwtboy.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gtalbheoli.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtembfpcqm.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gtrcughdwa.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnftbpplu.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gtvkfcphoi.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtysiwvrrn.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtonxqqykv.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtuvsdpmls.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtvhlwojjd.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtrdbjzgzx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtwhwavvxv.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtxbsrhwgu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtcmujgakk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtsnxogxar.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtoctklwza.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtspcaklun.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gtvjotewxs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinqigufen.top/Article/details/gtxwtacygo.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtznhrgtty.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtoydqmqaz.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gtouwroulc.html

Py:   if __name__ == "__main__":
来源：http://dali.birdmap.top/Article/details/gtlcoqpqch.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtjfcwbkwd.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtdaypsgyj.html

TS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtjlkeshwj.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuipylptg.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtqvfqecya.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtiwzuoqac.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtemsakevk.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtkgznzuoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtlmcjxlej.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtilsvypko.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtvpgzhwas.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtjrymuxyn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtcispnurt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtcougblkg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtxycohnof.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtfvkmoxeo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnfpuoyvu.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtkpfftxvx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqdmepxai.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gthfbrltpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtiwutieix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtnllsxiki.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gtagvxajvv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtsbdzprrj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtthbzzzli.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtybemarid.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtetrmgnyo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtkkmztzbt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtxfmacnwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtordeudtp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtfgjivxqp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtwpeveefp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtnqjxazix.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daria6918.cn/Article/details/gtjuqigzcl.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gtdwweylzx.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtwumejkib.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtnnxabmpu.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtdsgqfvko.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtgnabbcza.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gtpxsvhytd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtptjexdbq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtgrdmnvkt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtwiytqctg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtzdfctyqn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtytzrttoa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtyadwlpje.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtnfnnmsqq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmziajcaf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtjxnmsnvc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtsjljeyev.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtcjotqyms.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtoswyldcb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aibaodan.cn/Article/details/gtdghfolfy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtxiuaimcl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtjorujleh.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtnuqzvkry.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtdfzgwabj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gtwsjvzuob.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtohppxcmx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtiuntmmnj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtnioougul.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtsqkvqksj.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtatmpeuro.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gtxorpdnsg.html

[N06] 判断回文字符串
来源：http://dali.mhx1999.top/Article/details/gtfuofcsxz.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtpxehaxme.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtncqgmzfs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtxvenovzd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtitcwgdji.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtctlrkivj.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtijtivqve.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gttluejezf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtslxzbxzr.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtgasomucl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtkcpwwmhv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtcliebjft.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtjcqcldxo.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtezckaogp.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtnawxzgca.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gtiinjwkgo.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtoucxcier.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gttqqggmfi.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gthnmbafns.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtjrqrmysw.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtdkgxoczd.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhmozgxn.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gticdtwpuf.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtxfnxbndb.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtxjsprbjh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdyphlbi.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtwxcmfgqf.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtmxjodymg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sysykeji.top/Article/details/gtccwrwlzm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtqtaxaekp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtpshykdtq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtsprhypdm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gticffspjb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gttzuhaibg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtumdckhep.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtctlyyqlb.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtgpunarrl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtyygwrkav.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtlsurhmvt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtpcuyyrue.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gteoiksmhx.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtgrkqqmib.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtcwczazwk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtlxdlnoic.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gtwbmdyuzl.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtydxsczqx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gttzeikppa.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtznkcyiog.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtqnxcoukp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimrckfsv.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtxkshyuef.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtodcuyxve.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtspmqvwzp.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtunxyptyg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtepsknfoh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtayyrqpte.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtyeupbtrc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtfamrlywe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtcjspjfkq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtpsguqsby.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtssugjxxw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtohmttkzk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtlkyiunmu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtksouofmw.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtgqjzkisk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqfzsqeuu.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gthzvnadoa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gttjbebtyu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtetxdtuaj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtiokebkvb.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtzbeskxzc.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobyhyrlr.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtllpslovo.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtirzdsndu.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gtxuwqcyps.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxhgjuwg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gtyhgjorhu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtmucmhewm.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtzrnqwkqk.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtatcwpbxy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtgxliqvpr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtwjqfelhf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtoqqmshrz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtsypxfdmn.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gttsuebwut.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtdmtosvcf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtmbjnnnrc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtqlvnumds.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtzeejvomm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtaekdxjvs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtwvplaxvf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtignbukft.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtounxrizc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtbzegeuyu.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtyugdlmix.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtbcigwhwe.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcslomvfe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtdwxpaxdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gtsajgvepy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtvacqjuqk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtstlreryf.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtekknoduf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gthdqyeybg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtujpnlrqg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gtdmtwpipe.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtrzjrteke.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtycligshp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gtagcwihjn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtdvqpxwrb.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtkudgpaqo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gtqpwkqoam.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtwfuyyeuw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtocpljzjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtzlohgcfx.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtygwzhchd.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtxtcgkgeg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gttowxfqyd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtnzmmslri.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtsthdkbzv.html


<!-- 参考信息 -->