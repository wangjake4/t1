代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.kuanghao11.cn/Article/details/gtogiyoecr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtwujrjlmk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtlcqwtubt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtlpofojot.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtvebywtiy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtkbjwyoei.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xziqi.cn/Article/details/gtqvcygpej.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrjjegfam.html

J. 日期与时间
来源：http://dali.aizwys.cn/Article/details/gtwsmawptb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlqhnrtjh.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtfopnfovg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ivvv.top/Article/details/gtpwwlbdkf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtotqhgcda.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gtdxtycbuk.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtdpjvrkvb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtajwrgbdq.html

Go:   time.Now()
来源：http://dali.andypj.xyz/Article/details/gtyeovnuam.html

Ruby: Time.now
来源：http://dali.0kj1m.cn/Article/details/gtekvjnpcc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gtjrrjphpd.html

[J02] 格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtieqrrzgf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.vqdsnc.cn/Article/details/gtkbdqpvmb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtpmqskjql.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtjlhwnduz.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtkeycohvv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gtmnanynbj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtrhlnslma.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtcthxdrtr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gttvpdntvy.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtmfzjzxko.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hfpthk.cn/Article/details/gtpyghlwaj.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtspioelnd.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtbswoglya.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtmrojhaub.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtznyulctx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ydzc1.top/Article/details/gtabareclm.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtqjjaumzx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jlsjyb.cn/Article/details/gtwxotrqsx.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtqlmsgltb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gtidcsdqyc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhongyouzk.top/Article/details/gtswslyvra.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gthplmfiaf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ivvv.top/Article/details/gtaieqazhx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hfpthk.cn/Article/details/gtrfxkhaan.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtqpxknpdg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daria6918.cn/Article/details/gtqeijdhzf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daria6918.cn/Article/details/gtqzlceexb.html

[J05] 时间加减（加 7 天）
来源：http://dali.mhx1999.top/Article/details/gtiwquuejy.html

Py:   now + timedelta(days=7)
来源：http://dali.mhx1999.top/Article/details/gtuwwcimzx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gttbrwnufo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guowangkeji.top/Article/details/gtmodzsrlx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcknsmqqv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtjosieuxl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtwpxwvden.html

Ruby: Time.now + 7 * 86400
来源：http://dali.meibo888.top/Article/details/gtmcqcoali.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtouwjogjq.html

[J06] 计算两时间之差
来源：http://dali.havefunace.top/Article/details/gtekcqwkpe.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gthlxmdfgn.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtdintacfr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtqqxejlxt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafbewrjt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtxrmqdwkq.html

Go:   end.Sub(start).Hours()
来源：http://dali.hfpthk.cn/Article/details/gtapcpevfw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtxhzfciwn.html

C#:   (end - start).TotalSeconds
来源：http://dali.yueranfly.top/Article/details/gtuhqofqtx.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtcxstkkzq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fengsongda.top/Article/details/gtjkbplaop.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangdashe.top/Article/details/gtkfidtghu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrdeqngz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtunphcqoc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtjbgeocul.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgfzy.top/Article/details/gtbrixtwfz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtcjsnwoir.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gtuncrying.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtellwzewd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gtofubwhjt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtugndgpqu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtlsnlijon.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gtkeiuwxzl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gtsdtcgzjo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gturlzaxbf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtepcrxeem.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jlsjyb.cn/Article/details/gtyvhxenxw.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gtokpfsqqv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.c1oappe.top/Article/details/gtizbzwcfy.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtfqqkkyhm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgfizisi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtlixmnucz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtprmpofro.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuhlkqaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtjdaqbtby.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtqaituziw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbklvicpz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtphidcwuc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zdqjudy.top/Article/details/gtcphxrwli.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfsmweewb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtlhxryewz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtnnxfdvat.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtptbmunoc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dianchejie.cn/Article/details/gthzzjywwn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtpyveqomi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiwrqager.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtqtdydncl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmaifffgv.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtnsgwivyc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtobyeuqrd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirazgylt.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkefdtlow.html

TS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gthdvtffvy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gthyqmeiyl.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtlazmiwlo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtefpdpkhn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfumipecg.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtddvmccgj.html

Py:   json.loads(s)
来源：http://dali.nanxinkj.top/Article/details/gtfohptwmu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtabolmqvz.html

JS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteglcjigu.html

TS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtryobyxzj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtdxqnyvio.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtzccvdbyq.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtkfxfvwyg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhongyouzk.top/Article/details/gtyobxvywe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtishwmrmd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtkjocfulo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtgtfgbqqy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtrbeabeqw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtltkzcbmr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtyxmdwlun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtgtohbtnd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtfhlnpcma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtyyryzunu.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtoiovujxs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtfvlihcts.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gthbbpqdlf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtosgaetvx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtwfyzaaai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gttwgluvva.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtzffqntwj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gtkruttbst.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtosreaowq.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtansqlfkp.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gttyldfcln.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenjidiqi.icu/Article/details/gtarnwcfse.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtzndzfjcu.html

TS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtkfmtshtn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gtbfujmtnp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.havefunace.top/Article/details/gtfdbhxqlk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.andypj.xyz/Article/details/gtvozvyrma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gttfxffyrc.html

[K06] 解析 URL 查询串
来源：http://dali.jyoumei.cn/Article/details/gtlippviok.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtfmqxaymg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtpibznkhn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtzngnsqqm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtvhspfaet.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gtashzoizn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtagjwpfwx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtisvtdvsf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtkrwclpbk.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gteidtunof.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaptmmhfx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtanacpjko.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtkmrymiyt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtlgoopwlu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtnrgicoxd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtyqtkogdp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtxkcczfas.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gthqkhtdqa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gaohongyu789.top/Article/details/gtgjpnkvyi.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtebtnnglb.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtdwctzpfz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gttttrfufa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtommwayfo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtnqyfljcm.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtarroexle.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtvtequolh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtngnvwiea.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttcsmaiyt.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtkhemayoc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsezxinkr.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtrswbtuop.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtusongpgv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtqbfrmpzg.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gtdnbnvgog.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtmdgindhn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtltjuaakh.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtrsyuirdn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtzaxpyrbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtllikzymi.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtnnlifxuf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtawztreqb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtpxlwrtte.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtcidhbvsm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gtbxpjzrbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtjydxqetd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtktveyxwl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtehycuneh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtxrrnruwa.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtqcdenneo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gtxyvafnin.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtxqzyyriy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtrdczorng.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gtynvcyprn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtjenobkat.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtkrtbvpnr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtndjuxoiv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtsyseepop.html

[L04] 设置超时
来源：http://dali.iojbl.cn/Article/details/gtxmyehfza.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtmpedkoob.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtjlhbtpdr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtchgkqxnp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtovamazab.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtfjroflwc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gttjspnigb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtddnkqplv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtvawfwnit.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtgytbasme.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gtdavxknce.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daxiang520.top/Article/details/gtbjfgfxbg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtzkelnfvk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtituvqjxh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcjjpmxk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtyoypxrwp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gtkufruvvz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtbjpeyeek.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gttnthjwwh.html

Py:   resp.json()
来源：http://dali.jinqigufen.top/Article/details/gttofvywnq.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtantlmjfe.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtmpowrcwj.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtncozrwyo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtmgecujkn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gthtbgiokm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gthegptoaa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtklafajnx.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtqbdewasn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtooenpflz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtggumdskl.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtqkgwpvzd.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxgazwgh.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gtnuhytdls.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtwrpofmsu.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gtripqffaf.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtuaavjswg.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtqejgblwl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtakwnwuvw.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gtjxtsrttd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtfemuhqtb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtjifgbowl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtfcivaajv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtelrqxfcp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtshcdfthq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtpjmjqvqk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnvqkcmip.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtfhcpuopu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtonnohmiz.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtljrwppuv.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtjrsaqakw.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gtfscjvqcv.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtbgjebjmm.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtctmddqpn.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gtifevijzw.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtsffmnkyg.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gtdkpanqya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtdiuixwhe.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtmwdfpkaz.html

Py:   os.environ.get("HOME")
来源：http://dali.yvedp.cn/Article/details/gtbifsaynv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtjqjosfbq.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gthuvqxrlf.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gtrgcvpava.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtvgchsdvj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtyrrjoobc.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gttzllrlmt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gteuktytqo.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtgclcthal.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yongpay.top/Article/details/gtzwsewnpw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtekyyofcc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtwcffwlfa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtoennrizh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yongpay.top/Article/details/gtynezcene.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gtidnihscm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtdphavhjs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtjrfwasiu.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtlkkymkja.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtumsgxrxg.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtysvymwfq.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtnsupxuuh.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtybzyorxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtoysskpnh.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gtwyeejkae.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtmltzbwdg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gtveebmcko.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtlmslxizs.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtbomgbogx.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtaxjzkris.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgujgcfba.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtsgzdtydc.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtzppeycma.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gthrmhvwqn.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gtrwxefofh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthvbcbkg.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtsrktqane.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtifhuefho.html


<!-- 参考信息 -->