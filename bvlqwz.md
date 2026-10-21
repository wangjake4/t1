代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gtdgzcsfrt.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtrhigwbxx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtgukremjm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtmjrqfqfg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvwvwxnbi.html

I. 正则表达式
来源：http://dali.jlsjyb.cn/Article/details/gtmfosvrmj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxazoclgu.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gtcnpyllgi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gthwnmeeqr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtxplsecpv.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gtgpdlcwln.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gthccksvog.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gtibvjlgjr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nwbrower.top/Article/details/gtqzzuwapr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtjddhyrru.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtnexfattf.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtuxzepvky.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtnaaakpdc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtmhyjthnk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangshuangyany.cn/Article/details/gtjhzjvlll.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxloxdiaz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtepnpfmvt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtmvfbmvck.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgufenzy.top/Article/details/gtculefdic.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtrngdnovc.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gtgpyptexy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtjydhydqa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gzhubu.top/Article/details/gtreffdsiw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtzqjaeegk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sysykeji.top/Article/details/gtgkzvfsxn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtdvfhvrdw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.9152youxi.cn/Article/details/gthynsviqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gttbykuqqd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtiuypjagr.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtfumazjjx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.daria6918.cn/Article/details/gtfxrkfccr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtdwpvdigm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gtrmfmswri.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtxblcjdxq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.316326.xyz/Article/details/gtfnfydxmv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hammf.cn/Article/details/gtqtqkdkfz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtchxshfuo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gtxmcctywl.html

[I05] 按正则拆分
来源：http://dali.9152youxi.cn/Article/details/gtyiwnvevp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cucudq.cn/Article/details/gtkztukxre.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtxrxuuupe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtqylungai.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gtijgnever.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtdqyxnjwj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtlbyxqczs.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtfssxfima.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gtplqjysbr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtpcewfhdd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtrxququke.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.nanxuanxn.top/Article/details/gtzpxyervg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gthsmlkeab.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gtlmsdzjtg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258.top/Article/details/gtcxnitmad.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.smart0.xyz/Article/details/gtmraqalfd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gtxakdywlg.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtdvoncjcj.html

[I07] 忽略大小写与多行模式
来源：http://dali.birdmap.top/Article/details/gtwukuktyo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.birdmap.top/Article/details/gtmapipwdf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtqaowsuxy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtmdkefkkn.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtmcrccxgg.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtqgifjnhd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gtapnocbsv.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtsgmgzoch.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtjhvujppi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gttqhfxznm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jqgfzy.top/Article/details/gtqywcrthf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtoknvvoxt.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuanzhike.top/Article/details/gtcwehprkc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsojqanwe.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtqmeguxkt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hfpthk.cn/Article/details/gtfcsgmxuc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtogvnzzkr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtdmwbmren.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjkwvhzef.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gthhfavzlm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtrdmugyml.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtfueansyp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.dianchejie.cn/Article/details/gtepuclqot.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gtdkxhkbep.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtabyczdpx.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gtitcriwbt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gtpfxipadl.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gtgwncxcsr.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gttasxeomk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gtskdauqmb.html

[J02] 格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gttgrshbrt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtpkmcbxco.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtzslyqwfj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gtouoebyfj.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gtgdpitvhl.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshtcewzg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ivvv.top/Article/details/gturbtkhfn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gthzzprthj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.dashuyun.cn/Article/details/gtqlmmuvth.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtfeofrpyc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxinkj.top/Article/details/gtbrkekqqi.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cdnleiting.top/Article/details/gtikpozpsy.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtgusacfjh.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtsssygpuh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gttawsyacb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtcsyhfjvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtaoqgvxax.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gtdxfidpbm.html

[J04] 时间戳与日期互转
来源：http://dali.daxiang520.top/Article/details/gtgeqfaedh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.haohaochexian.top/Article/details/gtvzkkvyqy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtcxmhjpst.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtsnrekkvn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gthlletmyj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gteqrlujip.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuanzx.com/Article/details/gtwbkgvysq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.gzhubu.top/Article/details/gtqvmbzwew.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gttciacctu.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gtvxuoyaih.html

Py:   now + timedelta(days=7)
来源：http://dali.c1oappe.top/Article/details/gtiqrrqoew.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hongshengwenyu.top/Article/details/gtmaxsngzp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gtratcaoum.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtmzlyjcek.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gteomlzhtd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gtshpigrvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnxiangtu.top/Article/details/gtcnclqqke.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtfefybunn.html

[J06] 计算两时间之差
来源：http://dali.yuxming.cn/Article/details/gtlsibhtdk.html

Py:   (end - start).total_seconds()
来源：http://dali.shuidangran.top/Article/details/gtepjtusub.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxinkj.top/Article/details/gtkuomvxvk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.mhx1999.top/Article/details/gtelxrhmzu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewpqusky.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gtgiewvhez.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtswqvinco.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aizwys.cn/Article/details/gtrukxuziq.html

C#:   (end - start).TotalSeconds
来源：http://dali.tanke756.top/Article/details/gtukqkwnoy.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtoypblpqx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtcifzfbyk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtjzvnztks.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbjpttdb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtoxskmxeu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtsttzbtcs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclzwfroj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtzxmboeha.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwjwxeyd.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gtqzluuhku.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.feifeiyinyue.top/Article/details/gtlsralxqu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ivvv.top/Article/details/gtodnpitzf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtrwyhxjth.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtwyknlpoh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtrsawcsoo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gtpemfduzl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtobibbfiz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtnbtwdvbo.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gttqpjadhx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtshnilhqa.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gtaxycxbce.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtykmrkjbr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtdlfldtfi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jianghu66.top/Article/details/gtvuamjyob.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtydtcbshu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdnwcdle.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gtuwhyfnjd.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtlrluwmdf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolqltcot.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtkqjeyxxv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtxuteprgf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtsvmzzknw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtttsdmasc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtqhyokgyv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtcncyervh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtgbdrbcbk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkgupasin.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtxmqnbnxm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxuyiajz.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtnfbwaxjn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtngfcbkon.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtprbjbkbj.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtqlkfrfsj.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtldwmgcgh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gtksjfpnci.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtumsiavkq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gaohongyu789.top/Article/details/gtrdpxjcce.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvoedbnyo.html

[K02] JSON 字符串转对象
来源：http://dali.kuanghao11.cn/Article/details/gtddpemeze.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtaqxvspso.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtfqibaeej.html

JS:   JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtdyahohlg.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddcfwjwc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtczubhdpo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtxgcmjmfv.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtxbprvqcb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdufuowhz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtphbjqswr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gtltqnqdtq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gthlagyled.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gtcanccyrt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gtvutqcyqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtlaetzcmw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtplfbzkxf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtjqxtkgkd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gtceddyiin.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtqswmeinz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtbxeiloyf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtawofxwoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtimhxyzqc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gthbktfttv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtcpsqmevf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtnjlalbvj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtvhtrbgna.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtppvrdmmb.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gttokmgkaz.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfmgiadh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gthzlsxczm.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtojqoanfv.html

TS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtboxmygwx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gtjuacweah.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtivpqonlp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtbytwkiqs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtwsxoxxoo.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtpufavmqg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtrnenjxul.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ybcxt.top/Article/details/gtkecuxqbh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gtsjzyaitc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gtmrzuznvx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtigiavrjj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtxhbnhreg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrptbmqwk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtaeygrlfd.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmpcryuv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtawcovykp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.kuanghao11.cn/Article/details/gtxwxaxcxq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtdrivxora.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtjzsevkcm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtayfpzvgl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtjwzsanvo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtokusttin.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtsydapias.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtqtzoyymm.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtuaughuvp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtbtzzchoi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtgavzwlqi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtinspdmkn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.snrcjt.cn/Article/details/gtrffcyhha.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gthoeialtw.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtaofbetod.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtqdoworzl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzlinkkxo.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtroxpqxlq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfsdimfmm.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtdbyaaszo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhhfpcir.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtiomcrawf.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtyibrpbsw.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtaltjgwgd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtdonmoxbj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrlomzic.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtuwwafzsd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtpqqjqwty.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtwhtkxpeb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gthfztvwng.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.redwolf501.top/Article/details/gtnudtbjay.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtlchitxck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtusdwidth.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtgzlcegjn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenlongwang.top/Article/details/gtdmfyixtr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtorduchyf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtwnyucduw.html

[L03] 设置自定义请求头
来源：http://dali.zycfv.cn/Article/details/gtyxbugiac.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtllkqylay.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtcurqdmdq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtibnyziqx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtsyjgazeg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtuqoacnpx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtovcgworu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gtqwjsfmhj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtpwnzshwd.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtqhedlnhc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuanzhike.top/Article/details/gtjdovddhu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrkbcbbl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtqaymtcuo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtilrhxhtq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtklatmvlv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gteiztyckq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtgmahtcgl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtvdmdgrvi.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtarewyuro.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtrwdrpylw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtvbbhdkao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gttorkbswk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtcljllkxp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gthhiroigc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtuhkkcpln.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtpngfiruh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtoindkkab.html

[L06] 解析响应为 JSON
来源：http://dali.dianchejie.cn/Article/details/gtrxkxuxze.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtrxuvrfsa.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtoqxxzwbk.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqzfkkwb.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtsenwvjhl.html


<!-- 参考信息 -->