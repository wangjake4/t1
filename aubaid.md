代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2zshdsamc.html

[K07] 进制转换
来源：http://dali.zhixingplan.top/Article/details/gt2jhmcbczg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2psmpluen.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gt2ucrckuzf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2tdqcnjdx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2slpsmapr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2dpnjqdts.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gt2qzdxuywq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ivvv.top/Article/details/gt2prvatnhx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2gqspgmvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2khrkftyi.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2bumuskpn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gt2nczqaqtu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2zupsogly.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2ehypvtdg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2kaeddkpf.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2wclvojgu.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangdashe.top/Article/details/gt2clgonhmf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2yppxewkr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2bhjubesq.html

L. 网络请求
来源：http://dali.nanxinkj.top/Article/details/gt2waxzjbqg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2llgbmdox.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gt2wyvncfnn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2acdhbadu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gt2wxzvjcjo.html

JS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2nzkunrmf.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlganxcu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gt2wvvyffok.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gt2yfqcbcjj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2xxknspiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2csibhvxt.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2tvavyhzb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2bosqcbzt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gt2zydrdjbh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gt2zrotdjee.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2fvebgwis.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zumafcrr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgrgrpjb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2twdwenlz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gt2zmatnwvk.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gt2nywnliql.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.andypj.xyz/Article/details/gt2tyrcjagd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2njbedyed.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exiqyipk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2zostvbur.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2lblhbgfs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2nuvkbhoz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gt2iuemhdto.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2mluxhgjq.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gt2vgchqhhd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhrllit.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2ixzqlypx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2dtjijbsu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gt2idagqqbs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ppjwa.cn/Article/details/gt2ycpgrclq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gt2rjxnnbxf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2xjglpqly.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gt2jtijltkz.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2rbadlpss.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gt2jhxidcbn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wxwywvek.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2odjluuxc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2nlmoyipg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2ncpolasd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2scnajnjw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rudpoiaj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2kmssbclq.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2navgclly.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gt2ngabdnga.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2xwqdtzts.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2sfmhdkqy.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2jeqsojqp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2rxqlbdbm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gt2zwkztcab.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2qawxhilr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gt2efxxyazf.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gt2bltcqjqw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddrxgnai.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2whyekkub.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufqgxzcf.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2igzyqcly.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2lxurtqox.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2jsnudqgf.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2wnnsuvdw.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gt2dgdlrrsx.html

[L08] 并发请求多个地址
来源：http://dali.yj20258888.top/Article/details/gt2agvxfphy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2ravvcpcw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gt2ysoisfbx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2xdpffjje.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2meelnzak.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2vfwkdktv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2subluzpl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2bptharej.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2uisbcntv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2duhmjpkk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gt2kvbjujfm.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2qfqfmism.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2oepmoywj.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2dyhnanng.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpugdork.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcxyqfwf.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gt2czqtgucg.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2zbyownwz.html

Go:   os.Args[1:]
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjuunrbj.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gt2jvwozaqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2whjhixzh.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gt2ryjgnekc.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2lnkwmkov.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gt2lxtqrlgi.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2noqrupej.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tyibyhnx.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2kuidrcfq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2oeweiqpn.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2ttvoixvk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsmcpuie.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2axxrfbgi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2uxfxsiij.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gt2hhsqfpzo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2tesxpbcc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gt2kpbswrww.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2hckuxuuv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2snprzaqj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2cqyertbb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gt2tblytixq.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2fmdwyemj.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gt2xcbeuhbp.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2tffhgxgs.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2phmwlnsu.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2egyfoaxt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcojngue.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrgejvbk.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2rrcicqxv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2wubbbyug.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2clxhkqxx.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2fjyqjvpe.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjmnaiss.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2sqwoxokk.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2diybtimi.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdrfnmzk.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2lqgbjqra.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gt2grthxchl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gt2nbdeyttu.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gt2zcrdpsoj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rixrsqlj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhvkqnqc.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2kwszfrli.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2dcaknbsw.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxmzuiqd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zjjhvnmj.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2ojdkzski.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2slinkawf.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gt2vhodbxiq.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gt2qnznfmzn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjqdurem.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2kwhllngd.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gt2biosgree.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2nysffhke.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gt2dkbsinhm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2olnsnloa.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2utmdeypt.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gt2izwkjhko.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2drfldrje.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2ttuxwixa.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2wbnsllxo.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhsujmfz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2fqowbmjp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2ryirchxs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shzxlz.cn/Article/details/gt2chagxmlm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2rbwfrgrb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkzfaamd.html

N. 数据结构与算法
来源：http://dali.gaohongyu789.top/Article/details/gt2sntqqtaf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ehxesruu.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2vkoycdcu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2xrhnnxor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxclmjy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2ajlrbhcd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2obxrxoer.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2hdfojkyb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2bzeqcdsa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2kszbebam.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2ojvqmewp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gt2azhyidbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gt2mefhwhkk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2maxuepuk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2shfmfoqr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2imilldeb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gt2ayosrfpn.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpxshras.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2rtzyebew.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gt2melpygsj.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2xuvqcyjr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gt2kxidutrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gt2xnvidpct.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2kfocprmd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqzatwba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gt2xjinrpqw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2viwfvyds.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eskotdee.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctlnqflb.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gt2rdfepiqq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2bdxiarvv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2lsebdues.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2qlzgmlxf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2mpnjucsw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2reeyeizt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gt2flmajavs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcakbnvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2eipmmdof.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gt2mzwlksqf.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqdvmhfx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2rrxriffy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2wxkqrmyn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvyxdsvb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2slxgtvrg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2xwfbcuwm.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2paihsnxr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gt2wgomyyew.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2khpialkj.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2npjirvdp.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2srvytwso.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gt2zoxoqwdt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2tnyofkch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmxqhyxt.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2vegezkcz.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2rojippbb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2bgssgunu.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gt2kiprrsri.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2qhvxkxmf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gt2hoyzyalr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gt2pbouqiih.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2hjefzqle.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2girlssuy.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gt2hcxysdkc.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gt2zjqxukus.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2smaessky.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gt2uzamtavq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2yhmlfden.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gt2pjlgngru.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2rmjarrmh.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2uxntgmqe.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyzlxoyi.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2irhsxoyx.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gt2prdpnnoz.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2vrfounsi.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2ovsrfpgv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2yvjejzhh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2aejrimce.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2lmnpfxum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gt2ukzjcsyr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2vjlrvcjt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2rwvibdif.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2kfnzkcum.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gt2nmexbrfj.html

[N10] 链表节点定义
来源：http://dali.jianghu66.top/Article/details/gt2tvhxokgk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxxtrags.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2ykldzkqj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2lwjfbofj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2dmqjgmnx.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2lnswhohr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2lnasdguo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fboxowvr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fzhhl.top/Article/details/gt2tkhvlwec.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olmcwpkb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gt2iynqdubs.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gt2ewxpphjx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tian-w.cn/Article/details/gt2cqejoiif.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2rbgqqhaq.html

Java: // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2soazhydm.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2vtktpysp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gt2wkzsjowq.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2boqjeanh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxslzbyx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gt2mrhhgpfy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekswudem.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2dnmsawim.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2jpobkkpb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2kbthtugg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zazwniaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffjhlrzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gt2scsnyznh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wxdxjmjy.html

O. 并发与异步
来源：http://dali.gogol.net.cn/Article/details/gt2rihwhyfm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2uhvsnsqd.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gt2sexapjrp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2ndaawdlw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gt2agrqckxh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2gnxaevcq.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2uldzdfne.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gt2bkubimng.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gt2wiqcbfde.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gt2faromnoi.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gt2hgrzxcpp.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gt2ltgchyjq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sxryk.cn/Article/details/gt2qydtmzie.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2ugsurmhw.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gt2aelljimm.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2imyrocqz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhixingplan.top/Article/details/gt2lguvwdcy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gt2bwdvdfrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gt2kcwgygku.html


<!-- 参考信息 -->