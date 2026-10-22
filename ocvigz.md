代发 wailian999

L. 网络请求
来源：http://dali.dianchejie.cn/Article/details/gtnuhjvftk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxandnpaa.html

[L01] 发送 GET 请求
来源：http://dali.yj20258.top/Article/details/gtgnwpeaqh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmepsfln.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gthxytgenp.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtftqrspak.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gttqdbskrj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtprchmjgu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gtfvoquswq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtgboccugs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtggowaldw.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtbbjlhkap.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gtwfsafhga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtqrmapyrr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtdmrdvnaq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtlvxhrbnw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtypiixetj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakjdaqzz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtfvhvupau.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ydzc1.top/Article/details/gtgnqnrdnr.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gtkrayytcj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtyxnoayra.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtjrdrezbu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sxryk.cn/Article/details/gtlntlubiy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtudovsgsx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtmvrcgebh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtzgojjmyi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tanke756.top/Article/details/gtbsmtxhrv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gttoaczvjz.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhyowagx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gtkpcqvyvd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkekazoie.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtdnldqmqg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtdiqngewa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gtyddtbzjm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtvmbkjlfy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtrmwlazyp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtvbvdjbwh.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtjuiuamtk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtxznnrsrh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gtnfyqlahv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtudwjwoej.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwrwxnyr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtrxnqhmyn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtfyltmxiw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtomiiqwty.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtlyrmiduc.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtazcarzix.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gthlzsxdxr.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gttgtomtse.html

JS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtorvcvmpo.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtnyeubgep.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtggabzxuw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtbsmfvlzt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtvoadpefs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenlongwang.top/Article/details/gtbdaysumu.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtacoxijoo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtzdtoygvq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtvqrjolcc.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtegamifhp.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtyuukeuto.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtgccaowxs.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtvbsppbqd.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gttfrewhdv.html

C#:   (int)resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtvnsjzbgq.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtciyzxfcj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjpnahwr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqjzvcwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtthnrczbq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gthpzwyjag.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtkyrmuuys.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtgjtgcjjw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gthlltbwdp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtxdksifsn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbajclhta.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtdylugeom.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtibaakvwj.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtchhcpzcn.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtbpzbxohv.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtthysgehe.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtqxeoejqb.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtodjjwsyy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnneaxhg.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gtrdzeihkv.html

Ruby: ARGV
来源：http://dali.ppjwa.cn/Article/details/gtmwvlmafo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtacxljzvv.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwerncoty.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtutsmffjx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtdyorqajb.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgklsudds.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtdfmaqjvt.html

Java: System.getenv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtfsxixmtc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtalxhahqu.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gtclzxvrrp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtjvtrymav.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtshafeyzq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gtvgcplxze.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtdvcmzjzh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gthickeest.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtpnqtmqdl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtsgncaguw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gteojzvztl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyxgrdwj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtwxcgumnn.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtpzgxfhqt.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gtxjzzeciu.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtcgyrfedi.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtllzgqrcm.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtyetopwjh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkajtgspw.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gtebomgmhm.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gttsqdnsot.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrujozlr.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtskpnfrsj.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gthsvopbcj.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtzcsemyjl.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtybahtkzj.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtjxvfxhjj.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtbddtwmfb.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtmvkknavf.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtmcygiunt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtjmtrlplo.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtwdowyeot.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaywfnys.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtlklpxwuj.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtkoomtwth.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtgntjxhdh.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnljwlte.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtaulmbimr.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtkkrwoyfe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtksehpdkt.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtoqbzlatx.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gtghfyxpho.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtuhqjkyft.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gttbiepzlz.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtnwnsokry.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtxwprekch.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtzxitbdqd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtnovgnwps.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtbnuzkusp.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtrnfcaxkc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtwsndtoek.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gtxlgbalef.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtllxbrull.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtmozgtsbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtyxexnxzt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gtwopksmfu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtijlzxgia.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtwlyvijhi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtbgquifoq.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtsalqxcql.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsxwygvtt.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztvbvuce.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtnanceaea.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtzyrvxybq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtsxdcgdwj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtqytrmvwl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtwewbzzmv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulcxmwpa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtkdvzeuzi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtjmhrlmqk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gtwubqprko.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtpcswezah.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtkxxxuegb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtmqffrntg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtrrogwkxk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtefqgflge.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gttjvmzqwq.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtzflrslqr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtvditehpo.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtzvxpjsvw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtcjqdtoqd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtvrdbspxu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxcplbyr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtzyqfbegz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sysykeji.top/Article/details/gtlagljqjk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtdnnpwvtn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtabexgbrl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtnxfxmlbx.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtbreuycxy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtizoekgez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtqzfozjby.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtxegkyney.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gtgfwdjuvb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtjjnuxsyz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamhhnsby.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtgevznobj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtybmldhtg.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtxrxlrtje.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtgnrkurgd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtjjjydxpk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gtebtmnuip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkgeygqo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtpxlewvxj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gttidcdmhw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtldgbkxnn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtpfvzjrgn.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtunvibqrc.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhfjlsfu.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtlemhqmml.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtqkewedqf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtvbzmvioz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtxavyiqgi.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtjbnvhiiv.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtstgulzet.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtkyxpueux.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubtqgbtx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtapanmtsz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nwbrower.top/Article/details/gtxwzxrqai.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zycfv.cn/Article/details/gttbumaqom.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtodeueprn.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtpkxmhnkd.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gtfhhrexvm.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gthppdrfux.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gtcxwzsatq.html

[N08] 生成全排列
来源：http://dali.dianchejie.cn/Article/details/gtnegqnjpq.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gthyjmjtbu.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtbirreppc.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtxocuinbb.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtiehixqjd.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtwnzcbhnd.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtpeqgcamr.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtocdrmbte.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtqdugqjfz.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphqiolsl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gtjeqksmzv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gtekvefuwg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbxskwer.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtrvstatbs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hywenlv.cn/Article/details/gtgbzqgqce.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gtllayrhwb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gthhwraizl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtxtsfpkdz.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtsmokuaxq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gttqakwefb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtkebitbwv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenlongwang.top/Article/details/gtvtlqfwlz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hammf.cn/Article/details/gtnaxwwlov.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgpsexsm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtayldjczl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtvkqjgnkq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xziqi.cn/Article/details/gtbyhvannm.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gthufgjxze.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.guowangkeji.top/Article/details/gtqfmcizzz.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzbtoelqb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtkdyqjmbw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtcmgiwcxp.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gtxcgmlyds.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtahcmwgeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtgdrtapdv.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtblqzkifi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtvdaxjrdx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gtwydyzzoq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gtvknibgsg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtcpmpjtfq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtlheiqoxi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtkpzfolxi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtpbyelint.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gteltslxgt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtcqtwoycy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtesxcnmse.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoydewjs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtgucgwiyp.html

[O01] 启动一个线程
来源：http://dali.jinqigufen.top/Article/details/gtncpyumod.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhongyouzk.top/Article/details/gtmhmcsyve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ehwqpu.com/Article/details/gtlvykhqql.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtqmfmrqbx.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtpfywsfnt.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtcejrotuh.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtgbycjhzv.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gteomzdafu.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtfjtyzict.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtpsswsien.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtcfuceptr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtbfqrsfcy.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtwbuizguy.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gthjacvibm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtemzjulaa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtdtleemma.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuanzx.com/Article/details/gtzefhchzx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtymmavkmn.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtzvbqbibf.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gtmztmpknm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtmizicusy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gticnbqrcf.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtvxfbuawh.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtunycvyks.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtichiibmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfsmoigv.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqkkitte.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvuseqcw.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gthxmpplzn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gthmopwwvr.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gteylrrruo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gttejewskj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtoyxknefa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtfctqilxk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtopyzjhjd.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtouovhbby.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtdrdvhgdr.html


<!-- 参考信息 -->