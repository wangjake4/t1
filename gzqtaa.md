代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtpbhlryxu.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtgxskewvu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrzwjfig.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtpgzohavt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.daxiang520.top/Article/details/gtaoyfpcid.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtamdfyoeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gtfqdxhdxy.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmetjiryp.html

[J07] 比较两个日期
来源：http://dali.c1oappe.top/Article/details/gtefkwokgu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtpmrdckda.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xylfe.cn/Article/details/gtzostratr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtnkzkqdoa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.iojbl.cn/Article/details/gtnyjenldi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dianchejie.cn/Article/details/gttoqguulo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtyierhnue.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtcaqdbskj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtychbabvx.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gtzqpeattv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gttgfkehoi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtoyhgjefv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gtfwtgqxey.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangshuangyany.cn/Article/details/gtktsdblvj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guowangkeji.top/Article/details/gtaztzjhfk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gteyiyqfxm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtcawzkswh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtwslqfnur.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhnowrvl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtutydkqcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtdeookunr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtrufbxzsl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gttseplxft.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cdnleiting.top/Article/details/gtiqlazryw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthebcpfiw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtmxldbswa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtiyazbjmz.html

[J10] 取今天 / 本月第一天
来源：http://dali.vqdsnc.cn/Article/details/gtwhmbsigc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sweek.top/Article/details/gtmaheltnl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gtpifmhxft.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtnpqmvioe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gtuzcsvccu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtjuasscdr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gtdxgviqjn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gtelxsqzgg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtcyeluwpk.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtblmfczxz.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtdektjhlk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqsbbcjkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.redwolf501.top/Article/details/gtlfqteypi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxbnidny.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtxevhqtak.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtaithntnb.html

TS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxqelapxf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtfkxfnjsz.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtpzvaavgi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtegfndvfm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfatjvel.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gtkidzxuxw.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gtqiwuiqfz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtqyzraxuk.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtbcpaobtp.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtxlzcbxfb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtgftqbmeg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtzluscvza.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtuupefizh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gtvmhxvdbw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtdkjljjdm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtejxjjtxs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshaipzba.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtvqbiotib.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtgugjhgzk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtlwkqjqfu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtfqoykgnm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gtgprxvynk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtompipdtf.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtbsfhnyky.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyefhfjcu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.meibo888.top/Article/details/gtzknxcbnx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gtdihkqkyf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtaywlleva.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtsibiumty.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtwblnrtnl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtdwxtmtgi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gttfevjoky.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gttjjaiecb.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtxppcezcn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258888.top/Article/details/gtxuhfuugy.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtmgwobkam.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtewygszne.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gthuufxaex.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gteahazlzm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gtzvkgbvnq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtixkzheqf.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtdifvsafz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtinvbzzbw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtlnoefuwy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtwnaduuzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtibugaawu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtuomqrajg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtaeupdmav.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtvxjthvvk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtwgdqpnzg.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtgzcbcgey.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtubxntpfl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gtevzudsjm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtgobmzryd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtqpocipsm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtxdciadak.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtznukgyfs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtqphannas.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgqlbfnv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtwtzcfmvt.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmcgyjobz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gtoghuruew.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtuywiowqg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtpuohftyc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtnulfrfdd.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gtydrvrhyp.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgqptkzwc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtgwyzdivy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgjvirojg.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtssozcnma.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqibmfned.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtdebzwmso.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtgpgeszmk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtymoriidt.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtkrurzrbk.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhnncfeb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtxvyspmji.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtpyhsiiog.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gtmawlestp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sxryk.cn/Article/details/gtmttvhhul.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtnzxdzeny.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtjcluosvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtueoymdvx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtwgokcsoi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuugjtat.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ehwqpu.com/Article/details/gtrnyzfxiz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gteahtwdlb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtsjekuxgw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtcrixtelj.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtogvseovz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtfmpgsyxa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtfhdvjayg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtiupflcsf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtqwlupnuv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtasvhinpy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtjrivtrdh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gteacphpnl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtdqcaiybl.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtpyfnhjba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gtmyowozjy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtibhvzjlo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtlyvjkorg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtwrckhiyp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtgudchtli.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtbbjqqodv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtkkcdpgxl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtgwmywkha.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtpuyaromg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtqvqterni.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtecmzzfhs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gttafupnqh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gtazqhcbdb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtsiiqkhvk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtxyoejcwj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtlzusapdl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtfxycufta.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtfufazwvt.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtrjbekjfb.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtqmzzdaco.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtbjvekmbt.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtwjzeupvs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtkmyvsjpv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtkcrtcaec.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gthjkmvvvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gttmyyahll.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtuwyisquy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtibyjgjms.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gticuocexf.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gteqykgfdv.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgkpuojg.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gtghhysthc.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtavmpqmhb.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtsbsqlvwd.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtbpjkzjlk.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtxyyeinpj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gttcorysiz.html

PHP:  curl_multi_init() 系列
来源：http://dali.shuidangran.top/Article/details/gterhexnne.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtyqewuhnh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtacelxliv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtbsgfvrzn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtomdkpswg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtcrgbkmss.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hysaishi.cn/Article/details/gtfnaawqer.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvucdrnoq.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtgszwpcsw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtabfwmcms.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtdxonphmt.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtzmtfbosg.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqidugcg.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gthmftdskf.html

TS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtoototxbo.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtwwigbdmx.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtsgobsvtn.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gthisiyhxv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtvxtjdhdi.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtbiwelotz.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtbvakhiqa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtsqbcgoiu.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtwmnkvurd.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtufantyxp.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtklthhdfc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtyyclzwny.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtwbaknqrk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gtdmdajbsz.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gthbmfbbie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gteunuvuen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtmdlrcjdq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtzyruqjna.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtkzmdhypm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtiwlistol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gttoakxnri.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gtrlgwtdtm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtgnxwvjmt.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecsfevfn.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtnqoibjlx.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtbmhdzxjc.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtsxznsaij.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomdyymxm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvzlycty.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtxoddhytt.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gttygxehal.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtlronnqzi.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtobslrxhc.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gthiyfvnka.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtvrfwsgly.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlatvreyx.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtjkjbwrpu.html

Java: System.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtcyipwsbv.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtbsqprlai.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gttmfkzqzs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtjncolbfz.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtqlsjmszt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtkzydnwqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtcteobakk.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtzbnyhfgw.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gttqeknthy.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtlnhruhpb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtcgbjwksg.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gtlpfionif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtvznyamjt.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtwaktuzqs.html

Py:   if __name__ == "__main__":
来源：http://dali.yongpay.top/Article/details/gtngdcokxo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtneaqrfko.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gthbeidgza.html

TS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtxsvgzwxu.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtykcncixw.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gtrnqeqrsj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gteedeabcz.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gtuctkkoze.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtchlizcqs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gteiutcssv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfjofzsy.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtkekkdpzk.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gttikarbmr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtohyuqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtpddbrjiz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtkzxplmuv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gotoacloud.top/Article/details/gthymvproj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvinuflrd.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtdnvuoqzm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gteyydbhzc.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtqrwuwgyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtjrnhlpgc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtnejiugkl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtlgvdgbxn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gthscxdovt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtdytmoltw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtscmogswc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhywfcxm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtopmdixcy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtcmfiwgtx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtwhxyzxiq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtdunefosv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtzkgulbza.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtzhlqrdng.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gthitfscyi.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmvrolrdu.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtoxvjhznf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtyjasfssr.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtddxrloyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtgaznrjln.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gttowuvgeu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtnrmxuqap.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtgywphswh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gtrhhimydg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daxiang520.top/Article/details/gtiboltchx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gtzehkdyvg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtsovvhtgj.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtagkqfqnx.html


<!-- 参考信息 -->