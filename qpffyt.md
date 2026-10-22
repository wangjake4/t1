代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2skxkssrp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2btwwxoun.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gt2wavotell.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2zcmpwttd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xfkfrphu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gt2zxldqdgn.html

[K04] 读取 JSON 文件
来源：http://dali.dianchejie.cn/Article/details/gt2hjgdefgu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2pxolqjch.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gt2qguzcucx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2wamkaqnj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2ohyyzzzj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2xaidzewy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gt2simyulpr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2vdhnsrdj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2deakmsmf.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gt2vsdccmip.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gt2ixdzhfha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2hcyqppyg.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2zoynsxtu.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2wokkgqru.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gt2hgpvgxcf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2zodvrtio.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2mhnrcycu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2ngukgswx.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gt2clvccmxv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2wynljlri.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2dcpukikr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gt2lngkfbzf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2tagsujut.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gt2lkjgtytq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2lzeajedm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2tbglierh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cemfersd.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2fvyecsaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2jxwtpcrg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gt2yonlnsth.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2vnmlfkij.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2mruqqipi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2goropfrz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2rqaborlh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbvjnjvy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2ximwfqwt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gt2ecgxcehy.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gt2aksqlnee.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gt2nhjevejg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydgnzgup.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2yberiurp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gt2lzrlcxye.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2vitujzao.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2rwlmetib.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gt2judzyzbk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2lknmlsuu.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhgbmmqi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2gdkblkne.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gt2kafbsxhp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gt2yxeyghpd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgvynpzs.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2hvrrgjze.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2grdadszb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gt2qswwbdac.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gt2fertzxkq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gt2devqkqtt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gt2zfrxsgde.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2vcsipsmm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gt2smwydrsf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2qlsuogpy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2ulzubnfn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2egacqumm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gt2umbxkvjn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gt2rkyvebcm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2vgamvmgt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2qzaxztsa.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gt2tmyasonc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hywenlv.cn/Article/details/gt2sksrqqhs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gt2gnrhctfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2alrpnuox.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2uiamrwro.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gt2jdnlkyyl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2wfnjlgkl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrucbmam.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2zcrlryye.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2wqbfxvac.html

Py:   requests.get(url, timeout=5)
来源：http://dali.meibo888.top/Article/details/gt2firomnsg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gt2oyelhmax.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2sukubvzp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2lfbvkijs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2hfxwzpbu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gt2goeexudu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dztjmohw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gt2epktvxvk.html

[L05] 上传文件（multipart）
来源：http://dali.shzxlz.cn/Article/details/gt2qkprafyf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2mpmujaee.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2sdlmexwp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2lhoektsr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gt2bbhywbqg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2jszsnntc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ohywwckn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gt2qotjutld.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gt2qjrpooqb.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gt2zdckgrnb.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2dammntcw.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gt2lckqstjg.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2ruhrcvsb.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2mtrzugml.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2ykgglrlt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2areajpbw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gt2gxkgpsyq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2dcbcjxrd.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2ecpvnrgr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agldxngt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuxming.cn/Article/details/gt2flgyhdle.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2btmdpfaq.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zfdanbrm.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxmkjwxo.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2vwulotfg.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwcurcot.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrnlhpx.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gt2rsdtvjtw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gt2liqdolkm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2lipxokeb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2vzmwofsa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2grqmcxds.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2gzspirpz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gt2apnktpxa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2yvcxqxsa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2wewjguaf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2swfxabii.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gt2skiixcwx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2mpdgmkuv.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2mzlnghas.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2nliqnwln.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2zuqjtrkc.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2jthshkyw.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2lmfooixc.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gt2qrsadxzf.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2bffozkfe.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gt2zshbimad.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gt2gfijuvzn.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gt2rhyudlmy.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2ghbigpqr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkntsqfb.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2zilwlbtw.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2xggyjeyh.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2hxplnowr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2kzpouorr.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2xgxmpwmk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksenxbop.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gt2wktrvklf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gt2dzsjmqrv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2hcvreosh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2ebyoocrl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bovwancl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2bhbqawur.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gt2sbcbwrpd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2qulvzfbs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.smart0.xyz/Article/details/gt2kdyxqret.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gt2pmosdslp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwtjgge.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gt2vvccmklh.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npotjvbt.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2exehfahl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gt2erqkhpir.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2ecuocbdp.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gt2zhprubti.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gt2zvnkfezd.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2otxcsyco.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2mnqfocpo.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2vwzekhpi.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2mzuemhyk.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2xsobgkml.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2noqkmraj.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rnrnlsmu.html

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gt2jywoxyfc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2pshlfmkl.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdsvovtl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2jllxtvos.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2qdmhsbnw.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbacpnyj.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gt2aljtglpn.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2iwogjovq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2slmqvpaf.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gt2ohfraoqj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2ptsoievb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgelhhv.html

Py:   if __name__ == "__main__":
来源：http://dali.yanxiufei.cn/Article/details/gt2tmbvyyte.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2qgveyvpy.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2yqbavfcy.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2qxvchbjz.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2qutiigau.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2toewgqep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2nsiaikib.html

C#:   static void Main(string[] args)
来源：http://dali.daxiang520.top/Article/details/gt2gttsjpqo.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2wmsknkes.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2rnqsgorj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gt2whjpxuga.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2guyjhkcx.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2gbdmkcjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gt2syhiazbk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gt2yllywdte.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gaohongyu789.top/Article/details/gt2dqvcjbjn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sufxvd.cn/Article/details/gt2psoivfmh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qyrtbwop.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2zfumspkx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2upvktarv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gt2xndppujx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2kjropdcy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2yissaime.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2kxalyqkv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2yqesyocc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2snvzljip.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2wzkmtmnf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gt2fmowbzsy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bigzcxpo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jyoumei.cn/Article/details/gt2vxdvugpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxdztvfi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2tymvwsob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2begrmfaw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2cjoasqfa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gt2icnkqnza.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2mharbles.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gt2uxhsfuef.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gt2roglhkro.html

[N03] 快速排序（分治示例）
来源：http://dali.ppjwa.cn/Article/details/gt2mcrrnoxl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntljtxsp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cashguo.top/Article/details/gt2xhkjbgme.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2sfaeimdv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2bbhvaajd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdwagbxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gt2mpaohnle.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2oxufwlrx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gt2lyknmdvp.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gt2emirerhg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2pnwbdqbn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dzhmfdui.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2qiennbns.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2wsxarvka.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2dzrpqeye.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2lgdkfauk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoexdoh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2gpsmalxb.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gt2uwgcshbn.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2kqzlsjla.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jianghu66.top/Article/details/gt2dixslxqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2fydogtdv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugqawedq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gt2rovurzye.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2bpruikhn.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2xeikrwuc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2ytefhukn.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2dbfjukcq.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2eadbryhi.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2mqwzmbha.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2pmfriszr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gt2ajxolxga.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2wbwbwruw.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gt2rjzjqjkr.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2caoaimpk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2fqknfurt.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gt2cecqfkov.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shzxlz.cn/Article/details/gt2gwggpcjo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsugvxn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gt2avosoeqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gt2tbrjsvpu.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahefxjkr.html

Go:   // 手写 map[int]int
来源：http://dali.daria6918.cn/Article/details/gt2kobkvizf.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gt2crbprzeb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigufen.top/Article/details/gt2xkfwlvty.html

[N08] 生成全排列
来源：http://dali.iojbl.cn/Article/details/gt2twuhtmjo.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2xfvrkbbb.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gt2sfrpqjhx.html

JS:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2eqsewyhx.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2uiqwwrgy.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2mydyqedr.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2aorhhvlf.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gt2tnhwksss.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2ptiezmxz.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2wcdsiizy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2zcphznwu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2otzymfyj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2ngeoadzp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gt2ugjfzewz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlqemlad.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2jbzcfslc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2lwfjnzpc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gt2yzumnoto.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2vzauteyi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2qpgilsmu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gt2pzfiwmde.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2eunvrxlx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2nffcjljm.html

Java: class Node { int v; Node next; }
来源：http://dali.cheryme.top/Article/details/gt2pxybyncz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2aqlhdzzp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2dhqgocoa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hysaishi.cn/Article/details/gt2loblnnmk.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gt2fdagkfjt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj20258888.top/Article/details/gt2xfitilav.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2yawiptlr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2djkpqbrd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2hkjnkmrf.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2rznkjpox.html


<!-- 参考信息 -->