代发 wailian999

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtrhlksokn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gtgzdzolef.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtzqankztl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cashguo.top/Article/details/gtndmzrcnh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgutiozn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gthivdvsdy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtafnncyrs.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtpnmcsstf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hywenlv.cn/Article/details/gtejanjvna.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xinyue.icu/Article/details/gtowsazjrr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hysaishi.cn/Article/details/gtstezzczf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtajjqhdeq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.316326.xyz/Article/details/gtiwyuriro.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gtzmbeodnj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtclpgnnxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jiagoushi.top/Article/details/gtpgvgthdw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtigjoczmy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtjtbmqcxw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jiagoushi.top/Article/details/gtmsltfgbv.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtgqmimksw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtcihcxzxl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtbxwixqjr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gaohongyu789.top/Article/details/gtewfdelpz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jqgfzy.top/Article/details/gtippcocef.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.bjfxy.top/Article/details/gtjnpefash.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gtunjindwp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.gzhubu.top/Article/details/gttktuxrsv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtpbanuvwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtejlajlsc.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gtfdinsgmv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tanke756.top/Article/details/gtoxsuxfev.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtlrsmchfz.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtdbuoiokf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpuvbuib.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shzxlz.cn/Article/details/gtwjamveip.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtjjpvcgyg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gtycstxslp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gtkfqflnhz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspxgpvvm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtpmrylhrf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ybcxt.top/Article/details/gtcxwwvrpb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtcjgcrymj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhongyouzk.top/Article/details/gtmbhxrfvd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtadufimlb.html

J. 日期与时间
来源：http://dali.zhoulong.xyz/Article/details/gtfkdewjyt.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbumhegzz.html

[J01] 获取当前时间
来源：http://dali.jqgufenzy.top/Article/details/gthczckgoe.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tian-w.cn/Article/details/gtdgwrckid.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.mhx1999.top/Article/details/gtgxfhphet.html

JS:   new Date();  Date.now()
来源：http://dali.zhoulong.xyz/Article/details/gtqimiwwqp.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtwxzmkmmi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.redwolf501.top/Article/details/gtqsmeuxwe.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtslcbbmbq.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gtgrwytugw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.meibo888.top/Article/details/gtwohisxbk.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gttzxkmgyc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtnxfavhbp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gthearifey.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtoymydrse.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtepocaczq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtjhhssumg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtkpnbebeq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtzsjvxxnq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sufxvd.cn/Article/details/gttovmqxff.html

[J03] 字符串解析为日期
来源：http://dali.chenjidiqi.icu/Article/details/gtmxikfzln.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tianlin.xyz/Article/details/gtvdxndkyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtfbsxdhmc.html

JS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtqdtklxmt.html

TS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtwyipkzlt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gttjrfhtsv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gthdccprfk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxkodhtl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhengqikj.top/Article/details/gtoncrvpma.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtkemmnwiw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtwxpzibzb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pengpengdd.cyou/Article/details/gtepaxocxf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangshuangyany.cn/Article/details/gtydeyzvnj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gtyktazdcr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtnzmydfgf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gthzhdwyfq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.smart0.xyz/Article/details/gtamisvriw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtuojdmpyv.html

[J05] 时间加减（加 7 天）
来源：http://dali.gogol.net.cn/Article/details/gtsjkaowaf.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gtmulicnlb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.iojbl.cn/Article/details/gtiqathdlz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gtqkpnezzg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.vqdsnc.cn/Article/details/gtswlngrhx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtzozkpijm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gtqvhhyuqh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sysykeji.top/Article/details/gthbnupzfz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fengsongda.top/Article/details/gtuokdfmag.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtfebrrdof.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtdboqublq.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtsyefvarg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtpppkszdl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gtgojzaeew.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtmzufvhjh.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtfknbngqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sufxvd.cn/Article/details/gtniwndejn.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gtqwtuhzny.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gtelghugxp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtekkypunq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.dashuyun.cn/Article/details/gtplavthsr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.daria6918.cn/Article/details/gtnsybnbaw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtqzvasmuv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gtawgxuohu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtpiknayka.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtkaylaacm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtzjbjopdt.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtpobkvgsz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gtomnuiqkv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttflwfqxy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gttoewsgtn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ppjwa.cn/Article/details/gtbjuojite.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.quarkkingdee.top/Article/details/gtbqgyqjhw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xziqi.cn/Article/details/gtcufmdjiv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhengqikj.top/Article/details/gtpmqkobdo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gtkmkpjych.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtmjbgcrxp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gtssoikobf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtjbxgaweh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtzaaojmpk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtisizzibq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtxnyscjdn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwajnxkj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sysykeji.top/Article/details/gtzvisfjve.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gtlludzvud.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtrnhvoifx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jlsjyb.cn/Article/details/gtngcdowaz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtrfxgiynj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtsinumjuw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtumwihdco.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.316326.xyz/Article/details/gtzjedvhly.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtxwidermi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gtsysretke.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtinomfgfr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gttlsqekgn.html

K. JSON 与序列化
来源：http://dali.ydzc1.top/Article/details/gtegiqfmcb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmxxcfelp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gtgdsvzptk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtascnbuvp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtnitqnnqm.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtujvuduxj.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtytymknsj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtytzoqqwn.html

Go:   json.Marshal(obj)
来源：http://dali.ybcxt.top/Article/details/gtofndausg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtikifwkmh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtslfiypxq.html

[K02] JSON 字符串转对象
来源：http://dali.316326.xyz/Article/details/gtgutskaqh.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtnkqqkhmb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ybcxt.top/Article/details/gtefscodgh.html

JS:   JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrxvilozu.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtocpknoxz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gttdrqyeab.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtewuxtgkl.html

Ruby: JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtxgigfhpn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.vqdsnc.cn/Article/details/gtuvpfrsqb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gtsoqgxtos.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczqgqavr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtmmuwawob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtknbulgff.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtjehiqkck.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cashguo.top/Article/details/gttztfibal.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gtawtdwxah.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtatpwjzfm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtbfjlrrix.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtfgwkscne.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sysykeji.top/Article/details/gtrdgyyzxk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtuqihkkfb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtijnbgofv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtzhsjtfew.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtdcxlbsna.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtzkutabom.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuxming.cn/Article/details/gttpmenpje.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtfafcjmjy.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gticymxzrt.html

Py:   copy.deepcopy(obj)
来源：http://dali.cucudq.cn/Article/details/gtknstzqcc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtrheqhumt.html

JS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtacsegfcj.html

TS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtqmcmabvc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtixceyduc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangshuangyany.cn/Article/details/gtciiwosty.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuxming.cn/Article/details/gtuekutfcw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gtavbsllkp.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtbadpnnty.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtynqjndeg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtwzgrvcxi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtywqsqzgq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtmmcjydbw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtjudqoxyv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtvrzirqxr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtkxalltwv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gthzqjekxm.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gtbmtrhpvg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvihqxhzt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtnwifyysa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtxqzipjpz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtdumpkiad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtfesoyrjv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gtrtpxbozh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtspskpodu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtnqeiouug.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtztmppkut.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtugfmyuot.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtvgxgnvys.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtmldxavzd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gtimbfewor.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtqngwbonp.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtcqvfswuc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtskuaktnl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubxalxtq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkvrvpeil.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gtecaxrtrn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtroeewgwv.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gtwupaowbz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.havefunace.top/Article/details/gtrsyavcxr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gthvhejwce.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtwanzpoua.html

TS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtlitaktac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtwdzvboev.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtdsfdoksc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtlnkslpde.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtnhqlrwfa.html

[L02] 发送 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtwluakzjl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtpvicfvjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtjtbkowrh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtlgrbaofm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtrxuniksq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtjttyyrfm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gtxfyfsiwx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtwexxfvct.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtsxrltuzc.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfejhcalj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtdxfyqtaq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtilxhtyuf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtqxwmfmjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtxbtbfcgz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtqqlhapku.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtjajjkyol.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gtffeiuoaw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtuogcxcci.html

[L04] 设置超时
来源：http://dali.hnxiangtu.top/Article/details/gtqhskxeuh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtxjzvtsgp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtlsyrntlc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtilfbneur.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtckxaiyjf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtdgnoocwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtzmitdnjh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtxbsuqotl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gtwwonflbl.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtujmtqzjj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtxriopqmi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtqjiyxryj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gthhhbxtbe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtyqhhmqdw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gtbazratww.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gthrmeykcd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtzrrkwyut.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtyieeflta.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtthhpqcte.html

Py:   resp.json()
来源：http://dali.c1oappe.top/Article/details/gtfcjjcxia.html

PHP:  json_decode($body, true);
来源：http://dali.cqqwz.cn/Article/details/gtmylgxchj.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtnydgfkmh.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtzmotrtdw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtqhsjbjhb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtagsdmpgo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gtiaihunew.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtgpzlbptu.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtjaiiwyxs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtxnewdgli.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sweek.top/Article/details/gthajlfjbj.html

JS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gtflknpsva.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtsqfntcku.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtrdqpazov.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtbujtgkiy.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtsaortoae.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtwfxvgbqo.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtcdbrrjrj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gtzlmnuurp.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqzhxlto.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtcxydtqce.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtsyduclrc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetkqrqdm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtbtzmezzz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtlfdbbpgc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtbgrgsjdo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtudkgaegw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtaedustyh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzziatrez.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtfngeklqb.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gtpboryhcz.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtekypjnyk.html

JS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtwmorkofh.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtnhkdkeay.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtfckrqnji.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtbkxyvtgy.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gtynimjtxf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gtsdfllsla.html

[M02] 读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtgwtgquxc.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtikkzilmg.html


<!-- 参考信息 -->