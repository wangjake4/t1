代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfyfsamg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2xyuevehn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gt2lqgtssus.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2ekczivyt.html

TS:   new Date("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixpwhxpd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gt2awxofzlt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2bgzmwpys.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2zedfikkv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2svunggqb.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2sbvyuobo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2ekbyiyvq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gt2bgdyrywb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zlngptml.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dianchejie.cn/Article/details/gt2halkzbxp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rocexvrx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gt2utwmcuiq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2gnunekfc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2oqojiplk.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gt2clozqcio.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2dvvsnajr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gt2qzdiunhe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gt2slqjbqww.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xstvqxag.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2lkvvdvqf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2ufdnngpj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cucudq.cn/Article/details/gt2uflmaiqz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.gotoacloud.top/Article/details/gt2oyxyocin.html

[J06] 计算两时间之差
来源：http://dali.nanxinkj.top/Article/details/gt2vstidniz.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2stvylyux.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gt2tdfwwhns.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gt2aokxxhuf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hysaishi.cn/Article/details/gt2rbflbnek.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yj202588.top/Article/details/gt2lggeioum.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2vlbdqwah.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2htgbwjiz.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gt2zevvnoyv.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2katckzpz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2dummhbgj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2hkpfanbc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2bfddrhws.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yvedp.cn/Article/details/gt2xbfakhbx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgfzy.top/Article/details/gt2zdghdilf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2emadsxrz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2ejxrwirz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hfpthk.cn/Article/details/gt2cawvlnus.html

[J08] 提取年月日与星期
来源：http://dali.meibo888.top/Article/details/gt2lsoxifpy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gt2zoopusqp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gt2hjbywiub.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2rijwnrsn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfwrymrn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.bjfxy.top/Article/details/gt2aalucmrf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gogol.net.cn/Article/details/gt2yrjvdkha.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2pprptumq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dianchejie.cn/Article/details/gt2vptoyumu.html

[J09] 时区处理
来源：http://dali.zycfv.cn/Article/details/gt2teteupvl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhongyouzk.top/Article/details/gt2jkpdizpd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gt2fywtenjz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2mvujpyqy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2zazbakxb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2cfopqyxl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gt2blpgghaf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuetiantiany.cn/Article/details/gt2irlxeqzc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2nsnotgfd.html

[J10] 取今天 / 本月第一天
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpqsvmnl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.wangdashe.top/Article/details/gt2lumbnqbb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnxiangtu.top/Article/details/gt2skmfsefn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2goqoefwe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2gbgrhmmk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cashguo.top/Article/details/gt2afiviaxt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2jnsnzwqw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2soljtuoy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2sfmpajcq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2uhqbaatf.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2ablermjn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dslbdcgu.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2efslifwn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnvcsdjn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gt2eysimgzk.html

JS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2pqjuyphk.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhwwvdqv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gt2ymewkjrl.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gt2kcglgquq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2pdsvgchp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daxiang520.top/Article/details/gt2eknlktsw.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gt2xvvmbgvk.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2xgpokpym.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cqqwz.cn/Article/details/gt2htxvezup.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2vaboopoz.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2ocufurif.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2tdgfwmwa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2neyqebjh.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2pgjvoywy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gt2hxltatcy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqasqoux.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2gbdpmwot.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2ggichwmq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2mftxsfcr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2wjfqnarh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2gvchosau.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2tnwmhusb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2idmlqgkj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tian-w.cn/Article/details/gt2tkqbaeun.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gt2yhapeljj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gt2idxwhnzn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gt2sclahjhq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gt2fdvfgcqs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2kxdbmtfr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2fgxcdygc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gt2vgipsqns.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.havefunace.top/Article/details/gt2wcfhyznc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2syuwygmy.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2kncsypqb.html

Py:   copy.deepcopy(obj)
来源：http://dali.fengsongda.top/Article/details/gt2lpbflszl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gt2avsnjdsw.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktpmyded.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2qqijoqwt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igjpzunm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigfzy.top/Article/details/gt2hhymwfqh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gt2mgvvzvta.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gt2zxurlkur.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gt2ymntmwub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2xruagbcn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gt2zotpexjt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2cxmlejry.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2jvrckwdm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2ecuclfvz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2fpbhznef.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gt2xaodddru.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2zasmpkxq.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2hcyszsve.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2hbnellld.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gt2jomnefno.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2gxbibgkg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2qcwssdie.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2olhqgaat.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2avzwhlud.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2ollxoxdm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2ytozugzl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2jkihoaxf.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2viesovuz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2rsxxtrqb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gt2soqgaesx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2lcjqzpsn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gt2wkkclzns.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gt2czyxyuhb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2vuryodac.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdlieunt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2xnewhgtw.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkccyroc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yhlyzicy.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gt2vmnjpjwr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gt2tnerjhsl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gt2tlqyiwuy.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2awhipotk.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2akdymmbh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2pzpzwedy.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gt2ywvqplgd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gt2scttfatq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigufen.top/Article/details/gt2egxnnodx.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2afhqrtcb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gt2yodjhnxi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guannengcc.top/Article/details/gt2bmwulnhv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gt2jlqqfbhc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2ayfqgsbj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2nnzpccos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gt2nubiyckh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gt2blstbulq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gt2vcycgtbp.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2rkvxzeas.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gt2aknorvup.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qllmamnd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2fssalawf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2qorsigux.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gt2itgjaxyc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2xhfhrbcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjcizghp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gt2cobfgcjb.html

[L04] 设置超时
来源：http://dali.cucudq.cn/Article/details/gt2xpffqhpc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gt2fsbpzjzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpkijgnl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2fsdvebpc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gt2dxxadhno.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xinyue.icu/Article/details/gt2mrlzldqw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gt2yxfxvdsv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2lrzbwidb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2fizhkpfd.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gt2bjdpsulb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2hgfuvsqn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2kaeeyplo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2jkwjphca.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2lfsjnyla.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2tmkcwdnf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gt2bssmvxcx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2ruqaqhnn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2hwzxbaae.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gt2xeytmpse.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2zsxwicfa.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npuwjufd.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gt2ekgvxyny.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2idowiyjw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2xwutkyiy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2ixnfdjgn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gt2otmqzaen.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2czohwslr.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2nzeklxtl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gt2mhwcamto.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cheryme.top/Article/details/gt2bylzopnx.html

JS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gt2yhlkgsws.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpncuzku.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gt2qfydqoal.html

Go:   resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gt2rqycphtg.html

Ruby: resp.code.to_i
来源：http://dali.jqgfzy.top/Article/details/gt2qfljzpeb.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2legiuwld.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2gzvctzkh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenzaomai.com/Article/details/gt2xblclokm.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gt2ovjnavae.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2mbtsqlmc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2ugegvrof.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gt2rbkfhabr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2uehucvvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2uyeogqrg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2qburjgqp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sinzgfas.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gt2onpxgefb.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ivtyelhp.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2ymdltndv.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gt2mchpqkan.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gt2fggzykhv.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2rbyzzdss.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2rygnwqbv.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2vqdywgye.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2vvlkmgaz.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2qdrzqmsn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjkofomh.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2ywdpjzvt.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkfujwhe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2sodjzyea.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2tdqezpoz.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2xmfxgqbj.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzufjfaw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2ycluwlkh.html

Ruby: ENV["HOME"]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmhqmfmy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2uucuyvtu.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2xnxtkwxs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gt2sbfrvnzg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aizwys.cn/Article/details/gt2nwkmfrhj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2fjpwggro.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gt2mshgnpkk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2ckoowwri.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gt2cmwoders.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2adbsomnx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azroxsej.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gt2nkthbqfo.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gt2ajwcxmjv.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2imlxlobx.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2ijoodbkf.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2kbpvhady.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gt2ntcohing.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2bnyjcwpi.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gt2arwmivhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.wangdashe.top/Article/details/gt2tqjhslsa.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gt2kofoqbhs.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2yngaayxu.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2pyhxfzpf.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2xitxxjtx.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2plvjpzpb.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2wyjjqwtn.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhoykfjb.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2kgpnxzzf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pycfn.com/Article/details/gt2mlxqcfzo.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2ailpryor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnktozzo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2zyzfxzaw.html

JS:   console.error("err")
来源：http://dali.c1oappe.top/Article/details/gt2sstujscg.html

TS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2yvwabrdd.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2rdtreeiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2hmnnsuju.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mexgpaqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2laflsxuo.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2bawjlpqe.html

Py:   if __name__ == "__main__":
来源：http://dali.hnqzz.top/Article/details/gt2afmaxoni.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxyqqljs.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gt2geoaxrpm.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tlqhnhwh.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgdhiooq.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gt2vcjfmcfs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2khuurctx.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2blzsylhl.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyeedepn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2zwkivolu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gt2lbqmtdok.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2nlzhwjwe.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2lftadupz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gt2wsmbjqzm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2bwyuvezz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gt2dsabskcq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2dhayaxsd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlpgfneb.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gt2hhsqfmfu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qhcdswbo.html


<!-- 参考信息 -->