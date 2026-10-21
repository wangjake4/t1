代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthikrxdfa.html

[J04] 时间戳与日期互转
来源：http://dali.zhongyouzk.top/Article/details/gtikbirile.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gtnvsormjk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtesovbrxy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtvqoczbah.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ybcxt.top/Article/details/gtuqlxzvcg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gtsmbuoxix.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtglrfshhm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtaxeufcli.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtqslbdouw.html

[J05] 时间加减（加 7 天）
来源：http://dali.gzhubu.top/Article/details/gtivuqkibf.html

Py:   now + timedelta(days=7)
来源：http://dali.hywenlv.cn/Article/details/gtuoiaodoj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.bjfxy.top/Article/details/gtsagxzbzk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtocbdmbmx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtjiyeqqyt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtigsvubak.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtgevhsqmz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzfnrmpx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenlongwang.top/Article/details/gttvmljjdg.html

[J06] 计算两时间之差
来源：http://dali.zhixingplan.top/Article/details/gtwfjwxals.html

Py:   (end - start).total_seconds()
来源：http://dali.cqqwz.cn/Article/details/gtqlgiqwhy.html

PHP:  $end->diff($start)->days;
来源：http://dali.0kj1m.cn/Article/details/gtweykgmkg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtrmcrjscx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtmfqpiyld.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtfocsumjx.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtrnumdfjo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpatuypnf.html

C#:   (end - start).TotalSeconds
来源：http://dali.dianchejie.cn/Article/details/gtutbmywqv.html

[J07] 比较两个日期
来源：http://dali.yongpay.top/Article/details/gtskfrfbgh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtfuclqkab.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtfuzgxiqr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtwkuoofca.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gtbmcwqapu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gotoacloud.top/Article/details/gtnplxbfdq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtqwciblfz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtycakhukk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtfbdsjwdn.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtdiwdmusp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtmbyfolyi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pengpengdd.cyou/Article/details/gtmehqmkel.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gteyuhfajd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtwnnqnpyn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.daria6918.cn/Article/details/gtinwkksws.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtsahfux.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtvhwgtiyf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gtkhswmsvu.html

[J09] 时区处理
来源：http://dali.jinqigfzy.top/Article/details/gtnjrbkxzp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ybcxt.top/Article/details/gtsyrlvlag.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtvuyexrla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258.top/Article/details/gtaxfjcogg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtghppqkyo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuetiantiany.cn/Article/details/gtknethylg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtcvrakoos.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtdvwowtqb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtbfncdjwi.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtypgmriwx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtncqqrado.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtbakjgnoh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtbdzxcwby.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtyamldztw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daria6918.cn/Article/details/gtqxoxitrz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtavbcukiq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtarfuugvz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.316326.xyz/Article/details/gtdobjpnnj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdsgnhupc.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gtcnmajvnr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgkrjvmnx.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtxkjjhmlc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtdsahlwwo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbltjozn.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gtduncgwta.html

TS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtlouydqop.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtugtwmewh.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtywddrner.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtpyracwjk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj202588.top/Article/details/gttrxoiopa.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtmtqxyatu.html

Py:   json.loads(s)
来源：http://dali.guannengcc.top/Article/details/gthtezztgk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gtqucyqvje.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gthxzqpart.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedjojqav.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoimjfnnq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtilvzlzun.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtcnimqwag.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtbegwcgop.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtwtnvduij.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtvsmcuamm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtdbtitabw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtbeicunnj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtxawpjkca.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmhhzebcy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gtotvsbhmn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gtrotahzgk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtmcoyvokc.html

[K04] 读取 JSON 文件
来源：http://dali.xuetiantiany.cn/Article/details/gtjxyadsai.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xziqi.cn/Article/details/gthofsdocv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtrsiqqrlh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtnvrlymhg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtywxqogph.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtacihyhoz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gtgybubmss.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtephvgkzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtphjxdffk.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtklrkqvth.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gttpeczjpl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtoqwymgbg.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtqhuaymtv.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtecgogwaq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtqmqnhfpb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtlmyymepf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yangfankeji.com/Article/details/gtkbvspzez.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtggkmguxc.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtgrjcuzrh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtpgqhfkap.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtyhperluj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtewszarqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtywmrjhqd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtbqgemfjw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtscpzaznf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtabxvtjpx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtvqlvvkyq.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtwvpvtnya.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtbbuhbgow.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gtvlhvwirl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtjpiloeus.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtnwxhiemi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtfqyewnup.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gtcwpfcymg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gtewdmpuum.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtbqtdqnuo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.redwolf501.top/Article/details/gtqsdphhqw.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtriscyjpb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvkyfsdcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gttbtaviin.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduhisylo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtopwlevcn.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gtrmyaxtmi.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtpkwreiff.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gttofbeqix.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteetqzslz.html

L. 网络请求
来源：http://dali.quarkkingdee.top/Article/details/gtzwojxmxe.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtduypvlvn.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtbbjhtcsq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gtfvgytffz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gteeghbpfp.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtdghwaoqb.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtiucrytal.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtdejkylnl.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtghzkuadv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtocjrvmpx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtasmodpjx.html

[L02] 发送 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtqnhnniyu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yongpay.top/Article/details/gtmwbovqeg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtczxfjbhv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtyonikplm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gtsarhzymi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtfyczniuw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gtfmnoswgq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guowangkeji.top/Article/details/gtmsltufsg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtwupferfb.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtlxplnrss.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtoguouagf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gteiywjktn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtfywerjgq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtypyxftfv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtgscyatzl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtqppumuld.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtpjnkpegr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtquququey.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gtoyxwkihz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtnydcgfoa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtlhssetdx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtiblejyxv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtbmafuewd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gtrdxhpuvo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gtetbghrxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdveldjmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtkgowjtrz.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtpyxjnakz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gtwqfphume.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtnsaaelcc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtgnrsrswm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtaufprjme.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gogol.net.cn/Article/details/gtrwtovnzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gttrwgyfrk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtpthdglyy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtiuootmku.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtodtxohrk.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtsdkcmitd.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtnyadppve.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gthvlzrkdx.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtgqelkjtt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtnggdhdgs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtjkdramrf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtprjkoyrc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gttihlmawd.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtkjxzxfap.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtiyomicod.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtozjpqwtt.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gthjjjkqni.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtxfzreoij.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtzeuffxlq.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtgfviouoo.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtkwvwhcvj.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtctdficyw.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtkyecsftn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfhinpij.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtlgiegtmd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtjvjqrxte.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtszvlmdfm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtvuljqwxz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtjrtdtdni.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtdqhtzssv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtailplyes.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtyapjlyyl.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtzkuvsxxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzerfkanv.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtdlbebczs.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtptkfnnuy.html

PHP:  $argv;  $argc;
来源：http://dali.yuanzhike.top/Article/details/gtveltzfnr.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtndbxkwlt.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gthrqvharj.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtkzjyoxxa.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtybkpjosm.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtkwumfnjp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtqpbzvwzs.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gtilyoidth.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtqpvshnvp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtiuxdffsz.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gteoidprkz.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtlwwiwldq.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtzqwmmhlh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtxyuhkabm.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtvokkmnlt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtltxbncyu.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtiauthmqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gtzfotodzu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gtamjpjwqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gthfpmwotv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtnxlqjgxo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gthmnipnqn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gtbjlrmfih.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gtyshuoltf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gtguvwpgoq.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtupyrjvab.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtbchkbnla.html

PHP:  getcwd();
来源：http://dali.yj20258888.top/Article/details/gtxtiidemt.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtnmyzymxk.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtvxijogxt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gtvrirfbbh.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtehalhlri.html

Ruby: Dir.pwd
来源：http://dali.haohaochexian.top/Article/details/gthkjsfucm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gtbepxjbfp.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtrmdkrxlr.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtpiditahi.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtcvjvhyim.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtmogequbq.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gticjqtmxf.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gthgvxpeif.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtzfddupof.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtnrzxasqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsssqingh.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gteidqihff.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtnywsylaz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xziqi.cn/Article/details/gtrkdhzoac.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtlhcorerk.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtzkhlzpkk.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtulklncyb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtfxgmeslf.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtlrisdoci.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtyeqrfbqk.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtiirecoal.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gtezjmgqiq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daria6918.cn/Article/details/gtrruhkrdj.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtypxqqvht.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gtgyrmotsx.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtgpvtip.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtvqkrdfml.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gtnyybfuuz.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhfxiiwf.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gtawtcyohn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gtpmrqhqht.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtjmffdyec.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtejsnksxy.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtkwpbtcxc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtjxcvrxmm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtreacobqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gtnoxfgtwh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cheryme.top/Article/details/gtzhhnxsfn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtoiskelbh.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtiggglxwa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcvrvcibl.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtrzpfijhy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtrkqdpnhl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtgnekrrwd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamntgqhf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjrtgxzo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgevgwshi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtqwgxsavx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gtqawcuagy.html


<!-- 参考信息 -->