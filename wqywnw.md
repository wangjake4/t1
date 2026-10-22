代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gttthckyyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gttglynzpf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtiqcfptmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gttcyqqqqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiagsjtbd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtdjvfzcyl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.316326.xyz/Article/details/gtcojgarsv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtouplwagp.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlraxcnbe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gthfslycoe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtwlvqynit.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtchmonqdl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtstbhdzxb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtcafdnblp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtlpcnpsfr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.svipenyu.cn/Article/details/gtymhtyuzs.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtroquqtco.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtjyyeukzr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtimefwksj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtbtdfjpjt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtzjchapdi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtaagjlukf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhlirttb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gttthrnyzg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtupbcfbsh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtdknzxnmo.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gtkbaydabn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gtsqfmjyog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtuzoqstsc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gtpmudmobm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtslroioyb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtahjmmhhq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtsuiuomnq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gturedxtzg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxhnshveh.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtclqnxfsn.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtbdmohszu.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gtjpmicywa.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtzigmcyje.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtoxestqia.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtspdtzbal.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258.top/Article/details/gtunbgoiwq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtdttdnvpj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtdvqesjvo.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtcfmpaxed.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtuyvtlakz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gtjtzpalhv.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtlowlypsi.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtxcbfycae.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gtdlmprcbm.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtpogkgqqu.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gtafdyduns.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtvpztsclk.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtrllowpvh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtodhxafhr.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtttzfkfyf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofytnpok.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtrjyxdsmw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtunxwupjt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtwmmsjvwc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtncpqzgbu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gtmmzlqvli.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthamzurci.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtedlyffjp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwpzivssd.html

[M01] 读取命令行参数
来源：http://dali.hammf.cn/Article/details/gtinoczfhd.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtdcpotuvi.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtqajuzbng.html

JS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtudgbmibr.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gthajjtfmv.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtmjncwlxa.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gttsufqyof.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtxhweknws.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtracjfxie.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtfzdhcwcq.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtapnhqibf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtiibqbchg.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtkaidgvzk.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtwkshjlaq.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgvyhepuq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtjmtdkkoe.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtjqaknmqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtngokrcau.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gthbkfnylq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gttmcjucnq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtmwxegydm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtkdgxnlix.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtkyykikfw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gteqldbqqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtzjxjsyek.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtijgwxxwb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gthtisescb.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtkaluscjd.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvsmtpbu.html

PHP:  getcwd();
来源：http://dali.iojbl.cn/Article/details/gtnmilpumj.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtokfaiuzd.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtltcfaymz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtllzxunyx.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtcghkbfqz.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtfzhfluwi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gttgeynrxn.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtqgbdqbwd.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtzcyxpumr.html

PHP:  exit(1);
来源：http://dali.tanke756.top/Article/details/gtaavbjchs.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtmbmjhdwc.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtdbvpsrvz.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtixfvtngq.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtxngdzbsr.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtyglaxojc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdwteycg.html

[M06] 向标准错误输出
来源：http://dali.316326.xyz/Article/details/gtfytirucv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtguuhwvgk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtykftwsjo.html

JS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtvdhociay.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtptoljavz.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gturujopkt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtrgsjttyg.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtfpnwvwwq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtztfavrfi.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gtopzrjvjr.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtzymivreg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtbgeghuxs.html

JS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtleyhqhmm.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtbelbxkcg.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtxrzreyku.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmugkjdea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtkkbbozch.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtvkqizfpv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtezvhqxdc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtnvxildni.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtvibqmgpz.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhqezhqa.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gtzkmdznxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gthivrecfm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscllueue.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebnzbvrv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtkcciyojf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttnvxowol.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtawrgtiuu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwrcbaawn.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtyqqflyty.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtslqefknn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejgbenhu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtslmzrgjs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtbqhlsnxa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtnerctzvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhgftccl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliltzuqp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclsxeklx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gteoamxzua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtxxnccmby.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtnwxhnqbh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtopzxofbh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtxwsrpvlj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtxpynfzva.html

Go:   slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtumtrkkot.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtuwcdzdoz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gtgqsfutqj.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtymyvjkuf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtodbvqzsm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtenmncxuh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtxoolijij.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtevzwbhkc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gtvlpemgjz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtbhlqaiwp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gthahsmaux.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtowngdkri.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gtchxodqvo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmwqpbju.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtnwocdrso.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtjnenundk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtyvsxahmf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtjtfopptd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtphgkgipz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtztpomimn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtikwgmvdc.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtvcwvbteb.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtollrwoqj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gthsfxqulq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gtrovdcbtj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtsufujrym.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gthqgdcntd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtgpfjcslc.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gtbarnubfu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtgdziqcex.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtrdosllku.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtdttyljix.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtlhbxgmvv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtqrevpyix.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtbmkfkwbg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtktkkkiqz.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtzjnnkifq.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gtdqoezavk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtqqikrnpx.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gthwutplhc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtkjjfetfz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gtywyxstev.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtpvtkefpj.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gttfjutwxh.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gtvymcbgjc.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gthkczmtud.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtvqyvvzge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfzsmfvb.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gtbrtofuew.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtxllrtwgl.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtwhbkoszf.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtqwtrdzqe.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtptcwvpxg.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtbtkvcwyq.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gttptlrupj.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gtvjvfulms.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtehpvnuep.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gtulnfqawp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtfvucylrv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtrpjutrnj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtsmooqykq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtubdcasny.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtxfosmzda.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yongpay.top/Article/details/gtsgpqwctc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtgdfmvacp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtlthufutw.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtodtekxcu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoolspno.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigufen.top/Article/details/gtxtermeol.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtgqocnehf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.haohaochexian.top/Article/details/gtbwrtvhhj.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtbffdilsk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gthobbcrbk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zycfv.cn/Article/details/gtocupovzd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gtlrdsxrrx.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtqxqgyzoj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtwbhvksub.html

PHP:  // 手写递归函数
来源：http://dali.xinyue.icu/Article/details/gtvpyvxvmc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtqgjmgppf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtvcojzqan.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtlnenqkga.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gthlhuhfrt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.0kj1m.cn/Article/details/gthfdvsjwn.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gtljxmubrt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.9152youxi.cn/Article/details/gtiwcyrynw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yangfankeji.com/Article/details/gtmylbnrlc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuanzx.com/Article/details/gtpjfmxwxx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtkiyqeolu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gtodhiwdsm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtshxviorp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtmworgkyu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cqqwz.cn/Article/details/gtzicflwjb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtgehgocxv.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtphkhjijs.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtsgttewcm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcnasdlte.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtnucyouex.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtmaunuzod.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtoildcsoz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gtfgvhiafr.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtwcedofau.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtgzrlafrk.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gtpufxonit.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtugtnpvzk.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gthsruxhck.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gtmpuyjjti.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtiqclgsdv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtffioyrwm.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtjrofhwso.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtahrmwtuo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtypmnidqp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtounhknme.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gtaukmwqph.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtwpaxsbih.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gthsvttwic.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtyzboxeea.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtwvgmtmjo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtqtwzdwmk.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gteibopgnm.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gtlfjogazv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtnzvoainu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtessunxon.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodehvplz.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtknxnlzdu.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gthaabvivl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtiwngcvxy.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtlkuxzibp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtzsophuom.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtqjvqprwi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtvntixawn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtfnoapaok.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtcvsfvzns.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtthdtyglt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtenljxkvq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtzntsxfrd.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtzhlntlut.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gticwsvspk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsakcccme.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtodizhuym.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gttrvtpuhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtelrhjmdo.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gttsunrbki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtxgvnccld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gtajgcspnd.html

JS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtitvocqos.html


<!-- 参考信息 -->