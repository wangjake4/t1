代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gt2afvjbqka.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sxryk.cn/Article/details/gt2cenzjlbj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gt2brzkyyji.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruxyflpm.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gt2opnhyref.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jiagoushi.top/Article/details/gt2gjumehpz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sweek.top/Article/details/gt2ihayfnph.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2actffwyy.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2uqbwwkys.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gt2geruqzvf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kssxqysa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2xctrwtty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gt2tmtymxmf.html

[J04] 时间戳与日期互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgsjgsmm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2rsyhdofb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gt2brgtifqv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigfzy.top/Article/details/gt2avfcdxpg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gt2vfuqodto.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yvedp.cn/Article/details/gt2wjcemevr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gt2cteekswp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gt2rpfjlgob.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2ifmfysnw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2vnbiolmq.html

Py:   now + timedelta(days=7)
来源：http://dali.quarkkingdee.top/Article/details/gt2ttepadou.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2bkbwjrir.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqafzwym.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuanzhike.top/Article/details/gt2sjhisqli.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gt2tuzzequb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.wangdashe.top/Article/details/gt2niewpsyc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gt2pgoagpel.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvpbquqk.html

[J06] 计算两时间之差
来源：http://dali.gaohongyu789.top/Article/details/gt2lbggkmqp.html

Py:   (end - start).total_seconds()
来源：http://dali.hysaishi.cn/Article/details/gt2nekuztxs.html

PHP:  $end->diff($start)->days;
来源：http://dali.xylfe.cn/Article/details/gt2umbgbxhj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.316326.xyz/Article/details/gt2nsasnjjr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jianghu66.top/Article/details/gt2dlembawc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gt2awhcujwt.html

Go:   end.Sub(start).Hours()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmkgcaeu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.smart0.xyz/Article/details/gt2sholhenl.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2hmeuejup.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gt2omdnekrp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2qljafqrc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gt2jbqkdsmo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gt2smzucvuk.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gt2hftdvmom.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.gaohongyu789.top/Article/details/gt2pbsnajyu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2mmqshhpk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2kbszuxyc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwblqayh.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gt2qtzziytp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.redwolf501.top/Article/details/gt2zgdmxuop.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gt2enrgdzmz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gt2wkgmkqfx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gt2arlrcgxl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwngxtfu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gt2jygqvgtg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gt2imsyopuz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gt2svuopzhu.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2onyeluli.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gt2cmuqbcon.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gt2fozheqll.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2utaozlnu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2deonfmab.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhongyouzk.top/Article/details/gt2noxeeonx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2tsbalfey.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gt2cbxpjodn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jyoumei.cn/Article/details/gt2kjftdffb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gt2fawiuntc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gt2awxddhez.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gt2elfizivq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2xkjkkltn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2oqwbgpeb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ujxhaefd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.vqdsnc.cn/Article/details/gt2fkqukvuh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2hmjmbekz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fzhhl.top/Article/details/gt2jpistiaq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tvoueujq.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2qsmogvbo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2lfwfeicm.html

[K01] 对象转 JSON 字符串
来源：http://dali.guowangkeji.top/Article/details/gt2cklbnlct.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2oujjngfz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2iyqjnrjd.html

JS:   JSON.stringify(obj)
来源：http://dali.yj20258.top/Article/details/gt2vniqfdzx.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2acswcaar.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gt2dvarfibf.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2jngzdmmp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gt2zwfxqtwt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2nlmjhtan.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gt2osoyibyg.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2uzqmktsn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdyfbjoe.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2uvbwlvnc.html

TS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gt2knvhzpyb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2haastsyk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2eplpksqh.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gt2klepceoe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hfpthk.cn/Article/details/gt2uadpucxx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2hrtwauxm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gt2krtjmvwz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gt2urtojymq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2tghxdjzj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gt2gpjrzwsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2pnycjlol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2ysioyovh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ifwlxqhh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gt2wrxinzzz.html

[K04] 读取 JSON 文件
来源：http://dali.daria6918.cn/Article/details/gt2ptofglhh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenzaomai.com/Article/details/gt2etovdjgl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2qggaxbkl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2bnsfyumj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gt2oopcipnu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2sndclovw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gt2hgrjxwsc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gt2wztrwhga.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2wpfgdrhz.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2usuuwynu.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gt2zbcgrpii.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2nqzdilkn.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsempdmt.html

TS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbolrsxo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gt2mqpvpoih.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guowangkeji.top/Article/details/gt2sjuplfxj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gt2asuwczpe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuxming.cn/Article/details/gt2aefhkzud.html

[K06] 解析 URL 查询串
来源：http://dali.guowangkeji.top/Article/details/gt2aubsetes.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2zkgtcmgq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gt2dlardbyi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gt2huvsvlts.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gt2mhqyzotl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2hlhulxqk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2dtpgqlzz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2lrvxqmfj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gt2tlmnfobi.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpqviedr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2cxknkulr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cdnleiting.top/Article/details/gt2ezwuqdma.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2bcmmjgzd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2rqthwhwx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2gybgboea.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gt2fqvvtmay.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2yrhrmafq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2hvetlskv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2nmarngyb.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gt2yvqlrnen.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gt2kwbvsnxy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2ngqiyzqk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2yfmuafkl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gt2xcwkstjm.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gt2epelvcjg.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2sgoxbuld.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gt2ntbchnlt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jafgisqg.html

L. 网络请求
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpawppkh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ykeidxeb.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gt2nbcbrjew.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2wrozjpif.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2esrqzwnv.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2gomrzgur.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2wafiuoqt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2rwgetyzt.html

Go:   resp, err := http.Get(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcglpcem.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egkrsckw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2smslbfxu.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2cloyjekw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2lizpwubj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gt2jclpbgrs.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2vberprdb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gt2mexfflxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgufenzy.top/Article/details/gt2qgfhthvs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gt2weuamfow.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gt2gwzfjheh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2vkmcnglp.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gt2obsnijnk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gt2epzylvms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.svipenyu.cn/Article/details/gt2sywolyuk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2mozboicu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gt2bikqhqwk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxinkj.top/Article/details/gt2rhjukvei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gt2iesgnoab.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2wzjsmvec.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2mrpvdpzb.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2eltqcair.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2dwnzqqlh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2phuduqmf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2sgaxvbcy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guannengcc.top/Article/details/gt2dzvegxnr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ynrnbnrq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcbqrril.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gt2nymagtnk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2skecutri.html

[L05] 上传文件（multipart）
来源：http://dali.xinyue.icu/Article/details/gt2spxcfxlq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2oicdbyfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ernughee.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2eplgyney.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2pzbxumzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.aizwys.cn/Article/details/gt2rzmzvhni.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2cdnouics.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2negsxapz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ajurevod.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2ioeplkgd.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyrzenho.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2dozkqebe.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2osyoptwo.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2xawzcmdl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvqbqave.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2cokxbmvg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iprbrvjo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2ylgzajly.html

[L07] 处理 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2oramluqj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zycfv.cn/Article/details/gt2bkeqmkio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2kgjmwhiq.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxxdfbny.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2nmqyforb.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2ihxvsvkg.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gt2prfwqhxg.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gt2cvgrgqst.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2xyoucofd.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2ftpkrvuk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tanke756.top/Article/details/gt2viuzlbpe.html

PHP:  curl_multi_init() 系列
来源：http://dali.aizwys.cn/Article/details/gt2jrwyrvtq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jokcuwvg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gt2gfhzfvna.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2rexbgjvy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cazivkan.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gt2nyfwdqbz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2ivazlunb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2tgsibqkt.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2enaaoyun.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vkwnoxok.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaazgjut.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gt2knpizvux.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2amilpbfe.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gt2dcjrwlej.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2mcnmhpaa.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2cearmezg.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axkauzle.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gt2qofetkdg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gt2rodrgrok.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gt2dxvozpog.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2oudjyzsh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2schrqxak.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2cgviimch.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2ovquexqk.html

Java: System.getenv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2cnfyaclg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2cqxjrzuz.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2ogtmtenb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2epfenaft.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2utezxici.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gt2geaaxeur.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpyktjxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2uivptlta.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2moepeogp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gt2vzcomyfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2iaybjdmn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.haohaochexian.top/Article/details/gt2raiwlrxo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfbbkexq.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuupdrmn.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gt2mcayinyg.html

PHP:  getcwd();
来源：http://dali.yuanzhike.top/Article/details/gt2ihbcnmad.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2zyweamdd.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2ojerxokv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2chhzesmd.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gt2kdipsxuk.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gt2oyfvbmnb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuanzhike.top/Article/details/gt2xfixtkqb.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2huhgtqzp.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgwldcvl.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gt2niytjpzl.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2uvkohsrm.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2zcpjzqvw.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnqpjaev.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqtwjplz.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhefmmwz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnwfxybs.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2etmlipxp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsxmwdzn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenlongwang.top/Article/details/gt2cqwezxbr.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gt2ixagwzij.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2owexrexr.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gt2nnhwcoga.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gt2xmfbwqcu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrflppr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcgfmpbt.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2wiswibpz.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2nztbzdkb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2joxqagxd.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gt2qlxkxzpg.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2sxioidwj.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2fniqetej.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulweqjdc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gt2hyxlqcll.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2ajponwtj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2banisdlq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gt2lzkccccn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2oeguyftp.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2yhcjperv.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2vozholqc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2vfjliphv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2modbshzq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gt2wlarmufk.html


<!-- 参考信息 -->