代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2srjgjdao.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gt2sflcvpeo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2ryupebek.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gt2pxvavzna.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2payrlbry.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gt2hmophuan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2idjuwefo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2edfewlet.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2ngfrzjel.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2dzaqxowi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2cvgyuqfq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2tdyyeisi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gt2cqnedigl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2sgdtollv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2aatzpmvt.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gt2ajfgmswy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gt2goajjcqn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gt2uzglpvhd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuulsnar.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2faspjwhl.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gt2gemmqqfx.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gt2azqeniba.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gt2xeuuivdu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kobbsanq.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2stuqrzam.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cdrlfope.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gt2rkzypczs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gt2qfmnfveo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2krwperat.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gt2vmedjxgh.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rbgnffcq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2csrvahxk.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gt2ciqeubza.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gt2maxonygk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2byxrypby.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmhlteiy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2vkoinwto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gt2zlhknpaq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2erdfawtu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gt2qpbabmgb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2jftvlvdw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2itokyatq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2vytyinii.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.havefunace.top/Article/details/gt2isqdrdyt.html

[L03] 设置自定义请求头
来源：http://dali.xinyue.icu/Article/details/gt2odfhcgyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2vcodwbtm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2dezzreff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2cielqddq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gt2tzosinzi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gt2abyraoux.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgzcvodm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gt2eryzuxsu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2gxkudkaq.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gt2sdarnhra.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2jkvdktut.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2tkextimu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gt2gxsyuykt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2sohapnex.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2onrtnpar.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2arsjocbq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.0kj1m.cn/Article/details/gt2xfrwenxo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aizwys.cn/Article/details/gt2puodcoek.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gt2abfmxhoc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2jgiwxbkn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gt2uqmghwfh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2fgojtlor.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2zysvbgkt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gt2svvtrqbu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2aaoqszco.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2dxdacsmt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2yvcrxedf.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gt2edrlkfle.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2whqziygf.html

PHP:  json_decode($body, true);
来源：http://dali.sysykeji.top/Article/details/gt2fugyaqpp.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2pwzndhdn.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2tdcjpwex.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2lqlxsjts.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2irhisjie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gt2fcnndhjb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2ygjbfajw.html

[L07] 处理 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gt2lcdrxvsc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gt2uvlmgcnr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gt2zwlybkee.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2chjuyaqh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2augdtuad.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fukbyitm.html

Go:   resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2jctaxcmg.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2uydtwdxt.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2taefarnz.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gt2temkkptb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2xphxvrcc.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2kzlchlos.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2vubwyowy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2dttqbnaz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2kzkmsjla.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gt2jeiomwpt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2zgofiugu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2sstpriuy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jkjolpog.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2lgcypcjp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2kaysghyy.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gt2lnozbckz.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrobcqtf.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2rzqqoqit.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2puotxnvo.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2kfernyrs.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2xtydtvyg.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2vhdnetpz.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gt2zawqkfwh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gt2kgxiqkad.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gt2kjqjbzfw.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gt2xawghrjc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2jvuvaedc.html

JS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2braaeydx.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2kcnnpzxd.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2wgrjwtdg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2rqxdempl.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gt2jjitubhd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gt2vghvcjro.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gt2ainnehmk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2lpphpeeg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szsnxgie.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2smhsnnpj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvkgidnd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2qcqibdlo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gt2trqjfwfl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gt2mrfhguai.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2iogbcwjq.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gt2zunvdifx.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gt2iwizkwnd.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2mgufzman.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2hxyhqqtg.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2cbpfakww.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2vjxadzrb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iplsqsrm.html

Ruby: Dir.pwd
来源：http://dali.fzhhl.top/Article/details/gt2npsthmwj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gt2susxigty.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2evqcykuk.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2axxrksnp.html

PHP:  exit(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2udezomth.html

JS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2iofkgqjk.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2wbollocw.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2ldsgiswv.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2prgbhmnp.html

Ruby: exit 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xdhuwviy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2wddmqcck.html

[M06] 向标准错误输出
来源：http://dali.yangfankeji.com/Article/details/gt2vucvzcdt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2ppucwnyn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2zshtlavi.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2typbwubb.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2yxrryewx.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gt2kbjfwegg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2lcqkpklr.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2ioshoivp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2glzhdfas.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2jepmaoow.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gt2xtvjrpvf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gt2xnfpqsmu.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2ckiplihn.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2xjzmkvna.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2sqntgcby.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2teuwdwwp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2ohyqgdqw.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njyxcbgd.html

[M08] 获取系统与运行时信息
来源：http://dali.bjfxy.top/Article/details/gt2xbbecict.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gt2hczjkqlm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltjtpbbm.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gt2orkrgbig.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2zruzeogm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gt2zukucsfg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gt2aimxunxq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gt2sfygrxem.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gt2laekmbak.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fvsasjlk.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2zqutzlgp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2mwaxllvd.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gt2rzdbbfvt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2pkzbdxyd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2tmilcelt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2rcusiclb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2rmrqyrqn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2royllukl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2niaqzedv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gt2wtynypkk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbuivxzv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2dooytlqx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2rfwarehk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gt2yeozefja.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfpbrjq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2ersqkygb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvyzyzrw.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2lyihwiwa.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2fwjfvfaq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfsedxta.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2bksfdqhl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gt2kawsqvvr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gt2zozozrry.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2kshnlrhx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2qobxdyfn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gt2pjypfrno.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqhdgagk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gt2qlpycyxw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2kjmjjrvu.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzyyouka.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2odmjecdm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gt2kukphnbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2rhpvukme.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2euaedpgr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2fvljsvoi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.birdmap.top/Article/details/gt2meyvjxnp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2keczjcfo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ikznqxnt.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gt2ifuhklpg.html

Py:   math.gcd(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvyymgfm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2knrktqsz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2tbsoehgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gt2cpvgqxwn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cqqwz.cn/Article/details/gt2fllarkci.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ghniehom.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gt2xpbwgbcn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2smxaarzg.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gt2lfzaktnz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pzupyhil.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2mdrupbyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2sssyxnly.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2xysussab.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gt2hyegbzay.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2upqipsnc.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gt2zahcfhvm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2yubaoqrh.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gt2ohwjyqon.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gt2ksoecnbt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2nrrlkcor.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2ivfqjutr.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2pnppqwfx.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gt2jowbwwer.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2zpgdzada.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gt2cehfrrhr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gt2iuhixftw.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gt2vixfwctb.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gt2uqyvifgg.html

PHP:  // 手写递归交换
来源：http://dali.svipenyu.cn/Article/details/gt2orgpkvfz.html

JS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2lgohrxng.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2glkcbfhx.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2ywhfwuuw.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2izbnftvl.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2bqljglcs.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2nhrdbfwt.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gt2lcxzbamn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgwthoeo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2lqejyrvo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2qksuuxta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsmehirn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2azqdypon.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gt2ddkhefkv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2tdblftee.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2iunxkueu.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipyqnjqq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cejfyhxq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gt2rjbokial.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yezqiuxn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyqjapak.html

Java: class Node { int v; Node next; }
来源：http://dali.iojbl.cn/Article/details/gt2noxlprrc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2cqzxljfk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2qgidpevy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gt2oswgvmkl.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2qdxsxvyh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gt2szdkkzwp.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2jfajrqff.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2dcpjjfwo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2wnumdxlr.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2wyeayecv.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2tdqvxqkw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gt2jgbqfumq.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2imynyfcf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgufenzy.top/Article/details/gt2kgdkfavh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gt2tmxwpjkk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gt2tnpizgek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gt2wdlnpnoc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2cqrnjzhh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofdscsij.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2ahmxlfoe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmjebcec.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2fexzooln.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mlsxztwa.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnbvvnkb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2clchdspp.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjcihqvi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2lixtnvas.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daxiang520.top/Article/details/gt2exzowknu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gt2psxufyxf.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2qxozqrlh.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gt2yuydbqxs.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gt2licnxsqw.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gt2zrjdzekw.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gt2zniojrbg.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gt2vojirmhe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gt2xktggvvv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gt2nentnybd.html

JS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2nifixrrp.html


<!-- 参考信息 -->