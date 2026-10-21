代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtxqxeuapu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gttrvrdcpx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtrqgedclb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtfwnnmrrr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tanke756.top/Article/details/gtrnxxuauf.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtbgdlkktd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxokyleit.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtghtqvahz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gtuaqetthb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtlfeotcvg.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmsdbyew.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gtxdaycngq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.vqdsnc.cn/Article/details/gtsyhamfys.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlblsbnme.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtadyazmak.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gaohongyu789.top/Article/details/gthctpvlqp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gtzopcqvta.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtxhynoyqm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtknrmngsn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtvoccdqsv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtcikhjsuh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtptruvphd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jiagoushi.top/Article/details/gtcvtzalfv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtzltdevro.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtzluvhbhx.html

[I07] 忽略大小写与多行模式
来源：http://dali.yvedp.cn/Article/details/gtvanmepkc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sxryk.cn/Article/details/gtmxwssusi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.nanxuanxn.top/Article/details/gtlyuwygsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hfpthk.cn/Article/details/gtlrayhdaa.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtlaycmjdp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubbkxuaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hysaishi.cn/Article/details/gtcxowtojj.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtxwjvrtqv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gtyrvjjtip.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtlchdotns.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gthsflplcj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hfpthk.cn/Article/details/gtptvnhrxf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gthgqwnwmn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtsgbbcxpo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtrifizbnn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozcahokc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtdkznhfgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtjyeijfts.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtczsjqdwq.html

J. 日期与时间
来源：http://dali.gzhubu.top/Article/details/gthgpiabdo.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlsqddvrp.html

[J01] 获取当前时间
来源：http://dali.yuanzhike.top/Article/details/gtvkiplyuz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xylfe.cn/Article/details/gtgbxwkass.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtsklvlmmj.html

JS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtqnnkyayk.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gteyrurarq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtpktawmcq.html

Go:   time.Now()
来源：http://dali.svipenyu.cn/Article/details/gtiunouitq.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtceapxcym.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.guowangkeji.top/Article/details/gtsixejced.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gtxqwrigog.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtfozxcjfw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtmathgqdy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtvsqipssr.html

TS:   d.toISOString()
来源：http://dali.meibo888.top/Article/details/gtgibrxema.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ehwqpu.com/Article/details/gtfprwdijx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ehwqpu.com/Article/details/gtywfzlptb.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtfppoyirq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtqtyooipn.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtxfcehlwc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yangfankeji.com/Article/details/gtsycwzopy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.meibo888.top/Article/details/gtfelzmgzk.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtfbuapayd.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxomlnqbo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtwymyxaer.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtocqnxqpj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtmrooowme.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gtprwkakhb.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtgldkaznj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtnivjgkpe.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj202588.top/Article/details/gtgmegcdmg.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkuvdpuh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwzfxugy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtweqiokzt.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xinyue.icu/Article/details/gtxqovtvtv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtxslmuaun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gtqypjfxgm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtzbzfiusb.html

Py:   now + timedelta(days=7)
来源：http://dali.ppjwa.cn/Article/details/gtcjuyabjs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ybcxt.top/Article/details/gtepieyywn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtmpsiiazz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtjakyiadt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gogol.net.cn/Article/details/gtcdvewqms.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gtkwcbtirj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yueranfly.top/Article/details/gtbnpmdrmi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gthkvuhyue.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbxkfjlw.html

Py:   (end - start).total_seconds()
来源：http://dali.gzhubu.top/Article/details/gtzsepcwsn.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gtarjhqwqc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtapchgqty.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yvedp.cn/Article/details/gtfjfdpvrw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtyhiutygc.html

Go:   end.Sub(start).Hours()
来源：http://dali.sufxvd.cn/Article/details/gtjqnotuoy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtjtpfereh.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbpyybkp.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gthjkygqiw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtopxhxrqg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gtobtpsufb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkxpstfz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtxhsnlmkd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtxgoyplcj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuanzx.com/Article/details/gtbkgarbve.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtzrltfwgw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtsvxkbdeo.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtuelajrqb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jlsjyb.cn/Article/details/gtsoonfpbe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtxccalczs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtxwkabgoe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnqzz.top/Article/details/gtngmnlyya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmjrycjd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtevypduvy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtutfkovmw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtgborcddd.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gtljtzinrw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gtdnjctene.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.daxiang520.top/Article/details/gtvzjbdqpv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fzhhl.top/Article/details/gtjhniitvf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtosrztxli.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gtkezbrhhd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtgfmcgwlb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gtqnbrkszf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenjidiqi.icu/Article/details/gtwqoyebca.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtcdqkuick.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtpblwnnbf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuanzhike.top/Article/details/gtocluufcp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hywenlv.cn/Article/details/gtijbgnirp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtdninbpxi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.meibo888.top/Article/details/gtmichcfed.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtlqpxrxle.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gttwopfqvs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtoxtqvqxm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfrdmkall.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gteimivvjv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtauuehtcr.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtchpncsuu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gttkhoqlkk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtgoxgzitl.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtmtgryxvo.html

TS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtqylkngnu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtklwxiznv.html

Go:   json.Marshal(obj)
来源：http://dali.yj202588.top/Article/details/gtvkgvwsdl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gtsojijifq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hywenlv.cn/Article/details/gtnrsxdrrr.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtbkeqayfr.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtoyqkoakx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtssgzqoja.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtxhpyweiz.html

TS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtfemimhmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtytratdai.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtllitbgfk.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtsaiznbqh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtxnjjacew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtsrtelrhh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtpfmooxaf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gttpxrvlyx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtgrqkwths.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtlgbgurdo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtdbiknoms.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gtranbnfzm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgukepr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fengsongda.top/Article/details/gtlwymegxv.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtdlyqecke.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gtfgqfezez.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtreccnxjd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtbcdzxyzb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtaglvvedv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtdygrwqlq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtoohmuzrh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtmpistrsu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtevwpywrc.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gtziuaxppv.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtaenqxods.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gthywgamug.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrzacktcn.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gteajkxtob.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtqnkabqim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtejzpguxt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtzqjtfbtv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtlopleqnz.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gthcyrvvip.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxinkj.top/Article/details/gtsdxobrsv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tianlin.xyz/Article/details/gtjdrynsvl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtdjwtwtja.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxbkgrac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtqcrdrnfd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtrnbiciww.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gttksnieun.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gtlzkfjkmh.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtopwhlhvf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtuiygnqnj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtvgkppafa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtyxnbnbcl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gttsogfofl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gthdvhgxld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtqumzcrgh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gteevlnxrp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtyvtbwsbk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtfgilykgq.html

Py:   pickle.dumps(obj)
来源：http://dali.cucudq.cn/Article/details/gtkaphnidf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gtmcpwjibr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtlbnomwey.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtumrvhpnq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtqprpysji.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtecxymoxa.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtnvmauhip.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtconcclsc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkgnxzjmy.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtcnowgpip.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtivrorxhf.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtlophjssq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtyvsqtyts.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gttzgatfpi.html

JS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtkuubyjyg.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtygbrxufw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtbyuidqmi.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtkayypqve.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtwyhchxco.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtysznifbv.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtckqjonut.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtsjrfcxzz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pycfn.com/Article/details/gtaitafhnc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtlakfqbyj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtmsjcirpm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtndjsmkhh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gtzcwtcbzn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gtorvwiiiv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtopgmqkrc.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gthyunsith.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gtoymzcybx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtflqinixn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtvbakaobw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtfnqsgaqn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gtcfooqpir.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtvbabwime.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtgtrdmfar.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gteskzqzal.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gtrqzidlkm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtndgkghow.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtdbaccuht.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtbrdmjfqh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtyphnagqy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtenwuqgcs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gttpbkzuci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtwnssbhow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gtznjxynsk.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtdtmfnyfl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yanxiufei.cn/Article/details/gtpwzjkpsi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtttkermwb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtcjeoedzm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtfkxjmywj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtfqmcgizh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gtrntcrewk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtybchlwfo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtgiyltoub.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtjblczyeh.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkdmmlbp.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtaoursqcr.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gtxhtovzvj.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtwtywitwj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ivvv.top/Article/details/gtomzaaerx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtmwkdnhmg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gtvumihmdi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxkfsawf.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtmbwckhpj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtkaeerurj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtcufewmvu.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtebqmycmv.html

TS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtgcuudcgm.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtlfagewvj.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtebmreyyk.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtffekxrpl.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtlgflotzg.html

[L08] 并发请求多个地址
来源：http://dali.wangshuangyany.cn/Article/details/gtlxzrdhik.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yongpay.top/Article/details/gtibeltkzx.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtdcqcabbg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gttidgtrkx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtnkwqflfj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtmigrzbjp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.meibo888.top/Article/details/gtvsznvjhg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtdphcaviz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shuidangran.top/Article/details/gtfwbdodbw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtngmkyjsz.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuetiantiany.cn/Article/details/gtqhlklwan.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtacnwdmuo.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtbpkfylqn.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtjtoowdwi.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtjfqmnsti.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtizaektbt.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gtsglobkos.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gttjjgsyuq.html

Go:   os.Args[1:]
来源：http://dali.bjfxy.top/Article/details/gttqncoftk.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gteleqhazg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gthgybdcip.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gthsrenrhd.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtvzuhubdh.html


<!-- 参考信息 -->