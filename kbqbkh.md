代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtwnnihmrf.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gtruifcssj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtrlthxfpa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtwxpppopf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.quarkkingdee.top/Article/details/gtrcntzvbc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nwbrower.top/Article/details/gthqwxefpo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xziqi.cn/Article/details/gtbdftvwtc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhengqikj.top/Article/details/gtfrafzkql.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gtjzvcomes.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtyufliylb.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtjnjuvfnw.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtxsaaeedo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.0kj1m.cn/Article/details/gtfsyvjdpr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtngvfxbnx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtadegwcob.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtlhvbyvkl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtlwohpmaq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gttpohrlfp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gtkkgdvkwi.html

[J06] 计算两时间之差
来源：http://dali.feifeiyinyue.top/Article/details/gtawopueug.html

Py:   (end - start).total_seconds()
来源：http://dali.vqdsnc.cn/Article/details/gtesfudizg.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gthzipywbx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gtnzdavukj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gtvioesrns.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtsbvsuegh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtabnybreo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtqhoeiexc.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenjidiqi.icu/Article/details/gtwnbqkimd.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtfsnbcmnw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtgezyjohb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ppjwa.cn/Article/details/gtvuecyyan.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gtsfyapvbk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jqgfzy.top/Article/details/gtovwevvtc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gtswtvfgat.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtccfakjad.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtqiamrsfx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gthyvhjnsy.html

[J08] 提取年月日与星期
来源：http://dali.zhixingplan.top/Article/details/gttcvhfibz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtfyndeodw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtjsahbfou.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zycfv.cn/Article/details/gtttlmnivt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gthzxedzsb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtqzkgxmyq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.vqdsnc.cn/Article/details/gtkxtmwxpr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtchubiwcd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ppjwa.cn/Article/details/gtejjbuupv.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gttlvgfxnv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtmxuqrqsm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cucudq.cn/Article/details/gtrbtjlzxn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtgrqqkcnq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gtsblqexjb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sxryk.cn/Article/details/gtpowvoztr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtynwzmpuc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gttacrhtji.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtzieonhmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.quarkkingdee.top/Article/details/gtumtrcvyn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gtvfiuavzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtwlehfvlr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtshxbfltr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xziqi.cn/Article/details/gtipiepaug.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtnrmedlka.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiralyrf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtsrzdelsw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shzxlz.cn/Article/details/gtaipktwlf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtptdmhhgn.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnalzreho.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjwmgeyqi.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gttqsvdxml.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtiuibomvf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtsawmfmlz.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqxwflals.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtjyunduxj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.c1oappe.top/Article/details/gtrebaecni.html

Go:   json.Marshal(obj)
来源：http://dali.yuanzhike.top/Article/details/gtpabnliod.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gtpzgymoee.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwjhhwli.html

[K02] JSON 字符串转对象
来源：http://dali.ydzc1.top/Article/details/gtddxbnzxq.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtzcrjihwx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.feifeiyinyue.top/Article/details/gtahgqjrdv.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gttzfnftms.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtinavbngo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtmkrubabm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtbfbcyjiu.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gttxtjenuy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtpauodcld.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxzhrngv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gttbxllgug.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtuaqxvvsx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtjgqchlai.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtgwtefqvm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjvecxsvc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtrbgmkitd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtrslsvcrl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gtmsplqynw.html

[K04] 读取 JSON 文件
来源：http://dali.zhongyouzk.top/Article/details/gtisrfrhgr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtdqsoduzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gtcouhemqh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtufktgrot.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtfeopgmbw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtbhrmdygt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtssdswydj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtdmdfmxrx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgfzy.top/Article/details/gtmrkegexa.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtpjbazwuu.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gttgbbzdca.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtlfjkiueb.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtjjvbgugz.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtcunwosmv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtzwialfdv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtzdeedypp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtllgaxcjj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gtdffopefg.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gtlswztpsz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtmklujqia.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cqqwz.cn/Article/details/gtafgegsjz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtkmlqwtuu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtfayfsazi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtbiwdhino.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gtubwkzjqj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtotoaojms.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtaxdtjftj.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtqxsnhyld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtjtyeupol.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tianlin.xyz/Article/details/gtwklyvzhe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtkrbgtpvw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtfesefvxu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gthirnemor.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtchrbjxsl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtjrzeekbd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtcanypivk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtkwdtiuqu.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtgjzgkcfz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shuidangran.top/Article/details/gtfbcprqmc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtvppihcqi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtlasotzeh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtrvjmiyto.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtbutoukwu.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtufaxxrif.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtjimberwh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtofisyyep.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtfvstfjte.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtxxingt.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtizawqaju.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtstknwbgx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sxryk.cn/Article/details/gtpsajyies.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtymqdhqno.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtwwvmyzso.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsrwhpnu.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtmphamodd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtpychfvlm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtmelhhzqu.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtbybrmwas.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtgsgyyhcc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtevkpidrk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzpvucko.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckgyakrq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtlyqumnrc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtjizalkhy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtwfzfoovd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtodbqgdjl.html

[L03] 设置自定义请求头
来源：http://dali.wangdashe.top/Article/details/gtimvresiq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shuidangran.top/Article/details/gtbcxcyosw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gthezfitmz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtxjeldbng.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqovtxaji.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcslczqa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtfuslbmgy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsibwxejk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnutgghcz.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtihbffjeh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtewfwbuum.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtdxewzqvi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtrbpoumda.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtyjjgawoy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtjzxqogyp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtogzvlkwb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gtqkgpdplm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtsibtnbsr.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtegkqkkpm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dianchejie.cn/Article/details/gtbtmrzihq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gticoeehta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gthaqrxljk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtjmgvedjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtuspfqzam.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtpfbjaxky.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtgcblemoe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtmemgcvkg.html

[L06] 解析响应为 JSON
来源：http://dali.jianghu66.top/Article/details/gtzxvifrsb.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gtrkrttsvl.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtmfxmmmao.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtgpbljfnp.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtbuyhkndd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtadqamxel.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gtyuvlfcyi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtggfhfbbw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtlnvwsndk.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtnigqxubk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxinkj.top/Article/details/gtvcxlubqy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtfxziqtaf.html

JS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtyywzpsvz.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtrciocugv.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtqwxzujpl.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtmljgzpnr.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gtmyhdtdwt.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtxcrahkcl.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gttdobfeqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtazgtofdf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtwenxuvex.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtlbyxacab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtlsfpokgy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtuysytkac.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtqubibccs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtliuiynuj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtfyqxvyyv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsmohjbnb.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gtigrurnmg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteffrmcgb.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtrtmhxyzb.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gtwxwmbmnc.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtuappjynq.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtxmpmtdqe.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldlbtkep.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtrmaezgqa.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gtpmjlukiw.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvvkuscp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtbdaalone.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtwopyxxpg.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtzcclfrxn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gtmzstxfet.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbksddoet.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtbeonhvum.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtoktyczvh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtfcnneuxg.html

Ruby: ENV["HOME"]
来源：http://dali.hfpthk.cn/Article/details/gtvbowwgod.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gteanaesok.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gttbithjet.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtgukhchfl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddmkspol.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gthvcixysh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gtyybtbypp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtwtvdaqmt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gtumimviaj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.havefunace.top/Article/details/gtmptlcnmr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtvhredvae.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gtjzqnzstl.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtxwiqzmvx.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtnstjnplv.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtwpypsbhj.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtiwtwqjze.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtnqwbsjsp.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtssujduur.html

Ruby: Dir.pwd
来源：http://dali.jiagoushi.top/Article/details/gthiiugbyv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtrmandxms.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gtcazgsmbm.html

Py:   sys.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtlhdvxwxd.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtlvmvxowc.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtwotqnxrn.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtvktvtpjo.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtyeimeupe.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtkuhnhhno.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtdywmxsjy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtsjdzyebw.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtalxklbxw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtgccyrayd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtvpxwvtaz.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtyexahtdu.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtmfnrsief.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gthikpkyay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtpwqnvuha.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtfwubvvik.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gttzxveksv.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtpajpejtv.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtlfszikva.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtybkgazjv.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtmocaznsw.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtfdojtngr.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsbbogep.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gtmkslgdes.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtsnrtzprm.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gtyoypmlfj.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gttcxjzjci.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yvedp.cn/Article/details/gtiwvoujto.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtzlamezcg.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtzdovcapl.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtmcylruic.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtqhnrqish.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtskqjiald.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtsenpqbgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fengsongda.top/Article/details/gtsziovtqe.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnguuhbqb.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtdymdhsqs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtawllwrsy.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gthukqxvjx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtqkkoamev.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtufetorjc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtysxbdilx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtgsbgkiqo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtmbgqvovf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtoumzaxsf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtccfhfkir.html


<!-- 参考信息 -->