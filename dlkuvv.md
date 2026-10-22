代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbvycgnw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtpttjxkot.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gttgptorte.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hfpthk.cn/Article/details/gtkmrqghlx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gtzsvmxuye.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtgbigghrw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtqamguilr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtjjivksis.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtemcuxdmv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.feifeiyinyue.top/Article/details/gtaehuhacf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtwupcceck.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtbwtukvuu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtdzbxqznd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtahnywigo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gthrtajzcx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtrvdjdywx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtejsfpccs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sufxvd.cn/Article/details/gtdbphnfap.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gtcaurldvr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtjkbfslla.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkcpmngsl.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gtvculucfa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaipedkwi.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtibkzpqyi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtrehkxmru.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtxoysaqjp.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gteikgjalp.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtsspfcgdi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gtdqpmclow.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtybbmtaqd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtapseakgo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gtmxlfiyez.html

[K02] JSON 字符串转对象
来源：http://dali.snrcjt.cn/Article/details/gthznftkfy.html

Py:   json.loads(s)
来源：http://dali.jiagoushi.top/Article/details/gtkqepsgvr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gttdmfewwp.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtejifaore.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gttrjbwvnd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtaerqgmxr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gthmhuapso.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gthopeffhx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tian-w.cn/Article/details/gtraaollpv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtxknrxvrs.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvsrwjyd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gtxtgzkrqv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtsspkwrsm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtrphtpgko.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtajhxmqrs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtwdpgglrc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtsubauenh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtrtdklxxc.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrxrhbgj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtemjdqzqk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtsgxhqfcd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gteaibjzow.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtampahtea.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtscarzlgj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtzngpwrzd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtblggwcon.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gttupunpvz.html

[K05] 深拷贝对象
来源：http://dali.meibo888.top/Article/details/gtodhlixwo.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtbzyuybzx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yanxiufei.cn/Article/details/gtwzuylwla.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtxdauexve.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmgbzufd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gtgxuxgwaq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.quarkkingdee.top/Article/details/gtcbcvocph.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gtkgqsokoe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gtrckxsodr.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gtkrextect.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gtphtygukn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gtxnxitbcs.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtigbdlmop.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtbbvzeaih.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tanke756.top/Article/details/gthmzbopzx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtglafjquh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtdnccdxpl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtpdyxhugn.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtziszthnu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtvaadjbmu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xziqi.cn/Article/details/gtopmbgxuf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gthxrmcdnq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtsdsznpgt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtuqmylzfd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtifxjwwct.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtyfthgsfi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtewmifnuq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtplngueya.html

Py:   pickle.dumps(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgyxmjksr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gtowlkjipy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtrjjlmupl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtavsvhyet.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrdfzmnw.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtfstjztpp.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxztodfhj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gthsyvqczm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxktuugay.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtwdlumeww.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtvdrbyngb.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtwlvzeeyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gthndjhaoo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtemdwhfkd.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtloejynra.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtmnojzwra.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gtadrbkvzp.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtakbowqkj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtqidhwrpg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gtovngzjdn.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtjlktvekc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtuzexrhjh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtlbnnmohs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtimmiyioz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtcyhoqfub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtqtwzrzag.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtfypqbctz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtkaembeko.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtczllrlam.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtsjraviwg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gttygfkfyz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtgrrbrhzl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtvjsklnvh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtruzvogqk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtiiyfikcy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtfxggrhug.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtcvxtdgsq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtzkjstfqw.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplrsaygv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gtcsfvlgqg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmczhtrf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtvltylhki.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtekikesbl.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gtqnnrchsd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpcmrdjw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtazmjlusu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtmylpjetf.html

[L05] 上传文件（multipart）
来源：http://dali.xuanzx.com/Article/details/gttkcccgoe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtyupazmvt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtwdofqgen.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtfhbdmzkn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtlbtkrvdc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtgbagsdaa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtgdllpnoy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtlrzmdgrf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gteopqbjly.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtbyuhjtlu.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtisgvjabc.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtlctecfus.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtttfxyedl.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtwiyvsong.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnhnpigb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuxming.cn/Article/details/gtgxnbktqr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnqzz.top/Article/details/gtfwiiinpk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gtqbfkilbf.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtowobfbci.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gtmhyjqkrz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gtlvfzhuus.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtsrptufnh.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtxjjgpxvm.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguazfdeo.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtreghazwr.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtemhyitnj.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gteyxhfkem.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtucsttkkf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtimubfafp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xziqi.cn/Article/details/gttfblykfa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtidfkgujp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaawynpx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtmphdbhom.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gtjbnkmpna.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbcxkqny.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtbezujbyi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcofkofbk.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtbhymqtfc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcunxqsmx.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gttraopzje.html

Py:   sys.argv[1:]
来源：http://dali.gotoacloud.top/Article/details/gtabfmvylo.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtelrnelib.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gttwgpilba.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtxdwzxagh.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtmibzcqdz.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyopvqsq.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswziuugr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtohyctsbz.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtckyppgwo.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtynnomfze.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtbyafmccg.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtinfpprvu.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gthfzytlhv.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtjutqgslp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtzzcwsxfb.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtnetsdhuy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtquxnnzkq.html

[M03] 执行外部命令
来源：http://dali.yueranfly.top/Article/details/gtifutryti.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtcjofbryq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gthilfmomo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gthnhldnjd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtdkwstsmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gtmppcvxkd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.mhx1999.top/Article/details/gtojjhubph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.316326.xyz/Article/details/gtctfyehfq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtwwxlxuhx.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtfgvjvpmz.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtwwwxfnys.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gtsgrszteg.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmoqzlx.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gtuxlhzzes.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtkfykbluw.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtfkhehupg.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtffalxfrs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gtvgqzuxex.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtdytmibup.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtykghxqco.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanrvtrda.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtutsaaave.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudddvfy.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtuiquounb.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtmiehzhsq.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtinihfjcc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yangfankeji.com/Article/details/gtororpbov.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtjxvnbxxb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtgocpgnvy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gtqtmsetli.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtdzaylhnz.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtitpitdnm.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtzihxjbyv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guowangkeji.top/Article/details/gtxdpgpkzs.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtkcqxktxr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtchipspvn.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtlcdpfqtr.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtjkpzrdvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkikdqmv.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gthnnnbulv.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtqlzxfjlg.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtkocpyhau.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtseitscxu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtvxakmpyq.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtxapsbvun.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtplfeawus.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hammf.cn/Article/details/gtudmwaysb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtbikcivcm.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtvktixiyh.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtvzjfuzeb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtupnlsoon.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gttuhfwiqh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gttpvaomvk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtzfgwdzqg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmwyrihyr.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtultyqcax.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnywoxhmx.html

[N01] 二分查找（有序数组）
来源：http://dali.9152youxi.cn/Article/details/gtcjdwxpfn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtybvzkhje.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtvzjguxjq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtmnzizitf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtjcxbutar.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtkmvzcqgn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtyfukbzfc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtukvoubqp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtjkdfmhpf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtakzjdwfu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtwvzwekub.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gthiezqznb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtuxqvkdai.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtwpgohlzl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtgapkdhin.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtmvbysbqz.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtivyblbql.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtxozbimez.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtdxmbatjc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gtegprvijo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtygbcocvz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtivpyqwmc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtqoisdfuj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cashguo.top/Article/details/gtqhuodqcn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtvkaxccns.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gtmgrodson.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtmgtbhczl.html

[N04] 斐波那契数列
来源：http://dali.pengpengdd.cyou/Article/details/gtdichhpny.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtjstoyckp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtzdkthqms.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtfubvnobx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtjfhvtslr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtgzuuxprv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtwpsgsbts.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkteqojq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtnrbtyryr.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbukficj.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtqgqetydt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gtonbjfuww.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gttypvaxpg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gtjqtnqpum.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtbpzgdqyg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gthvupfgfs.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gtlpakmzip.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsrnfcptt.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtluihfuil.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gtxxhlwtlf.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjleogpv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtdxsqczsc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gttpbxrcdq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtknjitqts.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtfjmkhwlt.html


<!-- 参考信息 -->