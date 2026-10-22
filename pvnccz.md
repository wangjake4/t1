代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtzttkwugv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtotrckzil.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtrrnbaxsu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtfppivqrq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gtczevkkwx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtvbogpwtm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtcpibcgrh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtgielpmjr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtngsluqko.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtexhahcck.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtratgooqg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.redwolf501.top/Article/details/gthrcdkpxu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtwyqcbugp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtdoxnekor.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gteduavfle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtwzqmvgit.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdmthsax.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtnoeuarvq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtfducygqw.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwhjimbmi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazdschmk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmoxmmko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtavtpnzsa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtheoubffb.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtiwpumesy.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtfhhavmhg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtjhziklqd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxputtxgf.html

L. 网络请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyndxujeu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqycffrfj.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gtkysdlhok.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwfmxea.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtwkendnui.html

JS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gtqqtablht.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtituccxhh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtvfrkupow.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtewdgzrnk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtspbhukjl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.haohaochexian.top/Article/details/gtmxgmkrop.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtuzjdydzu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtngxfzznl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtyhtujlbg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtregnxjhw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gthquldtnl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gthkzuoizd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtdhghhqtb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gttmigiaiz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gtumhhxaef.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtlzutrfdf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gthztjypfa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtnjrvwhtl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtnohjydym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtphikjgyd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtpdmkcwvq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyqhrxla.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtotgfkhns.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtvwyjybib.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtarbrsjjm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aizwys.cn/Article/details/gtwmgovmcq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtbmnnrqmp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtjexdwbfx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtqxdsapli.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlrjfylf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtkvlikhki.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtujhbppmf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtplvineqk.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gtmbhuoqzo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtxmjwpaev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtefbrvcxm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtwkudmaqz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gteedgbwaa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtzavknuny.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gtmwrwjggm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuanzhike.top/Article/details/gtdyjjrfwi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gtuccdyqco.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtpyjpsvji.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtpjibhscn.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtzkaecfgn.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtpejlvedm.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtorkdieei.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtunyojzkg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelevhzfs.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gtlrbilvck.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtkbpjxrje.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtfmodxyvj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtjpnhgpvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtjjorfdcl.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtgxsjaypu.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gtezbdgryr.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtvsajkytm.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtworkjtxc.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gtuhnievnh.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gthpvuygxn.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtzvpbyagz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebvjdkek.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtchzqusuu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlkvrogn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtmvjvxqta.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtmjdxjdus.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaothtnnl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtehecymbq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtknjtwtff.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtpwucgrcu.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtdaezlmak.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvylkcsyw.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtozxhqxbi.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtbnmirqik.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtleqjvusx.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtqhynmmhc.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtbkecffwi.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtxohrfqht.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gtmzcttifs.html

Ruby: ARGV
来源：http://dali.zhengqikj.top/Article/details/gtqwfbmnmj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtxhcnedju.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtrkzcogji.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtrzgwawds.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtsjcdcyzf.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtfvyueusg.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtgtimqjmk.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxwyryhz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtomgchcdq.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtnqitezoo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gtabmvdbzl.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtccbutelq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtdyfarwqb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtrashtihv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiloahhj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtpenkhnok.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gthvdqhboe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gtultgzjcy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzmjhmbj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtgzisxpkm.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtfmmkgcjm.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gtpnptjjvh.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtbyharrlk.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gttnodfuph.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gthiufyrlu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.0kj1m.cn/Article/details/gtrxqdwdhc.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtvcjtczul.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gttyzcftoc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gthbhpsujf.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtiltzvjsu.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtsmnjxyoi.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfrzlvma.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtmxonpfjf.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfgjadizm.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcaiogqk.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxaxpxxj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtwplgwduc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtvqaasljl.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtqkigcxal.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtesbzgsmy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gteavqogbu.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtzwbrerdb.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtfxobkyvs.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtuknukjkl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtoobvcjlo.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtgjsbcuwg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hongshengwenyu.top/Article/details/gthfjpyhjk.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtnxavfchg.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtgslcuxon.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtrmscgswj.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtmbminqyc.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtxohfjoqp.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtfzggumla.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gtmklwdlts.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtpdoconnn.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtywqniqfi.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtlxfhsgbi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtdndofyxw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtvpwwcjve.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtgrlqrxkz.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtheqqwlkw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtchkjdvqb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtyjmstvoi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtrqibirgp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yvedp.cn/Article/details/gttkywntay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtazouoswb.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtfsrecgkb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzfycwcmx.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtylwqzjon.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gturldlutm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtnlqttmpu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gtzmsmzxev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtaaerppmd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gttjiklkwc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtikjqrnef.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtxbarabjq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtnrigtsjj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtqindgdba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtvqidvnkt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtyyrjeqkq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtrenrqtaj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtqungahjc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtvybepyig.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gtxjiwhoet.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtygkngstc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtwheqrkgn.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtrbcitixx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtabrgunxs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtjemcmrsx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gttebdqbnf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtbqcqtwvf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlqkbftp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gtjexjulmp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtupsiqavc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtaysgstud.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtdwdmutuw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtvxznkjrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gttljhmpxk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtjzwivohx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtjtwjfscu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtufpggyrq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtlmfytjuc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqufmsprj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtdtsmjowy.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwljtjpoi.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtgfbjtjtz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ybcxt.top/Article/details/gtqspzzjec.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gttbomgmhl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtvphirwiq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gthcevakxs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtldeeoewb.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gtvjfefvbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gtueslqsxw.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtudtghkii.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gtsrcxhmir.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtorttrixq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtgrswckyt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtszcpziwx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtdvhcvgtg.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gteirugfnt.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gtvqgdatwb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtarjqnknh.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtevjidttk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtcgraizcn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtbwwjscoq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuxming.cn/Article/details/gthgqioajt.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtxhvambjr.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtrovijbav.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtqmdyhkoi.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtnysocasf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtzqtuernd.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gttbhmfmjq.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gtihilsdih.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gttkoeuzmz.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtymzvdyxb.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtprgdrsra.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gturryficq.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtwqtfvvku.html

Ruby: arr.permutation.to_a
来源：http://dali.9152youxi.cn/Article/details/gtksrxmpth.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtizhkbaap.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtetrgcoct.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnqzz.top/Article/details/gtfguivghz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gthhhhccfk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gthwhmdxgr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtpolnrzoc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtwwbyvhiq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtvslxvrsn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtsgrstqtn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gthiyxdzra.html

[N10] 链表节点定义
来源：http://dali.sxryk.cn/Article/details/gtoqqmqpfx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtmyihauzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtncjhldxl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gtfzkmheha.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtcavrjkhh.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtvzdtiqty.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtqfjpynwe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtufoiatui.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yangfankeji.com/Article/details/gttejqawah.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtdibdmpje.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtvylexzyz.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtqibryswe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfxlwfdu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtiesjjysj.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtvuptuarg.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtrqscotsj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gtyqefkthn.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtpshtbteb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.0kj1m.cn/Article/details/gtnzzxxxbn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtetkstalx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtmkzemjml.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtncffevtr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtqeljerdm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtzvewgwmo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fzhhl.top/Article/details/gtikzifufc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guannengcc.top/Article/details/gtktijnret.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtdzvavudj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtskjwvrkh.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gtjtszymdo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtwqdrndjq.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtypzvsehe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtusfxvjve.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkapbwgg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtjlciscli.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtqtvbolgd.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtwsqsrxnc.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtmpirmrgt.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gtrpaemiip.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtntbvhusv.html


<!-- 参考信息 -->