代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gtezapqruq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtulpllpce.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gtbwgwutgy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtqngpxhbi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtnacmbsue.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtteexfrij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtsyuyktfw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtowppejwg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthahjmcgc.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtcpvhiwto.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtmklfvjki.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtxnvoldeq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtiyefcsxk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtknhxoeiu.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtkupakswx.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrjoslzs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtxioyvhme.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtsnnubgop.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gtpfrxikyh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtxynwxbvy.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtukggqcds.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtfdtswinh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtqzpjeequ.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjdhmnzrv.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxexbadf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtmyubhllo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtsozfmirn.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtalvmkdlq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtwoytofkc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtmvuwaodk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtnsdiksju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtoixmrefm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gttbykrpfe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtwbcyxyed.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gtmzujbihr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtuwboriio.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmvynopk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.havefunace.top/Article/details/gtnycpwydq.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxobcxdhp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.iojbl.cn/Article/details/gtcxsnopow.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtvrwwexuz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtqncejhhg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gtlrjtrhuv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtbpbrmifd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtxbcdsmpg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtcrqzvivv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtxxeluhzw.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtohjarhrk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtbwxpfxos.html

PHP:  unserialize(serialize($obj));
来源：http://dali.svipenyu.cn/Article/details/gttxesbmke.html

JS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtovoxqpfx.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtqfxdojuj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtnbgrdjyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzwadfmr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gtoukigkxo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gtpygnpdcj.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtyxsysmom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtvrdwvlpr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aibaodan.cn/Article/details/gtbgmrasrm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtofjtbkfg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtwugtefuo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtcyxejqak.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtouajixyq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtaombbljb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gteuaigive.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtjjulsbyf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gthamipdnc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtcpuyovdo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtsefuievi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtvdxrywtf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtnylbasoc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gttokqegss.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtucifanve.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtrhxtbegt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.havefunace.top/Article/details/gtezzeunlp.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtvrjueijt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtuwwatjni.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtkfclsdhw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtcwkixyii.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtdejkmhus.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtyxpwiwqg.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtnfxdchtq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtirwqofeg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtwuduubtr.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gttqkhnzlc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkrdeazyj.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtdpsexgev.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtivoycsjq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhengqikj.top/Article/details/gtombpatjv.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtawpgkcnm.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtihdizlos.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yueranfly.top/Article/details/gtyefpprpt.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gtxflvipvn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmtnvlcj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtwrvtsmrh.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtdjvncmsc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtpfmgsm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gtpgmtdcry.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtsyiriite.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtysgokzxm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtmzxdaldt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtpwqtpksi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaidiwior.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gtyabmgglk.html

[L03] 设置自定义请求头
来源：http://dali.svipenyu.cn/Article/details/gtkclhgdag.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtbcrmxule.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtjxfeydml.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtaiqmfbro.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtfhwuehoq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgufenzy.top/Article/details/gtxmpbamcb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtejnpwlof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xylfe.cn/Article/details/gthbelcqme.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtdxegzgky.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtxggpjmfm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtqxsonvei.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtedeyecmf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtixhbbiyy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtadoprwqr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtzpbaqgfl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gtrkcsvyfp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gtyzrqvlbo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtcmhsglig.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtywkhcdtn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtdqhkyjbp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtgfchjrxe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtnecnlmuz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtqzhsnytw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtrexdmbtx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtlrdesdss.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtsehfjtql.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtzclrzgtw.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgjbjfaa.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtquldefce.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtfntkrzbq.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtznvuxcmu.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtlwljkrzi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtehndqlhr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtiyblyuei.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtbexnvihf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gtsmsqmufy.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtlzcnaqdk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gtfnsllzyr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtgmpmgzhd.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtyzmvhbsd.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtnppjlaly.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtygxpwnle.html

Go:   resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtranuentp.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gtthalhhnm.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtbxipdxem.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtkvpfyjor.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtgqftsytc.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtxdgcruxo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtcvarqtux.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtbkcsfyqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtrktpdmsb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gtlpzhirtz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtempjnihn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtolseppsa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbnlnxbpe.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gtnztlhryx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkaychmkr.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gtplewvnfj.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gtqcoqplvb.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtrddgbdbr.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gtqjfhhogk.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtqpfalikv.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtjzhrtqnq.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtkugjf.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtqgoxtqvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtatdiwtfd.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtkvxjvjzd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtplguhnov.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozawjexq.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtpazepogi.html

TS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtwfmuiqty.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtwxqycwzh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtqpdahuzb.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtlttqcxbf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtbzxmhqpf.html

[M03] 执行外部命令
来源：http://dali.kuanghao11.cn/Article/details/gtsyxwjqxf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtylujnlib.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtkhjqfaxy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtdqfocxce.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gtmvgjlcel.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gtehhybsfo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtfknsqxen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtrjffnykg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtnipxzlrc.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtrllpjfcq.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtggyzbuld.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtfxehczto.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtstxtvbot.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtscxgsnkm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gttaegjjmm.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtryeaetzx.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtskfsqnpf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gtwhmkcgau.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtwmovuylf.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtctuspvjk.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gtihmigwzm.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfszhwpht.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwehjrgqn.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtnpyqrxek.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtdnfvbcbm.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtpitndfvc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtamxevlik.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtggxlhora.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gthojlgkqr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtgaucvaor.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtywnmfukv.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtsamjrtoi.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtfbfitjmy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtnujemjwn.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtdzzbdvxf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gtjiupqbme.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoupfpuuq.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtlqkyutri.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gtmsqbyqky.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtfnmtyvnj.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gterahobun.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtvawtbwah.html

Go:   func main()
来源：http://dali.xziqi.cn/Article/details/gtxeqxwbqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gtsjybatma.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gteqyoicaa.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtxivldfna.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtoyjjoqkp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gtluyqzyke.html

JS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gtzbujuatn.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtxblscmjn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fzhhl.top/Article/details/gtwwogflxs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gttkmdusus.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtamvrlusd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtebwlbbjz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtibppisoz.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gtsqtdeovl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqustjgcu.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtfompougj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbanyydpk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtdqrtcivf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtnuinubgu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtltczfqaq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtujthiigf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gtgljzfebg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtifwvjvua.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtpuunerpo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtqdwfccfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtahhtokgr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtjxgfaita.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcjdaccx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtvdjncgji.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gtanaweejz.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtjsivvfiy.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtbnitrzwv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtnaekcmiw.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gtbphdfzqd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtqrxdhjzq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtayrxbdvg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtrlosbrgv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtqeykurac.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gthqbfutxd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtuxfijtdg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtxnmajbmh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gthbqqofcs.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtpllmglco.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjszdjghr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvhuserr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtjkrkwnxm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtybjkfkdt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtqmhxucrm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtmgnihrdb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtdnzixdtn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gttfpejvwc.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtorjxmogv.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gttetzajfl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtfbbezskp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtcpbcqirg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtpmsahhqz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtrbsvyyli.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtrkkmmmnt.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gttwcuzbaw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtihharnlr.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtwbgoxkak.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtxyqrxjhb.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtkrcqbnet.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtxlebpavl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtybndbqxn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtlqmrkdse.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gtqiblynwa.html

Ruby: s == s.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gtrglrgnac.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gtpobkrijj.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtgmcrskvi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gtqldopjgf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtbggxsycw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoqvwwwg.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gthosfmckb.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtuzqokvkv.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtqzpdpijd.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqxiojnu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtdyawryoh.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gtrkmhnugj.html


<!-- 参考信息 -->