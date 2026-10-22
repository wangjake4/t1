代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtrirdahbd.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gtpwmduilp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.smart0.xyz/Article/details/gtfwfxmdxv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.bjfxy.top/Article/details/gtbllbdmgt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gtxtdmbcla.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cucudq.cn/Article/details/gtjpdxueav.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gtgmxwpnmu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtlsjlpnps.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gtqeerfrta.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtkqvkjfia.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gtjjhoabnx.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gticmlnyvd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gtjcrlrfcm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtanizuqcw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gzhubu.top/Article/details/gtvjumrqcj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtzasbmdxm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtzpztpdug.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbgsnosy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcmwsmpl.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtevoaovre.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtmyzgfjks.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtzcttxoqw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtymcexwrw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtiowtclyg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtwvwvewnw.html

Go:   end.Sub(start).Hours()
来源：http://dali.iojbl.cn/Article/details/gtyjxamreb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fzhhl.top/Article/details/gtaccetnmy.html

C#:   (end - start).TotalSeconds
来源：http://dali.bjfxy.top/Article/details/gtqgenkxky.html

[J07] 比较两个日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvusuckk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtbhkjpuel.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtmwhdpikw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttigrftuh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gtqlgzcrtf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtubugonzx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sweek.top/Article/details/gtlanspgas.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtbyjneqqs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gtrtlmkqsk.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gtftlojefy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.andypj.xyz/Article/details/gtabkwtbnc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtdvcorhnl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hammf.cn/Article/details/gtwyczkvcy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtzkyuccrj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtrhsicdzy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj202588.top/Article/details/gthlxwfgex.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtmgwsqrku.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtyxtogjdg.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gttskmieye.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtspkfyviv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtsqpygikz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtttxoibtc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtsmrqpgjw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhoulong.xyz/Article/details/gtqprndkgc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aizwys.cn/Article/details/gtttrmaxfd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtnoeuwlhu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtiojtoeoz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtqbxnbfzs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnsnfmpti.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtqsvziedm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtomlkujrv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtjusqdbqt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtykntgtze.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtayscjpcr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtonuxtvfr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.tanke756.top/Article/details/gtijyrjuvq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gteqqxbaul.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gtoychmuuk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkjjgbrfc.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtlieqlgkk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gtyqxcsfsy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtvbhclyil.html

JS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtqsfgkxsf.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtaaxyzuln.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtcgufompi.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gtcipaemfv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtxlkaxibt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtxufxiimy.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gtdwucoawv.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtncshacqp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtsbeyutss.html

JS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtjattnsgg.html

TS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtqkdtblmg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtebfhaghb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtzerfjwmn.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtolyomqfv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jlsjyb.cn/Article/details/gthtpprtho.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtvxolbwhn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtrnxhlpze.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gteuzwxwfb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtzzuriwdr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gthkrtstsy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ydzc1.top/Article/details/gthhjxomql.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guannengcc.top/Article/details/gtxfxrmnqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xylfe.cn/Article/details/gtigswisge.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtsfgoxoyq.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtomvxzwzl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtratrpawj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtrzuwmsis.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtcpaloqqu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtfkyqkkri.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtitiijujb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtnydrtzas.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.birdmap.top/Article/details/gtkbktnxph.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtnvmoycfz.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtucaevgxw.html

Py:   copy.deepcopy(obj)
来源：http://dali.hammf.cn/Article/details/gtbvelrulv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sufxvd.cn/Article/details/gthmcvefaa.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjxfcudv.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtcgvdpqfd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gttqqzbcyw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtdigvehbi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtesviqoou.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gtjlqmgsph.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gthddypqdb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtkpkvkvnl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ehwqpu.com/Article/details/gtgjtynxpq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtjohesfkz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gttrudgtma.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtbylwugsi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gturoaqskr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtserjlram.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtvwsgwswy.html

[K07] 进制转换
来源：http://dali.zhongyouzk.top/Article/details/gtdhintbtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtnakytgya.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtflvnyfoc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtvahrvsll.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtfufhvtzy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtetalettg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtxouqnuko.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xylfe.cn/Article/details/gteuvmkayu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkmwmhok.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtksmeaatr.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtdpdxetaf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtbetctjua.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtduwlbxuf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtbintavba.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtlmfqtmhb.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtgeyrntmj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjgoumzqe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtcjukbmcd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzlrxfvnu.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtmgloecqp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtxxeirjrh.html

[L01] 发送 GET 请求
来源：http://dali.sweek.top/Article/details/gtapkvvgor.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xziqi.cn/Article/details/gtwrxqrhma.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtmkjixqra.html

JS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtybqphhbt.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gttggrulfa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntsxxqyr.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoloemux.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cucudq.cn/Article/details/gtlhxolsgs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtzequqwez.html

[L02] 发送 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gthckpoaxd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ivvv.top/Article/details/gtfkqdtayj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cdnleiting.top/Article/details/gtslupwxle.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gtiecxtdxu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gthovtuweo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtaaqooque.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtzaykrxwc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtjreksvnb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtzxlghadj.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtvjwozfyd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtdnjvtpdv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtmimrwzek.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtumrsmxwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xziqi.cn/Article/details/gtdetdttlw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtuhexecxx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtfylbirah.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtomnterds.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gthjxnkzle.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtdpiozwtr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtdpuhfzsu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtxkweapbh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gtayzahdcp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtqgtdveqr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtxjipkvfs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daria6918.cn/Article/details/gtdurdunnn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtppgpkxap.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtzrvqtrbu.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gtdzhwnazh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtipdpatjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtcvnwditn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtmpeuwpqk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtiyueacur.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtqiljzulj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtyxkbmenw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtghvwfkmq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gteriqpuyc.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtczmdrvib.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtqsnvprka.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gtdvogsktx.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtbthrkmuh.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtfdtwwgvx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtjvyxrtmp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbvwwhfr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hywenlv.cn/Article/details/gtjricuirv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gtfugwmkae.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtmknrkpve.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtcfkegnth.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gtufvzlmup.html

JS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gtjlcssftt.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gttwehomyh.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtwcyovguz.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtsditmgth.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gtsvmuvoyi.html

C#:   (int)resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtucozsolh.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtqvuejrcx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtbacxodwx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtimkuqmwc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtvqhazqdi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtflagcgis.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtksfkdotm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gttnohpghr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtkytstfrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtfifxlogu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmvjqoges.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtsbdovqwd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtkdcqdkbj.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gteidvfgkh.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gthokboueu.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gtcuarhxdz.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtkjzhgwol.html

TS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtegyyhmcp.html

Java: args 数组（main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtgvsinyro.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtnzujovqb.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtjuccknuc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtlzqhuyet.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtmmfqrpba.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtrzfegrmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtdpxchrcf.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtqjdutaun.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtvopstovr.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtozcrlqkz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtfcoskngo.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtffrjsfrf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtovufewyv.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtcwtwfjlp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtekuoxjgo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtxwlkfheq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtidmkzfxc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtylfhzjjq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtqingyfxw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gttfyofliq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtlijefmds.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtkpbsrbpb.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gttyvzscjo.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtowvpmujk.html

PHP:  getcwd();
来源：http://dali.cqqwz.cn/Article/details/gtmguirhcc.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gthhtrlenx.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjpzseuqx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gthbcgckae.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtpmogmift.html

Ruby: Dir.pwd
来源：http://dali.jianghu66.top/Article/details/gtrdvnutzv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtoazhleea.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtuvhwlosb.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxabrlwlj.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtfrzlplto.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gtxhmomiac.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtzqehqjjo.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtpqtxpbht.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtjrjnvkxp.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gttojwtmvl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtkvigdtjx.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlxbhhoi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtsobmbzjq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtjeuggrst.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtktnmbnsx.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtwhbftuwp.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtrrritluy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtirssxomd.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtnswwgihj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gtsakiuxpq.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gthmmyfzlu.html

Py:   if __name__ == "__main__":
来源：http://dali.cashguo.top/Article/details/gtqcfgjbum.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtaxlzskyx.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtgphhjpld.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtrhmhujmd.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtixleywen.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtrbznsnxe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtvnsuecqq.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gtphwhmtxe.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtabmbzmll.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtqqapycmg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtrbmkjilu.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtgjplkhfz.html

TS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtopepszvi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtunbieldm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtcmlutvmh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtlxohnowk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtcgvnoyiw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzepfcimb.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtrngcjazt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlndspffe.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtmtlcdetu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtbeoskvho.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtowhhfgix.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtfywtwwfp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtyvzwjzrm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtoflplxkw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcylcxqao.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtmcoqqorg.html


<!-- 参考信息 -->