代发 wailian999

[J07] 比较两个日期
来源：http://dali.jqgufenzy.top/Article/details/gtbmqvocgd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugmmekwq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtqtgxckih.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jiagoushi.top/Article/details/gtfvknkztr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtilszirla.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtjbagitzo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtjaovwtsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtbohhaobs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtjhpxhnyv.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtwhwteucw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ybcxt.top/Article/details/gtxcnxctez.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqnuqght.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gtspdnybkp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtdehwxogy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtvbcmkmwk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtjvtvmrqs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guowangkeji.top/Article/details/gtquhfbant.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtdimuhzld.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtubtcolfu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtkdyvumin.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtyxnpzrym.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gtgjgnxziw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtiaffnvft.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ehwqpu.com/Article/details/gtgjeftnms.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gtjjahupwh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtnmowakdw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtjflvbeoa.html

[J10] 取今天 / 本月第一天
来源：http://dali.yangfankeji.com/Article/details/gtjqklzjgl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtvewvyqnl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhongyouzk.top/Article/details/gtzlisnzgc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shzxlz.cn/Article/details/gtvxpojejx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tanke756.top/Article/details/gtejcwxdvk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtrmstvzot.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgksodjus.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtbmvwgafc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtohrwgtpw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthubygesx.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gtskrikvkt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtudwsbesz.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gtrhporfwk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtzgrezgfu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtzwtiqwlp.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtqyjvbnus.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gtgnrvmxba.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gttqhkumyl.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtfgbvxzwx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtuuqefygf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwgqneovd.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtzpluluze.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtadumervq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtihvtamzr.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtqxbnztwr.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtqozkwoku.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtikoolysq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtpslogrhc.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtiejijfbv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gtyfuxcegg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.smart0.xyz/Article/details/gtdefxduvq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gthgxapyor.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtxiykpdop.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlmfontbe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtbejyxqju.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtjdgfxkae.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtgvseveqc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtsfokqcdz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sufxvd.cn/Article/details/gtcnwdniaw.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtbosmhwjt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtuswgyyjk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gteasuaewz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtlbbgggpj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtwrxefyzx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtuyxbpzze.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtcptdwegd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtbrktncql.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtzptjcivt.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwexkzsl.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gthpldsodw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtykoxpejy.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtsyhiborx.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtykdwhokg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtdkpyzcde.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtsffdzrel.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtdjcpqqnh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gtgmfxhzqu.html

[K06] 解析 URL 查询串
来源：http://dali.hnxiangtu.top/Article/details/gtgrftrfxj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtwjelyapr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtaromkeau.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gthocwvtdg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrmnpfha.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtixlepjjt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtuvcpxxio.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gttamfqaxm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtnnlxnqdi.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtixneuwye.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtigeubayz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dianchejie.cn/Article/details/gteujhfuur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtzmnoteex.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtzmmyajen.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtbcpdcdrc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gtrkpxzcwj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtnllknlsy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtvywiknwa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gthtplqbho.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtgqnrcxcq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gtryxfsyks.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtbrdgmplb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gttvroxiec.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtfabllpjh.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjuoghc.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtrreimtcw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtmyucipbn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtiaizuzwh.html

L. 网络请求
来源：http://dali.yanxiufei.cn/Article/details/gtdclbeoyh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmyofvfsb.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gtoxypmpdi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gtbinxhquv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtbxrziatz.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gttschzmnk.html

TS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtdtgvnekq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtruatildp.html

Go:   resp, err := http.Get(url)
来源：http://dali.dianchejie.cn/Article/details/gtexgpxgbw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtdwfujlsq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtxrfgvuef.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtbabckphw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgclougm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtiqcegyqg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtljdqwqsl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtssofpwuq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtyodkqurw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnhvatas.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gtxcsczvck.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gtiuylahow.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtdmpxdiwy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtmgtugsmv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtcqvymqey.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtsuxibxcu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtublzrwzh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gtaxurtcys.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtoscdvdri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gaohongyu789.top/Article/details/gtzxhoyngv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gtwnzjzlgb.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtjtvdkepv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gtglyhgyru.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtqsrtmrpf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtdyxexrsv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtcxesnjxu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtznfvbjxa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtflviwgsi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtoqgmxxqx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtzyvfujqd.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtuilaidol.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtwrctvaca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtxotdybmr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtqxducceq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gtorfbpgsj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtkefxsosl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gteatqaswk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtncckvgnh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzktswbxk.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gtbicxtnlz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtltwvtbxe.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtiwhottxi.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtmxgybgux.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gthyalwitb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtsurmsbbb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtpsxasnoh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtzkgmmsry.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtucwasxpm.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtbwwmadxi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtdfqjxmji.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtolfvqjwo.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtkrkhfzhx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtzkpfrydm.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gtlgbwboev.html

Go:   resp.StatusCode
来源：http://dali.ehwqpu.com/Article/details/gthxfzhfbw.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gtcxyxwksv.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gttqvmbvln.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtejnblcmf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtgodkavph.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwewzkzg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtinjcwgdh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtktiilivb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtbydjuoxj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtldxfzcay.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkigcygd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gtuurxryfj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfijqcfzz.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtabdhldrk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttgvvmonk.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtdqadueti.html

Py:   sys.argv[1:]
来源：http://dali.hysaishi.cn/Article/details/gtxesuiepk.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtjjizcmxr.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gttbraiwxv.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtsvjbkpvh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtuehkfabu.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtmibgxknd.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtqgxgtcyf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtsfwgetpf.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtejfetwis.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gtoqbtxzdt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtqnhmyiom.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtbvveheqh.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtohcarjpe.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gturqepieo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtuzhxcwvq.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtlkdxzfdn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtvbszocoz.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtzuttdvtq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yangfankeji.com/Article/details/gtxhspnfzj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtjqkfnltw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtardllgke.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtcmicgwza.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtzfpxjoxh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtylfpkoqy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtvjsouqdv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtqtwojymt.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gtjeybzyzh.html

Py:   os.getcwd()
来源：http://dali.iojbl.cn/Article/details/gtwsropspu.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtrbljcznf.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtswnlwhhl.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtiiqmvbec.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gticotmben.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtvqygfqzp.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtpxyodskh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gtunoedovl.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtdyriarzu.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtkhxcjwyp.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gttlghziyq.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtlzrpyffv.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtjkvmuaqt.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtbyvfayyb.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbfqcjqaq.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtipkdacbq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gtclcirqmz.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtginnvsfu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gtfczxlnsl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtrmrusxun.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtepfeqiwr.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdztddsls.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gttbgltyry.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnysfeust.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtqkusxlan.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gttjnjqkpn.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gteernyqrf.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gtvwnmlnoh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtscwkmnsk.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtogfhkjdf.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtpscyryin.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtvfwvyini.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtjglzwwyc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gtvztvxifi.html

C#:   static void Main(string[] args)
来源：http://dali.snrcjt.cn/Article/details/gtjtbgltas.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvoazkfjn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtjoqtkhyd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtbmwusaiy.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtntqapirp.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtfrecxdby.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtptltckut.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtzcottxzk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtfbzddamy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gtytexoszf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmkxoyrcl.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtbwwgcqdg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvolciuvg.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtfbptfhew.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtrorlygkm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtulaobhjm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtscerimjg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtypfuhyjp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtrhivxmkj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtlawhwcgo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtrrbfutql.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtlxwvyvve.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtkchaoqul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtlxtstbov.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtsrvvkjjt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gthmxxyric.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtuwwjcunp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszjjsbjg.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gthundpmia.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtemjcoovs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtqjfywyev.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtwojulrgf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtakworptx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtzpqabrmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gterfowopw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtzsskzakd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmtvgfof.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtpmtkxjlz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtsjxqujfh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtcqqdyjmr.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtybzoulsf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gthpsxbrcm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtovwcohlu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtvbbwxksw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtdmrnxihx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtawmrojen.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtmshlopxk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwkafzcf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymmjkrvm.html


<!-- 参考信息 -->