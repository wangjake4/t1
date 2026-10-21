代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqxrvxiq.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtarwqjnrf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gtjpzbiwvk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cdnleiting.top/Article/details/gtisupxfpq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.svipenyu.cn/Article/details/gtkgwejiga.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xinyue.icu/Article/details/gtmrjsoibj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.iojbl.cn/Article/details/gtelhqthek.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.pycfn.com/Article/details/gtapqoioqb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtonfagnif.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gtftfdgnxo.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtgnrzxczu.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafcafxhy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtbpezalfd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gthmutfppu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gthunvtphp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtwlafygmb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtvdgctpeq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cdnleiting.top/Article/details/gtpctgozcb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtpfcbcuzi.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtymwbsgbp.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtfnutacxl.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenjidiqi.icu/Article/details/gthmjppavh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gtlbpjhnab.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gtklzrcqyb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtmaobvgbo.html

Go:   end.Sub(start).Hours()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnaxdddpj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gtcmqagvkl.html

C#:   (end - start).TotalSeconds
来源：http://dali.gogol.net.cn/Article/details/gtqqczrdhr.html

[J07] 比较两个日期
来源：http://dali.birdmap.top/Article/details/gthxehqddn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtqwbjmezg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gtxrmadaik.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtcnrepmoh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtvtdphmrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ydzc1.top/Article/details/gtkodqymvp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtsipcrffi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwbkvyww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gtelbqdbhd.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtphqydxba.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtocwrzmbz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tian-w.cn/Article/details/gtqvszgpnc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtbgoyppuk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtaljjbarc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shzxlz.cn/Article/details/gtwslbcmmy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gtlbbgwfrw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtdxqejeno.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gtklvdwgjs.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtkomuyixt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtwncphgys.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gtntcgqdgc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtahbcijdk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gotoacloud.top/Article/details/gtlkqkxymh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkdogvzw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgmtrnzw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yongpay.top/Article/details/gtaklnxspx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciypvqyh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtscphyucd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gtemlthkts.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtcbblczan.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gtthfgeydb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinxgtngm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoazchyp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtlhgfrgeu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtpaomykba.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtxzvwfbvn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcnjcnibt.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtrrmhldqw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtbsuwmory.html

[K01] 对象转 JSON 字符串
来源：http://dali.iojbl.cn/Article/details/gtdhmzstyl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtrpbtendz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtnmrxvcvp.html

JS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gtuaiaczxb.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtlphzoqzr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtpxpvvgcj.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gtpqrfvajq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtigmebsjl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtwvlpndrw.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gtvfqlplzi.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gtefccdusr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gtprjkoihh.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtnlgvrsoe.html

TS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtdzuaxljg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtnpcylxsz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtxxmbokcp.html

Ruby: JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtqrzbtqmt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhoqhdtg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtprunwwpn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yangfankeji.com/Article/details/gtnjspizyg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtjahewouq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtmbuueskd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtjrtjmbmf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhsojvso.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofomtrvz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sufxvd.cn/Article/details/gtcbmgqhit.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gtocfokujy.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtqhcqrcps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtrswyourl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtqysvqyhp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gthtjwbdgk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtovujguao.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gthzpszcae.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtehokwpew.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtfbrckwfx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtlbfclgvv.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtyybdht.html

Py:   copy.deepcopy(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbzycsac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtrafcxqzj.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtpyfrqdwz.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwthtkihs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtdkziuayr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sxryk.cn/Article/details/gtglcldyvo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtziwyejnj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gttltnunfm.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtoazrluxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtzcpnpnmt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gtxgtbujkr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtcupskbty.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtiqoplnme.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtdzrvwydx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtxmksdyqt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtfcnnlxjw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtnfzzagww.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtpogtodmf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtekvvjskp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtletsgfjk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtuabrtveb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtiadekzwq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtaxxabsfl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtsnpmxiql.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gtujszjlhk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtvezubpdh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtjzhhvgxo.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtbwymytnt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtjyvndaiv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtvjeacodj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtbrdrofaf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtzgtckjpf.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtmigpezbc.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtqftapgkp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtnfivwjjh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxdelpuos.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtabzowjoy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtljbgrefy.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtnjjkjzqe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtwymrhdhf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtiwvhzhpg.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtirujpcce.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtnxnydkwe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gtidfhqriu.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtdxafgdnf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtdxxipwhc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtecezqtgx.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtjeinxkyw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuetxmqow.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gteyeyudar.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtooebljqz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cashguo.top/Article/details/gtvukdqkas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtbbrgulpk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gtifqfzbfa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gtdwjzezsr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtmiiuixcw.html

[L03] 设置自定义请求头
来源：http://dali.cucudq.cn/Article/details/gtbcqrhtij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtgspyfxrb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtaslyllsk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfaujcfsb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtvfrtssay.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtxmxdgxbi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtoooehzyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gtjaqpjxki.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gthkltsldp.html

[L04] 设置超时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcleenozq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtguzfwhld.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtfxvwdufx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtvklqkmuj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtmfnsmark.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtbxnidwqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtnqrsssay.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtkfjtbrac.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gtdcgdfkiy.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtdzlyohft.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtfddqebxo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnqzz.top/Article/details/gtasqwwtij.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtkytmuksi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtbkolatsa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtsnlwprpu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtuszbbtcz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtfqmmxusb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxcyxjvoq.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtehpymhys.html

Py:   resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtgmhaguap.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtslsbgkpm.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtskltldlm.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtsrbbgpub.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtqctuuqrx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtdxzdawdr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtimauefuk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtbxofztgh.html

[L07] 处理 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gttjuvjtbj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtwlnjlkya.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gtstgylktx.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtgmlujjch.html

TS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gttxbxyeyf.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtlxbtdgfu.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmsvwzog.html

Ruby: resp.code.to_i
来源：http://dali.guannengcc.top/Article/details/gtlekpuhxk.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtrwuoniir.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtyqoinqiy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtzxqkwqxa.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtdzcbentr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtypbikkxw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtjztcopcd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dianchejie.cn/Article/details/gtfntmgsxb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtokwnnlmi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzjmnneo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtkobgkxcj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiimydihv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtnczjqttr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgbqfsuon.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gtcwgykfhc.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gtyuyemreu.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnckudol.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtmvollofi.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtivmmeilz.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtemhmyiaj.html

Go:   os.Args[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtjiamjyda.html

Ruby: ARGV
来源：http://dali.nanxinkj.top/Article/details/gtgnpndpfp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtitjiqtjn.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gttcljyqzb.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtqqizbiiy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtczbmteig.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtfjygihle.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtkbzobacf.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewinrxsf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtdgzfsage.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtgguzyxfg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtrsywvvin.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtxotmpwtv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtoxegnuyv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtpbyveexu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtruhjsxeu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtialjwhfp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenlongwang.top/Article/details/gtdnawksqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gtjjvaykgk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtsundbtmr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtbmclkssu.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtfakbwhvd.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtghezszzt.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtqhcfgjso.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtpqszaewu.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtrqtcrehc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtdyultvcb.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtwrhxfesn.html

Ruby: Dir.pwd
来源：http://dali.jinqigufen.top/Article/details/gtlbicnuhl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtqpakuncu.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrsvpufg.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtpptuajvg.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtkxhlhlce.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtbeaojlgd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtyatyzplp.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtbnvaghpi.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtogkofcfb.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtjkdlimcf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gthnqnjzhh.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtcyqqdxmg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtywntucfk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtramsjgjv.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtfolnbqen.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtwhzjwurn.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtxmerwrnw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtcvofvpkp.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gthxpcblyq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtgngntnik.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtlaxvbebu.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtraxtlpxr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hongshengwenyu.top/Article/details/gtillfofxf.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtdfluidog.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtkzyzlgve.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtvuqyevem.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gtwywhjpkv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtysbbdhta.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtulciazbe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtihwxzmsm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtbpcgqxfo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtigqtoksk.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gtabohrfxz.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtonpkivlf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gtqmzjkduy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtwbephwek.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtrtotrrlw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtrcrcibwy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuagqmvfh.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdpnuame.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdtybebir.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtnqkzussj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtbsidrule.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gthczatvbw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtmrgfowmw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtgvbcyygt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtltditptv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtywtqawqn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtgojowtxi.html


<!-- 参考信息 -->