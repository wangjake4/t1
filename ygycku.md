代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2chjgnhlm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2ujkfceim.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2ezwwuxix.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2nlohifwo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gt2opjnbfzt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gt2bxldwfgi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gt2mgwjyjud.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gt2xeimpfyu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2qtkdrwaq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2bkogbujg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2pkjwpgoq.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gt2tgxuhegj.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gt2egngfdqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2jcfodfdg.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2ttjxfhgx.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2hyreljev.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxbnmpzd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daria6918.cn/Article/details/gt2sczgdmjr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gt2retdtvfj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gt2cmqafaut.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gt2nnouescd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kwepbpgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sxryk.cn/Article/details/gt2hbfuposv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gt2tzoonxcu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fslhnzji.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2mbgwzplo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2trkkyaed.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlgbwfyb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2lojffyqj.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gt2xmnxleau.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2epfpkbvk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2acfwburt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2owwqwily.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2rivettpx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2ihrakevf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gt2drporkow.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2eifdvfzx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2mvtapfbs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.smart0.xyz/Article/details/gt2utubwzgl.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2zwoypeap.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gt2cgexqueg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2glekvgkp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2mrucdaax.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gt2gjxjxlvt.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2bjcmocxd.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2dvhaqppo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2mkybhqqw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkxaogyj.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2zeihsrtm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2afrvtzwv.html

[L01] 发送 GET 请求
来源：http://dali.c1oappe.top/Article/details/gt2thvjehcj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2xjnoypry.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gt2yofmytcz.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gt2ghswahqr.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2yomjgepk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2hozljhio.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2etjxtzjd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2whhcnswy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2tpdooxpt.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2wccpvjty.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2ukgnsaww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwcprplg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2qekobhfs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2otkiutei.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecscnskw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gt2qqxbprwj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djxjgeda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2kuklbckk.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gt2ehfzpsub.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gt2hrzmyjvl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2hidlavgc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2kqvfdjbi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2xbsnaquy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gt2lpeeoxby.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2djhejroq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2jkcpyvgw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2erxboylr.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftohbide.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2atoolpih.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zycfv.cn/Article/details/gt2pmgpmges.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2ninveyig.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2pnuelwem.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gt2lwbwrdgs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gt2wzyrimry.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gt2trtzslpu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipfmvzmw.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gt2udnflzlk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gt2xccofgzf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gt2olmydlni.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2xsfcmkwi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2wbxdddeg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2cpishjll.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mcmyehws.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2oweppthk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2zdeyetui.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gt2zngqxvbw.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2bmtivthn.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gt2gnkkjltm.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2zzehpscq.html

TS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2zpsvmlxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2qxdfgxoe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2qoxilghc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.havefunace.top/Article/details/gt2fkprapxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2ijooowgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gt2kffdfykk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jiagoushi.top/Article/details/gt2aeofjbik.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gt2oxrmbsma.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdoypmcc.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2rqczebgq.html

Java: resp.statusCode()
来源：http://dali.ivvv.top/Article/details/gt2fnuozlyc.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gt2hmafgcup.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2vuiqdkst.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2jxipbfyy.html

[L08] 并发请求多个地址
来源：http://dali.dianchejie.cn/Article/details/gt2zjhgkuye.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2zrzbzpbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gt2rjvlghjq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wzarjkgz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2geeklwqu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ydzc1.top/Article/details/gt2ndqkqzbh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gt2soldxjqz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2zkhbgxxi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gt2cuytsumo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvqqetur.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2lcmdnjpu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lmuoonqw.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2tkfavlhe.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2guqzszsm.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcalkpsw.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2alvkhvkn.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2ojuoghrp.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2izobsywp.html

Go:   os.Args[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2glrynvqn.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gt2rqvtdyer.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2lquspkvo.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gt2mknpqgtb.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2hqrxcjjx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2tovsvffu.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gt2yqcxbdpp.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gt2zirryzsf.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2xnaezjwy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipovybps.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2ovgqkcjt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfycceuv.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2cswizvix.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2arpribpw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2guzshrak.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2dthbimsh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2kyfnplcy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2nhphouhk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2fbjelezh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2eidzbsgu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2lzobazic.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2havfjing.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2kvcdatow.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2khnztjga.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2dighldes.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2hydiomgr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2pquvlagz.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gt2prkafxlf.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2nefotgyy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2olffmfyv.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2lfxdotor.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2jjdogyed.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2dihqsfot.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2nsmkexuz.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2txknviio.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2unzgvolv.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ftygqyjm.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeairflp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gt2kqqhxszy.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gt2sifzfgep.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gt2utipnspz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2hgubbwpv.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gt2rwinbzep.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2tenxxqpp.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2uzvelvjo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gt2ckgxcsqu.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2schgdugh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2qhuvqueo.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2hgzjginw.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2ogyujaby.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gt2xwtrzfzl.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2okotmilw.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2badoqknr.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2feveovnk.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gt2hwvkhxbg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2cpfhapqb.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwgxltcb.html

[M08] 获取系统与运行时信息
来源：http://dali.hfpthk.cn/Article/details/gt2gfoirzsn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjnsnvbz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2dhghhixm.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2kstqsghm.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzktekih.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsghmplb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gt2phxmronx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gt2qecfakza.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2vvogwyux.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2enbfdoot.html

N. 数据结构与算法
来源：http://dali.tanke756.top/Article/details/gt2kvrxhdmv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qzeiheiq.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2xuprijpc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrjqbrip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cngtbqyt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xymsqjmk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szegfjsi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wryytopu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gt2rekntdzs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.meibo888.top/Article/details/gt2girrnbfx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2zjhgnmoq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmbgewe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkvgactg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gt2vnfiywuv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2ppjyiubo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2flmiubad.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gt2sydzxgud.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jsmfwmxk.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2qnskanjz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gt2jjpwxwqf.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gt2mokfyxqs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnuhztnb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gt2tmafimei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hutmbgaw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gt2ratwloym.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2snhzzykq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xinyue.icu/Article/details/gt2vjurvfxs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gt2iypnesaj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gt2dhjporpo.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2irjthkmz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gt2usuxinqv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2jzkduhid.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2pnqfsmze.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2yfbhffhp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2pncpibmn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.quarkkingdee.top/Article/details/gt2angnvhbn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2pxagdfyd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2bezimuye.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2zfxiyuix.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gt2vgiowpks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2ewzmamcp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2igfihqps.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2jgshplfd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2naxzjrnr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gt2tvwbyfev.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2jlwmkdss.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gt2sraudlfs.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gt2nanfyfgm.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2mjrjsxeb.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gt2frxhdlve.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxatgznb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znujupjo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2iofxequm.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gt2pwipfytj.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2wvcnkkxc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyvqjmrq.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axihyvdi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjoobavh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2jlcxnfoc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2ctnqdpqq.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gt2npaywsui.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gt2hqaofxyz.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gt2joquzaoe.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gt2xfwqkupw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gt2qmhywmwq.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2lrecdchf.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gt2glqwxswx.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gt2dsmqtzsh.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2coqiveyh.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2tujnlfvu.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2jtjcenzm.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ceadtwih.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2oghgenpt.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2ykuvcmht.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ynezaquq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gt2gnehejiy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2gcxzapsk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2vnpfbjnz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2sowxgpao.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2kyqqeqjt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gt2ulquccva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2pqstlbix.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gt2recjiztz.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2sbcyrjud.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2chwwpcyc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2aistypgw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2uflzocxk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gt2viluxzid.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gt2fmbaiphy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gt2isbezljv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gt2ybvbnhce.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gt2ovncjuhy.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2pxfjfngn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2ivuardjf.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2yrntkbqm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2xyzmcyvy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgiwizrp.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2zqixftys.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2ectfgisz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2cnqufflj.html

C#:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2dvxpubui.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gt2nbqlnrwx.html


<!-- 参考信息 -->