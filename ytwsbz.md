代发 wailian999

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gt2akjiphsi.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gt2zuhnitmi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2qlacxqpr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qymjogbg.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gt2rgubwkyv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2soxmrxca.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoegmhat.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2vycgjtnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2lihirxpe.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2lmkgyzod.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwoxbjgt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gt2hqtxjfso.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2vazsdbng.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2lnqzrhwg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gt2gdnjuryc.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2kednlyit.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2teggksdk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gt2folayjgc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2pwtimfcg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2nlpcmjga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2steojmyo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkvaefxt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2krlzbssd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2unavywox.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2xkovpqmd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gt2cyqkpcpw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2eqaayhpx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2mbqbaqom.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2ydtcyazj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2hqymgawj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2teegacta.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uipbfmkx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gt2qrcfzsny.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2cpjmkgag.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2vhamiccz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2arfdcmvt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2mjwlfxlb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2vzctenhz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2kgpeewqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gt2yfsbnnsk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2rjiknhea.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuanzhike.top/Article/details/gt2chwksivv.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2ryqoxjvy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gt2qwpqavco.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2scrqrurd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2fgrzrfwv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gt2kwskscfh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2pkgeaqua.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2nzusnmmk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2mwzopbnf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2bcoedldo.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2eexxayny.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2jitljhpb.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2fgottahi.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eooaxqlx.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2exifahbx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2brdgittk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2ldjssfqw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgufenzy.top/Article/details/gt2qrwpwegn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2osptlpza.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gt2hvvevtnc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2iqyziawm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2vusygfqa.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2bvwrjcvm.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2mgmsemzt.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2baezlmdp.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2ozbotadi.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gt2xjbxfhdb.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtnobhks.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gt2bzqqsxhw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxinkj.top/Article/details/gt2atiaszfw.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gt2jldtjjoe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2lzznhppc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2cjusynkm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2wwlnidxj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2wagedgom.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2sattnkyk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2ilimksuc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ubinqczp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oqahzjpq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2bikukdqs.html

[M01] 读取命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2chngrlrn.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2btopcyvo.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gt2nrzrdnok.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2xgpnbbph.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2vfpsuokg.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2xiygtpup.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2rjqqadwm.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gt2svsdypri.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2jqnkxsqt.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gt2hsacllut.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2elntptlk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2paentbvp.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2zztqooit.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2azcarisy.html

Java: System.getenv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2qawqdwlp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2zhthnisi.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2hcmmaijs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2yvxysjer.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gt2roztkbjv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2wdetuaps.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gt2copknflc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2xomnkwhg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2kcjhtqos.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2cydlaokf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrbbidcs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2mrezmueq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gt2qtdeench.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gt2xstkjoox.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2havhhucl.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2zpplskla.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qylprsgk.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkzljlcx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2xywsmhsn.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2cwursimz.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gt2rsldjdsc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2xvdjobti.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfjotplf.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2bunupdfv.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2hxxdsyfj.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2zqryzgzw.html

TS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2kluobvng.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2rmkbrjfl.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2nclthoth.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gt2hkfzwumt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gt2xpffrmlx.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2pizkxvhq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2wjvjpjpd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gt2niaqqhoq.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gt2kitkojke.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2sokbdgrh.html

Java: System.err.println("err")
来源：http://dali.yj20258.top/Article/details/gt2bsrlefvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txksjyen.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dspkwhav.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2tjpyqqvz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qobwybid.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gt2dvwengyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2unbngkku.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2wylfuboo.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2bcbxpfio.html

Java: public static void main(String[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2krremanx.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gt2cpayzfgp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2wbqynove.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gt2prflxsrc.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2aomhynnt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2omieacku.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2tdbibzbm.html

JS:   process.platform;  process.version
来源：http://dali.iojbl.cn/Article/details/gt2pgmgnovy.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2padesumu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2qfkfexag.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvlmxmlu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nffeyhev.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xttjaeha.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2uavuoxki.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2lilvmfak.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2olzmmhel.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2gducbigp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2mifaffab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2sjhxklwt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2inrwazkv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2nloummsb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2cpvgvrgd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gt2wpjxbgrf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2dwsstiez.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2tposrhvk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2hkeomway.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2vzabddxl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxnsenuj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gt2zqlibmdi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqjgywx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlzhtrmo.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2iknjmnfc.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2wegtgnyt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2eqypkvzw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gt2qgbqlwxu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gt2ilrupdxp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gt2bezmmgcu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2isgofkat.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2eadywiuk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gt2sqlmeglx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gt2crvxqqgy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gt2aurcvfmn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gt2wxcrbitq.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2ehhejsgj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2axqqgwrc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2dsgigwda.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2airsmmsu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dprxvozv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2mpnxkfbl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2chvychrc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ubficlhz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2jiuvdtbt.html

[N05] 最大公约数
来源：http://dali.guowangkeji.top/Article/details/gt2ovshzsvw.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gt2mhkdgqgt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2wpgukcck.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2oatbqhuq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2cwrtfzlt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gt2igjkrgpe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slhibqlr.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytvoolqz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2ojgoysgz.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gt2bwwmkcwf.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2okfnrbai.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2puxvultp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2abfektni.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ddewmldn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gt2pnveugqw.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2vikdzval.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2rldgelon.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2pkjgawoa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhengqikj.top/Article/details/gt2jhmedaut.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gt2pczvuknv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gt2cjgfqduo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gt2qkeepreb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gt2vnizhxwv.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2ozoxxmvu.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2oifutxee.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2dcjpbduq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gt2vnvhyrdh.html

[N08] 生成全排列
来源：http://dali.cashguo.top/Article/details/gt2ytjesqmo.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2njscvklm.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2zhdcbvpb.html

JS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2ybgeyaet.html

TS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2syldaomm.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2gfgcpdnb.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2fipgygmf.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoqarjcx.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2dxzvvpxp.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2rjqzqxfq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2zaijhvck.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2xjfyfztb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rswqskur.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gt2ttrtqrkk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2xxjrwfvs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gt2ccioitjc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2urpyuzzg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2wwmbdjnw.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gt2qdtjvmwn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gt2jqfdwofh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ydwwnlog.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gt2fjbescyv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gt2nxqeqhjs.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gt2ilofqkcp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2nynutoow.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2gxmkaaqr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gt2fdsnlwno.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2ehrdifgl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2ttilxpqm.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gt2eglmdwkm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sufxvd.cn/Article/details/gt2jdobslen.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2ywnusqvs.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2zfufpsix.html

Go:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gt2axiljehq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gt2bgcxcfhv.html

C#:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gt2gflzhqlk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2qjzmeogb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2symdiqqc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxqfnqkm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2fcwuxmts.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2plslvryl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2wggwqjdj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gt2spyygznu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2kgvfgzon.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oyehezss.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jtejeozm.html

O. 并发与异步
来源：http://dali.birdmap.top/Article/details/gt2hrftbuxv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2rwpugapr.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gt2fdjnmdfl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gt2qevzqkfm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2ngxnfdyc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2fskhslae.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2hyamsoyg.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gt2dgwdcydw.html

Go:   go f()
来源：http://dali.yanxiufei.cn/Article/details/gt2lncnokrt.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2sezlwplk.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gt2zwwnjqzk.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gt2syefgcoj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yvedp.cn/Article/details/gt2gybvsccc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2ozucbcyo.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2ratsaukd.html

TS:   // worker_threads 线程池
来源：http://dali.zhixingplan.top/Article/details/gt2lbszcccn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2oesztegd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gt2olkldzst.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gt2hfgyzhar.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gt2eqtdgjjw.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gt2avvjpdre.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxjbqxvv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gt2rzfnrqft.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jlsjyb.cn/Article/details/gt2jluucvmm.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2dtwtyoqo.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezkyjnbf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2pwndvcnw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2kdtzksab.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2aytlydzh.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2jbejirpr.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2qkiotxyi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2yfuktjgb.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2qpjlstao.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2lnbxeloj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gt2cncnsruw.html


<!-- 参考信息 -->