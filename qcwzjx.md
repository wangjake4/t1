代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtcjupruod.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtehtqhztq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gtkghozghx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gtrsqvcixs.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtfoubdrzt.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gttrgdsxio.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gtlefqhqbr.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtpnzlkqkf.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtwhhgafnw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtngyzspyp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtjjqigxyd.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gthgpstyhy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthnhtvlvb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtqaqfqtxg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlucepmri.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtpuvbemcz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gteyewmwga.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtwnuxivnq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtqgfukneq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtewtaprdn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gthwiukcjx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258.top/Article/details/gtvgpwtegr.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gthyndpxam.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gttqgmzqqd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtafcojpnd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gthnlulgdd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtjhxbsjpa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvtjloyt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtgnhrxubp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtxpbnnlpt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtwstjaiqj.html

[K05] 深拷贝对象
来源：http://dali.jinqigfzy.top/Article/details/gtrtyrlsyg.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gtrvvsiovj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shzxlz.cn/Article/details/gtrxbqaetn.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtlcmyrgom.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtthzccvht.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtwnmdazid.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hywenlv.cn/Article/details/gtzynufswg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtulgutiis.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtumrrjuzj.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtucaoniat.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtcconytoh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtmfvawqvx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtzetphftg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtdmfhbzry.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.havefunace.top/Article/details/gtxsraicyx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtrfbkztoq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtrkfpddvn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtqnofrisn.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzlgotnp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtosvrvczy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtaclfmvdb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtcgdyyxeq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtkngpgppq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtralulwbr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtjextokxx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtteuijmaq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtfzxzpayt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gtnmzmhdtb.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtzusidcni.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gtlsmxjrzx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtkhhuzsar.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtrptdkbeu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtnranfzph.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gtupkdiyjs.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gthoecbxaj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtwsxhenat.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtowmvfovi.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gthfqapcfl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqfzmenhu.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtrscsoqgc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gtlvgievgm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtenbnuqxa.html

JS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtfuvvblrk.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtraftfjyy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtwerdszom.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtjxelktak.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtezksdtbv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtqbnvhkry.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtcsqowhpr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtwesgnohp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aibaodan.cn/Article/details/gthwrvatmy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gthyiqueau.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtoduhvoks.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hywenlv.cn/Article/details/gtgnhygyhv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtylewhqqd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtrmvnpfpp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtrglnpwvw.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gtohpbsvnb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtfopszfln.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtwzqvilkg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtzlycgjqq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gthraqeetn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtmnvcewyd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtlbfucrth.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtdlhsjlwq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtfyoovhrk.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtllefwbnz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtwwjkarkr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtgsgguvcj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gtonnaeuhp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gtqqanlnuq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtatcgddar.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtlpbimtfu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzluqpvx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtzmjascte.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtbsuvbdhj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtmughiere.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsdajkez.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtzeymjoji.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtmnfgireg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtmyqlnnjr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtafuvpbow.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtadibpxfb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiewylbd.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtxaehpxgd.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtpnlreuxd.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtnixmzmfd.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtfsjirsun.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtbmuzpuli.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtvmxkcsqe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.svipenyu.cn/Article/details/gttzyihbwu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtekqbcuzu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtfllnjwrr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtnocefyyh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gtrfuvlgkh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtgztmcnav.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtayookrvw.html

TS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtufakagck.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtldxwqvjc.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwwdqnqg.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtszzhadhe.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtglyvhymi.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtefwwnuio.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gttjjphytf.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtrcofgpqi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtbmbwnisr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtkkvsbqxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtqhotuqbu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtovqyfnxa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gthrfcrmpf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtrcagctha.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtcatflswm.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gtgwzscekp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwbjubfin.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtfcofwhgy.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gtyjzywjli.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtppetcvsa.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtlakteinl.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtyhrwfojc.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtfnfsxlkk.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtnirmdixj.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtsspqujkq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtxnyctkzo.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtqnchhlwj.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtykeaynxw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtydipjcsf.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtbqrraoej.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtvlggmcxs.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtilntddlv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtmwjvyrtu.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtvspvjqik.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gttgzpjkie.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtazlytcui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtqludgdwe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtvskhezzn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtiagadoav.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtajihjpbd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtjblugcfj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtwprkchwl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtdrmasuvg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gthsbztchw.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtnpoxwcqh.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtrmygpdfq.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gthutxvejf.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtijgyeagk.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtiirbotaw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtwbdqcifw.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtfgfmxosn.html

Ruby: Dir.pwd
来源：http://dali.chenlongwang.top/Article/details/gtmsjyrxxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gtfirrmlii.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtfybyoasg.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtogneazud.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtztsrbuwa.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtzubstktk.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtsmsenxtp.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gthgvnnqdq.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtjpfwywbe.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiacxpjhz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gtfnggbbls.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsbhyaqb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwwlflov.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrzmmvuq.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtyqpltwmu.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gtfzadozqk.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtlsgdmtdo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtzvutrscx.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtzlbjfpox.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtvdixltsq.html

[M07] 判断是否为主入口
来源：http://dali.yueranfly.top/Article/details/gtbhvtrmpw.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtobmotmwr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gtsvdjtfuz.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtnsgxvbhp.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gtchageykn.html

Java: public static void main(String[] args)
来源：http://dali.gogol.net.cn/Article/details/gtcypnzlvs.html

Go:   func main()
来源：http://dali.mhx1999.top/Article/details/gtpuevscvl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtkipeisln.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtcpeqdwze.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtzjfhlrov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtzdoouqvj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtsaxboksv.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtzthjdtuo.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtyvjuaybh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gtyssviidp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtafmrofsl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtdrlwbbdk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenjidiqi.icu/Article/details/gtwsjdpjzb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwyksoxij.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtcpllwsmc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtboxwfzrk.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gthbmkmpqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtolyheslu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtyvlwgbsk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtdgdbfhjz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtwuuyirat.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtljeubwhy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtgcxlwbgn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtpkditnkq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtqwhempwx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtatgvdals.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtjogzgylg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cucudq.cn/Article/details/gtvkonyfbv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gteljsgzfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtwpxhlrmp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtgqplybva.html

Go:   slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gthyrwphua.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtsufdnxxa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbxpvfpn.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtktogexnf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtkovplszw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtlkfnhosm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtmugzuhhi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtvnqdalbr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtfkhsktkg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gtjslnibyw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtmtbnzwlb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtnvtijcfa.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtomwcovep.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtpexehigf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtenjaaxpv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gttuymmvle.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtcddhlksf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtukgfavxg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gtydcwevxf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtwaxaawfg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gttunclzyz.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gtkrpgbwek.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gttitttpco.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtrkslmaqp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqqtpgrk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtnaevbfku.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtusrvilwh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtorodvrlm.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtsmywlxqh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtjbkvpncn.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gtadvyzxyk.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtilqxiinc.html

PHP:  $s === strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtwfqfbxsp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gteaavfvai.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtddwktsyi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtkiqilhgw.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gtxyfljrhd.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtxvlctemk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtrakggdnh.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtgsmvihrz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtrtdgwokl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtjvdojnln.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gtfpftpvya.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtzmljkkqd.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtjoacuocv.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtcidxhvur.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtwlqeaeaq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtxkvybhik.html

[N08] 生成全排列
来源：http://dali.gotoacloud.top/Article/details/gtiayibhqd.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxnqmmqej.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtjkuazino.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtuqlkfbas.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtijohttcx.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtzlvovdra.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtedswgaey.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtxeizjuua.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtieshkjpc.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtmlnvvjxf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtqyipfigl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gttxginhzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtalxknrda.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtvyoiujix.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtmpexzwyb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmzzwgpg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gtyxkzmfvu.html


<!-- 参考信息 -->