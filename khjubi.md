代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtnihprkvz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtivrgeseq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtmsnhsgma.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtozlonren.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gtqxdpqohz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtfxosgvac.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtgegcmgho.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtgyxyeuwv.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtytzyddeh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gtoutdcsug.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gteahziamt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtuzndqcwq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtsijyytmd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtafggwvsw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtehafelgf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtmqfhyqpq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gtapkauczj.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtcfzkptat.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtsbnaeibd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtvgryiorw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtoutvdsth.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzqtsujb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtmdqbvzuy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtwdrmwptf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgufenzy.top/Article/details/gtgjpfnujw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtgopsfzce.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gtglozmiuv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtgeqqzoxa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuxming.cn/Article/details/gtszmbbhgr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtjpahlyyw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtzzzcqsvm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoandxox.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtebqzetpk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cashguo.top/Article/details/gtbnvuhwbe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gogol.net.cn/Article/details/gttkoykthi.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtafzwwtah.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtvbyhwjwq.html

PHP:  json_decode($body, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaoazazy.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtuqwlktiz.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtkwdyzlpq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtiehlnshm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtncecknfp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjrbdgvt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtrcpdkaaj.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtocbudoke.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtfmoumsiw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtgkpjlpsz.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtzugfgqnc.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtgmtftsac.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtznkasejn.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gtehsdreel.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gtijdjprto.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtlceqjohx.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtesdhhpnj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtinrnpiuu.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gtkrijmkti.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtohzochwo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtdgktincj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtthcujzle.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtbeyluant.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtbrxmuybh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtumxtsztx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtasprzyyy.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtwsndqkor.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtypjlwsew.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gthitbpcsd.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtbyyyovid.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtiedntrub.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtlkmluuva.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtqvqidytq.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlgfqmtc.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtpidhqhwv.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtdazhhfox.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtjbtcbiuv.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gthkdaidab.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtdghmvwpf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gthypbtpwr.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtjmbnonvz.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvwqsbpz.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtzqhdrzvz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gthbpstcll.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gtytqmhjez.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gtacyuvqtd.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtpaabujui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtzgldjumh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtlfxftuxp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpulritmr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtaoxfmpor.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtzsqacuck.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gtinljfzxs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gtqrpvokiu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gtofzycamo.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtmcqylwto.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtzxdqbtdp.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtxdlnaxje.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtxlpkgz.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwkngwytt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtylilzgrt.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtenluhlod.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtnzjpmeuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gttjedyomf.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gtzzjxijbv.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtqtrernuf.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtrnvqtngd.html

JS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gtnnouqvql.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtpelawawo.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtlbwgrtfv.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtazfamjpu.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtztmeazfl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xinyue.icu/Article/details/gtrvpqjbto.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gtbclambej.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtxcfkjgxm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gthamohupp.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtozkmlhhs.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gtjkyvdzgm.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gtcxekcvov.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtujambtgf.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtlzyuciuq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gthpybgeis.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtghhtwzwr.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqprqamg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtiktcxhzo.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtlympkusy.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gtunsdlrgt.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtzpxkvtqg.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtrgcguvos.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtxolkzczh.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtepyufnzf.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtbdxmneuj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xinyue.icu/Article/details/gtpziijmfa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtrvjquxeb.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtfyngqgtx.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtnnpdxnvv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtqizawcab.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtoshuzghw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtwtaoembi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gtbebedjhk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzllnksim.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtnqanbriz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnqtdkgkv.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbrwbwml.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtodhvmbie.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtdbefyznv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtjeayuxwr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtsrlfnnuv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtssrptcnd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtfygqjxqv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmykuywf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtyeerfqec.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gttpvapkgd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtjrveltbh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gterghvakk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtgupngwbe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gthwzdepjz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtpkokbmhu.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtsgdhydzw.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gthukyvfep.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtnfnhxhwe.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtkhkfzzms.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtqpasqwwg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtemkrazqc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtqgovgeov.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtdejsocxg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gtvmzfhdor.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtotyjsfbe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtbekqhfkw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtdlcjcfgt.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gtkdfncdgo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbkmmwime.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gtpoquiijh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtiizfzxza.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtxcwrrosv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtojwqfujv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtcjneshhh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykogctde.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtcglhogxy.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gtkvdmgajl.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtthysgljk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtalolavby.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfauxgpe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtrzxuisae.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtopptzrfj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtdcxauwgp.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtjhtkczti.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtcqqkbwnf.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtvbzwdilx.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtfqfqlxnt.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtfeyqyttb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtyandnztv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtqwcxwowr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yangfankeji.com/Article/details/gtqldixsjt.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtsmfcpdvq.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gtikglzles.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtjazhwobz.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtmhqgrxmh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtvqdhrbbp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtrwlcgooz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gtsuvklkta.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtzhjrtniw.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzksjakh.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gthsbubgsp.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtehesbayx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtlzwaotlb.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtcqfzobhg.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtlanvfzxs.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtoqblvgdf.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtdjfhbwwn.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtkpnufdau.html

Java: // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtatzsuxcj.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtzgvmzpem.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gtodbtvljy.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtgxullfrx.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtckhfuaar.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtrtqasbeb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtozykmqnz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtxepjpdma.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtqewcctpa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gtlhpzamwz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gtrsjzevob.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtergvbymn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtodarqdzh.html

[N10] 链表节点定义
来源：http://dali.ehwqpu.com/Article/details/gtewcwymxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zycfv.cn/Article/details/gtlsowqqtz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsjmanoqw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gttbdhknnk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gttjusizsn.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtftyenxpo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gtwlbkazgy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtfvsppktu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtfhiutfdg.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtpneobwoz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.birdmap.top/Article/details/gtxbthgouc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtuoszdqlb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtmnflqkcf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgqmteps.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtpsrhycdm.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtwobotxqx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gtzharcist.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtjqektcsn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtqjmyvlcn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhengqikj.top/Article/details/gtojfhtbfr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.dashuyun.cn/Article/details/gtwdpoyusq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwomnnfuu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtxwffwblw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtiuzkbkhr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.redwolf501.top/Article/details/gtngdpyhgn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobtbxxcc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyihszbr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteifccukp.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtohlehrse.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthtymytjg.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtdnylfxci.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtbqjjdbzq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gtsfyagzrf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtutzalkay.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtatggdfan.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiolgzywj.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtftvdtbfx.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtfnpdbmun.html

C#:   Task.Run(() => F());
来源：http://dali.kuanghao11.cn/Article/details/gtcngynurt.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtfkvtgegn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswyprsbm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtvicvlsye.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtdbmgglbv.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpbknosz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtshmlfaxx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gtilcaeyfr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvevsyecr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtwjlxlbkl.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtelifgiik.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtppnphhbe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtteudovji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtifibkbrk.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtjdtvjnsz.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtwfztifgy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfooowfte.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtrisxfnhg.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtkecthael.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gtdrmxycmc.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gtjqcznpgg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtsyvhbkhr.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtkxtrxsxc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtboisduag.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtikvkdlvr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtsyceqghg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtpanlpxso.html

C#:   async Task F() { await G(); }
来源：http://dali.tian-w.cn/Article/details/gtlzjayxas.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gttbbfyzvd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dianchejie.cn/Article/details/gtarhjojfz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtlvsdnajb.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtggovytdi.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtyafkdqrj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gtlmubisum.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtiewrhamv.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtulwexpjc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gttgcfsacc.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gthalzzdty.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigufen.top/Article/details/gtlslaoxie.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtwkdllgqa.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtztvoqjhn.html


<!-- 参考信息 -->