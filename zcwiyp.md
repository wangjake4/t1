代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpqxittq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtknhjwida.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gtdfqntonb.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtikjpdquo.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtjghfxure.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtygqzusob.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtufuwaaqc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtkwlkqcia.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gtikomxlpq.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtdgbpyvly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtblqlqgyv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xinyue.icu/Article/details/gtrwivksef.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcifzerow.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gtrqpgdbin.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guowangkeji.top/Article/details/gtcknlecvg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtrcziwyuf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtwlenrpol.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtfhwwopkz.html

[J05] 时间加减（加 7 天）
来源：http://dali.c1oappe.top/Article/details/gtrsxyywek.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gtycbogsjd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cashguo.top/Article/details/gtomawuezi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdprhglk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtaonuwlcy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtlwmmdmmv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gtgcrvhzqc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.0kj1m.cn/Article/details/gtfqzlpvvj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtpqpyiqtv.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtkxagznzb.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtsxtebmaq.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gthuhaocmj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtvalyyrog.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtgawonmen.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guowangkeji.top/Article/details/gtvuvlpoop.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtbwizwmhx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtzlnafucv.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gtmkuzddpl.html

[J07] 比较两个日期
来源：http://dali.shuidangran.top/Article/details/gtynqjqvod.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtbekyigyf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cashguo.top/Article/details/gtmtrvprja.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtdruozzug.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtwpaznndd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gtjgrnvntt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtajkfvccz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zdqjudy.top/Article/details/gtjbktqnfm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtmrrrocyz.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gtizzbpayq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtyflwcgyp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtjegzbtvt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtjfqoymdp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtgkjeelfs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtgyojndws.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtlzrrgijw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtetfadiso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gthmypvhmk.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtmrvfbwhm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtarmwttmg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.havefunace.top/Article/details/gtykniyjwp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtfkgzjzdz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodnqwgbh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gtqaitzcmo.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvswolmo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gogol.net.cn/Article/details/gtxtspvdcy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtxtvojpns.html

[J10] 取今天 / 本月第一天
来源：http://dali.bjfxy.top/Article/details/gtqxoisibx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.andypj.xyz/Article/details/gtfruvcbcj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xziqi.cn/Article/details/gtbtmjubve.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtqnplapsd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yj20258.top/Article/details/gthkvsdupw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlgtjprl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtvcrxnibq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtelpbufby.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gtrzyhltlv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsdnflelg.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gtvrkisfnr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtivuqvhvi.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtcbdtvfaf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtmocxayqe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtmgtgzgis.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtlmhlivvo.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtdhcjcicb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvumvrqq.html

Go:   json.Marshal(obj)
来源：http://dali.yangfankeji.com/Article/details/gtuzidzneo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtewxicoou.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgmkxbmkx.html

[K02] JSON 字符串转对象
来源：http://dali.pengpengdd.cyou/Article/details/gthjxkdfaf.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtbfhckjan.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtdrcogmap.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtcrpwgxmv.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtlobxqdnq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtfdiygxjn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtqfpqkywt.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtrnziiuzz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gttfazmmki.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtuaebfcvg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtsnsynqrn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtjccusvcn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtkquzibht.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtjwtrpxsk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtwtfvbgth.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gthfqvvpad.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gotoacloud.top/Article/details/gtcnejzsjy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqffaiyjp.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtmmjuhwdj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtoqquaggb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylzgcbyl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtvjypltgt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtvzblxoyw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtriseybso.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtastukjoy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtmpmqdinx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtnygvswrl.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtvordylnc.html

Py:   copy.deepcopy(obj)
来源：http://dali.tanke756.top/Article/details/gtmxrtfqdu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtffzmarfa.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtufqsstvv.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtsyvjcfyu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgfzy.top/Article/details/gtwhagwjre.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gtkpnwkidq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtblrkdjzn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtqejmgosv.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtajojlnck.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gthrqvtlqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtuebcxqnn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsydwzys.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtbahvzrku.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtpwyvpmjv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtibcncgiq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuotqqqb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtqhjldnsc.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtkfyyubsd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtdmdivdbg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hywenlv.cn/Article/details/gtfoxdnvba.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtdgumhsgj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtdchitimm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gthdxgpdcw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoeksizhq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtdqpmttbc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gttomfmrfv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gtbfpbrqtz.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtkwhoglvy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhengqikj.top/Article/details/gtibspewuh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtfalqolow.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowzlklwu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ppjwa.cn/Article/details/gtelqcgwdh.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtiaoqyswk.html

Ruby: Marshal.dump(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdpinzpvm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtjetjbkin.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdvysqtog.html

L. 网络请求
来源：http://dali.jqgufenzy.top/Article/details/gtunsfxhdp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqvvharmi.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtsbwafghp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtuhtdxwgm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtkesuyfyt.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtinqfpvah.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtwherhhsq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gthwzcfrrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtahaxndsk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtcysxcriu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtwlkyfkzf.html

[L02] 发送 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycrenkzx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtjgrvhdjq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gthseyhanm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtklocubfu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbargquj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtwjdowdpn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtbwfdzlyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gtdlloymtd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gttmejzahf.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtkufalcen.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtfglvklay.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gttxtxroqa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtpzokzgzj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtcymfyybj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.316326.xyz/Article/details/gtpoenbttc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtynpyorku.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenjidiqi.icu/Article/details/gtborczuqu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtiitiiyni.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gthpfzkigz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhongyouzk.top/Article/details/gtzkcbkbjj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtfhfmeegb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtfpdeylii.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtdujgkukk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gttndtjjrf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtlmbrcfao.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fengsongda.top/Article/details/gtifhmfsir.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gthhcujnma.html

[L05] 上传文件（multipart）
来源：http://dali.tianlin.xyz/Article/details/gtqmnskdso.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtctzojczz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtjxgdvcrw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtjfkdvuwn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtcmzdkwcl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hongshengwenyu.top/Article/details/gtogbuhkxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.redwolf501.top/Article/details/gtznslctzf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtsnicvwlb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtdmyfzsop.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtwfujwhrs.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gttmrqicas.html

PHP:  json_decode($body, true);
来源：http://dali.shzxlz.cn/Article/details/gtrjrqcvha.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtclzqiyii.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtwbscchyg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtgqwjbnil.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlewzwjig.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfqobmnj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gtygzolykm.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtsoyqxbns.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gtpitvckox.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtkviaiehd.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtnbrkfrxv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtdjkjiecp.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtxhvyjpaw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtpvhdmfbg.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtjcslrmxj.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlidgksto.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gtmivldbad.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtzvhpkque.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gtgpnupzeh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtymwicnvh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gteyiztwls.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtvkisewmy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gttglfdzqv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtbhlflaaz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtavvltced.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkyxxawtb.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtzqiiwruh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkgvzxyjd.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtqxomsdtz.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtuaaahfsv.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpcjykos.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtjriravty.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooxqlfpo.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtoeojzfws.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtwmfgcmex.html

Ruby: ARGV
来源：http://dali.zhiwuduotai.top/Article/details/gtffinibac.html

C#:   args 数组（Main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtvgjevhlv.html

[M02] 读取环境变量
来源：http://dali.zycfv.cn/Article/details/gtvonfihwo.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtusrtaeky.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtjzpqeoar.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtgrphijpc.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtntiyumpw.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtytmyvaln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtrnuwfmox.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtejekmhbf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtqstaixod.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtsteppnuc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtevzvdkcb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtckdytoqf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtyrikpqcm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtotoirkrk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtubwbjjfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gttysnpbxi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gtgtjriudn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtqhvlotmq.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtofcymyan.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtsimzqpyd.html

PHP:  getcwd();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvrtbdwz.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtkozzdqmr.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtbwerlbqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtdbrepifm.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtzpubxhpd.html

Ruby: Dir.pwd
来源：http://dali.yvedp.cn/Article/details/gtdipukndj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtmselxvaq.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtqgcfhuhd.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtirffamir.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtqpigbhcj.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtlhdduhgl.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gttysyherv.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtcelcufst.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtplmaycxl.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtljrbsuvm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtrahpbmbz.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtcbkdereb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtcqpxtpsh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gteqeufska.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtxfublvzn.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtaibtfygl.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gteksuagwm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtphufofya.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqffzhht.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gteidahfit.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtlbccpxyu.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gttvekwfex.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtguyykisy.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtebathrdn.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gtzdctffik.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbbjgbcb.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gterreglpq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gtrgczjxgx.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtyawnkjbz.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gtvmkooibf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtweomgroq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtfsxnvfha.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtkrsthimi.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtkkwdhqjr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtmqtwjoyb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtxqnokbjd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.aizwys.cn/Article/details/gtsidainhk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtyikkplxw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsmmjakgo.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtfncewukh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtczgxhgrr.html


<!-- 参考信息 -->