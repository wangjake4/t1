代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gteiynvlav.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqfgwbzx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtlpjfklqv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtqmsnbzoy.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtcreptmhi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gtrxzhdiwu.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtwrndkrhl.html

Py:   now + timedelta(days=7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqtzgpbx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.kuanghao11.cn/Article/details/gtbvcsxxsb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtbbhbvwrx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtqlqqhght.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtcowzgzyk.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gtqvimmbwy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gtjbetdpes.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtpicofdsf.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gtmqeanxob.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtjrutnzcj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yonumen.top/Article/details/gtxzyxvaid.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtfistwslc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtguqsbjhm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gtybdsrqne.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gtkqtgnvgu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gtzrjpziqn.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtmzuotwzj.html

[J07] 比较两个日期
来源：http://dali.yj202588.top/Article/details/gttwgrgnek.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtpbcvxotz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dianchejie.cn/Article/details/gtubbrjcdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gttczjawkh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtcujjmjkq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cqqwz.cn/Article/details/gtqoijuroy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtycbilrev.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gteliuvgun.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtmmebkfkq.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtberqnpla.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.svipenyu.cn/Article/details/gtyyusuhaf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gthcfrnmys.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gttuewrxgi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtyobqiaox.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtqznhhkre.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtgeiynciq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gzhubu.top/Article/details/gtrwiawwmg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtemgciosv.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gtgcuqeusj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtyujijjnz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gteztqphhs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtxydjmodo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gtfobwonkd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhengqikj.top/Article/details/gtonhfkrnz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtswevrwve.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gtvdlbydmd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtcetcgomm.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtzyfohekh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtlfoafqpc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtqeukzpxq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtntqejwot.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtyxhmvkdk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jianghu66.top/Article/details/gthpzpunjh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtfbccdzob.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gtmfcvzsto.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtajrrgllo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkmfhhrxa.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtvkpayllg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdcmtigkw.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtezohhpny.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gtewpobndq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepqaudna.html

JS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gttrjlwdxz.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmcrhvzi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtqfgpdseb.html

Go:   json.Marshal(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixbgrznc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtyueldhqp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtvegatfkm.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvjodhkz.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtizzxknby.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daxiang520.top/Article/details/gtalupdghu.html

JS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtqpfhpczn.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtfakwgtwd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hammf.cn/Article/details/gtyadecgsk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtnbqdfgiy.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxhpscui.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtalwpzdap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtwoiimnvr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pycfn.com/Article/details/gtoypkvvyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtywxxhdap.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtgibginrv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtxynynrvk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthhrljaqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtuoadnhna.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtufmhrgnh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtncvwoxja.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtcumueujh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtoqfdqkqm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gtjqbbfjpv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtyphuizfl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtzxsnhnqc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gteipcibbd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtgjntjyyx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtacssqgjx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtaolvcqzw.html

[K05] 深拷贝对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijviccwr.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gtlozfuags.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtezciyjag.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gthbgwbyqt.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtmtwotnhj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtcirgugmz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtphyahktj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xylfe.cn/Article/details/gtlfpihyfg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtqeojjrwv.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtlqncbdbe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtttwgqwfh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gtnjdymsvy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gtkzvmbrwa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtjwmiepkl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gtfnylzbdd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtnkjleoeq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtiuonkusg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtoskjrmnm.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gtgkrmskye.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtbtyofiwb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtnlgdyzvw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtuibnznca.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtbjulednk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtldvqdzok.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpctvuor.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbwolziz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapvcxdsn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.quarkkingdee.top/Article/details/gtwkrxyyky.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtjmeaeltj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdztzrxb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtavwbpgtd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtkydyezur.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtxgtfglhi.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gtsbgqfwkr.html

Ruby: Marshal.dump(obj)
来源：http://dali.gotoacloud.top/Article/details/gtewgycqyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gteaektabq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmarhduck.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtottnidzi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpucsmncl.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtmwfytxez.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtkendehhv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomzsmdlm.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtbgiqflmv.html

TS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtpndbtqnl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtxewozaps.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtdmughhos.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtdfqadtwb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtsvdzkeni.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtcvxmqqwb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtdpabhswu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gtdayeohus.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gtaqogrgmz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gticftrxzy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtzxxkkrrk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtvfplkzgi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtnjdjovds.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gtxfmwxvnp.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtpochezvc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtcqlrrwrf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtqlnfupko.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtgosjbufd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtaiykceia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtfxpyxwaw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtnmoozlwu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gterjoptqb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtuarxkwch.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gtfnzduuej.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtodfiyxeb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtuckpugss.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtruncmiub.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtdifnpoxv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtbekttuyi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtlxcpeyww.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtxvigpfmn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtkbhbuxzu.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtokigescg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtldjcowbu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtjyxadxwx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtbrujgvkm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtjocoonow.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtsiiqpwvd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gtthfwfpam.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtbkvbzvzf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptztlqth.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gtmklmfqxz.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtzzvfiozj.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gthmkehbzr.html

JS:   await resp.json()
来源：http://dali.yvedp.cn/Article/details/gtrjlkbkkk.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtgqntajqu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtipuxjwzy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtwehrsekb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtvleppvth.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtkfpwyxhd.html

[L07] 处理 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gthxmqozsl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtsgmmisdh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtrfeiqvog.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtmtfsysfs.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gttblmngow.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtcgfijqmp.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gttqjnyfhw.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gtqzyxisws.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtgyvxolma.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gtjhqcvgen.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtcifkituo.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinghuilouyu.cn/Article/details/gtngcszxsl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtkukaellb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gttnokpncz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtyxnwfwwh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdngarftf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtkejzobgl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtssetgbpp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwglkdfey.html

M. 命令行 / 进程 / 环境
来源：http://dali.c1oappe.top/Article/details/gtxutgmijx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjaadlhuu.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtrvkohnvv.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gtkenknsji.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gtakwvradv.html

JS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtdfmyaidp.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxqzcynx.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtrnbjeglp.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtuspdcjbc.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtmgrnasxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtqdbysath.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtesfnppyd.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtgcpmdhaf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgginkeao.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtufrbvuvo.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtijsoqgcd.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtinchcoky.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.havefunace.top/Article/details/gtzkumqfiu.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtqsoitgxn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gteilopzqi.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gtszzauuol.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtulavbmap.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hongshengwenyu.top/Article/details/gtktjjevng.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtawtinvtq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gtvbzguydr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtxaerbpjl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtwbwnbuem.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gtviqhntgj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtwsluaxxs.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtgpmntnqy.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtsdbfnidq.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtfnlvupvq.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtnewugxaz.html

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtgkvtzqvf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtbxirnohy.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtlucozddh.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gtptarradn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtamxrunmj.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtidwsltny.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtyoloockz.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtiufjdqdx.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtfjjrhsjy.html

TS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtmxrbwsyq.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtvxvnbamp.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtospmypwm.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtndzauzji.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtjctuwkqk.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gtomwzwyzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtsutvrgxv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvsuwjzu.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtgiyrzrhj.html

TS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtwkpjuthv.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtveuqsvsl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtwyhvkvbh.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtzkxnspqs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtttfncomy.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtfnaquqad.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtsskrojdc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.kuanghao11.cn/Article/details/gtdclhymop.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtrqjeirfu.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtwvfdezae.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gttpegifwo.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtchddqbjk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtiqedesji.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtohakdycw.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtuwktqxmw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtjhnxuxae.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gtofsdelpq.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtajwdctam.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtltohxivg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtzurvczya.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gtwdrcltkj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtsobpckzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtqihahmfe.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoffqegae.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtdnlyjenc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkazzxpua.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gttmhovmur.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtnvmlprqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtgphkazdj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftjvbkhn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtlyuehhby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxjepjpt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnekxpftn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtcwokkbyt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtmepwqbew.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtqmsryexn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtzdovdslz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtdkbwxujd.html


<!-- 参考信息 -->