代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtvpuacjbg.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gtjaeztfxn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.birdmap.top/Article/details/gtowaaciqw.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtghtfsznr.html

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtmpwfoxlz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xylfe.cn/Article/details/gtubazzqee.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fengsongda.top/Article/details/gtiowgnjiq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shangyingyoupin.top/Article/details/gtsnjtacps.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtwpsbzmgj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gttgfdmert.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtisvllugw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkorrita.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxinkj.top/Article/details/gtogoanzml.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtxwgctjqr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hongshengwenyu.top/Article/details/gtjedhcqgj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtbpmuuiad.html

J. 日期与时间
来源：http://dali.yuanzhike.top/Article/details/gtffqyzmnh.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvmkzsthq.html

[J01] 获取当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtszfqhusi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtpicqyvwm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtbaitqnvv.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gtkbcgjrfk.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtgyarplac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shzxlz.cn/Article/details/gtydvpygex.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtglzlhxsr.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtgbynocns.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtqgfvgeld.html

[J02] 格式化输出
来源：http://dali.aizwys.cn/Article/details/gtoiknxjnj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtprsyci.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gttdgnzytg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtzdtrelea.html

TS:   d.toISOString()
来源：http://dali.hfpthk.cn/Article/details/gtepjamasl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtwwnnumvq.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtupxrwhgn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtcvkkgfyu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnaxdnfu.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtuilxpkdj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.sysykeji.top/Article/details/gtcdfzaray.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtrcqylbnt.html

JS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtqbihixlo.html

TS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtddbuyxmn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtavihkihm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtaqnxygth.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtvwqkugnd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.haohaochexian.top/Article/details/gtsgmyitur.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtomnymrcu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yj20258.top/Article/details/gtflyftkld.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtujnatlxd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtkcuolcus.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpahoqdc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtwrifblpu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.316326.xyz/Article/details/gtvvfghvqd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtikuqwpso.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtqdxtsqwo.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtlxcbghhr.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtkkzkkfrc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gtelnoonjc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtbvszzgsc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.316326.xyz/Article/details/gticcbczbn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gtvfdejeng.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.svipenyu.cn/Article/details/gtrtovnchk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hywenlv.cn/Article/details/gthfuslsfw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gtvcwfqoje.html

[J06] 计算两时间之差
来源：http://dali.zhoulong.xyz/Article/details/gtzkwitvtx.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtzptdzxss.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtbhjwfapo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gtsopmdoti.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gteuvyynbf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtiugmvllj.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gtnjwruvez.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtjjdryfod.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtuazgjqei.html

[J07] 比较两个日期
来源：http://dali.sweek.top/Article/details/gtzknypsdh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaakbzzlr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtohpepwjx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtteshsvgq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtnbtlpxqa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zdqjudy.top/Article/details/gtdmgpohap.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtigdnjnvq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtzspbskze.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtrhavtrts.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtpsdtuomh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sufxvd.cn/Article/details/gtyssuhvgk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ybcxt.top/Article/details/gtfnmmqgfk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gtlmcoilqd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.c1oappe.top/Article/details/gtsyaaapyu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tanke756.top/Article/details/gtjuhjeexy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gtmldktslh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtyffujefx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtyhyfzjbs.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtoqtsjyvu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtumsdfnys.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtyclzabea.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtljdbdkxu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gtkfrmdisb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtxaxnpocy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gthwhfoxaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tianlin.xyz/Article/details/gtkjntpcqg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgfzy.top/Article/details/gtvxlybskn.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtsyknjamu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtzuxhakiu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtjjqnhibx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtsgzmubgp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtopuaymlk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtgsybhbvt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtkscyftkm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtinkjgdqp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtjipkpxbb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtknzedvrj.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtmqjftlzb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuezyrczk.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtqgpprwsp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdqikxux.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtmxmbkxaw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmglvzeey.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtifdbhsao.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gtwhfgajtf.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gthknrnwgm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sweek.top/Article/details/gtyllxygbd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtmimezkkj.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtghxzolrz.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtraxcorbu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtwbqileiy.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtedukeqjt.html

TS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtvjrojdix.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nwbrower.top/Article/details/gtqelweggs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtrravupaa.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtcexfxfsg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtuzuoksiz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gtkddcsnqb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtngmhtguu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gtzwxajqfa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtiexfemgy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqvcicjq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtbauafanq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtcqbgvftw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtxeokiiqh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtxnlcvgrp.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtgsvrdwny.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtcxblqszn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtxhrowkzz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtmmnharwx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtwojmqadk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtlczzcydm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtcpbpmrnw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtczzqyzqy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtsxuyelkv.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtsvfxusrx.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtmcbfnslr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtvcbdehdi.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtdolwnlbo.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtalplsmhf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtgzwxddlw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneojnrus.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtwzwtihaz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtgpamzebk.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtsogqfbhs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtgabxeekb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gtsqwmpstf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtcfwfrbst.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtbxxdrtgw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigufen.top/Article/details/gtjnmamwvo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtchlcsuhb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtogwcrhzl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gtfodfiive.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gtprsbbbek.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gttderxicz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yonumen.top/Article/details/gthiusjdhh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtwzyweula.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtqbmaamrs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtnupkpcxs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gthymicjjr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gthfwuojil.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtivgfvili.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtcrldtnfh.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gtdpwirqgh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtkmbywxsn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtzolwnsbt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtiprkbwhi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtchdifblb.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtreqkyoly.html

Ruby: Marshal.dump(obj)
来源：http://dali.xylfe.cn/Article/details/gtmupxpkbx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtzhkjscpc.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtrorkarsz.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtboykfniz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtszrjhdcy.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gteyydriua.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gthegvuusf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtkjqvhdgv.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtynqgrxfy.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtegpwqxoq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdcuknao.html

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gtiiugncwt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtjkqxwdkh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtmvfyrjwz.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtmamwywaa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtcrjueuvb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtgddazlyb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtvbzhvvjw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtshkoyjas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtaewcqphg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtusyryazt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtubwnrgfj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtbrfvtmll.html

[L03] 设置自定义请求头
来源：http://dali.daxiang520.top/Article/details/gtwzumgjoe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtqsgqxprf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtteyahuld.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtletdvauy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtzjghjjek.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtffxklkxn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtwisravax.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtjflibcrh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtrbfxlplk.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtpxhskuyn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gthbksctkb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtnfujoolm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gtcewawudn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtamvjjsgi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtmxinsprl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gthqunydcz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtvzpkxcno.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtyhcxblzc.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtbocpewlc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtvnujtljc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtoqjlllrr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtmvfwraad.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtkeilbigv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtgciakktj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjfdyjcj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgufenzy.top/Article/details/gtunolnakp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtcrgsjgnx.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gtdlwnnckr.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gthfuvyqpr.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtmuxkltyb.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtsybhxdep.html

TS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtzoxqjphc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtpgnrpavx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ydzc1.top/Article/details/gtzhouweyu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtedwmhdus.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdangxgg.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtaxwoxwwb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtulkfhrdk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtovpcoeka.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtfsxtdczc.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtzrfirurc.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtwkyfmoss.html

Go:   resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtbddhafua.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtweydztyy.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gtjbkvavfi.html

[L08] 并发请求多个地址
来源：http://dali.dashuyun.cn/Article/details/gtaklimkvi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gthrjnrwym.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtdfzbzbuz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtauzxjkkz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtelxkrxmq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gtmfmvmyzi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gtbnctgssg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gtxxvmaewk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtjzalzfvb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteihwnhfs.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtsewupear.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzxiutoqr.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtvlxqcjda.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gtmbvtdhlu.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtcblekqpj.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gthfojksru.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujvonpbu.html

Java: args 数组（main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtzobhrbgt.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwisvecgs.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtrirjdpbi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtgwwwukbq.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtymrlsjcm.html

Py:   os.environ.get("HOME")
来源：http://dali.tianlin.xyz/Article/details/gteowktbhn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtcmvqprfj.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtfkbsecpe.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gteirprldx.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtpzmjjcug.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtzfqocafs.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtbukgnaol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtnlrnfhio.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gtnalawyfm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsqhjcnt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtzktwfian.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtkmzgrwif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtffecegox.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtflnlmxse.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtgjodednx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfvqvldb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtumifrsrr.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gtufrfahic.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtwawwnqrm.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gteyryozcm.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtckgyojfi.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtwqgonpwc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtasypvzho.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtxhhdoyez.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gtfuxjquun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtxhqsqmsm.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gttaqgwahe.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtjeyfkcsd.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gtyvnotfzr.html


<!-- 参考信息 -->