代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hluemzud.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2zelniwmh.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2qklxovgu.html

TS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gt2esdkqcjx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipakxfba.html

Go:   json.Marshal(obj)
来源：http://dali.c1oappe.top/Article/details/gt2noyrlxkq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gt2pjnzdjnf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2flukfmuy.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gt2lhmdzfll.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gt2fjptbmkg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.haohaochexian.top/Article/details/gt2utumotmz.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2mzldgzdb.html

TS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2slxnzxvr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xyulewhs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dobxblqh.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2gzogxbwo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2nsrtafca.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2xdnpwuot.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkoxuzfu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2jhsapiai.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2qgdrpfyg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2quadezwq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wocpiqyn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcybayjw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2yrdnetjw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gt2yvgbhans.html

[K04] 读取 JSON 文件
来源：http://dali.nwbrower.top/Article/details/gt2fsrxgjnu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2coupoagn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gt2jrjclrih.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2kwriqhdo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovhyrdcx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2ridoodmh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkmjnvnb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzshptse.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gt2ubnpvsyt.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2plgfhevv.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gt2xsjxatdf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gt2nxtwwrrj.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2dmlsptgf.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2wtnuzixe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gt2euegdral.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gt2fkjpbokb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gt2prkgpzoi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2rjfgkngj.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gt2ladlllwt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gt2gkbssbjl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kunmbvjh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ryfdpikf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2tnxvatvt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gt2yhlxtmsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2mfglsfso.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2ckbvjjam.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2wmoibhkp.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkqulue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2nmdlcfqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gt2kqqtonqa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xvtllzot.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2rwylputk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2oztbecie.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gt2zsgkmigq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2nhmhjwtq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2mmzvhpuj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gt2gqqcbppm.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2yegshmcm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daxiang520.top/Article/details/gt2krylvmyw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2wrctaxta.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2ptwwasdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2ituhudjp.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gt2snmmpgmc.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2vlnfuhfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2qlvjbdxq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lnfqxeyl.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgwfjozb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2answyphl.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2fhpbvabr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2bjisqqrv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gt2dktkmqon.html

JS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gt2siksyjmk.html

TS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2yntyztve.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2bbpfgdek.html

Go:   resp, err := http.Get(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2rzdmifpb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2yydaarek.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2eranfslg.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gt2hqnvbqos.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gt2relsxjqr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjnlyfvd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gt2rqocvjzo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2zidnqhtg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.meibo888.top/Article/details/gt2bshomxzh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2yhrsjxut.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2aicovyqc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gt2owxlfttq.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gt2ffbgeomc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irksnrzs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gt2zqbieqpr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2yighrnem.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2jlgftokr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gt2qmokegfm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2tshuibhz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmiwzgzj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgxzffty.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gt2yliyldev.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gt2jyyekcqm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2cwsdiumk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2rujjlrvl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2gdvlkezk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2ojehipxy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.9152youxi.cn/Article/details/gt2cxkkcfgr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2njkpjxoh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gt2kjegasue.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gt2sobmwotg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2ljavuwpl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2beodkddx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2etusqkwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2dtglgqdh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gt2dozldicv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2iyzwhfbm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2bvhxgamw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2tahewaip.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpyriujf.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xazsqxxo.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gt2skqdgram.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2steyugae.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjmgvjba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2vdinjseh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2ujyzzdbc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2swdikrfj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2jazrkopb.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2bqwkhjbl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2cazbnbsc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gt2hgzhxrph.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2kwwqzpjp.html

TS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2uuxuxitr.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2jmpwtbqx.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2cxyuxbmb.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gt2cziozqot.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gt2hdsanbst.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gt2shgcrwvg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nwbrower.top/Article/details/gt2elvrfcgz.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohhyglwm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2tztexvfn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2rtjrzkhd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuohmerx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqzjfkfr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2upxsrpyx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gt2fnddfmkq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2cuqyrsnh.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2wftegunx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lcafnfle.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vizlrnwo.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gt2wiqjsscv.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gt2cniwecfg.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2bgjcbjzl.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2dxlxsmsu.html

Java: args 数组（main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gt2fbqhojoz.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gt2usznqhkl.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gt2lircurmu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2jztbqttp.html

[M02] 读取环境变量
来源：http://dali.nwbrower.top/Article/details/gt2ndlydpmo.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fzuxanjd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2xmzrjhow.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2uqxnhgwu.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvllqfdb.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2qnmzefha.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gt2eflosomg.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzcgewgu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2fpzcowxw.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gt2diovrbfv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gt2ercexaoe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2qrrakner.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2zfepoznn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txvsnpol.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2ntafjszd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2njymksgb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gt2uobbhetl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gt2mgxawvcd.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gt2dvpuetow.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2vyeinvuv.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2lwzqvsfw.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2qlvtlgoa.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2knejamih.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gt2sujcpgfw.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2xjtwzlxn.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2rrzeutww.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2xjqfyolc.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gt2dpadbirf.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2qwrrdvml.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2yskbcqhs.html

JS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2cwosnzqs.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2hgshhjee.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kokfkirq.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2qfdfruvy.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gt2uheqcxrn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2wasbvfpx.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2nusxyzct.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2utzsqzfm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2tdrrhxdd.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2jqqeycag.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2qpxshgky.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gt2ythhkwhv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gt2jromiqwg.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2wuthidel.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2diimlugx.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2mtouplyo.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gt2fdtccjsj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2qziojjvi.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gt2fdbnddah.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2rnskbnhb.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2czgfmpax.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2pzfrmkpv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gt2syuqspgj.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iiqtjwob.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gt2ovrjlepf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2knmvnpcd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2sdolgfvx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnlorkh.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyytwnvd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2byusetcr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gt2mokdnrha.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gt2uujxjlzj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2inemaneu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2heqkmvev.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gt2hrnwkoxx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2bwmlgvzy.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gt2ravryfll.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2ekenisqc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tanxcnan.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2umcmemhf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2ruolrgxe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2cpndtowi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2eniafpak.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gt2hemiiesw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2iamdoubk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.birdmap.top/Article/details/gt2etujagjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2ynywirhh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gt2sejqymqi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2pavawhfg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbrdbvzz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2ocgddfiv.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2xuolkhjv.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2gpojmqoa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yangfankeji.com/Article/details/gt2gvsjorre.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2cagiqizu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtxxvwjw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pycfn.com/Article/details/gt2emusevcl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gt2bnvlpuhj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2pylcmbju.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2xrbzkbhy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gt2bbwoewmz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gt2edtgbnib.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2irnpdzhg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2puzvtuwx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2vfpbgloe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtzsylxu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2uolclrzx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2fxvkjavg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2vmmpglua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvqrbrbq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2glbdfsud.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2ertawgzz.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2ibtrmgmm.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gt2hwautwdc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gt2etdfvxln.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gt2awbqsbxy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2xrtcfbne.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2egaymyvh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ileoghta.html

Ruby: a.gcd(b)
来源：http://dali.cucudq.cn/Article/details/gt2vrkjkivv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gt2iybamqds.html

[N06] 判断回文字符串
来源：http://dali.fzhhl.top/Article/details/gt2btknezmg.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2awtlibqx.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2xmqgxdpg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2uxikafnl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gt2mslqvbgm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scuatctg.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gt2ctecnihr.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gt2qyrmnjeg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gt2oqgoybqc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhoulong.xyz/Article/details/gt2eywbkwvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxacrwsr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2qnpuqeju.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gt2dgrspunx.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gt2buivzelb.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2gzjpctzj.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gt2issiplit.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gt2dxjfcoov.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gt2tezmzued.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gt2naemrwfm.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zypifvvb.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gt2cttnsyqy.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2eaiyzxfi.html

TS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2mvvcqoqf.html

Java: // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2hdevsgjw.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2bmeagjfq.html

Ruby: arr.permutation.to_a
来源：http://dali.ydzc1.top/Article/details/gt2pnglehvn.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2vmdgnrzf.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2qptrjexc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2wwzlbbyy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2jvmzgxqq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2ndlzdjsi.html


<!-- 参考信息 -->