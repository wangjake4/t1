代发 wailian999

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gtzslmrfrh.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlynlpqop.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtxrqiqkuz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtycjyrtdv.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtiuyulfzi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.9152youxi.cn/Article/details/gtmlszaske.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtghmqagtu.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtobwkdkos.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtvukpzvyv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gtvxjpbucl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtqfbbucda.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtmwvxbctf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gthuphhbvj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gthfediftz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtqpfiulhu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtjbfvvzjt.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtxivazfzp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtbhpaprah.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtgbfifnem.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.vqdsnc.cn/Article/details/gtuumqdcmb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gthjweipef.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtpdyqyipa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtyroptupz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtrsxokfkd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gtiqxlaoxa.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtautmttsk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.smart0.xyz/Article/details/gttzcghulq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtlaagctuf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtxnomkvyd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtebtakgcp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtwzuiepxk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gtengeinkb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtthinfrju.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtijdbjdrd.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtuastfkzn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtxcivvfki.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtuyduoyvf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gtrdbdlfyd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtpzcqiboy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.quarkkingdee.top/Article/details/gtwspamsff.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtxycizmmt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtbqhygmot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gttxxjqtiy.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtlnvzztbo.html

Py:   resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtheqitrhr.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtmipulqoc.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtzrldyfhr.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtufpaavvg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gteczohskt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtukwglqop.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtdxbzmayr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtkmhzxowi.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gteigwnmzl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtocchcvyo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gtkctmahak.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtrjsztrvw.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtkqhczpco.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtexjopuuc.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtooavzpth.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtqmppmgsb.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gticqndcge.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtwdskxwzf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtmiaeictg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gtlhgoarmk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtgjgsnxtp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gthublzasv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtuqwxgbfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtnopavnct.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yonumen.top/Article/details/gtxoyeruqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtkayobcjm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtglplvimb.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtyxlboavc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtkthhzvus.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtdyypfyjz.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtvysnhhin.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtidsgdvqb.html

JS:   process.argv.slice(2)
来源：http://dali.chenlongwang.top/Article/details/gtetxnzuxh.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtdqveivfh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmahdpamv.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtbsgjdlwz.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gtnqeisypd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtxnzldafn.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtjcvimqbk.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtavonoetz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtcpjvoaxu.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtjclxaebt.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gthvwkhaul.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtlcgsxysd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtioaamiet.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtnmtevllr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjgypzky.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gtaomxwdxu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtcpgeumjy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gtuqfwpbgu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtiefsavrc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtemdytnmn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtfjdgxhxa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtoimvwypq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gtyqcvjniz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gteixmvtty.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gtrlhqysdx.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzbfvqjd.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtuqfjmjhr.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtmxarmujj.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtpemxdpab.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtkvxtkbrt.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtfufrfqtq.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtoxtdvgnh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtfvawtpbr.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gthcvqviee.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtoladwice.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtimgsefyp.html

JS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtrgsrxwxd.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxcdhsid.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtenuhexbs.html

Go:   os.Exit(1)
来源：http://dali.smart0.xyz/Article/details/gtychggjzr.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtkgrwyvek.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gtxgkdlspn.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqxdgwop.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtlsoacrbb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwhaxkjw.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtrcfcmyqi.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtkhddvuvm.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtuldxywhs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtzzkqhqnr.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gthcrxbmgg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtuvmvouou.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwiqoufc.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gtkbblxclk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtqmbgkgdy.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtfwyxdqmx.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtsusnlyvv.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtehmytumv.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gtseahjstf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtuasyftcp.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtjmozhfwv.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtjdgvihiv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtokwtiiqw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtefcinbmb.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtlrgsflub.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtiprqcnrn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtqkyknnyd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtcrtwoqig.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gthttmjbon.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtkmxyaamn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtvyuswnyu.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtrijgmwsf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsfpudilj.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtaqnzsxji.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtwafvfpcl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtmbnvucvr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtldfyivsc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkdloloh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtbvlygemn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtmvskgown.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtvsmlucmb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gttchfmkct.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtrmvnhagi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtbzagnuyw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtlcapdbdh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtjuomjjyy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtdedqezfg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtkdayrexr.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqqeeorwj.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtoldnxins.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtvlzyxkhv.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogpibirr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtbrwtvyxs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtyutzkzlb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtperjqjdl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gtnpiufcgn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtcrnelrtx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtsgcbczce.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gteutveqpy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gtxtvhssrf.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gttmdyhczd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqcutsvsr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtriduecwh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtxkftgkvj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtaxnbglub.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtsbbidpae.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtnaivsrql.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gthdwniofa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtfzknnvck.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtrlidnewn.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtxrcjmsrg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhkzewij.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtpacnnpps.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtnipcpitv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtpqbwzkba.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtaawzchhb.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnrppjbb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zycfv.cn/Article/details/gtrlknnjis.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlcixtkme.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtucqhnaed.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtbryqqvmd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtkrmqlpmc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtbishzeqj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtvsiuclcr.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtdsqhldwp.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtgsjbtzjy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtvfrvmcgq.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtgidmwrcp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtldhyemaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtbhtednzr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtbzxhshma.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtbbltapzc.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gtarcxoomj.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtxfuukwxd.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtuczcfclz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gtqazyyjhb.html

[N08] 生成全排列
来源：http://dali.sysykeji.top/Article/details/gtjktlprtz.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtnmkyurxy.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtswiuqjgy.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtwqmqnejz.html

TS:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtvcfptfkb.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtrcohfvmo.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtzmxqjesd.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gtmvlsfrby.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtjalozmgo.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtbcwbefqs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtzccjhity.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtypxacceq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtrjdbtpuj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtyqyvovzu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtlpoyknxi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gtxrekovol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gthggvssfo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtyacybveq.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gtzhfkrbqc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gtusmrmnwc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hnqzz.top/Article/details/gthsthfgbx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtcplveeoo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtdxhgloky.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gtpeykdaqy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gttzaqpeil.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtpwdqxbsr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvgrceas.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gtmfqbhrwo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258.top/Article/details/gtfndwgxbn.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gtaypkrvgb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtxyrxwlfq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxcuxupm.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtkrvzehwj.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtlqwvgdtr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtzotbtuyv.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtndwlymoi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnxiangtu.top/Article/details/gtmukeaqjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtivwbqmfi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtaynpimlm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtjzuuyiqi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtbtprlsvh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtxqfydmfn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtwcwdjgft.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtgtawfysw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gtqxnfjumf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnujfoivz.html

O. 并发与异步
来源：http://dali.guannengcc.top/Article/details/gtymrarrqm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdmzacxvz.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtxmgjtopz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkljuzwpp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtlauuceaq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtnghmamnv.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtfqkuqzkp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzanftehk.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gtdirmzjog.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gthstmsbra.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtaajzluif.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtrzkthldp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gttwtifmjy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtqvjtqekm.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtvfyutirx.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtqhymwtrp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gtqrcbvsfq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtcchcwqws.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gteclronxq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtzoeolfld.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtzrtoiicb.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtnjwsqoup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtzovtuxph.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtyqeirteh.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtubxuerio.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtphvgcaym.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtxbyflmzd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtdqekiylp.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtnykoesxx.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtazzqikex.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gtdaojpvxz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gtucpxxsdk.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtwjwsqppf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtfiwpabzl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtzsaoqqco.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtebxytwpg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtldsdnngc.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtasmebhoo.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtpzworonx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtvzdgifdf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtitlaocpm.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgenlltv.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtbdbakdtd.html


<!-- 参考信息 -->