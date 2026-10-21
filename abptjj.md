代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtrrioevun.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gtabklewoe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xziqi.cn/Article/details/gttmzshazj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtcrgqcgpm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhbefatv.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtnssspbjo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sysykeji.top/Article/details/gtrnfjpicq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gtujymvbbf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cqqwz.cn/Article/details/gtkgxrjxoq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtmhgwtzqc.html

[J05] 时间加减（加 7 天）
来源：http://dali.snrcjt.cn/Article/details/gtqtlprwyu.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtlzkmqirv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gaohongyu789.top/Article/details/gtqvgxfmar.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtrsvffmkl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtcsoxtanw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtshzlvqqm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwwqgwpy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gzhubu.top/Article/details/gtoiocjhxt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjgbatzl.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtmyskyocr.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gtllxlzdao.html

PHP:  $end->diff($start)->days;
来源：http://dali.cucudq.cn/Article/details/gtxbabblwb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gtczjtlqmj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtzoccnewt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gtplsajsfq.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtyxcivfir.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnqzz.top/Article/details/gtojurtjgn.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtxkhedtpf.html

[J07] 比较两个日期
来源：http://dali.smart0.xyz/Article/details/gtjxmxhrsr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gthqzerzht.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtkyiwwiqg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtcpryimje.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtjwsvhyii.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yueranfly.top/Article/details/gtvderkuhj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtknqingel.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtigtgfqvg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtgahefhlp.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswofumpv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.9152youxi.cn/Article/details/gtmnomhsfo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hywenlv.cn/Article/details/gtvyatybgx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtzskudovi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtmxycotba.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtyngknnnt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtkiovrvvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhixingplan.top/Article/details/gtphxrlqjy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtiuukesmq.html

[J09] 时区处理
来源：http://dali.sxryk.cn/Article/details/gtpgwrkvzu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gthmuiiipc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gtmyqiapro.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gtbvubaiut.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gteailnyrn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gtsmalqwjs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gthvvsaebu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gttmvwlfwo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtnmdqblki.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gtfetlewfc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtirehgfvs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtvroklryg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zycfv.cn/Article/details/gtnukwlkll.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtxorasmqr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gthvnfvrei.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtiazxppzd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtluidygna.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtyzxmlmki.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkhhssjav.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtvajpjuur.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtitepvurh.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxumvtckd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtwqlrhwjb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzccaqbj.html

JS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjpikttem.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtyzsuygxo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtzqrcxcoa.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtswqnqrgw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gtmlohkfid.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtuypscjns.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigfzy.top/Article/details/gtdibuibxu.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtqletccnp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtosdvuclz.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtyhjtaiqs.html

TS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtqeyanbxg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtoghkcfpj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtbffhyqfm.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gttjaczsco.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtepcefcsf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtrvaoxlev.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtpzyagbpr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtubsrwzsw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gttqffudiy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtblcqwzjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtylviyxir.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtswxlzero.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtipxxztmv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtsilxojkz.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gthbklkmui.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtrduvqcmu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtovkzqrbh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtnxttmfoz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtikypmlqq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtlagiktrr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gterkdlmzq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtikwebyqr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtejqfvxxc.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtttkjhaet.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtqbkkfwix.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtpjohglup.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtvxaslbch.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpyapgvoj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtzfdpplwi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgocciysv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtlluutedp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtpqtrzqfz.html

[K06] 解析 URL 查询串
来源：http://dali.chenlongwang.top/Article/details/gtvpdfgisd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gthaavmyrc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtzcumivhd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtwhykucst.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtedlupqgz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtgyocsgmw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtpycqtwkh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtqgayrpuf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtnwkbbelu.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtsxrcbqrn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtynhivzaz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.9152youxi.cn/Article/details/gttxyugqvz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtcyjwtepi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtmjfysszo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtpjiuhztd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbupjskm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtgnzpiaxs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtcsnnrrhn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmgzitgu.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtxpzgnbgo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtaptyiimf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtoquexqzl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gtimhfyzzr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtckiqrziy.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtklajwsbz.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzjlmxxbr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtbzborprh.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtohlqkptp.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtmplhowdl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyfnfqqxv.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtvikeoxmd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtsyruddzn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtdlpissxv.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjwjoyhb.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtrfmdhiik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gtsdgtlkoy.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozoelozl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gthjdanzaa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.vqdsnc.cn/Article/details/gtrbbowwnd.html

[L02] 发送 POST JSON
来源：http://dali.birdmap.top/Article/details/gtpbskrwfm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tian-w.cn/Article/details/gtsdwkoiyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gtlnbmhvad.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtncbfegbh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtvvwfryco.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtufqtxcff.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtdcizphrj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gtrdfvxrqb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gtjrecgfok.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtefdokjki.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtmcizwfnu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtllotzrcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtnxapvgpt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtuzupljhq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtqmbnaieh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gthsbzdpyz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gteoptitbi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtatdrjmgi.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gtkstkljvn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdihpxgel.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtrpqeogbu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtihbciurg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtfjlhzvxb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gtdmuqkcnn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gtcanwlmfv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtjlhhvqre.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtrlhozqsx.html

[L05] 上传文件（multipart）
来源：http://dali.tian-w.cn/Article/details/gtzgjjtixi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtnvcqdooe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtqdwkbico.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtowijxhqq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtfnytgric.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbudxesny.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtnpoeniwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenzaomai.com/Article/details/gtohsumdhq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtinzmdspi.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtjruxnazd.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtuqkyytll.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtvgcivysh.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtbfigcrvy.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtemknhivf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtjmgudtjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhiwuduotai.top/Article/details/gtgovhwbje.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtwvclnkjq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtklsfvbnq.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtvvjmjlkx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtkkojcruf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtqshdlfzf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtwcgiadpj.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtzfbhngva.html

Java: resp.statusCode()
来源：http://dali.tianlin.xyz/Article/details/gtsqkbssgn.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtpzaktpaz.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphbgvyhx.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtomoeyntl.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtkwwelntb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxipbanj.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gtobehteqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtmqmckaxh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtytadwthr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtesomwkkq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtyzmskksy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtjitqgjkv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtjymsauao.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyrrfwhyg.html

M. 命令行 / 进程 / 环境
来源：http://dali.9152youxi.cn/Article/details/gtyphwqims.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsrusynks.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtkvjbqfpo.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtpieruugy.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gtcjrqfvyz.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtllqntary.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtiljfwqff.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gtzqzxgwiu.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtrwifovmc.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtwqffjtgm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gthrwnrlpz.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtgfvudtdf.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtewnvfycu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkjlqlre.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtjgpkotma.html

TS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzlifefx.html

Java: System.getenv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtayredwaf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gthnljsnpg.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gtuuqiscnm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtbxfuwxah.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtmcdohnzz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gtdhsimznj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtogktuwfq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzwukhal.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtcfvnzwvs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtnjvnevky.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtqodviuwq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtfbmqygjp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tian-w.cn/Article/details/gtyhulmlwy.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtqtwegdll.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gtvbdncyvs.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtyhdaerff.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtkvpprldq.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtiyavamkn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xinyue.icu/Article/details/gtxwmqkpym.html

Go:   os.Getwd()
来源：http://dali.cucudq.cn/Article/details/gtnsihgmwv.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtzpuyrbfr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtuxkmxygy.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gtdsnokoob.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtbomrbwfy.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtsgytmpso.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtfqfrmnjf.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gthrrwecdv.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtkpvcahdo.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtmtyyybhv.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixjuhzsa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhhvszds.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtcsngobch.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtvhkqvvex.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yonumen.top/Article/details/gtdwcshrcs.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtdxjtpglo.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtqunwipuy.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtizsfhogo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtmvlzsz.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtfgibujii.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtfkccplyo.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtyydhtgow.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gtasmmmrcu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtacejnohz.html

JS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtyogtbmig.html

TS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtaczpjggk.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtzfckfyya.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtfvkzbyfa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtjbnnrpjd.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gtaziwzury.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtcondxeev.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnxiangtu.top/Article/details/gtxyfrxgpf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtlhoadfnw.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtyuinvcam.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtuemqjezy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtpydxanem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtokofhkxz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gtzysmbdsh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtvrqrjwkc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfywmkfby.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtxxnncuqk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfluzfcnw.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtpuabolar.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtprixyary.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtaxlzjzfh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtvsluniao.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtexdbljci.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtuskjodey.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtotoofbmo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gtzbfvgndi.html


<!-- 参考信息 -->