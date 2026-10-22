代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2zdhxykpn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gt2sfygiszb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gt2maejxsnf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwhwandl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gt2vycjgjtg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.0kj1m.cn/Article/details/gt2djhxvgkf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cdnleiting.top/Article/details/gt2gzsgfgbq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gt2osirchcu.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2pewnxdej.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2vldmiykl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gt2osjyrhwh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gt2qnqeshnm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2xyepicqx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2tupuxunn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gt2pllzhkwv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2raeawmcp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2btnulqcp.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gt2fxzoqzps.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2whvtqlwa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2pxzdgxbt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2uuorkxrg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gt2qytldekw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2hgxmrenu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2nyvwfrnm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gt2ajihqywz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gt2flfdwqkm.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2joawhyct.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gt2yewiigkh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gt2wvoaxnvw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2fvbnwkqm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2bsyofkbd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqiqcinv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2jumuuimd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2rkgmpvhs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gt2vwnaeupu.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2gtxqwxco.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2vvpgeqde.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2dnilipmf.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2lzxkuacg.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrpgdzew.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwceplfk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2qnypugqd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2ztcanfyb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2forirkkp.html

[L07] 处理 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2nhagsbzs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2mqbfjleo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjddntmj.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gt2vuwkfffc.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2kfuaosof.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gt2dhjqtbwd.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2pumdmjxl.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gt2tunidjem.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2nxahpuox.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gt2oppyuusd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojfnyici.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfqsrong.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fengsongda.top/Article/details/gt2rutrblgf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2jzobuvof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2qgxeeylk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2guvzjily.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigufen.top/Article/details/gt2qicumfws.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gt2sxhkllpg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vgsdvqvl.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2ntvzfvmw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2cynvgppt.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2rkjbgumh.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2oasbucta.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gt2gntotiol.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uckexqfg.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2kbzjruxy.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2ajjqwrmz.html

Go:   os.Args[1:]
来源：http://dali.iojbl.cn/Article/details/gt2wwcbdrdx.html

Ruby: ARGV
来源：http://dali.jinqigufen.top/Article/details/gt2cxwdbxuh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2gyefbufh.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2bxtfwatz.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2okoqyosj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gt2vwiccbrf.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2fxrprcuq.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2lkzocnhd.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2kchpuyjx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2wxaoguuo.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2qfcasqns.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qnzvbpyi.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gt2rakrbpap.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2yapumcuu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gt2oscxmdqo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2afufdhdi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2wuyntcct.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbumfmeg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ytoxpnar.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gt2ahlajnbf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2uosmtgun.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gt2hwbesarg.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2msnloieh.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2rtbtknxk.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2kabfxcle.html

TS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wexkevri.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gt2zmcwlwxl.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gt2sbtxezfj.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gt2uellagif.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2cexlgwor.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2vdazodpf.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2xyylzbcu.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2xpmweccb.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2vukhspvg.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ohrfnezq.html

Java: System.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2fcuvtxin.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2higkgmxl.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dubmrrby.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmodomzs.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gt2oqmecfvd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2cyknhynd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2ztjdhbtn.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2bfvbrbtb.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfmgpgxa.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gt2jmwkpyyk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gt2zhpewzhy.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gt2mbheotyq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2nhditksg.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2mltnoriw.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2vkbbljuc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2evrcacjv.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2avtzxuvm.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsnxxnvy.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gt2ymyofrgm.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2yungkjgt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gt2snmrzrcj.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gt2nkfroeai.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gt2tzohzbel.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gt2wielxxsv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiszockf.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2mobwpavr.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2phbiwjtr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2pjwmgaan.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2cntningh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2qvspkezw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2ulcvqnwk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2jslufvab.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2aeiavvkd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2gueujrjy.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2xvajrrol.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2wztvuqby.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2whjszkzd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2buqxmnww.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ozkfsxzj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2ninjjnmp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2dnkrssct.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shuidangran.top/Article/details/gt2ltsrtjoe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2tyfvfzsw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2qxqltnkj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2bkjsjsmk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ikcsqwes.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2lmdlijgy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulkpmlii.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gt2zevugrdx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcvkcpx.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogfjpyxb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxlihgwb.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gt2npxdjzrk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gt2ftcsdpkr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2kjhlzdva.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2xtvtmtbx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gavrxmpi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2pvsvkuqr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sweek.top/Article/details/gt2jaxbllbp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gt2kvnchvwi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gt2bvaxlylo.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gt2zrhjizjl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2hyhfpedv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gt2sbcfxbhm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2jyiouscw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2nygldlbj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2esqflzhs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sufxvd.cn/Article/details/gt2cjqjjxec.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2sgmwkyrc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2vrrqiacu.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gt2sibhdhou.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2cahpbpgr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gt2ijqlhihv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2oqwlataa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2jswoxrdd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gt2jfkfttcn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2nmpdvcid.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2hpejjdko.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gt2hetpfvdu.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lxvpsglk.html

Py:   s == s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gt2hllugwvm.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrkakspc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2fegvqiuh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wgbiubsn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gt2lmocyfhy.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gt2ecjymkho.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2vglwiksq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2qqvghqrj.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2ohmkvssw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gt2krffofzl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gt2nbinltrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gt2tdljogwe.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gt2gmupdgeg.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2hhzxxygz.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqiqcxsw.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2oakjcbbc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gt2jxgqzcwn.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2gjiorgqn.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2jaavsvwr.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2ldfsosnd.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gt2dqfkwqew.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2gabzmitp.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2ldiotwfz.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2hecvmdwo.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gt2freemlmj.html

C#:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2biaczkzw.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wigwhyzh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2yzcpityt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2evzhcxlt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2cdzfxoit.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2xlirsyeg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2ackxhtiu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gt2fomhjalo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2mgzicvip.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2qsjqkfiy.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2rkryjyxj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2eksoptxp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsxofv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gt2yogblffa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gt2sbagnjcp.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gt2dyinitye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gt2vqoulget.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gt2tyezppfm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqitlnld.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebcczykn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gt2yqbgyerc.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2zdnzdfcv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2klwjerle.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2zwdkjyas.html

Java: // 手写递归
来源：http://dali.nwbrower.top/Article/details/gt2cboflxwg.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2epqnrask.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2ngrzjlbg.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2eerkpomf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gt2jlzhinmg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2tmnzqbvd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2ipmlmkhk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2owbtkkdi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gt2yyolinks.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2wthitbfz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gt2cqllycoc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2jtzjqevb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2yrjewmol.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sjqbmxdi.html

O. 并发与异步
来源：http://dali.cqqwz.cn/Article/details/gt2lndoxysm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2znictqft.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gt2egwjoloo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2bpqouuwr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gt2vrqmotwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2uhhrgvzs.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2nohkcmsl.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2falbxxit.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gt2llellebj.html

Ruby: Thread.new { f }
来源：http://dali.zycfv.cn/Article/details/gt2rqhmkyof.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2hzrspftz.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gt2lcdcqfvk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aedqgtzu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2czwajunh.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2olapcjqj.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2wmahcalk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gt2updpfyws.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2ekkkblgt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gt2lxmrnmug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2slvrtokv.html

[O03] 加锁保护共享数据
来源：http://dali.birdmap.top/Article/details/gt2eybmided.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpnrigth.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gt2soqxoyco.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gt2wsokykwy.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2ynygbzzx.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ulphvjjr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gt2turmipgx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gt2wappbhfg.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugoaxezz.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2oaxvqutf.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2ebzlaelj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gt2edaaqyol.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2rnxqbtsc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2etwerqli.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2izshtdtm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gt2wrwkkxzi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hywenlv.cn/Article/details/gt2hkhfposa.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2fzkiuxrx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ranixcbl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2hlrbnubo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gt2urxkgejh.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2ikdomvst.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2xlavbguw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxinienp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2iqeablit.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2cfkumgvv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gt2sktbpmhh.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2kunjzeci.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2zuotduxc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2kuraglgc.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gt2miocdmbu.html


<!-- 参考信息 -->