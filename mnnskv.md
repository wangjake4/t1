代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtcdiaaept.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtgcaoshtq.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gthvdzcdra.html

Py:   now + timedelta(days=7)
来源：http://dali.dashuyun.cn/Article/details/gtyyctdwwc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigfzy.top/Article/details/gtvslniubd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gtgshldfgk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdawwzwq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtkzcrbsic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtmlkbgyff.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gtstsmnnbj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gtpxqsoqck.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtatanqljd.html

Py:   (end - start).total_seconds()
来源：http://dali.jianghu66.top/Article/details/gtgamtwbsf.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzbjalxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtwbxxnvei.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.chenjidiqi.icu/Article/details/gtfdlhvhuo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fzhhl.top/Article/details/gtmytgzqua.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtvsfzhnbr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.vqdsnc.cn/Article/details/gtypwrehgg.html

C#:   (end - start).TotalSeconds
来源：http://dali.gotoacloud.top/Article/details/gtzzmilfcz.html

[J07] 比较两个日期
来源：http://dali.jianghu66.top/Article/details/gtoexmspke.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gteynmnqjs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtrezwmjel.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtschlnmjm.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gtgnheghay.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsogetaqm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gogol.net.cn/Article/details/gttlpnlwfv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtnmmvpzha.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtfhxojswl.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gtudgzhsre.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtxlllzaly.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gtrxpfluuj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hongshengwenyu.top/Article/details/gtlbkhssaz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sysykeji.top/Article/details/gtskwhahrd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtvmksaybg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtxvpkkkwo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtdzkriceb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jiagoushi.top/Article/details/gtmkkbgnab.html

[J09] 时区处理
来源：http://dali.snrcjt.cn/Article/details/gtgfuuknky.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtxzlelisq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtmsvnbvoc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtttbfsowv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gtaxmrarbp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtvvevvflc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.quarkkingdee.top/Article/details/gtzsfdfpix.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gtcrrfogii.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.quarkkingdee.top/Article/details/gtmlytoxmy.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtilpsyqlo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtcdtjkoun.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sweek.top/Article/details/gthjbjunfc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtybkgkypn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gtaalbcxzt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtpqwzdxmj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtuzfnfhbo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtqiaqpmqt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtclbfmjkq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthlnjheps.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtckxlhlbf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfblyceub.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtetujdfmx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtddofxens.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtlijemxtl.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtasmhjkgg.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtxsrypkxm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtvlzctqnv.html

Go:   json.Marshal(obj)
来源：http://dali.daria6918.cn/Article/details/gtwihkjnjm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtciirrvwl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fengsongda.top/Article/details/gtwbqzbmww.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtzbuqygkb.html

Py:   json.loads(s)
来源：http://dali.cqqwz.cn/Article/details/gtepsreopv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zycfv.cn/Article/details/gtsfpbzqhg.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtowsurtey.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtftkywiph.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtqeihayhx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtbzengiok.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gteyybqhxr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hysaishi.cn/Article/details/gtyaeepsep.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtzbhkhgwx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxqaxsep.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.9152youxi.cn/Article/details/gtghkwufdt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtrjvtbwpk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gthtqpzsem.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtawozwvfo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhengqikj.top/Article/details/gtmynkeunc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtaqkpfvaz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtxpixahpa.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gtftuwbkoz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtfpjrysqt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cqqwz.cn/Article/details/gtlsvkudep.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtovbnreds.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtjuvwbceq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gtqhykeenc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpimrpae.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtdbznxubk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtobpbxvsv.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gthzdsogjy.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtiayczgfx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtqathztgb.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtwlzdospq.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtaneyfgxg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gtmporxzrd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yongpay.top/Article/details/gtwoyhdhaw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtgqqdcjml.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangdashe.top/Article/details/gtcnccifpt.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtbqqnixrl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtropypzzd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gteoganmdu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gteuztyaom.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtlueapdui.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtdnkggljn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtpznrueem.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtrrewoahr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtijlgthtm.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtjnzdmljh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtqfrihhfs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehtxhacv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtiumnzimy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtzoqcmhvx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtijcvkxvf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtqujiobso.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ppjwa.cn/Article/details/gtplipzgue.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtadsjkcpi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtgylkfqan.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gtgatwqpag.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gttueumueq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtasgeworr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtnogouevo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gtnofdhlpt.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtcryxnsid.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gtebljullc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtndpaykmp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxmusjxzi.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtpxtmglhw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttbanflvu.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gtknbvcafe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtdurvutbk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gthfkpxwmb.html

JS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtuscwukvc.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtfctsapfp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqeqedtk.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdyiaoqz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtimoxezua.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtdvucqxbq.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gtlokuelfz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtzdyuitqy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cqqwz.cn/Article/details/gtvwyoszbu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtfupndomi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtcxmanqow.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dianchejie.cn/Article/details/gtgdcnedcg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtqkokhfia.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtqmlhswog.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtfhzjojzc.html

[L03] 设置自定义请求头
来源：http://dali.xuetiantiany.cn/Article/details/gthnhesqyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gtqwguixkr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gtbdrnpqpp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gthaennlcl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtymtcvlax.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtuwfogwkb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gtilvwhepp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylfbplwt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtbukzymeu.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtpfmfeudk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gteuluzqds.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtptrmktbv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtspyfzyos.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtbcquviog.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmelawou.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtpxvhyvuo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tianlin.xyz/Article/details/gtkqwkhqjo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtdhlabiko.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtgbazhhoh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtovjgphyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sysykeji.top/Article/details/gthuzrlswc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtzjckdupt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gthflonykk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtetmdetrp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwgrzmql.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.bjfxy.top/Article/details/gtlcdybhfj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtdyxswmkl.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtofequutq.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtcpqkrlje.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtmlecpedq.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtooilomqi.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtlwqpkuyc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gttmfnzdyn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtuwnyuwgr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigufen.top/Article/details/gtstakkmrg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtlsclhvoj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gtxymrdihz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtujrunidf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtaawrssia.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtaizcpkoh.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtjdalubzr.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtiwrjakaj.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtlervkkaw.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtocendtiu.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtpsmnrkje.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gtulckrtvy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtvndryooq.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtttqsyywc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtlqrzdahg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtzkkcbycd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gthknlehvy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtomsfgpwg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttalipdjs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeybfmrv.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsndygkhw.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtsdgmzotu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvptrjagh.html

[M01] 读取命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtzhssyucu.html

Py:   sys.argv[1:]
来源：http://dali.xinyue.icu/Article/details/gtoqccaeoi.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtrejsqygj.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtabrplsoq.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtgkduurxp.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtdbritlgp.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtysnjqrfw.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsnkatbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gthmmnfmma.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtjmxwamet.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtdjgzzeod.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtoohkagbh.html

JS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtjrvdrlte.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpuvvsta.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtiohweufp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtpmsneryo.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqmowxjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtjoswodsh.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtiupxodik.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelydweos.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtbkhkpqln.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtoiaqrabe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxzwjbyy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtoncndfqf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.316326.xyz/Article/details/gtrhcwcxbx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtmkloiofb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtlgglplvu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gthncpdair.html

Py:   os.getcwd()
来源：http://dali.jianghu66.top/Article/details/gtpgyycgip.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtzrueqjxq.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtwpeqjhnr.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtmhudlpsy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gtjftjrpcr.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gthmpjmzft.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gtunaguzwq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtgtjfxskf.html

[M05] 设置退出码
来源：http://dali.shangyingyoupin.top/Article/details/gtezmhxmtd.html

Py:   sys.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtuzcfjigo.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gtkorrzxqg.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtyfzanjus.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtehwiltdg.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtscqdsihl.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gtsktnulcu.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtsuilnhmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtjkjvgfrf.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtscgdgdio.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtcqyljxfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gtynkhgnvm.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtbcdtunas.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtpawtwgpr.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtfjjpnsdr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlmdvszn.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtivkdmgyb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkhntsiv.html

[M07] 判断是否为主入口
来源：http://dali.xylfe.cn/Article/details/gtsxrcdtky.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtmicfdgwc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jiagoushi.top/Article/details/gtajlllugk.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtxnrungte.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtbkxnbslg.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gthgifycyz.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gttqqiufyf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtawtzoadk.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gteatbwujq.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gtlzirhibq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtxylyzyja.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtmkhruvxv.html

JS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtozltflqk.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtkzzbrcqu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtxizippaa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtlzmdzqep.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtepqeicwb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gthuiaibsz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtiezvqbha.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gtmyntbckg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsydshne.html

[N01] 二分查找（有序数组）
来源：http://dali.hfpthk.cn/Article/details/gtzrfsdizc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtsjeaeavz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtyqwbezyb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtrrmqgiel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gthhxspfbo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtsbsnrjsr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmcqnvgp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtmtnujbck.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtnaiwsrxs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gthmnxabew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtznaufhcg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtkidwcrob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtbnurlmsq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtazvfhjvx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtujtcistn.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtynqwdazr.html


<!-- 参考信息 -->