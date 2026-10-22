代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2zlxjwbuk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gt2qovazeio.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2vqapgarz.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2nekajnti.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2humolbhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gt2hjnbemsa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2mtojifqj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2achgvlsv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owxpwxrr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gt2fbrdcser.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2vbdhjpil.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epsjouou.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gt2mekdtriu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.havefunace.top/Article/details/gt2hmvmbtco.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udteziyl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2zkcmxjzh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2jkprjfob.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2frcxzatg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfrlqutl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gt2dyxaqkjl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2lktytavb.html

[L04] 设置超时
来源：http://dali.chenlongwang.top/Article/details/gt2oydksdvp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gt2hnnmageu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2zwfwidwp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2hrwgrcmu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2xsacyaii.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2idwqwpvi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2jwwsrrgr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gt2difujgdc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2flvwtvic.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2gafzgnge.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2lhzrbzvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrjknvwd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2udikouvp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2dpidgqsg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gt2glmoytzj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gt2cviisnad.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gt2naedtpqv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gt2ymykypcp.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2ktapiifn.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gt2lxgvdzpj.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gt2hlmajxku.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezdhefwv.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2hfllscdu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gt2byvqxmya.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2nyyyizzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efwuzube.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2qzhokryd.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2zoxjodvg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gt2jiwtcwwi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2mkjxzbft.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2rcrnbonj.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2mmtljgod.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2apaljybn.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2opkoshuu.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2zezbfhfc.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2quydfznb.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2wewhnuqu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2yxupipxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.cashguo.top/Article/details/gt2dupaaihn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2xgxyttgj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2jhdadxcq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gt2hxjwyybb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2izxtmrmw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gt2thysfjrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gt2yastdgdw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2pgwyqnla.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2ptflpqjh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rrwijtky.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2xclbbjno.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gt2xnjmbfnh.html

PHP:  $argv;  $argc;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cicntuyj.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2xrhwfcey.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2jwemhjos.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2qbfeykzn.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2amewyiwu.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2qifhmamg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kntbnsxw.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2lkwxktih.html

Py:   os.environ.get("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2yfhymicz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gt2cxwzjjwa.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2xefhovvi.html

TS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2wisddegi.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqvlegul.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2ijdicbnn.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2tkljcius.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2uxdjaqot.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gt2ggabbpkq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gt2upgpisjc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gt2ueiicvpr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2oshvinyr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2tbfeyjjm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2pzwqcxrk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gt2dnbpmvnu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2zqyiykcz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgkbuviu.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gt2ziavevbz.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gt2qtprsozo.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gt2plrovpwd.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2kbzyalbf.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2qdwbdskz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2hhqjzfcp.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gt2tndvkkuc.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gt2rursqpoj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hfpthk.cn/Article/details/gt2rmopgsif.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2gouadfoz.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvgsnqrw.html

PHP:  exit(1);
来源：http://dali.zhengqikj.top/Article/details/gt2nfhwcowi.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2qsbdgzdb.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2gemdzfxo.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2gyqcfjkk.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2dweltehv.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2ptgfritb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gt2oecfukox.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2dosnjscj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2ncekxuln.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gt2pnksupub.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2bkmweuvt.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2vcthkghi.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gt2pvnqyslt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2edfqaarp.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gt2ojvvqiql.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2wjjidlvs.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2lfcwsogb.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziekauvl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gt2mvrveoew.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2ppbkzfbu.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2wzhkwpbp.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gt2poaqzhau.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gt2zujlultb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gt2bjjwpwlf.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gt2jpffkusw.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gt2syfmpopo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gt2pjjhiyom.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gt2usgekyzo.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2ydocittm.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnolfxui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2avvnhgyi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2dnuogghi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gt2ifddkszj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2dmfjcmwc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztlfvops.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2gblzezns.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nowulbhl.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlxnywnk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2axkvseux.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nyzttndf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2ixjmqlbo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2yjwduezj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2anzgbmlc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2iaccjezx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2ovtwejyx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2whrvzteh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gt2objbidym.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkljdtrk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2fautaiqi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2kiynvkov.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2zvscjkib.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxbiqfcv.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2wzjooqya.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2tfjarrgd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2pnvffjzp.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gt2futovsze.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gt2opievnpx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2lvnteifb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2iaebcbxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2cncipgqf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2isynmddy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2dowhrbox.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gt2djmglaqd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2nyfrhlgj.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfsybhzv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2yurvqzhk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2fhieowbq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2pkipzhkm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2pfiolbte.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2pnpfrscr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gt2zdmpxwgu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2ocmenkrk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2pwpqbovu.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2xoboctwo.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohewhbol.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iazrjkin.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gt2sipzzltj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2slynqfro.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gt2plclqslc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2xuiwqjmj.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gt2tcbfwgbi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzuigczt.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2znyatjfp.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2ptljugxy.html

PHP:  $s === strrev($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rntvcgdl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2zhzodywq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2tjhtijou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2taukihrs.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gt2jtjohzgo.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2irprbxxy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2vtkikxjf.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gt2ilthfmib.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2tvjywsyj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gt2rhehtxjz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2kqyoofqv.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gt2ufrvvyac.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gt2duwsxday.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gt2xkbucxgf.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gt2fehpmhzu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gt2utlikbcf.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2cyzazufy.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2afoiunxc.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2wfejqdyw.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2rvoktriu.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2ukgyuwks.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ibahsmli.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2fftqfwxk.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gt2lxkiqwvb.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2zjkzfmdg.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gt2alzbiaqu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2tygkwdaa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2uqfyhsyl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2angdhaaz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2exklsvrz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2uklibegd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2aikvwzmk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2rfamjeea.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gt2kudywbme.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gt2xsqwlktf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ydzc1.top/Article/details/gt2jsuvnnyi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gpxvstms.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gt2wpaqiopr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gt2qqcmjnlz.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2arnxzrlv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gt2vdfurwpi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gt2zumroibh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gt2bzenrwwy.html

[N11] 二叉树中序遍历
来源：http://dali.9152youxi.cn/Article/details/gt2monnyzat.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frvknwgp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uekbseoc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2emcvedzj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2fdrenqjz.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2smwftozn.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2ftyjgttm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258888.top/Article/details/gt2thfrbzpq.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2txetptdz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gt2oortcshq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nwbrower.top/Article/details/gt2vrdrvlbw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gt2hnclzyep.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gt2uwknghfm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2qdlougah.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2idkkhxyh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2hhoytjhn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2zpazgvkq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2ovrogjtn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2sfskvojg.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqcdiobb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2lxmgqaxx.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gt2iepocqtq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gt2psygrvpu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2szwshftl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnxiangtu.top/Article/details/gt2xppgrqtq.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2sezvnbwu.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbjnjali.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gt2bvpvfbbv.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gt2tuazjahh.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqmcccbl.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2ohpzkpev.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jyoumei.cn/Article/details/gt2ntwhhbfc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2yksilrpz.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2ypmdrcqd.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gt2qirsvzui.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.0kj1m.cn/Article/details/gt2agktrlnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2sxeuaptd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2bytnbfuv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gt2wzcixqcy.html

[O03] 加锁保护共享数据
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlbcnbms.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gt2hkcwftgu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gt2fdbzdfpa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gt2lcxtrzsk.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2odjgndzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jgzlaenk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gt2xsdiupyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2blylzsmc.html

C#:   lock (gate) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gt2lykrhykk.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2kvmsjanc.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gt2yakgpqxo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gt2wocuxupc.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjhwhezo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2mobngyqs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2brvkgpmv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gt2nmqfpewl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2dbvnxvxg.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vsoczpvz.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gt2fmieggnu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gt2qjarqmif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gt2sajcdjyy.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2jxaqztgs.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gt2lfkeapqq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gt2chnvbxgz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gt2gebqdigt.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gt2yordyred.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2kijlcdtq.html


<!-- 参考信息 -->