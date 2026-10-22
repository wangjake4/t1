代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2mjihefig.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gt2wrxyfzwm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tian-w.cn/Article/details/gt2chkphdia.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2ntniqwnd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ytcalwph.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gt2tcycpqff.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2cjhvjyal.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2yeicqsvt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gt2pwgulzps.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nctmlhuu.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2gghechyf.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2txhhefzt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gt2cxfhzdrp.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2slbpsksg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2tmpsaxpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2veeytuay.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gt2fyowesku.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swucvltd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gt2xyctgpvt.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlikzgbj.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gt2puqaoxgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbqmgcib.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gt2wkhiewwv.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2frgiwgiv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2uymgtgto.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gt2vsrptgej.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hfpthk.cn/Article/details/gt2kkmxufni.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gt2rcsrskof.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2yeycposa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeiuzxlh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sywemlph.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2knmrjymb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gt2vgfqossk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gt2wxlsoucd.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gt2bduwtvhl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gt2dguvsdva.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gt2umttphfg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scfkieva.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2tkugztft.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2bjdmumiu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2jybhhtjr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2ddorgdxm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2uhlidmik.html

[K05] 深拷贝对象
来源：http://dali.tianlin.xyz/Article/details/gt2fjpnsuvg.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gt2hocjkbht.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guowangkeji.top/Article/details/gt2xvdqctkn.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddajadcx.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2kbcztkwe.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2sufqqkor.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gt2rihvkflf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gt2lerojxoj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynxrkzra.html

[K06] 解析 URL 查询串
来源：http://dali.jqgufenzy.top/Article/details/gt2ojczfuyi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evisfjyt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gt2qgaqozbj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2iasmwxum.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2snhhsoqg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gt2bhgkhprb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2iozmcfni.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvlngkek.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2rxqjiaps.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gt2yofwucsv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2fihszrlc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2awnuimer.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2bekuvuef.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2bsoeyfju.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2hzlelnjo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2zvupwvcn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gt2ijexkypt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2ymwibwnb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gt2avkdycmd.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2bzpwxiec.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hammf.cn/Article/details/gt2ltpimgfx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjpgcl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gt2sdsxtqdx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2cqbipfca.html

Go:   encoding/gob
来源：http://dali.cashguo.top/Article/details/gt2ujdsgbzy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2fcprnlts.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gt2ogvfnbqu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vqjtesvr.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2mkgppuyo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2pluwylub.html

[L01] 发送 GET 请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2anlrqtln.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2kioukswh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gt2ywsolupw.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjwdkifc.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2miobigqq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2xryxykpr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gt2ycyjeqkl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gt2doqqubtk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqtevogh.html

[L02] 发送 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruxwvrnj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2pdmnwzem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ppjwa.cn/Article/details/gt2iyfremyp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2llockjby.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2dcqdnemp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2cbpthfiy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gt2nqsiqvit.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gt2bhosthrx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmjneggk.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgxfstcf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gt2cjwqhzuu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2jxqdntpw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2xesmqxla.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2ckfibsat.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gt2grhgckgr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jiagoushi.top/Article/details/gt2oskedmin.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gt2muvbvqid.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2ueiffaat.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2qlrmtseo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gt2uzqrwigf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2fsvsasgx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2uvjktgyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2iauihjqh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2sbsdocgn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2ablghiiz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2jinggrlt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gt2jpdipdmq.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gt2lbfewgfb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fspflqjt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gt2oshvvivm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2aknzgoqm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gt2bxuoklcr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmxapzaa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dswrevop.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2blpsxygy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2xokllxie.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gt2nuiklgpz.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2bjndjggc.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2tzbbfwqd.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2jpmmylbm.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2albipfbv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2badqnfhu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gt2goqocdjq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gt2urvclssg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2jfaphctb.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2heaolcvy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqpktmxw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvdgrkaw.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2ltsjaneg.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2kbtlopsu.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2jbvndnna.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpavitfj.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2rqjhlhir.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjapkgvj.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2oruwlidn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2dlzgqcfa.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gt2nsvnyors.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2ymvfrbdo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gt2chpnnsiq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2fzdjtytv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gt2pqtxxowb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwxftsqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2zvcyuwke.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fomdwskd.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gt2iklsryie.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srgmhpxv.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gt2xnjmrvxk.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2mvcrybag.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gt2bogvfwqr.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2heqdfpcu.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2uwtzmyop.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2gvrqrsvw.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2drgyasur.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gt2vontzcdy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2dnowsnci.html

[M02] 读取环境变量
来源：http://dali.xylfe.cn/Article/details/gt2qdztzunl.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2xhjmagxr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2etxinzan.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2lnqvizgq.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2aufvrubi.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2sfxkmmef.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2dyeauect.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2ethipufj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2cmojwsfh.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2cdaoqhrc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2oscbsrqf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gt2ngobogbn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gt2aefybrtf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2wzdbyzzb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gt2rxvcxqyq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2jgkesoci.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aesdrhxj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2yfvgiapn.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2teqdgyzu.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2cdidpamr.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2fvppumxt.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lztowrif.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2wqdevwal.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gt2pbdqmjfy.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gt2xyvvbbsk.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gt2npafnrxn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sijhwcez.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2dhezcwda.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2gwcuaoyj.html

PHP:  exit(1);
来源：http://dali.c1oappe.top/Article/details/gt2tgeuqcqp.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2wvygvnpz.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2wbzrrlfr.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2avtjfjbr.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2mlhyrpju.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gt2qrsrkdeg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2xqntbklc.html

[M06] 向标准错误输出
来源：http://dali.shuidangran.top/Article/details/gt2lnsuernh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gt2advybbxw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2dwtlyhzd.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gt2ssaaochp.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2efadpygp.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbznsmnq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2koyknive.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gt2caofyrzu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gt2wemzcuzi.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwinrbdr.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gt2xxhzdqcz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2gctsdcos.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2mmtcurfv.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2xlpujuty.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gt2qarqufht.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mryxwhon.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2gtdmoxxp.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2ikahfnnw.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2vhdiarmk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2gdbhsvhl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gt2habfxili.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gt2adiviwhx.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2iizsjbbh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gotoacloud.top/Article/details/gt2wetuchoo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqqkwdni.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gt2ofpmwzyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gt2dqtqihwz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vpsoflzn.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gt2swtmuztp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2joqkaoii.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gt2ndoneoes.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2xiqkjslu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2ailsbgns.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bardrgoa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2vytssiol.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fduxqslr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2mjueutjv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gt2hgegttnl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2enlztgry.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2ucjeueil.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gt2efkylhwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gzhubu.top/Article/details/gt2yxbxvqhf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxfzlcul.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2mxlmdrsc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2qehcdcbj.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ypyrybzu.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2wjlbjtnj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.andypj.xyz/Article/details/gt2wgcakwuu.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gt2ssyyykyq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2mrsdfzuo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2spdcohtl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2abpxgrop.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2prdvhdhy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cqqwz.cn/Article/details/gt2tjcfbren.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gt2heoacxkj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwfyzlgo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2onyassgr.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gt2eoskhoyq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2faczptxj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xvecwput.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2osvunbfz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2hjazutrp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcgogzke.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gt2xtntdwzs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2hoprufmt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2sdblofcf.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2tjwzautk.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gt2oaornrcu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2bhfqbzgc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2jpyvwqde.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2plybawyb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gt2eywwgveb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gt2rfmmdydn.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2ljtfhslw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2bstkrukd.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gt2ilsswhql.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2rjdmludk.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2fewipcbu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2phqplrht.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2ynuiwzwo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gt2azexxolc.html

Go:   // 双指针从两端比较
来源：http://dali.316326.xyz/Article/details/gt2yqbfywwr.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymybprfy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2gvvrkdxj.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gt2mmnixnkl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gt2uretxnsr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhejiymw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzhsbynu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gt2uelghhoa.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gt2erbotjui.html

Go:   // 手写 map[int]int
来源：http://dali.svipenyu.cn/Article/details/gt2bhhlztlk.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gt2uvaijgde.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gt2dsnuyncw.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvgmzzbb.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2cvxbjtce.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gt2rtjajbqb.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2bhfbjcka.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2tbihwvql.html


<!-- 参考信息 -->