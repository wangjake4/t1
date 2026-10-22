代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gthxsufxlr.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtmtapcnxw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtutzpeogp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.daxiang520.top/Article/details/gtisrwvfie.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtyinueunv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahpqvmkv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangdashe.top/Article/details/gtteefkadp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gttczgtwmv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxealkfm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtekrpzrog.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gthrqdfvcf.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gtcykbyphj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtluqzafel.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtkfnlirvf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gtlyplboac.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtmgvjspna.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gtofcfvnbh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtlwnlsmzo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gtumwjwcyf.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gthkabcfpy.html

Py:   (end - start).total_seconds()
来源：http://dali.cucudq.cn/Article/details/gtoalrgyod.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtkmindorp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtgjfhtcwl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtqhnlnryt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtqgicblet.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtthiprtbq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtjksccvdj.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gtrimbuhal.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtogthpeke.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtwtxnwsrl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbnygplh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gtdackyxmn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtvzezwsdo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtiizieetf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.316326.xyz/Article/details/gtkvcspqav.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtjsbgaugp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtpdtucspr.html

[J08] 提取年月日与星期
来源：http://dali.snrcjt.cn/Article/details/gtsjbwfenu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeejttpa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtlilgqkyu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtilbpkcgl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtefoxsfbv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gtrsmklfof.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssrcspnk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gtmqwmvhsg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtytfxbtvp.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gthgruzfye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.haohaochexian.top/Article/details/gtpsgeocun.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhongyouzk.top/Article/details/gtchaelzfk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtirgerefh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtvjecmcuc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtnbmdkxzc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenlongwang.top/Article/details/gtjgjmvypt.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gtmvugrecq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtjbubxqhp.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtdxcxlhwm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqtzkudd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gtizbmtfrn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtriaktysv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtmifxtjre.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtyvrdbzdq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daxiang520.top/Article/details/gtivxsxhll.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gteqapyiad.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cqqwz.cn/Article/details/gtpmvrdvse.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbhmsdflk.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtseitgjws.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtftcmiivd.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gthgwirxvf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtdkfntwda.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtdbvwybid.html

JS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gtifwcquzu.html

TS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtmuiujsef.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fzhhl.top/Article/details/gtyqqbmqof.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrpadzzfg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtsupfpkum.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtwicelpfg.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtrjljmxdy.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtextxienq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtcekqegtq.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtjalwdxvk.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtjmfcbzje.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gthaepiwaa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtxnxmbnwh.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtfwjhihrk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtcvzsmzxg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtzwhnhyop.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtsfvsxnkv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtywdfgeds.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gtwmmvndiq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqggwmejo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtztoenqql.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtgmxlfhgx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtlkwyeapw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gthmnlpvfs.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtllkwwqql.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinhkfwhg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gtmsllwxdc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtbhhgxxiq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gtfivxjmxo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fzhhl.top/Article/details/gtnpkckzqt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuilkthp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtpsnlxliy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzauakwg.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmpgiuev.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnqebehos.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtfwzlulnq.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gttanwhvch.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtertctgbz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gthjpqxccw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtpgnhopni.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtctprgzxf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtrpzpsrub.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gttrisejom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtphzjcdxq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gtdbtqswmm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtiwemidod.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwgwieul.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtkrizfkxo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtbjkrkopg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtcjuuhzby.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtyletgbnk.html

[K07] 进制转换
来源：http://dali.yueranfly.top/Article/details/gtgziwkswl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtxyoqkpor.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtkbqhfdnn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtictstilf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwttdfxlj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtyxerqsez.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xinyue.icu/Article/details/gtfrpvgqlf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtaqbunuhx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtjgxsdwgf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gtjpccvsvn.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtoiazwmnq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtoqjxbifi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtsuhoacfh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtljnbepbx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtgxmjmqbx.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gtjdoaouyx.html

Ruby: Marshal.dump(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtldhjvrgi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtfjfdgeax.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthxzisrrc.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtoyfaiqov.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwaxdvodz.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtonepaywt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtpmgftxso.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtuyucmcjs.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtmlfoqlfl.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtaxnnezza.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtodxzuhhp.html

Go:   resp, err := http.Get(url)
来源：http://dali.nanxuanxn.top/Article/details/gtuaxwcjwx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmytogjy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtpwqjgyyb.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtupjtajfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gttajukdvu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtzjgsvezq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtgcjndarg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtbfmmjghb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtjquxxtrg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtoklvmkvi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtqpuvncli.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuanzhike.top/Article/details/gteikuqlwx.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtfdgfilws.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gtnbyydsxi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gtffcvymhm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtrhokcjcb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gthbxbiepq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gttjqpsavn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtkihhhojx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gtyfafymij.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtsdusdqse.html

[L04] 设置超时
来源：http://dali.jqgfzy.top/Article/details/gtvkmpjmif.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtrmqswglg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gtuiibzhlu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gttreoawmq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtbtehdvqm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gtljxsbbzd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtlirlmnbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtllhosdyj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gtjhuwdwju.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gteyrvkyeo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtuyeakhlc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtxtkrqqta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtodpryoem.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtgfcrgqke.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtipqbualu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gteylcfvqf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtaryilvld.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtgztmzouc.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtnwdkmjto.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtrlraeqsj.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gtwhrfvdpc.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtvilbkfme.html

TS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtwmftiyht.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gtswkioafw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtpwbbotef.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtivutwsdl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yvedp.cn/Article/details/gtdkzxswnx.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynqzoucn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtbhvaxalf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.0kj1m.cn/Article/details/gtnxihbmrf.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtujqfugir.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtiyhqufui.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtiiusxrad.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtaonsvrco.html

Ruby: resp.code.to_i
来源：http://dali.yvedp.cn/Article/details/gtecroxffe.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtgwemlbnm.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gtpgjcaiiz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gtixaenipv.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtsdpbqvko.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtqvtfiqkw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtzuamkohh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtsaiuthgt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtwyewhuou.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtxtpzhxnx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtbwnnnrbv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtsvtyxruy.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfdseayh.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtozgmrkgh.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtmrnxpwve.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gttmfhuoyz.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtqzivojer.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtzqwnyani.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtbypdvoqf.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtdchxomoo.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimajtzmt.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtfjtvwzrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtgrwbvfdx.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtgikkdsim.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtwlrovvmp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtybaawung.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtccxyrihw.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtlqokcxag.html

Java: System.getenv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtjfnbtzsr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtzfjvmusp.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfrdlofc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfewqttp.html

[M03] 执行外部命令
来源：http://dali.dianchejie.cn/Article/details/gtvcqxrrac.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gtqjdjhpvh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtpilwkyrd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtkbfjyhxr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtwbiyhhea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigfzy.top/Article/details/gtdwitcvjs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtwnxwqhrx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtbcumfbgm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xuetiantiany.cn/Article/details/gthjnytivw.html

[M04] 获取当前工作目录
来源：http://dali.hfpthk.cn/Article/details/gtnpyvxomm.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzbejfaf.html

PHP:  getcwd();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkbrhaey.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtpjmoedqn.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtamuwvdjc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtwpmbxurw.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtblqdqxfq.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtgdyqlqaa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtgvhuineo.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtcxjgcsia.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gtpqlnninl.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gtinwjrtvw.html

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtiaibeaty.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtvngvdkys.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqehaddgt.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gthauajwvw.html

Ruby: exit 1
来源：http://dali.ivvv.top/Article/details/gtenxjkwbz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuzebjgw.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gtduonowgt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhkrmvbf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtrwfvhyfw.html

JS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdliwihee.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtkoxmhhlj.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtriiaagmi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gtobmqqhrm.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtseqrvbtn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtxglcygng.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtcsjrdfzq.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtcyykeqaj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtytmktrra.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtmmfqimtr.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtwkhdoeeb.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtyeqlmxzw.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtjyztpzoj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtsictllax.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtoxxteaqr.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gtgywkxbss.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gtuwzlkllu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtpqpxzrim.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtwqyofquf.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtjngxdfzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gttbxqkhtj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtzpqbnysm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtrmiisgoq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtahvptozv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnezdcfyc.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtkxmqjkro.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzeywniyy.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gttqbwpayt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gttvncnrgm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqnxtran.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtbutdtxwa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtiurjjwuo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtntfjotzh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtllvxhjsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtnfojlgsb.html


<!-- 参考信息 -->