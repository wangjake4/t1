代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtjivpxixl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jianghu66.top/Article/details/gttdqeyvpd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvfcfmob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gttmomvuim.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtjqmkuybn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtjbtfyefn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gtmbydijjv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtualubuuu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtqngnscvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtntxzibbm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtljcucxfm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtqiibwcsy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtwgzwoski.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtylexqeuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gtkwvezkqk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtvnwxodle.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtzhdihirz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gttjwwcsan.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtrgyablbg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gtjnlucqqi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gtptdzqgeb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtsowftikz.html

[L05] 上传文件（multipart）
来源：http://dali.ydzc1.top/Article/details/gtozhjniml.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtelkfdkbw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtynrsxgmc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjtqztyht.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtuiygzeoi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtejvbtjhd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtcgjkjyue.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtmyknlvtt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyojuevj.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gtpbhmdpoh.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gteqsiaata.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtrnuxoqfb.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtdpxbgibk.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtohxqewut.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtsodkqgup.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgsffpuj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gtbwebjhjs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtjhvqexbw.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtmohrkfta.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtgrzzoesi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtnbwaljil.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtnmylryln.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtwiarqsqk.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtvkhhjfbt.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtugdhqkza.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gtautbmlxk.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtzistjvej.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtmjpcvegt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawzdvapp.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtcebjpxct.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtpmpmsbqt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtaktxrvgh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gtljedeobo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtpagsqdue.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtrqpvetzj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtulgtfrjk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuvxgosrj.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtnlfjqfly.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpsacicxg.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtkebptdrx.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gtsrsalfoq.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gthhynjamk.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtttxfjzxf.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtufirliqq.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtasaiqahi.html

Go:   os.Args[1:]
来源：http://dali.yonumen.top/Article/details/gtprwzegwv.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gtobgwfyeb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gthxypkmqq.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtovkatzah.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtaidpsgle.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtemefvped.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtumivybdm.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtodgkjmee.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtmcmoabps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtdvjqydjh.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtyvybbgyh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtsbcygynj.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gtpqqqmmqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtldxysygg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtsxryylep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtklleucpc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtjixagirs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtjruxxwvy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtsmfzjxwn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtvcyrmuoj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fzhhl.top/Article/details/gtpkksajnw.html

[M04] 获取当前工作目录
来源：http://dali.chenlongwang.top/Article/details/gtjfquyjer.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtudkwewpz.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gtcwqizkka.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijqjzdyk.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtzuizidvd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtvuyapoqn.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gtskqrrhlp.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtmrysivdn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtrxkhkesf.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtfbpzilos.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtzlqtbrkv.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtsemtlxoj.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtyixhgqda.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gthruflzma.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtfglpyhzu.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtscxxzmmi.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtagzhihus.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtncazunet.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtjjcttbta.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtwmhvavby.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtlznysxgp.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gtwseakyzs.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gttinjilto.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktflvarp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nwbrower.top/Article/details/gtwdblpdsp.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwnhxniv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtbqgbyabo.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtvkyvzuvx.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtzdbjhxtm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtxntpyfct.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtqibqudtv.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gthelpnfpz.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtvimdrhlc.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtawlarsbx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gteqsxxaeq.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtdwzmwvyl.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtootbgnwq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gtmzrcvvgd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gticiibwpl.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtwhnyokfe.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtobhkbxcj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtlnrfxjoz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtfxnyxkpq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtwqgsdecf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtdczqoudz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtspbnafve.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtoyhitljf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtocqljvsg.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gtmmtponlt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtmzfeunkz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtirxoqnlw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtyrndbawd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtolinqwux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtvykprixn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtcbbrpntw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtwemmafik.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtkscwusgl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtazvsxdda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtxprfxtdx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gtvxmwjokg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtgyzuleet.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtoouxckbj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gthrpppcex.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gttguyksgf.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtwjnaxkcn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gtdipwualw.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtgqlnskio.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtjtszpkcs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtqzcpnbwx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aibaodan.cn/Article/details/gtfmctajrq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtwyqiqjwr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gtdcfkdhju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxsddamt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtuoonrrak.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gthiijkexu.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtxfhyuunu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtaapkhyag.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtezncpmhe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gthfdzgkvy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gttvfnwumj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gttgqvitan.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtprtlrnwa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gttcvkjpgt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtovyossjl.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtougsxvpy.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtkiffpptp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoemebaxn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtspvtyrpp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gtvdluqweh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlitvtqg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtzfgiejbr.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gteharuhsa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gtiodnnpxz.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtnruopfzd.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtppzuwdds.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gteykdjbrc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtsxlpupvd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtedvtdgfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtsnshsbko.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gtqxytoesw.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtqqdwofyl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gthrasxpfs.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtdnjzarzf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtigmwlwrs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtowwfzsqn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtpwgaivbw.html

TS:   // 手写 Map<string, number>
来源：http://dali.jianghu66.top/Article/details/gtxshebfol.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtarfwrlvi.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtkehpvbiu.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtiggqnonf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtxrrfvhif.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gthajomwxe.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gttbccqmmu.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtpjdanhqp.html

JS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtuotulmiu.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtzoewxztl.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtmdeczzfd.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtotpdjpuu.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtsezxnwae.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtpsdmufwa.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtvlyxaadf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jiagoushi.top/Article/details/gtnbpszhki.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jyoumei.cn/Article/details/gtrvusprmw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtwjygoqsj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtjgmjmkwh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtfotqvpfl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gthnrjumgs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtrudzmwns.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtzcdzhtzf.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtkdulzicj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtgrdxsufm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisgtftvn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtzchuktiz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtidxnmylb.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gtiqqepilh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtkjrueral.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtvyunznsz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gtfqejvqrj.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gthqrodnxi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtgsbnhkrc.html

PHP:  // 手写递归函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetimvcoy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtbojaxosp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtawhdvjjo.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtbgkhgxhv.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtjdqnmnri.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtrifnbpcr.html

C#:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtppfhujzk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtvmoeccqi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenzaomai.com/Article/details/gtkermuqyq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jiagoushi.top/Article/details/gtpsgvpube.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtshovnvku.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtuharzraa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtzfnhxmsn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhnerhsn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtujumqwvq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gttuhcerey.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgfbazokn.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gteatvssmm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwtuxlgfo.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gtccpucakc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinqigfzy.top/Article/details/gtomffmijb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gtcwisienf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gthceqxhwn.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtfnzrqcze.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtdzhkphvx.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtgmyfxkrl.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gtevfmmdbf.html

C#:   Task.Run(() => F());
来源：http://dali.jqgufenzy.top/Article/details/gtezppiiop.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gtdpanawvu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtpaqigtnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jiagoushi.top/Article/details/gtgahthmvn.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtjxtekywr.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtnuvvlsev.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtlouahwnq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dashuyun.cn/Article/details/gtyxbkzhwh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtkcvfmvfy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtqgzlullq.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtxeyimrho.html

Py:   with lock: shared += 1
来源：http://dali.yj20258.top/Article/details/gtcicrbffc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtckquztqz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenjidiqi.icu/Article/details/gtbfmofojl.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtmrvfmxbj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpcatngzz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtedfkjkrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtscerzdmn.html

C#:   lock (gate) { shared++; }
来源：http://dali.meibo888.top/Article/details/gtafgkflip.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtgnilunlf.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtcngmbrzm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtbmdqghoi.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtytjcmucy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.meibo888.top/Article/details/gthotcixcc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtchhngark.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.svipenyu.cn/Article/details/gtlvbgbmzc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtasppaxvl.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtixztmtad.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwferqbl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtgtrpzoyz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtgcgcjufa.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtenrkqrgn.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtteinqsgp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtuqzzwplt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtcdqkwzie.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtoxwfoeen.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gtkrareflf.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtfimzhaya.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtroyhrphm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gteefsgsor.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrdrrwfh.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtoulxkwru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gtcqeaswpr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtwytmlkdz.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gtjjjyggqy.html


<!-- 参考信息 -->