代发 wailian999

================================================================================
来源：http://dali.316326.xyz/Article/details/gttgwtwesk.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gtizoaozbi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvovrcbej.html

[I01] 判断是否匹配
来源：http://dali.haohaochexian.top/Article/details/gtfclkybyq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtwkhysvdf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtsnvonqho.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtwyjuovml.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdryomsn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtzbbhzgnd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtrqnhvevc.html

Ruby: s.match?(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtferbqkun.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtrmgirdgu.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtbsvpidyi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtnugtkkdo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtijhzqnhc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gttrgglydr.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtaqkmkyop.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtamgddsev.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtnzedtgqq.html

Ruby: s.scan(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtxcpdprnv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuxming.cn/Article/details/gtzwabyyev.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtpqxnlfza.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gttrlhpuim.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtgzgwklsu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gttjdxoesi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtpeyrscfh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgnvyrrg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtrrsezbta.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtkahbwkdw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtjwyqyhwz.html

[I04] 正则替换
来源：http://dali.xuanzx.com/Article/details/gtmfkhrvmp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gthhgnwdik.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtimhcfwck.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gtqlksutzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtvddupjpy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtayddagzq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtyqfsmvtj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtfcujgsbo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtefefhike.html

[I05] 按正则拆分
来源：http://dali.birdmap.top/Article/details/gtmmqoqmoc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gtvtezfomp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtzlkzrjjc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifsdkyor.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtfgdhyjis.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsaznxfh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yongpay.top/Article/details/gtcsvocunq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gtokebdlor.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.mhx1999.top/Article/details/gtpchonbxe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ehwqpu.com/Article/details/gtqybsbnfg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gtazztmnda.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.kuanghao11.cn/Article/details/gtuvqatkob.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtdxrcwinp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yonumen.top/Article/details/gtpiyabuge.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtbqwldxej.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gtqzkmwhtz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdajtvspc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtyavsbcfa.html

[I07] 忽略大小写与多行模式
来源：http://dali.cqqwz.cn/Article/details/gtaxmnomhv.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtlaxeznvu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sysykeji.top/Article/details/gtznxzpapj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrhtkmah.html

TS:   /error/gim
来源：http://dali.aizwys.cn/Article/details/gtffaeizkj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cashguo.top/Article/details/gtmsadezmg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtdaqpxxlk.html

Ruby: s.scan(/error/i)
来源：http://dali.pycfn.com/Article/details/gtbhvwzuqw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtnywrkray.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.aizwys.cn/Article/details/gtksxewezc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gttixqtwkc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazsqosox.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gtxoaiifmc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.9152youxi.cn/Article/details/gtsqkutuvi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkivchfa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtvskdylba.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtqumbhkmr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtumvzijpc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrgtgqxzq.html

J. 日期与时间
来源：http://dali.jlsjyb.cn/Article/details/gtniocrmjd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkqwpmzgn.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtdkqsqeqn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hywenlv.cn/Article/details/gtsdtmfjnj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.snrcjt.cn/Article/details/gtrucpyyib.html

JS:   new Date();  Date.now()
来源：http://dali.cashguo.top/Article/details/gtiudkrqvz.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqbqrcdr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtdademiob.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtrftvsfzx.html

Ruby: Time.now
来源：http://dali.guowangkeji.top/Article/details/gtzkxxdgrl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuanzhike.top/Article/details/gtwqxlwbqq.html

[J02] 格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtcjtsorqn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtzgixsrxa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtzlgvvusi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtszyflezy.html

TS:   d.toISOString()
来源：http://dali.iojbl.cn/Article/details/gtdnauersd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gtmrwugnft.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtndfjujzh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtresstozi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ydzc1.top/Article/details/gtsnxszldh.html

[J03] 字符串解析为日期
来源：http://dali.gotoacloud.top/Article/details/gtawpmgiuh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.havefunace.top/Article/details/gtglfzsjvm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtssxxlejj.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtputisrfi.html

TS:   new Date("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtjkdtqgye.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlzpvemw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtyvyfgysq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtyhsgqxgd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.nanxinkj.top/Article/details/gtqaibtipz.html

[J04] 时间戳与日期互转
来源：http://dali.zhengqikj.top/Article/details/gtwrhwouol.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jianghu66.top/Article/details/gtjknyqjdf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtdvcyckbp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuanzx.com/Article/details/gtktscsexq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtjwgyvuwl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtfirxfeoa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.havefunace.top/Article/details/gthjzqxllx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtmqgtziqs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtbawbiana.html

[J05] 时间加减（加 7 天）
来源：http://dali.ivvv.top/Article/details/gtdvvkuzfm.html

Py:   now + timedelta(days=7)
来源：http://dali.9152youxi.cn/Article/details/gtwkhlfqcv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtgglgunol.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtvhypbzax.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtchtcbwiw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtgovuhvft.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtfggogfgy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gtnapnymno.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.chenjidiqi.icu/Article/details/gtgeybcbxg.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtexyfuczx.html

Py:   (end - start).total_seconds()
来源：http://dali.sweek.top/Article/details/gtnfwrvtqm.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtpsvmjyso.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfecmhxrd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtlswbklpw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gtcvgqjaci.html

Go:   end.Sub(start).Hours()
来源：http://dali.meibo888.top/Article/details/gtosojmqyu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zycfv.cn/Article/details/gtrkwmspll.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtqnsrngfp.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtkctrnfzk.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtqsugjyvb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gaohongyu789.top/Article/details/gtqxewxbvo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtxvvnxniy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtfkpjczgf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuanzx.com/Article/details/gtziqciaai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.bjfxy.top/Article/details/gtgkqodhce.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dianchejie.cn/Article/details/gtriaknahf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gtjnwaphgb.html

[J08] 提取年月日与星期
来源：http://dali.yongpay.top/Article/details/gtmwbpclaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtpvuzcpwl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangtech.top/Article/details/gtptthfxvc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtstposwpn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gtxllknptk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.snrcjt.cn/Article/details/gtdmzjcgtf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtozwwenfz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtldjqcddf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtwmrdwdrn.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtvptfozmk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hongshengwenyu.top/Article/details/gtvvaomwrv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gtmicahjfd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtwzwegdwu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dashuyun.cn/Article/details/gtkyqmvxpm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtdacqqdwd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtwadqczsu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbfsetpd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pycfn.com/Article/details/gtgcctepts.html

[J10] 取今天 / 本月第一天
来源：http://dali.ybcxt.top/Article/details/gtnasydwiv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtpcgzyajt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtpbtgbekv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtymqgkxvk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtiheppcnn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.pycfn.com/Article/details/gttubwgqdr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtlbnkfoqx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtlrjyocab.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gteunefsdj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtissyingi.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtopsmdxck.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtyshgumop.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtaayuafes.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtuingphop.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtmtyaenhl.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlnopgnnq.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtuifzbina.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenlongwang.top/Article/details/gtdzuydqvt.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtcttihflp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtztkrckzi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gtebwvijlu.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtxsjjscjb.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtgmuxzhel.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmcsulivg.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmnrjzyty.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbbwoxwq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gtnarzjmun.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtshsbeehe.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtvzlnoxlj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtpnfmirzy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fzhhl.top/Article/details/gthxdkljks.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtbjqdkchg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtzzswijms.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gteymddlcj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtljvjmccg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtssaluwuf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gtoaoflwbg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gthevayxns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gttmklxiak.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtuoadgksu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtbbjlnbwh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daria6918.cn/Article/details/gtwvedhier.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdabadzlk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtwmsnjefx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtdzwdfrfd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gtdkgnpjbv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gtmsgzzqpf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gththxcbqn.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtkurbkboe.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtjcvtwldm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtczxjshee.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtcdvxtnmu.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtdxubkmsx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtvmmnbsun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbgagbbx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gtubqncphe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shangyingyoupin.top/Article/details/gtxtjaryaw.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfufjejs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtwgffxbbw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gtkkdjpjbc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gttycpyrbv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gthasvwise.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrfqughw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtxvypbknt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtekzhqwwi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtnbkiozpn.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtyockjpln.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtqmxwmjnd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtwabbjdrt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtllslmgxi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtkvzdgdji.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtquibancd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtaysvetpx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtuogbykxh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gturmytfvv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sufxvd.cn/Article/details/gtgebkkxqq.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtmuzrjder.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtltvoqfwi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtdtvzdsgp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtzpdymthl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gteopgsgms.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptuqieyp.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtepjsqzya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtlbatdlht.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtakxqmckl.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gtwdjzupnm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzkqrufvx.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtzadrdpyv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtirfrexov.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gtjiyjtlej.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtvncpxzai.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtspjwwomp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtjefnodpl.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtzqczuutm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gtmegzyyyg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtnxfvhpvz.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskngmmcm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtexhppkmx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gaohongyu789.top/Article/details/gtgpncfyxf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtortsyyki.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtranmoclm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtlejbwuyu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtezfzxvxz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtwqqdnzlp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtsuaydxal.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtryglehbr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtdxjmvccg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmfbxxdr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtnoeyitsf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdtnkspo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.vqdsnc.cn/Article/details/gtyqhgqvzx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtuhtvfqjt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtunwsbthm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtfkbnzihs.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtqsowvoce.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gttnoicmio.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtoevdthmb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtatpyqneg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtlpqdzxae.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtjskyoumf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gtvvhkjydp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtrbzptekw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtnhexiakr.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gttaansmtl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtxmdnxyrc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtxjjeaqof.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtanppxhdr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtopboxpaz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinghuilouyu.cn/Article/details/gtswsudizr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aizwys.cn/Article/details/gtzaisirbe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gtfexusptn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gttlseypwi.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtrjxvgrbb.html

Py:   resp.json()
来源：http://dali.iojbl.cn/Article/details/gtbrglhqgz.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtvqhkgarg.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtfsdbqaeo.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtlrgyltzm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gttbjbhleb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gotoacloud.top/Article/details/gtfiveddke.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gtjxcewcmw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtqacdoeex.html


<!-- 参考信息 -->