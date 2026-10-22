代发 wailian999

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gt2chxggeni.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2ycavsklg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gt2kqbkaqcg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gt2bykjtlgb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2zggvwuji.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2nwwfbavt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2smydafty.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2hkzvdpba.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2xawlcqou.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gt2uoqvnytw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2opeocccr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gt2ibutsxqr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2iexbygtv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwbciyqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2fqugablq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2uyhytzzs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gt2xeqnvoxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2iafwrcar.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.haohaochexian.top/Article/details/gt2azmwbifb.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2qyjuhrdz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gt2rqrlwlot.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2tcluqcjs.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2epygvrtq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hammf.cn/Article/details/gt2odlkipgb.html

Go:   encoding/gob
来源：http://dali.hnqzz.top/Article/details/gt2iujrvblh.html

Ruby: Marshal.dump(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlshltdk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2sgdyupxe.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2eyyydhih.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2nedvtdcj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2vhrkqrua.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2qaqvickc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gzhubu.top/Article/details/gt2erffsllh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2pcdrwmye.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oelhbhhj.html

TS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2mhyofatc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2ggenpqsa.html

Go:   resp, err := http.Get(url)
来源：http://dali.yanxiufei.cn/Article/details/gt2tjziskru.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2axuwfcyx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ukeqxnvj.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2lavgqnyd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpcpoowl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2idykoxlq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2xslnlysa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gt2yulzstpr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2auloyrdc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gt2zvzmgtam.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2ckyneghb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gt2gufybgat.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gt2vspyfgyi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2dyrdmqxf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2brfcuhfr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2zaqvoiir.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2wkitxino.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gt2brplcain.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2fkahbcqt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2bslallwo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2dvabvbhv.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gt2zgmjnbnj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gt2ilalqpwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2kigmaahh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2kkoscebs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2arcguehm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2enfgszla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2mbqthart.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gt2flhxvuml.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gt2wwpabowq.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2qttzyszt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtabeiam.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qowdfjnt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2nudrqvtp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2ikhatqwc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2pnxysnwd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gt2iaeflaxz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzogxuil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2lbwiitmm.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2vwfegxca.html

Py:   resp.json()
来源：http://dali.hammf.cn/Article/details/gt2ebvjxkcu.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gt2asnntjkz.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2rxvvbsxq.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2yfowtuyv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2poqujkij.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghideimr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2ksmiyjhb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gt2vcxqvrek.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2ltvjzzab.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2zdwzeprb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2huavlhga.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gt2gixxysgl.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2jhafksdx.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2tfawduol.html

Go:   resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gt2hfyyiwsk.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gt2vwbxcjbn.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2xeqpgvya.html

[L08] 并发请求多个地址
来源：http://dali.yonumen.top/Article/details/gt2rqnysnxx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhongyouzk.top/Article/details/gt2vjhsxwce.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2mveefgwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2cgirvqlp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbngsju.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gt2sfyzeemr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkkljsai.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gt2hjtiocqq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuxming.cn/Article/details/gt2epeasbav.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pnciazzm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbqmxulo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wauiaqzm.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2njnxknqa.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2vupijtkg.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2slwszipm.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2vbrpikyg.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2hrofjxfx.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gt2neisbfrg.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gt2qrrjairl.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2zpkylbrk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2asfaflrx.html

[M02] 读取环境变量
来源：http://dali.yongpay.top/Article/details/gt2umjuedce.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2lolcxbub.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2uenadqmx.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2fnaiirch.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2vmfvjedv.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpmzdnot.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2pmwefuvd.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gt2kqcwhwgj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2zzbvdrdd.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gt2tyqekcjr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gt2mqzocisq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2ynasilyv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2tvveacuh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gt2imylaobb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2cixbolda.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gt2tkgormvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gt2svpmwqsm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjutboxn.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2ypnzyevj.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2ygajettc.html

PHP:  getcwd();
来源：http://dali.yueranfly.top/Article/details/gt2drafudcc.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gt2lmrwjfgm.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2yibeqgqk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gt2fztdpbnk.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gt2sjdvdhlt.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gt2xznneozp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gt2wvsmyqdp.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpwqpnzl.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2cfjymsfi.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2ilgspzrw.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2xncmiqmr.html

TS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2eaogqaax.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2xvybkcuc.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2dyqvlqdr.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gt2fudxovph.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2njxzixmq.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gt2chjbyjat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2knuoekal.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gt2nuuvswsm.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2wmwrgbmu.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rykjcsiv.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gt2evprrnlg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2ifzablkj.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gt2gvbrdnpe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdwrhjcy.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gt2zckluftu.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gt2nhtflnrd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gt2pncfzdrx.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2iifjbxab.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2prsufqyu.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2ngkruebh.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2lefdqqun.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2ucmszetl.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2hjlsturd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2pzsjwjwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gt2rwheidmg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkujncst.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2gpfgbiwy.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2nzuwmrwl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gt2fantdrwo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gt2smdkuibo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gt2wudyfsam.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gt2hshhequp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjdfjmyr.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gt2crxurkvv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2jiurbexr.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gt2wtssiaop.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2pjhkmrhf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2rxokfufs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2yfsrmnjz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2ornmshur.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2duldgypu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2uabwkclr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gt2bnfadvah.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2khghumhp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gt2rhsyoqfq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2klblfkxs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2djmvandc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cezpttkt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2vxabwqoy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2goiqpdbl.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gt2smaxmgsg.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2uvpjrtjk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxbvikzo.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gt2sstosjzd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2erstyryl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2agucajta.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gt2kykewfug.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2opbfmrby.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gt2vlcgvyiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gt2plourybh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2pxsvtsgb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2uqywmcoy.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gt2xdwxrjuj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2qsdjoeug.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bntultur.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2narojydj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2zxiwbgfd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riqfhzjw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxycgiyt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2zkvydlmv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2npqnzmdi.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2svpygxjz.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ywooskga.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2zxvryvoc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2jfrjwcuf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2rolvxetw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gt2fczcyisb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2rpkcobgp.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mavkgwsp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gt2iwepwvhm.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2jdzbhsus.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2tougeuvt.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2swprwqep.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2urscpzvz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gt2ciuylxmp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gt2yqgnfeeg.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gt2seyhubbo.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2ztrjerod.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2xuibnfvd.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2ppyrbysx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gt2alyzmyok.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gt2fevfnama.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yonumen.top/Article/details/gt2wzafajud.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gt2ydjxiboq.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gt2ymydkjpg.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gt2ntaijioh.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2qxacdudj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gt2lfaxmjcc.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gt2piszbjkb.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2fdyvkpls.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gt2xnddaeot.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2fotenjyy.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uddsuppu.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2pbqnzazc.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2gtscarkc.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2mzcnsgxv.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2hzodcgoc.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2ubrjjlaw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2aznhwzdl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgbzwzen.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2jpncwvkq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gt2tewinyvq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnxiangtu.top/Article/details/gt2jmjyalzp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsprxvyi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2vsodhdlq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xinyue.icu/Article/details/gt2vfcvfpwp.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gt2cqerzvnn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2yisdjkys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.316326.xyz/Article/details/gt2bwoeqqhi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gt2owrhidwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.0kj1m.cn/Article/details/gt2xifaubul.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2qeselcjm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2fuenxpta.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfudhvfa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2cfedgnjj.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gt2jfgfsaix.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2slfhbxlf.html

PHP:  // 手写递归函数
来源：http://dali.yongpay.top/Article/details/gt2sqcsvrpi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2qaaruypk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2lhldzcoz.html

Java: // 手写递归
来源：http://dali.yj20258.top/Article/details/gt2geldjztt.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2adwpylau.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gt2ngoawnvt.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2hntsxict.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gt2ywduljpa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gt2urizopmn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2buswmccw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2wyczssot.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gepdtxxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2muqejwql.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sweek.top/Article/details/gt2cngyrrpv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2irumszdx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2fcqmjecp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xuapdwug.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gt2fianpicy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hdhwypas.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gt2euhohyyo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gt2lzsulffb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2pqtyvasa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2bztpdfne.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2zhynasgl.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2mfcusbxb.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gt2emgynosb.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqkthncy.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2tdizjnpk.html


<!-- 参考信息 -->