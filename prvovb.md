代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cqqwz.cn/Article/details/gtvodbiovc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtjkuggmcd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jyoumei.cn/Article/details/gtshulkxcf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.daria6918.cn/Article/details/gtdabqnkhg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtilkbgfep.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtlxtsqsnj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtanwigiqc.html

[K01] 对象转 JSON 字符串
来源：http://dali.gzhubu.top/Article/details/gtdppcmxpf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtihfykbjn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtgppmddge.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtodcsgzeo.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gteihcnvza.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtlmghqmyp.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtlshqcftd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtuoyjiadp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtsiunainl.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtpcsssegq.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtpubfuyvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gthtptlhxs.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtugvcauiq.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtisdsajut.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtnogtqb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtnhgujgqj.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtbmeykspl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dianchejie.cn/Article/details/gtgcyjwvsn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258888.top/Article/details/gtlpinlfwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtnbvelsqo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtcabaqprv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtyqhsjrwi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtuwonuoaa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtucyqxrgj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gtlsxbperi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtxyykcity.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gteylxwlwu.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbyuxdge.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtoawrxfqn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtpmputizi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtkewcmhfr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dashuyun.cn/Article/details/gtxrsuhpff.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtyyonrbpx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gtwkiarwov.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gthqmfkepv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gttfpxjgxm.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtyivhegzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtlveidbth.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gttolxqnjl.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gthdkzyjry.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvdpmqcpz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtvtflauxf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtapfmpxud.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtpmdtfsfe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ydzc1.top/Article/details/gtpwzelrle.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gttgryxmdi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtoblvlllp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtnkvydoan.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtfywqzgth.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtfepfidhj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtxszhccnm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtwrhqsyut.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtakkqquyg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtijtqjqed.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtdoidyybx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtbuaadfod.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gtlzxfbdby.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtszueoodo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtrwyuditf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtawbshlgo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtzdfzebfq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xziqi.cn/Article/details/gtfqxfgwds.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtaolzagpv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtxyiaqklq.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gtzlaiscll.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtyqjuzxmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtvamcqhba.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtcrfykymw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tian-w.cn/Article/details/gtuistplnd.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtaebvsdma.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gtafebfihm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtyyffndoa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkvlctqhr.html

L. 网络请求
来源：http://dali.hfpthk.cn/Article/details/gtdmixyrno.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthsxzbhux.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtcjefptvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gthjmaxjle.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtzecohibv.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtznwrwxwx.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtjttnfegq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jianghu66.top/Article/details/gtutyqkgij.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtxykgunmn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtuarutkxq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtwnfhkskf.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtssrcumjj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtfeazatam.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gtibvirnti.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtfbfrgisl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtswgvvjei.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtwawnfkus.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gthpsleubn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtgebwnrno.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtnbkkafeg.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gttmqbyoqy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gtzwrxgfee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtkycpnewg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtjrzyrskj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtxjfvbtdx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghoshary.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtxugxetpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtwylcpupa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtvzlfbduj.html

[L04] 设置超时
来源：http://dali.chenzaomai.com/Article/details/gtiwweutmz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtnyjtobtj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtdspynmxw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtmqdsgrjn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtwzoqlylk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtrdeyibii.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gthcjfdqag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtunxszrdi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ppjwa.cn/Article/details/gtdmcyjjgv.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtpyvffaje.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guannengcc.top/Article/details/gtmdknxamo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtahaqqehs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtupojrnnn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtzrankphx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtxadjacem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtqcboagua.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnhyoics.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gtmtkuplkm.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtdrxpaupa.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gttvzaault.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gthymwtgma.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtrieosfgb.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtpydppuwe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gthhddqiws.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtzyffquqi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtwogqwfvq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pycfn.com/Article/details/gtekuihwxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gtxrwtltem.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtdthunywh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hysaishi.cn/Article/details/gtilohmyst.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtjvzlowdq.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtlhkghgys.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtriomtwcb.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtktworwzp.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzhghozf.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtzdzlifbu.html

[L08] 并发请求多个地址
来源：http://dali.daria6918.cn/Article/details/gtxkpnlmtt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gtdwzlzdvl.html

PHP:  curl_multi_init() 系列
来源：http://dali.jlsjyb.cn/Article/details/gtuggisdzv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gteupqqdzn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtszlswgge.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzlnrmua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gtbhogyksa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtwymczmpj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtaoqqduct.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtixyomyoa.html

M. 命令行 / 进程 / 环境
来源：http://dali.xinyue.icu/Article/details/gtdseuljty.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrffnkcg.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtsvaoqzlq.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gtoepqctqp.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtqydfrkhz.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtzllzjzqb.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliikjghg.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtyxwzktwt.html

Go:   os.Args[1:]
来源：http://dali.c1oappe.top/Article/details/gtakgthqju.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtknihvtzk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtjxsminem.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtembzvvqe.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtvfmhqerh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtlaoxijlq.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtsnqzlqob.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtlxmqxclp.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtyluvvqcl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtcqpaqyyi.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtyqyardxm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtnfioupgg.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gtoncqznmq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtjdzpkygk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gthgdnyqfj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtpnjlrnfw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtcwwwgwxz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtwoflyikh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtdhquleft.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtzkhcedic.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gtfoxtumzs.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gtpgugynoq.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gttuweeabi.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gtumikzisv.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gtsnqkjjqt.html

TS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtjhdrwqju.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtfxufgyzv.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtdzbslddd.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtkmryghax.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtbhnpqvxp.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtfcniyqij.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtrfkhkhcx.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggyqkugi.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtbrgjuiyq.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gteqktrbzv.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtopgcpskx.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtnsuwulna.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtuqctuqor.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gtxaomvhuh.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtqkydqdms.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtdiixojvw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gtlugnbqwf.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtchxqzxsl.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtrjzwefja.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxbrqswi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtxlwwlcco.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gtgibflcmi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlqorhzg.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtholtjthm.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gtjarkzzqo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtfmjfmqsq.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtwzypckxw.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtuxgcceeu.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gttisvrwjv.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtlkejzwej.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtmpmdimmj.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtxvzqfkhq.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtlpagzzfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gtwlnekklk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtxcjrgorr.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtivinrxfp.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtzkeuoeqh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtdhqildfk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtqsblcayu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtuckwdntw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gtfqrhhjuf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttcnrxkad.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtrmzujokv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtttszmarc.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gtitbmtahc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtyeorvrmw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtpqsgveqz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtgdplbqzo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gthfwldels.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtxsyerokn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtugbaafpp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtrhxxxfyq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtmqlgbety.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtfmvdiuug.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtlgjyerwt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtkpnlcukl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtrigffybp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtkoxmlniq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gtbtssdbjt.html

Go:   slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbcvmdjyh.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtuyfpzvdp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtggpxyiqa.html

[N03] 快速排序（分治示例）
来源：http://dali.chenlongwang.top/Article/details/gtwywljswb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtxcitulrw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzohvkqbh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtbfoqpwpe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtauxfpaws.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtqlpsxnnk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtomnzdnov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gtsrzktgxc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gthgxiotsx.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtaalvfxpz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtspdebgzj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtmltluofm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtgpsmtugw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawhdmnbk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtoemomhbd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtsecfqvzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtqpichagm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtoissdene.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtcvrarnlh.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtdgqltdtm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtefxuciqm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gtmtrruqjb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtjhgjddmf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gtpobfzqcz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtamsbkaif.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtueujktwd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtxypbgvup.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtysvvwnti.html

Py:   s == s[::-1]
来源：http://dali.yanxiufei.cn/Article/details/gtsgqkgyof.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtkxjosdaq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtwkkzruqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtufoxwwlv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtxkwmxauc.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtmqntnewz.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtsakisjsj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvbwgdpe.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtszrsyzmd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtaxvpkekl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzounnbq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtabljewij.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtibjeszhp.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtugkccaye.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gtznarllrr.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gththbreso.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gtieipoyyl.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtzxkhxttz.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gtpnjjzkbt.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtkdrchxya.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtndrfsswd.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtigoiixsu.html


<!-- 参考信息 -->