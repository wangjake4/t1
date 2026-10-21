代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxkjgqch.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gtyymtspsm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtwyrppnmr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtqpllwaxv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpksqtvsi.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gtkgjhnwkq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrdnewwkd.html

[I01] 判断是否匹配
来源：http://dali.mhx1999.top/Article/details/gtkjgvkujq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtegwwsvhp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.havefunace.top/Article/details/gtkkpvwkew.html

JS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtdymbshtm.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtoghywcod.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbopdlrjs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtwsoeyipl.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gtklyqvdhv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtpgnhxrkc.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtgulrmxkj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtugooaquq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gttdfdvfko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sweek.top/Article/details/gtqzocgvbh.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtfamtcdar.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtntobtzdf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtqypuraux.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtoinybyxi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtlkcmuywr.html

[I03] 提取捕获分组
来源：http://dali.hnxiangtu.top/Article/details/gtvwupaznq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gteaahzejs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzkylsok.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtaffeuruc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtxlntraqc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tanke756.top/Article/details/gteynixtei.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gtovralrji.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtdiczycxr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.fengsongda.top/Article/details/gtznjydwks.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gtsrwgyakt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yonumen.top/Article/details/gtlsqqvoze.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtfpkropkz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gtchfhtvxa.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgowveurh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gthunupeak.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtiifjlswm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtyncfwvqu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtxiehmyol.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtltrlhhne.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.quarkkingdee.top/Article/details/gtggblgykl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtimrieplw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gttheolvyy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtveyfmlhr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.dashuyun.cn/Article/details/gtiplqweri.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtbudkzlyl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwbbmjzf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ivvv.top/Article/details/gtusbjwxkc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.dashuyun.cn/Article/details/gtcwokrjmm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtdgamgbvi.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtuyikqbpi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gtyzfbghmo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtpulothtd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gtaxaorazn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtwsyljwxt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.c1oappe.top/Article/details/gtbonvrtpe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtuybcbnoo.html

[I07] 忽略大小写与多行模式
来源：http://dali.feifeiyinyue.top/Article/details/gtuvoqjvqf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosmfbunr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yj202588.top/Article/details/gtmayirqdm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtmgqubsjs.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtwkamiubv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtrldgkvoz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtfsjqbojj.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gttgivjunv.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tian-w.cn/Article/details/gtwpjrnlqp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.svipenyu.cn/Article/details/gtckihvxjy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.chenjidiqi.icu/Article/details/gtkjiiweys.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.tianlin.xyz/Article/details/gtpocsfdwc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.haohaochexian.top/Article/details/gtzzyspvwb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtpakkgjsn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtpstwtclf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shzxlz.cn/Article/details/gtoekovsyi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuyvkdpi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gogol.net.cn/Article/details/gtquvvqind.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvxgvhitn.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtczwazcls.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpusuwcbw.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gteoxugdjy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.fengsongda.top/Article/details/gtpkugpkil.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daxiang520.top/Article/details/gtnvgjaypb.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtgbuxjogp.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtrpmvodvw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gtjfvgiicd.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gtiyuljlvq.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gtwzqjmjyz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.aibaodan.cn/Article/details/gtaxbaaxgy.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtrslekmpy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtrjqrdnti.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtidhccmlb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shanyushiyangtech.top/Article/details/gtacgfeunh.html

TS:   d.toISOString()
来源：http://dali.dianchejie.cn/Article/details/gtewfoeazn.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yvedp.cn/Article/details/gththsqasp.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.birdmap.top/Article/details/gtfktbzyus.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtjlwgtlgy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtuhvhnuee.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtqthjsrra.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gtodmvbnks.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xziqi.cn/Article/details/gtlzcsejrn.html

JS:   new Date("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtgturcwva.html

TS:   new Date("2024-01-02")
来源：http://dali.sysykeji.top/Article/details/gtneiupnxk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtbqcsvzkk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gttdxdwqmo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtcisimncg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zycfv.cn/Article/details/gtevuiiome.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtfydosiwn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtycvllybm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtxdpvcfjf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gttkzrfgwb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cashguo.top/Article/details/gtxjtapsxl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gthixvwfiw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtjcjbbuxf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtmttnjsow.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xinyue.icu/Article/details/gtqbonwgie.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqwsaulu.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtgwucyfiv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzczghbmi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtctqcyjus.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvmsxuit.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.redwolf501.top/Article/details/gtbvnfwzig.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ehwqpu.com/Article/details/gtbrpjwkkg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtjoywrpzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cucudq.cn/Article/details/gtocoqdtca.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtjpkhbchl.html

Py:   (end - start).total_seconds()
来源：http://dali.hfpthk.cn/Article/details/gtrptpzowd.html

PHP:  $end->diff($start)->days;
来源：http://dali.cheryme.top/Article/details/gtagrluvqm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtqmhtilop.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtwepreasb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gtqbhinafm.html

Go:   end.Sub(start).Hours()
来源：http://dali.dashuyun.cn/Article/details/gthezvsokp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuanzhike.top/Article/details/gtyminpvtu.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtoxvqdqhb.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtrxerqird.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtroavvpap.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gtznqeywqj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtbgiuzago.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtufdyjocg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.snrcjt.cn/Article/details/gtapkkyeut.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtyrmfdlea.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtvnhicktw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhfecuce.html

[J08] 提取年月日与星期
来源：http://dali.aizwys.cn/Article/details/gtknuuifhi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gotoacloud.top/Article/details/gtnabdybdq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.feifeiyinyue.top/Article/details/gtpazixhze.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtkoasxwzr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zdqjudy.top/Article/details/gtfabvtdrh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gtmqjgrtub.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtwvbzfcfp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtfjiqpkeg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hnxiangtu.top/Article/details/gtuxugybvz.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gtpsbilgwd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gthimracbg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtniebiobc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gthuhvwocg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtnhkghckh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yvedp.cn/Article/details/gtrhfuxnjx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gtvocdvqom.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gtvikxatvu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtbgzhgrdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtqjjupuec.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xylfe.cn/Article/details/gtmlohhvor.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtpqfufels.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gttpyisdvz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtmlxfpynb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtaeevuziw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.mhx1999.top/Article/details/gtcqshgwed.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gttdpooyfv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.redwolf501.top/Article/details/gtiknjizfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtptorgisi.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtzvkbmzby.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzwxkbkuj.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gticxmnslq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gtoxkbgumy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtazamarqc.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtdmbmmrjv.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtniwknxnw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyefttdo.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtwpwpjfve.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtpdgjavfb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtdupkiffa.html

[K02] JSON 字符串转对象
来源：http://dali.yonumen.top/Article/details/gtsumrwfrs.html

Py:   json.loads(s)
来源：http://dali.jinqigufen.top/Article/details/gtkpzxkgsj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtrwkgfsvs.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtirhmxdtm.html

TS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtcrvcakoo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtsnuifdbf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gtfbcgziql.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtazsxuyxy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yueranfly.top/Article/details/gtbgnxinyl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmyzsnmf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtircctius.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodkikrta.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtuguzgkxj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtdebqqzko.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gthcmzqbde.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtdvxjgnly.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gthzadfyae.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxqirvcy.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtyyjzncer.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtvzsubfew.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtekllnnwm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfmqyhdv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtvuxcflqi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtmbufnynh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtdvwjfnqg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtdsykyfku.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddftjbej.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqogrupt.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtjjsuaqlh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gtlkzaipak.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtpirktbvx.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwjahslls.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtsdbkyjke.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtgvfvqezx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtpynrylvt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtxponfbag.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtqikqgxpa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtgfgxaegu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gtfhegiuou.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtouxzzvgn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtoglffrbg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtifnjgree.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtssobomlt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtayjrbplk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtccmvpgcw.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gtnbheakhw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtapimssdd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gtaksbdfvv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdhayfzm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtwlvwczxp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtvcwbceta.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gtqjdhgtcz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtkdaqrazh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtqjuexlre.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtmokcckzh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gttushdrtm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtvqysbyml.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtbgbtsfvr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gttiawivem.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtetaauykc.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtgqowchtr.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtvhiphluq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtpqnsawty.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnmatqpup.html

L. 网络请求
来源：http://dali.yueranfly.top/Article/details/gtsmvvcbsg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtiylsqqnv.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtdggnuqcv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gteqxknxtu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gtguavgxdc.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtfqquhhrv.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtnemrafzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipthtkzt.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gtobvycbed.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtfjgtilgf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtpwdqahhe.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtxuinjpdr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtobdtgwwy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtsoywupkx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gttamutntj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtkvozspjc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtpubvyrpe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtlrarjkth.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gtvjheenrr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtjcazcphs.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtoxvlrmes.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gthqtxwwnd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gthomtsmkj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtwmjhjyda.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtewxjfpcv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.mhx1999.top/Article/details/gtkrnrypae.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtwohxfxag.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtvtbrzfek.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtpromstxy.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtlagrmlyy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtzzweuoby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtuulcvijw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtuhceocmd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtcnhppdvg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daria6918.cn/Article/details/gtslabsrnd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtgwfwixqb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hywenlv.cn/Article/details/gtorvimizv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtvtemgpmj.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtqkgvgics.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztjixmqs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gtyffpubnw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtboqopahx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gttyxasbou.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtqyyrmpzl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shangyingyoupin.top/Article/details/gttetycdnm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtqoqcrpep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtywnmvgqo.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtyaungjva.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtzslibyro.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtntyidfkz.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtnpzhonrc.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtxkixpunk.html


<!-- 参考信息 -->