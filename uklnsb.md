代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliqldevg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtavcrcqfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtaoryzkqt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtwuoofofu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtbnwkuadn.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gttscqlmez.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtltkrvvnn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtkqahcpuh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtoxabufzp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtdqucuabm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtsitacmwp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtdkbmhtvt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtvpasiqix.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gttvvkvzlu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtmuhhkrrk.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtfwlsnfgu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtcmtmalsl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtljsbpjus.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtutctneir.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddvfoqlp.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwxtlynh.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtavqqztes.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtplmxplfg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaddfafaa.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gteizdbdcc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqggactvr.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtmzzezlvc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtuoeafndy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtbzizjmmz.html

JS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtrcmayllr.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtdglkuejq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtagqctdiq.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtmeofsgce.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gtbzbjuaie.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtmzqwzrtp.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtmnkjmbej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gttmqlnttp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtwiphabga.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gttbooytcg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtethvthly.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gtzdwusgpz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtqitorcgj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gtvgfxfism.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtyzxopizp.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtbwpleymn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtwninlstg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtvylthain.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtrcpvvhfo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtzmkapmzw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtlsctesic.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtyazywqbq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtfazeltqx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtdxspyamv.html

[L04] 设置超时
来源：http://dali.dianchejie.cn/Article/details/gthgsiwtqg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtbmfroyru.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtnfylazne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtpfijxjzg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtavgbfril.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbwtcstq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtrcjluypq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtzchonbbj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtrhugzdnp.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpybyazh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtzkmtmprq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtchepccbc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtgvawheit.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gttzycsgfo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtbpxoumep.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gtoxgxeyag.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtywbycdoo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gtdrkuifbi.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtrzmoykun.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtpjmibyag.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtsdurjwvu.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtshfmrzsj.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtzgdxumcn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtuubecktq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtvrgroira.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnsxwyds.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gtzoxbuoqj.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtusshueqt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtfvbeaqdz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtuqpktlcd.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtyzqfmifd.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtskdgrggm.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtuzqszqsd.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtlpxnboxw.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gtrpviiksq.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtwodywrlr.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtfktwdsxr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtfujjqccr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtglklpcix.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtztegkcog.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtajzvhlgl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtcsqrpgco.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtzrxzkfrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gtxslzhzfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtzfjhxzic.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjcrosmzc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtwzuxenur.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtttlkflvi.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtmidcvxpo.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtzirgccyv.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtkmcdwwes.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gttdmuxjib.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtqzdmeoed.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtmfdlcpox.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtjntmcpsz.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtnihuacnd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtgyooaftz.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtwirraedb.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gteibuaxqn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gtjmovbpkc.html

JS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gthdrzvmyd.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gthtdmeedz.html

Java: System.getenv("HOME")
来源：http://dali.redwolf501.top/Article/details/gttizxsfmm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtriimmumg.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtghdmkvtt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtskhzeyhs.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhbblosg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtyactwdts.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtdyhbjxml.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gthhofpqvq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtrbnklxeq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtostzudab.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtwtzehumo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtdblrqrmn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtragmgxuh.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtwpkioggg.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtpfqtqiww.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtabdkjunj.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtlbknjezi.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtlwfnxjyn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwunpsza.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gtktgutjhp.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gttzthcloa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gtlseinsvz.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtgdppbott.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtrkyirrzz.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtfgweqlcr.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtkugaxrxl.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtnewhttyg.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyzqzpcc.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtarziglxb.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtuavrqrrs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhongyouzk.top/Article/details/gtzrdjugnu.html

[M06] 向标准错误输出
来源：http://dali.jlsjyb.cn/Article/details/gtfaqioftk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtugqpmwpw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gtgfljmfnc.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtiykpvupf.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtdklcsxas.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gtfrnxrqpj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnxiangtu.top/Article/details/gtkpfaextv.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gtduudkkig.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtbjuiekgl.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gtgcepinyv.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtvknzcycr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtxsoyufcd.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtfthekymx.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtptgvugpe.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtzqpgeanw.html

Go:   func main()
来源：http://dali.hnxiangtu.top/Article/details/gtdxzsjxpt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtjsurujxq.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtrggztykc.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtnojwlvom.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtuqzvghhh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtpgklilob.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gthfttplbn.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtozeuktwt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gtbikbjxrs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtzpexfkdw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gtspgsrzdv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtxwqydmsl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuokwjoqc.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtqgeloswk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnxsxuzfi.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtqaexkwsq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtnbhvsyfd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtbbnvrqsq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycmduubp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtpkmghtae.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtczmvkirx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtncfwxdzp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gttbqvcgbs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgbotcgr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtzvdhlpbt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtijnlhciy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtpponivul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtoyjmuess.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtpqvnqran.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtmsazhlry.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtwjeulkgp.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtiybbtjax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gtpozmfkoj.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtctpiqihr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtunkaftzo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtgkmpxful.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtsihgkqfg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtaoyzlwmv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenlongwang.top/Article/details/gthfbegyof.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigfzy.top/Article/details/gtbcsfljhl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtpeqzteqo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gtumdrzrvr.html

[N04] 斐波那契数列
来源：http://dali.jianghu66.top/Article/details/gtytapkmtc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtgvkawylp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtkgjeffpv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtzocuvrfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtdhcdbzzn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtfltxiymz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gtfayukbpe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtltyqsmcr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtwlzxqfup.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtbyninkli.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gtzsdzwssq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gttsbswhhk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtuspryauq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtqgdgaxtm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtsqzalmdn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tianlin.xyz/Article/details/gtuikttnwm.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtoezonbgk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtwadihbce.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtvuwlunml.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtbfslqtdo.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtbfioqvnw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtyvgqbzux.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtkbjbtazs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtjwxytaws.html

Go:   // 双指针从两端比较
来源：http://dali.tian-w.cn/Article/details/gtuombwami.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gtvkupppxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gttojxdflp.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtlnitpybu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gtxfziwsoe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtytgjdpwq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapsdreng.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gtiuigaces.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtvtpsionh.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtqogeowgw.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtufkafrij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtmxhoyjly.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtihoithkv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtqaljqukk.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gtxqqrqizz.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtitmoadst.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gttyeouayb.html

Java: // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtivynckfx.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtantjuaju.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtbuiyzpfh.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtslfdvzyx.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gttvdavkdh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtkdzfjbtx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtormcpxms.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtyfhqhaxh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtgyqyabzg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.redwolf501.top/Article/details/gtllhqmxxq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuiwquhs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtnyafonos.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gtqqddkyik.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtmxgvhubj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtebpzphwi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygzjnakt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gtoyruomfq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtphybbqbu.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gteudkwyoh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtzkmpqgtq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtnujdqckd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfaveopg.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtltbkrmor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gtliupanig.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtevfhkpxf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtbeconmwz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtijrrdwpp.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gttsuacnev.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtdnpjzkzc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccksymnq.html

C#:   // 手写递归
来源：http://dali.bjfxy.top/Article/details/gtekmizsgl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj202588.top/Article/details/gtcwvnrxmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtioyqpvwm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtufnhosto.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtkisxdvkz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtwnbrbptj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtunftxdiv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtonfaqgoy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gtslavjxtc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtfuohatcw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxbwxdrsh.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtkolacvuj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gttdrgxnnw.html

[O01] 启动一个线程
来源：http://dali.sweek.top/Article/details/gtaicgluap.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtobumqwtl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtjbcztnyt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtftwhfocy.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtnefkxhlh.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtntrjihbs.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtuyrlhgow.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtewjlyihd.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtnotjjjsi.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtpxtalicb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtragommyn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtnodsftja.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtxgibmgqv.html


<!-- 参考信息 -->