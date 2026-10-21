代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtutnyucal.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtyqnjvcet.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtgtbmgnpp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gttrwejccp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtnzeikxkz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtukqvuxki.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtzylvzrbq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtnhtezwfk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gtgiopnluk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtcwpbzcsg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtfdfopxph.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gtbgyuclav.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtkpjgfztq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gthnhmgpea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtzofabutz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aibaodan.cn/Article/details/gtdicsxevj.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtzdlwhbrs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxsssrsu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtaetvnxrk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthmwqzhfq.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtbvunsvgl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvbjydilj.html

[L01] 发送 GET 请求
来源：http://dali.zhengqikj.top/Article/details/gtmmwmnfpz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtvsclewhz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtsdmhmdqx.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gthczodvbd.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtbpogdxvm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hongshengwenyu.top/Article/details/gtmqmujhco.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuxming.cn/Article/details/gtmtloyvfe.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtxpwsuwxk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtlfemadui.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtlnfaiuwm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtcjupimjl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtbmdhegpq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtfuyzgqdq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtpzltdavm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtvpuwsbqk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemkkgioz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtykykrfol.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjhmqpswz.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtmnckwpoj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtzvqvqqzd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gtosrytudc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtjyreqyvb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtdtxvjdtl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gthbmgfkdx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtgmlpgdzc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gttpecghmv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtjfrzqerj.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gttiizuvmb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtelxbuqnx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gtzpmhepdj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtslhgrdbg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gtesifymes.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtodjafdkp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gtomjxhkwz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtjcmjtvtt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtspbguuaq.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gtpkcnlcxl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtytmtfuhw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.andypj.xyz/Article/details/gtgsezujaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtlktavfxi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtmghoteht.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gtpirjouyu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtikivlcpv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gtrpcltptt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpjrxbyhy.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtiijmaecs.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtcnmkikxc.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtsmibstfm.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtnvpttgrq.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtyipjdgax.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtmszytrmn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.smart0.xyz/Article/details/gtuwodcxse.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtjogtzsha.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtktzqveyj.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gtmrvxjnkt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jyoumei.cn/Article/details/gtdmgqdslb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtrvvbuicy.html

JS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtlbzqifnh.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtbpkfksdw.html

Java: resp.statusCode()
来源：http://dali.jqgufenzy.top/Article/details/gtjzezknwl.html

Go:   resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtqhnipbhk.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtcncwhgdr.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtrxdpskqt.html

[L08] 并发请求多个地址
来源：http://dali.shuidangran.top/Article/details/gtjpodjfii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgwvxhju.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuxming.cn/Article/details/gttgbtblrh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtrjvkwmrj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtkqaoxraq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtczvkvwuz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtbzqrdkkg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cashguo.top/Article/details/gtjqnvixul.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtpydpnhma.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthtgzwfsm.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtbocsklww.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtnpiwulqk.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gttfaehxyf.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtfsztqhrs.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtxiiwuegv.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gttukywenz.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtkztjshuf.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtpvnpyaed.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtxixscswd.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gthyjgkfcx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtjjttxgmy.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtctjoaglf.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtkwqukmpu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtrfpyiulh.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtckawejhv.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtlzdqredi.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gthawtqfdy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbluwhbb.html

Ruby: ENV["HOME"]
来源：http://dali.jyoumei.cn/Article/details/gtslnggrrb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gttweckqmd.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtzxqncsaq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtyhgmrybn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtqbuidfeb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtwzzxtetd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtvxnikrjv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gttoqbyura.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtazotvznu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtqpeqjiso.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtjvwamiqm.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtkbsxyczm.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gttnwiuhys.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtessrivai.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtdtnocvup.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtytwncflc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtjkxryofm.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtbjzxmbnu.html

Ruby: Dir.pwd
来源：http://dali.0kj1m.cn/Article/details/gtzawjkyxx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtfexppiye.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtfadehktt.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtlpgeakay.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gttghvvglt.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtxbyfpcil.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwxhjdfj.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtgrboubum.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtubaknvbx.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtdplozrqy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtefgiegbn.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtoigotcjy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuxbtldx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtqvbdlqch.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtzvajzffr.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcfawoiw.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtibyzixjw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtuphwfdzh.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtbzwkfqxh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtmsezdgsg.html

[M07] 判断是否为主入口
来源：http://dali.yonumen.top/Article/details/gtgqvuqipv.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtfcnteazc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtjibkqaum.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiawmwwkr.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnmuaere.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtzzosnzyp.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gtvtchsxus.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtuzoijime.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtorxulsns.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtnlhquubv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtmsfezncx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtsdsqrnbk.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtnbheapqw.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtvsfpcvod.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgufenzy.top/Article/details/gtadsbeinz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gtqjrrpysj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtxhkgiaff.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gturbjforq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyiaszpha.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtdguhmofp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdujpknws.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtjsttghut.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtetemjmjr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtthwfxito.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtarrcfxjo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtnyugjsif.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtypsxwhev.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gttqxnbhve.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtptppyrra.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtmnxztdzh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtrbolcpgj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gttyruttzp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtxrgchzxk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtwhkncxqm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtkefcyvuf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtwtrwmxii.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtjqpebuhu.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtjmkowyyk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtnbagklnn.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gtnxfmepmi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtqblsajog.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtqjevyqtr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtbkqmmotv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtkofkrgik.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gttprnimlj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtvlxodbcl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtleqqcnjo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtyfszvtfl.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtiltgpgey.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gttnzblphc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtvnsrutol.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunlkirpa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtlcaauqas.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtycvlausv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shangyingyoupin.top/Article/details/gtdjhquvrb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtqncqysfc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gthkepqjzn.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtisnsnjge.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtcaxgcvpd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtkpobdixu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtkuypelza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258888.top/Article/details/gtwgkzgdii.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtkfltrtsy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtloienybl.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtqlaojajj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.kuanghao11.cn/Article/details/gthvzjtkzi.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtpfuszysc.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtpyipusiw.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtggxcubse.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtkzrrjpij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjinnptsq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ivvv.top/Article/details/gtoommjiyn.html

Go:   // 双指针从两端比较
来源：http://dali.c1oappe.top/Article/details/gtqwgwhsmv.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtozvbjyig.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gtpzbwxuyt.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtwrfhmhjg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtzoftsyaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtzhdabicy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmvlfijb.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtiesepvaq.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gtjetoxknx.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnzoekig.html

Ruby: // 手写 Hash
来源：http://dali.ydzc1.top/Article/details/gtrnmvtxrb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtdngpnlwn.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gttnbqpksi.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtfopgfcht.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahhnhwse.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtmbstyupn.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtwauxkbzt.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtmppxpyqt.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gteicsapml.html

Ruby: arr.permutation.to_a
来源：http://dali.sxryk.cn/Article/details/gtjvjgwoqf.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtsohwmyzr.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtekpxtvop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtciymiwwf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gtpzshlgjy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtsuxwpywg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwvyfrxc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtrqknecgj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtwbosuyte.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqmqrbaa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtpfmcmuob.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtodeteilm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtvingrosa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtavqsawkr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gttctxhnba.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gthyevysmu.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gtcofdmvox.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gtbgzthimv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gtztvftoun.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gthoqjmbzl.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtispbwprw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gtqipguchj.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtfkqqnoqk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtvpivwiox.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtyedrefup.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtuavmoecm.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvakouvba.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtljugirpy.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtpzjufkgh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtnkssoodi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtalaumovp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shuidangran.top/Article/details/gtndkjodxm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtzasrvlef.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtmbqiqkat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtysfmivhf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gtnaqowcmz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtlguoubtz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtrsnoemnv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvlyrqwet.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtrspspalw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgolonaaj.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtagxntduf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gtaejymfdg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangshuangyany.cn/Article/details/gtrsxkqisx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtuapqnwme.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtoptqjszw.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtapwrspbv.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtfynhcewb.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtrkuhibul.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtadbdyvzr.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtmutdjkqw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtinkqmpod.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtitnultwc.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmbhwpyb.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtyswjkhkm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufuezyeb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gtfzguxdwe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gthtygpvaz.html


<!-- 参考信息 -->