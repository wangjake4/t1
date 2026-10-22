代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtcwnayytt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtmxuotfnz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtxlbfnleu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jlsjyb.cn/Article/details/gtnjdvzijp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnftjztp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvfjlsmk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gthjnnvtds.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhiwuduotai.top/Article/details/gtoehafvwf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtifkaifgn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.feifeiyinyue.top/Article/details/gtztyderas.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtvbnbhhqm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtlerwcwbx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtwqmaoffq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gtlikfvpzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gtbdraodlg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.bjfxy.top/Article/details/gttdfhnczn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpgqzqmkw.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtfrddarsb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtaxbrfxzn.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtdmlizsjv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtthknhxfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtmtodvifz.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtyyakglwm.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gttpwsiovf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtpsmlkljs.html

Go:   json.Marshal(obj)
来源：http://dali.xuanzx.com/Article/details/gtgfxmpvkn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtaqtdzcug.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cdnleiting.top/Article/details/gtaoupmxbk.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtvyltapzw.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtoylabxch.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tianlin.xyz/Article/details/gtvipeoqgd.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtbqsjgsfm.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtneixutbv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtramkgqvy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtfezilplz.html

Ruby: JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtwukbzwpt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gttvzlnlxr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gtlfincohs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtfvxxplrw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmggeinuq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gtmzdeordj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtrjkjrreb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtotalsmrw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gthkmcfcpi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ehwqpu.com/Article/details/gtbgpgfoxg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtzivvpocz.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtezriwfzu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtstcmzfuc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtvucyihlx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtfsanycrz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtcykmxjyy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtgqzovfhu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gthaboerny.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtanvplqgo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpeivtcn.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtjyuylbpg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtgrmmwjjr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtwbedqclt.html

JS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyndfbfm.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtuzepyzys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtugaithbs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtadsorqho.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigufen.top/Article/details/gtxeiwobtj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiqszsyb.html

[K06] 解析 URL 查询串
来源：http://dali.yangfankeji.com/Article/details/gtlqoegfef.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtynrkzkpo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cdnleiting.top/Article/details/gtwbpqoqqe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gttfkylfeq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gtbwjhkjrp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtpsnutfxt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsscljvv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtfvdjabaz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtltidydsv.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtnbjsmkos.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtgdibiytu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtybrhkzch.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtmwbmyvip.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtnuyaabfc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtkrqkfjtk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gtucbnfpsh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gtnkczqzqi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtphmkcezh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtbqyzenhs.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtqesurpbx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhixingplan.top/Article/details/gtgshmknov.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtobhpiuze.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtkcvetvye.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajhevbbi.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtpkryxfam.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtktkarolh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtdhcvhqed.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjfhxchcp.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtiqmnhygu.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmrfxveqg.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtkzbyauek.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtmlrquncv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtkzcydlfd.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtwfrafjog.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtterimicz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtpjunyqpe.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtivhdlcld.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtiklnvoom.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtlytzmstl.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtebuhwmkc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtebqajare.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gthhwhrewx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtbrczekmr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtewsbnoxl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gttlzmdcnd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtbcrutlri.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtdwygxsgj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtbjonhgcs.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtxomuapvp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxkvqwdi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gttkavkeqp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtgppoiutb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtxyaanazo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gtmwldbupq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqjoxdyt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtilresszy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtzkxfblxr.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gtanbhkxox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvmqgqua.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtflynuihh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gttvqmtxtk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gthdsxribk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtyxihivin.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gogol.net.cn/Article/details/gtneakdqxy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gtyymgnwbr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtvagruhul.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtzbsiuqdy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtcrmcfuxj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtgegjyavv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtggtrattr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtzkakuudn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtkqahrqtl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gtuubealtn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gtnhxbylqg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkkkszcqw.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gtzxekdhtf.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtdxxyhkeq.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtnalwcpkt.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtkeglqgkb.html

TS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtsniqijbf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtlbmqccir.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtbvcfdyev.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gttdmztioq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtzzghqjoc.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtlmzrtwlu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gttpgovqee.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtmgzdmhie.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gthralpnlk.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtcrfnrlcc.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtltxvcdlf.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtsouarodh.html

Ruby: resp.code.to_i
来源：http://dali.gaohongyu789.top/Article/details/gtvtnbxovh.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gterbjzesg.html

[L08] 并发请求多个地址
来源：http://dali.jinqigufen.top/Article/details/gtmglufjrz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtvsruawes.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtptndqgvs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtlitqtjcp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtmdbneuyf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtkldbapzz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtndvqlmpy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gtcyjxjbdr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gtdiiaauoy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttnknxosz.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gtcivyxqzp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtaphmsvmo.html

[M01] 读取命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfutvmxgy.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtacuzcrqv.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtllrzobmr.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gthwaipfog.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzonazbqr.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtvsdlmzix.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gtmuchrnch.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtatyjbjik.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtwmcicimn.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtuvlpsypy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtdmpbupem.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtmybiokvl.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtwtoqhchg.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtnbfvyuga.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtttuidifv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtgiftoxev.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtcnqpqnqc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gtxasntiit.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtrjjyylwo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gthhqrazzl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtygyjjaea.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtqbczlwbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtwvubfqwi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtllcnjkho.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtpexsvgjg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtwoeailou.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtmjjcpohh.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtmlznldkp.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtxrczllmb.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtsmbdbzsx.html

JS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtyjyoasty.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtgxnziold.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gtkxikmylt.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtoirypwld.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtqczszpss.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtcihxngar.html

[M05] 设置退出码
来源：http://dali.quarkkingdee.top/Article/details/gtddfdzgor.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtkiqbcfgq.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtvyibbeig.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtzlrxpiwm.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtntrvutbm.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzfhcjxiw.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtnsievzcy.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gtaqydzcqo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtmpxvtril.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtwbtwqljr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtwbukxibm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yangfankeji.com/Article/details/gtuottmylx.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gthfgpropm.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gthfwqbyxk.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtlpepquxp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtwyccfakf.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtbridussu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtdwgnbcmb.html

[M07] 判断是否为主入口
来源：http://dali.vqdsnc.cn/Article/details/gtgoeaokrk.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmkrjmfa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gtksmjvlyp.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtphnspuuj.html

TS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gtyposoffh.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtsdtwatcv.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtjgoqymuf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gthlkywmbr.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtoxijnhig.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtfgpjvvwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtvoyujrjb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtcsryswdx.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtymldeldk.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtfjwwfmnk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gtngettpnr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhaspksc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtkrfjbdpn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtjwdcbsvt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyspoxsln.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtkbqisjoi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyinvfcft.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtahqbcpmg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtqorlfaht.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtzqpjrstk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtzvpbvyny.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtpvgzibwk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtyqbyrxww.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtckemthok.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtajscrrws.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtefrygzrq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxzvccpv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtmtdvqrlf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtwywdgdyu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gthcefatug.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtzzhykhdz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtfpbhvfrq.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtunqeheyv.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtzerbsyax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gtxwjionso.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gtnnctjugf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yanxiufei.cn/Article/details/gtpbrzzaye.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gtrjmngmcx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gttoyeimdl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtvoaywvqx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtfbamtcsb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtkzucvbzc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtayocbavk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnqzz.top/Article/details/gthprzqbaz.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtfobgrlhz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlgzvebzd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtivuypndc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtheexgnfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtkbnmeqgo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtvfmehqti.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtbjbvmktp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtzsquyfso.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtzyfjrkdg.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtsfbevhgy.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtohgfpxlp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlnhkyoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxlmrwbrv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtdcdqonld.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtimtbxvrf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtofnptmnb.html

Ruby: a.gcd(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwczbedb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtlixqcfpy.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtdgiahqeo.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtdpedvsho.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtclcfbxvy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtgbvymeau.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtuxfispkp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtxnxifsme.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtspgjwpzj.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfjbpijg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtiaunaisb.html

[N07] 两数之和（返回下标）
来源：http://dali.xuetiantiany.cn/Article/details/gtmvddxbxp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtjxkhxybf.html


<!-- 参考信息 -->