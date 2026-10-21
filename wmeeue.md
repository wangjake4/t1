代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gtbmvlbrgo.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtvcbewhca.html

TS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtczdbjihw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtlhytedla.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtzanntbjr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtnixzumhd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gttqcwfqzm.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtjybgocvn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtetpycgnb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.bjfxy.top/Article/details/gtjawrkouy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtomidlcst.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtcsvldxpo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gteuwzhhaz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtdotqaows.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtqlypvyiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtelteryow.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtnpfpbkoe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihtkhlfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gtpprhckjg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gturuwfzte.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtrhidufyl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtzaiyllcn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtuaofbyqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtuirbbbsb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtvxvopbgi.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gtbotewqin.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtbgsyamum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtxuaewsoj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtihptlsrv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtzdbrthgx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gthtbzmmvh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtvonrmalr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtjbhhtgeu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtkijbbhnk.html

[L05] 上传文件（multipart）
来源：http://dali.ybcxt.top/Article/details/gtgwdhhyan.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtipdiagfc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gtzmqewywn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtshoibfyd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtimxyjjls.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtckeuqvzj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtdutstvsb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbdanzsy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtphogiyse.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtodfqqddz.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtjmxusxqo.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjzwoocl.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtaxciycmn.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzhloluk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtojgtxqka.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtysvvptkv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gtsjjzklhy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtgfekdymi.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gthskqbxww.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtddcmzqej.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtvrmtsmgu.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gttzcaaqgv.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowgesmrt.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtojovbkst.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gteplwmawx.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtzoenlawj.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtvdxywraz.html

[L08] 并发请求多个地址
来源：http://dali.jianghu66.top/Article/details/gtvtekmftc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtmrfdkbyy.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtmvdevgeo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtmidgoydq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtyoboztpq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtxugdkxvz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gtibhxygrv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrobplero.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhdhrbhs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthjyyvwmj.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtvjgargsg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtesctejda.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtcrngncux.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtmyrelwjq.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtyooxjftk.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtabqkzegn.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtzaczrxyj.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtcskofrkf.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtvxyigtqp.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtrmzqnjbf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtawsmlafr.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnspugyrn.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gthohlplsu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtgvnabbpv.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gtevvusisq.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gthuwjmzle.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvxgyvzlr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtkplvfxhi.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtiaplalxx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtpyofercm.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtrswnoptz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtkjayndys.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.iojbl.cn/Article/details/gtgxrhvsxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtwwabwkri.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gtomduyjev.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gthbofiynq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtzrvnanrw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtcpjroluo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoofohsw.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtbmgrerbf.html

Py:   os.getcwd()
来源：http://dali.hywenlv.cn/Article/details/gtxmeexdjv.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtcxwkhbyr.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gthsfwlsai.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbkloroa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cdnleiting.top/Article/details/gtdnbwrsrw.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gtjumneadr.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjjqfmow.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtwccetkqe.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtegxemuvw.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtcfmiorui.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtzeaykovc.html

JS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtvwhruxju.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtmiohihyv.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gthqlurhcd.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtzjxwnhmw.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzeutefw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtheauttgu.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gtcbqvcriu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtryxblucw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtbzxlmtjn.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtqttwcins.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gthkbbrpdy.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtgenvhcoz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtjvqaynwc.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtslcwsjdb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gtghevmvur.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtambxckcm.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtnntbrkdw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtferjvybc.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtasegsjxp.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtvnkkvylj.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtuauqutpy.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gthjrrelpy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtliwhjqcj.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtgjqfavrj.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtvvetipqz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtihlbjoqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtuwbqdqgm.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtytveuyda.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtfvdbyuff.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtnpbrcfzn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtqusskztb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtjztpxsmw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtzfnuqgaf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttfvfyhxp.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtiqvtnwlj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkiydveuc.html

[N01] 二分查找（有序数组）
来源：http://dali.mhx1999.top/Article/details/gtefhywkip.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtuhaevzap.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtqzsfdbvl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtvicnmtlm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtfqcnhxmk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtybjebipr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtbklydeww.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtcaidoybm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtvbrqrrdf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtdjrgewyk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gtitvlswyg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtlcjduhht.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtfobreysa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtsdnrxubk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtdcyvpnbr.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtuipkjmyu.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtqtbutdcr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtsjaiyoti.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gtwtsgtytl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtkspnuokl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtcmnlpqne.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gttehrlqng.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtzwjkdgzd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gtyepnthfu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtbulmguhk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtqhckcnnd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtamsctzcb.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gtrdduiadx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtiwkcvsgi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtqrlyysiz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtzdqaqidw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtwklfzsfk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gtkhkgfqpv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtxwhcqqaw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtsobcvley.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtgkxbspjr.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtuvmvpzna.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtzxmrabqs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtscvyybdk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtocsutney.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gtdqopzccw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtwryweoii.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtromnuoxc.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtiolugsxh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gtpbdtdevs.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtypfcrqzo.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gttjacodvd.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtiiwtsjxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtpgytzkev.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtbdccnbpz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtqznndtmm.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtamjocati.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxadtaxx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.guowangkeji.top/Article/details/gtfzovrfkr.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtzodewsuq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtpmpuqghk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkphwexrx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtqwacbinw.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtuieeaxes.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtgiwpdpek.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtnihidkrc.html

Ruby: // 手写 Hash
来源：http://dali.sxryk.cn/Article/details/gtudyxjsdb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttteyvlvd.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtvmjmdetp.html

Py:   itertools.permutations(arr)
来源：http://dali.yuanzhike.top/Article/details/gtbmahetoc.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtxanmjzkd.html

JS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtdbkmhcnr.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtaexniyjo.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesfdplse.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtvyqrjmbw.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtbbdsbrzt.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtuipfrsyy.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gttbozvlmy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtlmmnadcl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtalkbzsem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtnaebncne.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtsyfmblhf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zdqjudy.top/Article/details/gturtpgwln.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtfcqpddmz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtydkfziuz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtyhnxwwlp.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gtzstdwqcx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtrkpxtrbr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtanzdaukw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnzmssyz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtvxbzautt.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzzecpmxw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnalcevyr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtyxfnckqm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jiagoushi.top/Article/details/gtqedwsuhb.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtoithkwbw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gttueiqscq.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gtdvxwvlvt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtaqtjnkfq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtyambukga.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtasaweyfb.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtstzdepnb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gtfqkinldh.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtssrfsmpw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gttglrlsnb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtjhgwxzof.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvghdctwu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcttwyqx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtbqjmfuvd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtksnepisw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gthkkfznaz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.dashuyun.cn/Article/details/gtnijihyae.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtbpqqnifd.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyxhlfozw.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gthcxsdkfd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtltxayskf.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gtrzqpiwrr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtqldinqmw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtlnyexexy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtiuuafzhy.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtkqihpiwt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jyoumei.cn/Article/details/gtxccmovyh.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtgxawxzni.html

Ruby: Thread.new { f }
来源：http://dali.c1oappe.top/Article/details/gtwnetklkl.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtelrdckov.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtuczybbrw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtqwklfqrx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtcrktwggs.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtnhemiqmm.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtvkvyeycu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtyeprswgs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtrgxdmjmq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gtvjtflgvf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtnjdrpmaw.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258.top/Article/details/gtcubmxlby.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtelemyjhs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtfyjxdgwg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtpzjnbikk.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtixkiaacc.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtzjwcicbw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtflakjxrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjujzqlcu.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtefzkaswj.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtumsnsbac.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gtcujzasbh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtoyywhrsf.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gthutwkmzo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtzrmfvkrp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtqcymsxrd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtxzguxglp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtyeifxede.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gtoqnoitze.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtkdidntcv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gtlmnwlmxi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtnsxiqvfc.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtqlpdzevo.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrhzmvcj.html


<!-- 参考信息 -->