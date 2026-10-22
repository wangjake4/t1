代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtxbbouvqw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtyqkkmhpe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtbkadzxnc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtqjwhjysn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtnngcujos.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gthbmqthnf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimbjfore.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtytpsiyml.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtfztsibfw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gttcbugmyo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtjtyfuwtn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtivwtlcnb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtrhlplabc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtxkoxhuoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtnlmouyrd.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gttzjglcwa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyghibyrz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gtnuyqgcxp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgpiokao.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtjbyxzqfk.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtegzrudoj.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtmpghjmzz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtumllydzk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtfurkflcr.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtczeurwzp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqjvkzysl.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gtkubukgfi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmqqjrae.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtqdrsgwix.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtzprgpbtc.html

TS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtfjdodnua.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtkbvjansn.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtjqiwctti.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtsmmxxktu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtrozqssdy.html

[L02] 发送 POST JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtputczwwt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtqxmlhstk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtkldfyuyq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtxizjispo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtlhdurtsk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gogol.net.cn/Article/details/gtyaipsotx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtfcizmjrr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gtwyzompth.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtziavjncc.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnqdxbcmv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtmsmbkycm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtsoimlsst.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtbypyvrxy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtttpaphpv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtwvgvvdhc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtennkpxxc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gttoohtpyu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gthbhkzhzx.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gtmqntjtqh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtxbypsxvm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtpopuyxar.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtrhncbjjl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtfibtpwjn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtkigwzbwl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdexbxlc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtefquokfl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtuzjjptjs.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtobtlhscy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtmbdlmvcb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtxuhalffc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtrukgriar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gtshjkampc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtzzplwmxh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gthfywyjvm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtqzdlwxyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtncuxakmo.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtcufjayoj.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtfzbuuurg.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtvuhrltcc.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtvzhicila.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gttydsaoax.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtuercmoph.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gtlvqlhxgo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtqvxmjelu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gthwdbzlpv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtbpkvdzex.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtxwyeqkuo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtwcfidhjs.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtatwqzwem.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtghgobujx.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtxvklbvib.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gtribneyou.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gtcjzgskfr.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtrlhbsyad.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtwyvtbamu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtzxsvufha.html

PHP:  curl_multi_init() 系列
来源：http://dali.sysykeji.top/Article/details/gtnwxqdfgs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtjtpdwnkg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtlrhhgukk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtanmhmabc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdgbsrsl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtjjyqyixi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gthquzqexq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjikqhlgj.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtczjkjdhm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkqauznpm.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtraiicqpi.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfrnkqtm.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtyxezstjy.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwykyghgg.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtbafprmkb.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtpewshxrt.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtuwkbzbub.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtaooiqnxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtyxqpkefs.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtlrrnlwxa.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtxzkjrilp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtiowqeixq.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtozucglqz.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtijjdygpv.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtfglmkhks.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtgjlzjomn.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gtntvazxwb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtnaczyhaj.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtweheojyj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtjyncnqdm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtkmsviraj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsxvvyqo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtssxenfsn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtkdwqqxkc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtnqmmzfsj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtjlwbgjtk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtdviwydzq.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmpgous.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gtrkaukyjs.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtttalzvee.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtkwydbodx.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtlprlpubs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtaydqlsaf.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtpdhzrxqa.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtuvdtgepg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtgctjkqjt.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtplkdhaxy.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyopqzado.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtdzefenfj.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcdoydfq.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtumucuicy.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtpkzbdmtp.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtmorjqiyr.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gthaikzysu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gtpdiyllmn.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtwemaiekr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtabqnzqvz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gthlwftvqd.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtfhzggdbo.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtsbnsdprr.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtrwdrvfhz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtbdsjnppi.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtujcxbkrr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtjslnrssx.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtjsejjedt.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtggesnpwy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtodsolrol.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtjcbrvlwq.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtdiwfxuqe.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtteeztyly.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gtrpqywaad.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtjypoiouv.html

C#:   static void Main(string[] args)
来源：http://dali.xziqi.cn/Article/details/gtvkbqydmt.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtthxovoki.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtohcrlrik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtiviljuxq.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtkciijtqu.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtoeajyrpd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtiesjhuty.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yongpay.top/Article/details/gtnhezlvgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gtibnqfoql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtlweioirx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyrufmhco.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtbybslvlm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpcduywgq.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gttemvbnie.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtqkhgzoke.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtlqvdalku.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtlsiyhmpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtvqffxomv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtqkmsfvvk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthzegkrrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtswwtikqn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gteqqdklnd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtzmfgkslh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gthboxgvwx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtmtyjvlbp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtucbjroxc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtvzserhzk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gtauiynhuf.html

Go:   slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtkafqleqg.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtmhsbrfad.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrzmxkit.html

[N03] 快速排序（分治示例）
来源：http://dali.fengsongda.top/Article/details/gtiayotzip.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtsjmflhvp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbqpqhwo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtgidvxevf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtuvmejrkj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtubtljirn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtiydmcqyw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtpudjfwma.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtwaotovey.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtgmjnrvxy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gtfvfpwumi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtmaazfldl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtypqjzhsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtccjztbcy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtvtstolhj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtglurjbkr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtkbezsllx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gthiuumkis.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtufbknwud.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtsupxilch.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gtleoannsv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtwijbqlls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtqjdhoezp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtjpefcyah.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtkokmycdn.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtgyroawrj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxotsomd.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtcjrhcvbw.html

Py:   s == s[::-1]
来源：http://dali.yj202588.top/Article/details/gtxuvpwgmc.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtkcgnqddh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtxawoucee.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtynbfnypc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuanzhike.top/Article/details/gtctsacncm.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtthvbjvqb.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtyvxgmcpt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gteywtfkob.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtxfjdwpwo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtropxenoi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtyzgzmdmx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtelcqhksm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtthxyyril.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtpamkbcnj.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gtbpgmbmmu.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtnpuqsegd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihzgcmqf.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtmowifydw.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gtuqgkeodf.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtrtlndcfj.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gthsejbefh.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtbdxedugp.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gttnalkfrl.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtgqnwielh.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtzktijqxx.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtpnpeunnw.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gtomsrpwjq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtngdsnxfl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtuflxdemx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtqjevdpvp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtflvusaay.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtfwhbyiuq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtugfjoikc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtpvgwrxzr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtuadsocfd.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtmcpefqrq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtxvgwfjio.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqvkxnyng.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtwlrzmqrn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtcwummpii.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtyptblhwe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.redwolf501.top/Article/details/gtaqmmutiy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gtzwumfywm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gtipyjudzk.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gtggrwmvyp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtapoixwln.html

PHP:  // 手写递归函数
来源：http://dali.zhengqikj.top/Article/details/gtvpdrunvy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtxtihylqw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtftjuwxll.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtziubxoyz.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtsfgacxyj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gtsbprerde.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtpvqwapuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtlnhpjuvy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gteiqsupti.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtveremzek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtpwgsvahl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtarqothlz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtedpidrlt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jyoumei.cn/Article/details/gtvoqrleqa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtbgyqoqlq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtravojfyn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfbymurrg.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gttpsvbyaa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtnvmboflb.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gtgqfwarmf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgfzy.top/Article/details/gtfwhppyua.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtqkirpjmg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gtsrljdyol.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtzyvsmvcj.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtdhdtyrmk.html

Go:   go f()
来源：http://dali.gzhubu.top/Article/details/gtuslozvdt.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqdsnzey.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtzmvodsjc.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtpxohuqlt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gtylvgjmyw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gthehjjsxz.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtvhpvckhv.html


<!-- 参考信息 -->