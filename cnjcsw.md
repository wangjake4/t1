代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozvgrvzi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtkiobtrpf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtjivdhtea.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthdkiddni.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtyqunfzbo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkofzvces.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyytcjyt.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtfpilsjbo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gttepulous.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtjtucntoc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtfqamrpkc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtsyqjskvw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fzhhl.top/Article/details/gtozbsybyd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtgfgeghov.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtvclytdbh.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtsjdldjfb.html

Py:   (end - start).total_seconds()
来源：http://dali.shangyingyoupin.top/Article/details/gtnxsfumwv.html

PHP:  $end->diff($start)->days;
来源：http://dali.sweek.top/Article/details/gtckvvpkwb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigfzy.top/Article/details/gtguzvbwsy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtlnnpgbwh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gtpktiyoza.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtuynemcma.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gttggarsry.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtjdpohtix.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtgpphqnux.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtdzkkjkdy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtjqorhlia.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gttmndpdyk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtquvccvjf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gtqhxtnhfv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gtrmsxwure.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtzvntsjza.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtezmvtjdk.html

[J08] 提取年月日与星期
来源：http://dali.quarkkingdee.top/Article/details/gtflnvhewq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtjfjrnlue.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gtlvdtzmwq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.9152youxi.cn/Article/details/gtczfrywpf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yongpay.top/Article/details/gtvlnpogff.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtkiwkvzxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtekmcfeme.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtictsvqnr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gtrbpdjrjm.html

[J09] 时区处理
来源：http://dali.xinyue.icu/Article/details/gtkhupqzgm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtwkvvyeqh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtmsuxlknv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gttrbyqcjl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtolldmuzh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtfzmilvsx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gtuhnkoxhl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtgshqcpou.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gteosfbqis.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gtomxprihc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sysykeji.top/Article/details/gtfzjftkzd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtyyajtugd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtgevjupce.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtvzayyrty.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqndqmipj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtljpijdgj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xylfe.cn/Article/details/gtzdzptkdv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtfnvhmdnl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthwauwrgh.html

K. JSON 与序列化
来源：http://dali.feifeiyinyue.top/Article/details/gtazhpsmot.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtujdocgxe.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtyrqsblal.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtuimmkasc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gttyvhprrd.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtxgpwzybi.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gthhhayfuj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtsgmfpzym.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtwktiqsmq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtusbdhhnf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwfedvpqp.html

[K02] JSON 字符串转对象
来源：http://dali.bjfxy.top/Article/details/gtjvjqnoyb.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtkjgbrtbj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtnomqrkhr.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtuguojjme.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtwyqtxqxy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtvwdsxwss.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gttwmugqhm.html

Ruby: JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtfalljcfm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.redwolf501.top/Article/details/gtrcwwofsg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtvvlawcqp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtmfxdwxyk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtwqxllfvt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gttywdtpxa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtnhygpfle.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtbabutdus.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtcrknjypk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cucudq.cn/Article/details/gtucmxoxwi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gtmerbeugg.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtkislmyju.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpfalkgot.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.vqdsnc.cn/Article/details/gtzufeflux.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtxxhotzrq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtywisnxwz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtmtvfbkzh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtevcmjskq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtwfubpawg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtondmjocp.html

[K05] 深拷贝对象
来源：http://dali.cdnleiting.top/Article/details/gtxinuigyu.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtvoueothn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gthqervukd.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtfdvzwqey.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gteaqdtrwd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtrdgedrom.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtxldhusvc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gthrfcpnlj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtkhkhjykp.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtoyieqsow.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsgnxzff.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtfjqtfvef.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gteyzptojp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtjntwoegx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtzmbontkg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtzcpbcnen.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtxiqbsmvg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtfkpftxwg.html

[K07] 进制转换
来源：http://dali.haohaochexian.top/Article/details/gtumaglibw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoywosbd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtymmzztcm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtakioxmky.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtawgalrgs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtjltutlue.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gtltpqnhrw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gteryfcoaj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtrsginciu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhengqikj.top/Article/details/gtuxcobino.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtflmhoqft.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtplzvgrte.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtgviljxyn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtcdilsqsk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtjpcbxklm.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtmmlxyryp.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtwoosoyup.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtxiodgvul.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqaczgigj.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtpxtksxjj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtexahqmsd.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtyowqrmpm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jianghu66.top/Article/details/gtkouxjwov.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtpbqpnhsu.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gttezniuty.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtrgmxunde.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gthcopbujo.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebssvhdd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gttreajfzv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtbnxigrpg.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtgytstqtp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtqyqlykpc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gotoacloud.top/Article/details/gtbjcatyqh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtntvtfazu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtrleairmf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtkirupsdw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtfpnjsylq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtnldqlsya.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtpgjygdhr.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtctxtlrxl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtcfssplai.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtckbqnniy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtpigrdtps.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gtmznskrgr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtowylltsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtjkekeaxr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.iojbl.cn/Article/details/gtshjddqmr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtenvmrqsz.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtgdnboqoq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gthtdjsrsi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtfzpppgux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtggegcqtd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbhteaqq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtmwgjhuzq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xylfe.cn/Article/details/gtdhncybld.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbedszwuz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gtqamkfamx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtuuktpscd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gtrirmswnz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtvivukmqo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gttwqhlsdn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gtofkeabor.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtffwosssy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwoaqlfw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtswyuvapo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtwrysbkpe.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtmlooesdh.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtstcegqtw.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcplntvts.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtyitlmvym.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtxmebpgvn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtuzdirvwy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtiildkolc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtqhegxihq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtcbxqrgkc.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtqovcsgtx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtjokomqfe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtnecbskmy.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtuihlhrvh.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtogeuield.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtijavskwk.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtsxiybrob.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gtlgvexhxg.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtlvflakue.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gthzhipxkc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtardqvxri.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtvrcmqeuj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtzqzxeelh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtapqwotws.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gtxucsuloc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtijxunjvr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gteqycihxo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtpsoeghlj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtouvzgkoj.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gtygkhirlv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtujwkjmlj.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtfmtqzcma.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gtvfbbmeph.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gtegfttsza.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtboamiumj.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gthwnjsyrz.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtzpywduvr.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtfcxllbaa.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtouzgrpwu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtdnovlwuq.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtxretrbug.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtjxzvmbxu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiqdsoxg.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtstduqmca.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtvrzcahmr.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gtktvzvyfc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtxacizsky.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtexuhjdua.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtbsoetnvu.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtgsxmnisy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gtynusowfp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcxttewn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtayljvxwc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtideageyr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthgsnlct.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtfdyoykgg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtenbiiwlm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtazzzwsfu.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtvrneixlb.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gticmgzrbo.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gtninykntf.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtyltmtdap.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtyumbxvso.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gttehxcost.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtozizzlkq.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtdxxxclyf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gtwlqtlamn.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gtpcnlrllb.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkoktumxa.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtswmiztsd.html

JS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtygcfmjsb.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtrlslqiku.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtfcvckbci.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtbwveuwqa.html

Ruby: exit 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoexirkyj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtxppvnmbu.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gtymjnfeok.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtofgsllww.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtktwlvxnj.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gttmveinzu.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtrnwuiaxx.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gthkcnlbxr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtnqxviqbg.html

Ruby: warn "err"
来源：http://dali.ydzc1.top/Article/details/gtoonxvdfo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtkgibvhla.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtydrvuuey.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtyfydsvqr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gtlslbrtch.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtiyosxrbd.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtvugpqnwa.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtnpglqpis.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtrqqxktnz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtkbbqepyn.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtyzvaxcbh.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gttezbhkhz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gttyfxdznd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlueibmr.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbnfuywl.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpppsyrdb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gtjmtkcqyl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nwbrower.top/Article/details/gtcsferhkm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.snrcjt.cn/Article/details/gtvzvlxfxl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gtzejizijr.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkvexmxuw.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtlmaynazd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkemzoeeo.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtwwneqbom.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtrxyrtunt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtjxfllblt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtvpfhzdaf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gttjjrtxsm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gthvgjalrw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtucuwqfbs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtkkqdntvc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtasairgku.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtdkibfxaf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtmgzjzlmy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ybcxt.top/Article/details/gtddsnxcsp.html


<!-- 参考信息 -->