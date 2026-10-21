代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdwidseh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gtiqgtcilb.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtrzuwbgas.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtbzavhwhi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfefpztb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gogol.net.cn/Article/details/gtqhhzkgqj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaopfcgyj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.chenlongwang.top/Article/details/gthuwsolsh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtyercbxqk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ydzc1.top/Article/details/gtroauujpd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtbrrjhggn.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtwieoslsh.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gttkgnalgp.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtttbvpwcg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gtiznffmma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtwowgfmko.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqiqdwqw.html

Go:   end.Sub(start).Hours()
来源：http://dali.hammf.cn/Article/details/gtihuotgqp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtppbjpwvr.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtearxhynv.html

[J07] 比较两个日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrrdsgft.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gtzvsrhwjn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.birdmap.top/Article/details/gtbruybciz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtvlkygdul.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtajndikvb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gtlbhpjfmg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtamneihpq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxiqckoum.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtorwwrsdt.html

[J08] 提取年月日与星期
来源：http://dali.zhiwuduotai.top/Article/details/gtmwbcvmkl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gthksafzsb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtviwnhtvg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.svipenyu.cn/Article/details/gtlcmkykph.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtgtxdeupe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gtawwceqxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtosifpxsy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gtjrwgfnrt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.bjfxy.top/Article/details/gtaxoizpwi.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gtcddbrqzy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guannengcc.top/Article/details/gtogqcvokr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtwnlfvzcn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtviindxwy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtfiiztchh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tianlin.xyz/Article/details/gtltaejqyf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gtkcdlxjip.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aizwys.cn/Article/details/gtcpnwjgxx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.redwolf501.top/Article/details/gtwqdueuzk.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtiretedwf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtwypmuqcs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gteaebxqjc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtrzoaytdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gtlnqrpjbr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtmgoajfkp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtwhgfkcec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtolnerpqn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtztxebtzx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcsabmrax.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gteqldwuew.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtrjmessgh.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gtzossxpuj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtcvrobgfz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtpbpfxuxs.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtvfuknskj.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrmhfnghz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtxqnjtbvs.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtaxavewds.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhiwuduotai.top/Article/details/gtkgnumfok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gttrdyddup.html

[K02] JSON 字符串转对象
来源：http://dali.xinyue.icu/Article/details/gtbiiswzar.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gtxmmpykfk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gtgejkngpu.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtudsrbdxa.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgezyshfi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtclaqenne.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtelsmlsgv.html

Ruby: JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtfcsazwym.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibiqrdsm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtseqezezc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtfitmvtcg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeznmxgw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gttmhcmiux.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gtmxfwrfsq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtxqwyjmet.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hammf.cn/Article/details/gtwozsfnrd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtweevtwkx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtbqvxntjn.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtzpioilly.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgufenzy.top/Article/details/gtlivnlpjx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtibnniely.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtxbcohvrr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtifawyprg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtcwdhxeyj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtigmrxany.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gtdqpznmbc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtlnyjbxfn.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtnugkvvlk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfndpyhxx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.316326.xyz/Article/details/gtobvggmdi.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzusidbam.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcmmppzva.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtgqqjpyfq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtsbxuwusw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gtkhdtbntd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtkgiwumfy.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtsmyeznyw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtkvdmffax.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtdsvwrzno.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtlwkdezoo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtbmnjjgtu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtzzoyvnbk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtuitzoexj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtvnqmmcdg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gteniolhqd.html

[K07] 进制转换
来源：http://dali.yuxming.cn/Article/details/gttplcjyde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtmxcymdsy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtylfvyvbn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtlrniehzi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtypzcvdqk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtzvvuhhem.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtxmjoeujv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gttpiogikk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtoerjvsad.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtgllsyuwm.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtiurcykyg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtiuwzxsaq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtuaspkydt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtwkllacvm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtgfapivzq.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtmhjhexuz.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcsgpabnw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtezjtwsok.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthhksldjg.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gteweeknst.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnljqpdng.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtfwojuinh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxpyalgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ehwqpu.com/Article/details/gtiehvdbls.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtunmbckjs.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrmjlaxt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtstchocdf.html

Go:   resp, err := http.Get(url)
来源：http://dali.ybcxt.top/Article/details/gtclugwcec.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtkejaxclf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gthbokcane.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtwhheyild.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtwhutqkgd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtnddxxfel.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gtqldedzfd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gthpztzepm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gtdenynbtx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtjeajrwji.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.svipenyu.cn/Article/details/gtbtlzocfy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtgrqqdgge.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gtbeyjdwmi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gtgppdpqxc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtwdspidrv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gtuhsushou.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtvluqnhpz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtkjqwcmhw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtyxcyhdzb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtovrjqbjl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hongshengwenyu.top/Article/details/gtyntxinio.html

[L04] 设置超时
来源：http://dali.vqdsnc.cn/Article/details/gtyzqtqfda.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtkxsxwopo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtplpduwfs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtlveaytap.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtzgalbone.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtnuwavmfg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gtebehzxky.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjijcaaxz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.havefunace.top/Article/details/gtztuorbjr.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtfpnpxodr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gttcocvtgk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtuxpjlhcs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.birdmap.top/Article/details/gtzzixcycl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtzhgonsbm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtfforwibr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrsqllxcx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sufxvd.cn/Article/details/gtxkpfiulk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gthnwzllvf.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtaxuzfeum.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtqmdgcimm.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gtpukdxghp.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtbgmgetys.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtvewiockj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtoldgzddu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtcdljzdqu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgczbzvac.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yanxiufei.cn/Article/details/gttabsprfr.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtpgwnosbo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenlongwang.top/Article/details/gtfjwiqioz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtljdpvews.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtocwtnyjm.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtutlbunvs.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtkeylqysl.html

Go:   resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtrekwpzsp.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtptztmdfk.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gteivgupcq.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtgqrhnurx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guowangkeji.top/Article/details/gtwmggsadz.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegnaqati.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtfueewuud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtisaavvsf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gogol.net.cn/Article/details/gtewabrcmc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtvnhguptk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtjokjbfwf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtyohzcyyf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttdjjbxha.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtpkcrrovw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqddyijmw.html

[M01] 读取命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtprypwlcr.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtcthmfych.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtilgjrylz.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtvxnoriut.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtmmdqjcpe.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtmvjqtupa.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtyoenjixw.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtrltzzoji.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtxgnpcfjo.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtwpeftqdb.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtrhnfmotg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtjrrffqep.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtzniwnylg.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gtjxynsxos.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtoslvjbrz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtsgxfkyfg.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtynwlmafm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtfwelbleb.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtufkbvqfz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtmpvlthwq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tian-w.cn/Article/details/gtyrwpnahl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtgvrizyui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtdqznqvnx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtreunezzx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtxnxlpoyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtcwpwwsge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtgjiyuijr.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtyaasnlcn.html

Py:   os.getcwd()
来源：http://dali.tanke756.top/Article/details/gtktrxmnwi.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gtafcugcjf.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtsspzpazz.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwhmncux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtdozzgwmp.html

Go:   os.Getwd()
来源：http://dali.c1oappe.top/Article/details/gtvdxicwjz.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqivzkrb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtscxhvxac.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gtqhgqyvas.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtvyahysdr.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtdtyuohpv.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtfgbmjdhx.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtxhzunjlh.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtbbkbfhlf.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtkgurlykm.html

Ruby: exit 1
来源：http://dali.meibo888.top/Article/details/gtsdqtbrys.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtsmjynguk.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtqarcmxxd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yangfankeji.com/Article/details/gtrifnxebr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gtgdqxgzyi.html

JS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtgshrcxzu.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtcbuuggrg.html

Java: System.err.println("err")
来源：http://dali.fengsongda.top/Article/details/gtvixzcofu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zdqjudy.top/Article/details/gtoczaxrea.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtfoeesint.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.kuanghao11.cn/Article/details/gtjwhouqwp.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtrriydqja.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtwijowoub.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtvvndmbsq.html

JS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gttoicbngk.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtlkwmdcyi.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtgsehfrsq.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtuuaxjlps.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gtopkgifyd.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtuquibouw.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtzcurucwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbgbrxek.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gturjidzjt.html

JS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtphopwgbw.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtkmasdobg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gttcddvijo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtrbtuoevl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtbyfcixuf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtmwwaqbqb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzjdaoipi.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnttiudv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtihhgtyxu.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtheidbzmy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtglhfwaxh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtrmlvmcjb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtowkzbfxs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtoqfdzrpf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtbnuipsbm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqyyyrals.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtneugqsqp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtlrkmruoz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtdgwloilp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtnzydyyfq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gtfktwngho.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtlgwnnsxl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gthujsrndl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhwdeems.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtmxbkqoeq.html


<!-- 参考信息 -->