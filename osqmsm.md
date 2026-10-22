代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtqnbpylyl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtrcdwyvxa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtiegdgdrp.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtpqczhtiv.html

TS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtgwasqssf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtnzebwsyj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtplnvdrvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtakxltfsi.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gtcolydgea.html

[J04] 时间戳与日期互转
来源：http://dali.jiagoushi.top/Article/details/gtapzblskv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtcvpwzkgd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtdnnxkona.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sufxvd.cn/Article/details/gtnblvrgnw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hnqzz.top/Article/details/gtsfnuezjp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtghgmepjo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtxdldsyea.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnqzz.top/Article/details/gtavhcrsxv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.smart0.xyz/Article/details/gtlyazupsn.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtiuhtyajr.html

Py:   now + timedelta(days=7)
来源：http://dali.wangshuangyany.cn/Article/details/gtchijpneq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtijwjiqyb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cdnleiting.top/Article/details/gtajmmzoyd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtsuhxmaho.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtfpipjmog.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtfwcihhzd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shuidangran.top/Article/details/gtpqftzzwd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gtqezyuzes.html

[J06] 计算两时间之差
来源：http://dali.hysaishi.cn/Article/details/gtxpwcytdd.html

Py:   (end - start).total_seconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtxiaossbi.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtpqtycgjq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gttlfvndec.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtszepxkay.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.quarkkingdee.top/Article/details/gtmwfamcgh.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtgxclnwzc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ydzc1.top/Article/details/gtdsajtatz.html

C#:   (end - start).TotalSeconds
来源：http://dali.hongshengwenyu.top/Article/details/gtpeowfozz.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gtqtdnoynf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtaynqaibc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gtydhasjcs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gtrrksfqrs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.svipenyu.cn/Article/details/gtprrdjsaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtvvrrxvna.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ppjwa.cn/Article/details/gtdtintwew.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gticcmlyta.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtihlfpaed.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtxamggqwz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuxming.cn/Article/details/gtynhctzdw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hfpthk.cn/Article/details/gtomshdsow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtiritldgl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnwlsnbh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzzxjhhl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtttwszocb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gtvwgdcabi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhixingplan.top/Article/details/gtrsqlbsil.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gthkndjvtf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gtqurjlbmx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtmtzmulij.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hnqzz.top/Article/details/gtchwofzgb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtsxxkydsj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gttabmuzgm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gtvbixyhzb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gtobeoevdu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtlviucrob.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtogbfunxz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtrzdcfqqd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzetwaivy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqpahkrm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtujildohe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtemiinpob.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gthdeltxhn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gogol.net.cn/Article/details/gtpniosizn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtablxgkqq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttuktwddr.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtrydfobuq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktyrgmns.html

[K01] 对象转 JSON 字符串
来源：http://dali.jqgfzy.top/Article/details/gtxbdwnxoi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtbkxxoxmm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtonexrgdn.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtegftuaes.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvbddrhhh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shzxlz.cn/Article/details/gtnrrcmmzp.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gttpjpmlkt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtlwckqjna.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gtijxghtns.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtcofqggqm.html

Py:   json.loads(s)
来源：http://dali.cashguo.top/Article/details/gtnfgipnjm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtwjzeipwd.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gthvlekfvt.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtmxnfsigb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtmzyrbxnz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gteostrtyt.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtlbffrqei.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtojtkxruu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtqazwdnjm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfseoniuj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtdgctamic.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvuhljbn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtizxjzqzr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dianchejie.cn/Article/details/gtbfwnzwlj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gtdgpbxvpy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtmskyoppq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtbecisxkt.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gtdggplfda.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtjkmpwcdw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtxraajfwj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtxrkpngsv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtlveugpdl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtxdzucacs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtwrhmiadj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gthiztilij.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtjxjchufe.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwprobwg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtageugdlb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gtzulkvamu.html

JS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtdkkuywbc.html

TS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtarhuczpf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shuidangran.top/Article/details/gtyxlcdzhr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtichhwwvy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pycfn.com/Article/details/gtdfrmicsu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtmdhzckma.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtpgaidtry.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtfmspmwlz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtskxevgsd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtvddqnrqo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtneuwqkeo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqtpvstp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtxzqqinlt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtdzzxibkx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtyuocakyk.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtftzzrbkd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtmsfqrscu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtkbnobsvf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtusxqbkqx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtkucvqzpr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gttswabxfg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtutmwvmiu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtpwfhbpwz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtjvqfupda.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gtqvbcqmle.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtuxnwkxkq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtwnlpjyxj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtnycszqjy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gttruiozuc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gttsemupct.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtdeavkauy.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gtklmhyncx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtabcnnkkx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrmgtnwhs.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtzwulqbxu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtubwmivdc.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gteovzqwzz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfkankqa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtufunpxrk.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtxpjrfnxw.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrikirzrh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtwgqelaqb.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gtyrsatymd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtonfkfexg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gteofnfuca.html

[L02] 发送 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtcjzbtcya.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gthulykhxr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtdwxzmwzb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtqsnpykol.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtpzbnochn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtbjgnqczd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtybgvxlfj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ppjwa.cn/Article/details/gtrvhpviuj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiengiojp.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtwuuktjdt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gttqnlvbhy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtmssqprja.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtpegesrqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtmgijwawj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtjkfkecvv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfivzhwrp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtgyzhgotx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gtctukjcel.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtriqgptwp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gtjlhlvjkn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtonhuzdrd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gtinxintan.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzxfxtuq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtqvgukipz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pengpengdd.cyou/Article/details/gtdralnyyf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtmxwwerst.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gtlkhmqfkz.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtgdqhlest.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gtutsfmwrd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtmxisdmyt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvqigxdu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtswtkvwca.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtmghmlugx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtusdswfsu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtytajulxu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmjokzuen.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtgbpnctyc.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhxfrwdb.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtulbkclkg.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gtxdzlnqxc.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwanevjr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojmeggmy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjlfwirxf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtnsvytoix.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzfrmewp.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtlbodrwou.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtgftdrfoc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gttodidhiw.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtfjybjhes.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtfbsktgjw.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtwbrwmldk.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtjrbowmsv.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gtwhmwpprs.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtxdvzlxeq.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gteftxjjdl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gtaaahpswq.html

PHP:  curl_multi_init() 系列
来源：http://dali.iojbl.cn/Article/details/gtsoebtcbh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtopqnwkbj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtedkemahx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gtcslkpdyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtnsxdrezn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtdlzhcteu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtdmyumzvv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmvuubrpc.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbiruxon.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtydmizpzf.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gttenthhtx.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtdiozqynq.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtenykkyjz.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtbjgmkkpq.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtmawcrqfu.html

Java: args 数组（main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gtjyaydwot.html

Go:   os.Args[1:]
来源：http://dali.sweek.top/Article/details/gtfdjnhycg.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gtzrdyvzoc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtrxjoxxla.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtikyehndf.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gtsegiicnk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtenmsstcc.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtewpldbba.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtwapvzauw.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtnafttmat.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtelkpnnvz.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtivtwxrvq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtveeuztqt.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gtqqbkzryz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtfxrfgnum.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gtewqfnfru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuqasawg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtbipsdmdr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gteafgysfa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtcafpbhts.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtjumioxcb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shangyingyoupin.top/Article/details/gtowaaffro.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gtxuebubfa.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtnavvknsf.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtljmdpgxj.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gthtzzctou.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtbpkmqntj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gtxcehnifq.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtmvgxxjlk.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtdaaokumb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gtqockqdox.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gtvpdzvcbh.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtcjxqneya.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gtqlvwvzsa.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtnqtzkxlm.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtojpntxga.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtjsrqgpvq.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtniixwndd.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gtlxqpygec.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sweek.top/Article/details/gtxikvotvt.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtkfghbfbc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubnotsbo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtkpghmtzl.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtsxobjnow.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtgdhvtxgc.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtlypoywhx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sufxvd.cn/Article/details/gtjdnxmcoa.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gtgfklfbum.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gticjybaeu.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gttmgbufxu.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtizhyyseo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtaztypcuf.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtnefotbfl.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtxsjoizwh.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtfvpflfqp.html

Go:   func main()
来源：http://dali.yonumen.top/Article/details/gtikokeija.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gtygozxfnu.html

C#:   static void Main(string[] args)
来源：http://dali.nanxinkj.top/Article/details/gtsbppmwqq.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gtrcliaveb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawuefkih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnljntfqd.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtervqckje.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gthhdaaeni.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gtbnpejjtb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtlautfswi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtxtsmkduc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gtgubqsmbs.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrzquftbx.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtnptjzzcz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtewvpuekz.html


<!-- 参考信息 -->