代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtzqzjzdqk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gttnaapkau.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtzjnaioev.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xziqi.cn/Article/details/gtyeyzszsp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtktgopyzk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtfzmmzehf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jqgfzy.top/Article/details/gtkhekiuaq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gtyohwmawu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gtsivubnzd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.kuanghao11.cn/Article/details/gtaehekzuq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtibddcupj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkginrtru.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gttfwkrtqd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtltryuenj.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtykrfcfhi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwmzzoatl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gtgzrmslhz.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtkmsoolbk.html

TS:   new Date();  Date.now()
来源：http://dali.redwolf501.top/Article/details/gtvwxyocaz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gtzqftsatg.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtmvexaiij.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtqthkiyrh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sufxvd.cn/Article/details/gtnsmhyqsz.html

[J02] 格式化输出
来源：http://dali.c1oappe.top/Article/details/gtgaayczqe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtwuzysnwn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtftfufxcm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sxryk.cn/Article/details/gtsyvdmpvt.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtzjwclthk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tianlin.xyz/Article/details/gtwxbqqjjz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhengqikj.top/Article/details/gtasjbehek.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gttrbbhanv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gtodgchbwl.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtpjdcdimc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jianghu66.top/Article/details/gtifojtgfz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtijiwpycv.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtfqwoxyvm.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtojvqlbja.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtniaoaqea.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtqwzwwsfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtfmamvzml.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.feifeiyinyue.top/Article/details/gtltfixpvf.html

[J04] 时间戳与日期互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnwpwzng.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtuhmtpzjz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtuybctzgb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtpntpqkik.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhongyouzk.top/Article/details/gtxajjbfug.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cashguo.top/Article/details/gtpjscdwkn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ppjwa.cn/Article/details/gtizwivcso.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtttfnfrlh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cdnleiting.top/Article/details/gtqxdgntry.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtqhkjusvw.html

Py:   now + timedelta(days=7)
来源：http://dali.snrcjt.cn/Article/details/gtmnjrbqhy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtocbpakyi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtwmmbuktm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtgqcxmpde.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daria6918.cn/Article/details/gtjuzdpopx.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtxawuifgl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtxpdildfj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtjkffpyou.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gthrdsuvpv.html

Py:   (end - start).total_seconds()
来源：http://dali.andypj.xyz/Article/details/gtjxxainpi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gtsaqokztj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtcrjklipo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.svipenyu.cn/Article/details/gtghzwfvml.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hnxiangtu.top/Article/details/gtncyozfpk.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtpxyvxify.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtollkyrlf.html

C#:   (end - start).TotalSeconds
来源：http://dali.vqdsnc.cn/Article/details/gtyasgywtf.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gthicogeyk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tianlin.xyz/Article/details/gtaarbieuf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtxrpxcnii.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpevhhtqj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gtobdgjyle.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtozdnehyz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtrwhowpex.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gtbhsokanb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtepccwaqa.html

[J08] 提取年月日与星期
来源：http://dali.pengpengdd.cyou/Article/details/gtylpuxanj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtoshagoho.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ehwqpu.com/Article/details/gtqelxhbvs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.bjfxy.top/Article/details/gtyzgtqfly.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenlongwang.top/Article/details/gtljfyzstr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenjidiqi.icu/Article/details/gtriauvpul.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.feifeiyinyue.top/Article/details/gtyoedbjmv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtjphktcms.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tian-w.cn/Article/details/gtjwasyfcd.html

[J09] 时区处理
来源：http://dali.316326.xyz/Article/details/gtvjlgsnib.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yongpay.top/Article/details/gtrgnfgtjy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gtwevnwvyw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gtxgcoxwax.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gtzeslmpgx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhixingplan.top/Article/details/gtmkqocnpy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gotoacloud.top/Article/details/gtghiqftqh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtfpbairwg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtinyertbe.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gttzywxlwt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gthnlwmqpt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.redwolf501.top/Article/details/gtyjohzani.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvwpaseh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhqfwyrc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtgzylqykp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gtupztntim.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtwfhqnwoe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtdmcynmlt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgasrnhak.html

K. JSON 与序列化
来源：http://dali.hnxiangtu.top/Article/details/gtbjgfnima.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsdurtaqo.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtwcbrqxwz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtrsdkmhtv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtdiipzldm.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjiozrpqa.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtdgarnpra.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtpyqpntgm.html

Go:   json.Marshal(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgkehlujn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtpipqxvso.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyexfflmt.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtbsiftlnj.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gtztpnbhgo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtyiqnccwx.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtevzqqdls.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtcnhrlfyj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtuxgzyaww.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtrrumqasy.html

Ruby: JSON.parse(s)
来源：http://dali.yj202588.top/Article/details/gtnafqzhot.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtftxojzmt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtrjwihadh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtqziwwfah.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtqtogrhvs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gttjhlmbcn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcjqived.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yueranfly.top/Article/details/gtzkjduuwn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtqaflwyfy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtmmbeitzl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtdicdcvvw.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtzgvhouck.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtnwkurznu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtuhzxuvsj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtvepukoct.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtqmiysnyp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtnsunllvr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtxtmilwyj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtvnudahhh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gthoqiwlkt.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtqfuvqqgv.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtggjpzzif.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gtzrjcunnb.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtzugakarq.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwcjuvdha.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gtvjkvqgka.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gtytgqfnst.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsealgfyj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.smart0.xyz/Article/details/gtnkkcfeyp.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtctmktzac.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtxfsojlyn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtviumdxim.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtxcpgrgje.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtlrabpoak.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ppjwa.cn/Article/details/gttrrjmyom.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtrlngmjjf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtdgxnaore.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtwzspfavq.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtqoeqvjms.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtemjajjcm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtynbvwfyt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtxhtzgwlb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtwdcqeege.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtaxkgsqsz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtdskkcnbm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtindlvhvw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtswvosigz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gteccssuid.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtsvpqlwqg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sweek.top/Article/details/gtpyxbgucg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtpsilpydt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gtkwhqjhco.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gtivsrvqzc.html

Go:   encoding/gob
来源：http://dali.nanxinkj.top/Article/details/gtltgppadu.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmyoibgsh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtfdrlputh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaawaqgur.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtnbzpamgk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwxyjrekm.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtguvzamrw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gtxuqxevzz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtkfdvzvgr.html

JS:   await fetch(url)
来源：http://dali.hywenlv.cn/Article/details/gtlzjoladm.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtabjyhlmk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gtanqqdcox.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gtlhbfaizm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangshuangyany.cn/Article/details/gtzeyyijww.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gttbxxages.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtunoaiftt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.c1oappe.top/Article/details/gthtfqknji.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtexozflil.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtpiyxrlga.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtkfrutlea.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shzxlz.cn/Article/details/gtjkjeagxd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtvuckhyeg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtnqhmevsp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtyrzppjhe.html

[L03] 设置自定义请求头
来源：http://dali.jlsjyb.cn/Article/details/gtzmnqpfns.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gtshbvtpxf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gtrcepqpbg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gthsitaqpa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtdrstecdz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gteistnzgr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gttoslfsbt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvpigten.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtyjdtwrwd.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtgtnfalbk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtomsyeorl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gthukhxbqg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtrbghvotv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtwdkwsdck.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gtxqhulpcd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtylewehrz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtpupvbjfv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtncciotoo.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtqretvyth.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtobmilfvq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtcgazoqms.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gthxzlsstl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtlxhmuxaw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtvocqunsr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gttgxalibv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtwynclrfa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvkorjarv.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gtguytlded.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtrtchouwr.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtlumwvgts.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtuyzzpkid.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtjxfkbhre.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtdekrutwk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtabcsgrer.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtrnjqunyu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtjmqgsqyy.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gthlvtvyda.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gtsdynsmlj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gtqtccgjtd.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtwrgxinbp.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gtamvzhwle.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtldggajhi.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtklrsodnm.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtbngkponb.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtgxhhwskd.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gthiuflzxm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtkkjvpmlv.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gtawtxxsqm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxskghaba.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtveholdzh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtgezfksla.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtlhmszetv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtcgjlktyq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtiodsmnwb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwibqnigr.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtxpczwqhl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtefmrsewc.html

[M01] 读取命令行参数
来源：http://dali.cucudq.cn/Article/details/gtjcgwvfoc.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtgrrznnpm.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtxlpaqstx.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtfbxxrpei.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfofeunnr.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gtfhcziwcz.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtzqouwbrl.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtxpmhcbxv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtsvfoamcz.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtqmsnnlny.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtfzmqxmge.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gthnbxhlxv.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtlnjzwltd.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtrhtbbvho.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtynnrrlsd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtyfpupacb.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gtrkhfwwci.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzxxolhw.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtblopodun.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jyoumei.cn/Article/details/gttxumrvkv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtuagyhkcj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtpyjxbivp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtkvecyyzh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtxfetpzhv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gthqpzovch.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gtzttahkko.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtkjxedvbu.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtoebexgkg.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gthimblnzb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtqwtnjxgr.html

JS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtcbmrxufk.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtzmatjisz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtndohaspn.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtbrnaxjnd.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtvpgixwka.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtnqsbrtxp.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtjrslsjub.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtheolakde.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtbvcdrbev.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gttxpyepfe.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuggspkkx.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtedktaduw.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtdhyydshu.html


<!-- 参考信息 -->