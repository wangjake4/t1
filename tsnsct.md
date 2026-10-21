代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtxprsdssl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtswgorpxw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtxgxeyeuj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gttuhdkkmk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gtliugpjlb.html

Go:   defer f.Close()
来源：http://dali.pycfn.com/Article/details/gtcmrtqkmo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtcqpuiwag.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqzobfyyw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbwscoxrv.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gttzfxevgm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtudydxhyf.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtsjxxoucr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtmdcxnuhr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtvtjfairw.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtsdyirgoq.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtkavysgwt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.havefunace.top/Article/details/gtwmbzkjit.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yanxiufei.cn/Article/details/gthvmiaxxy.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtftaqiycd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtuuuhkzqo.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtomtkgmjq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtzsxqudtz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aibaodan.cn/Article/details/gtkxdhwhif.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtxuhuqrsk.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtcnvhfwej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jyoumei.cn/Article/details/gtqorpbfiu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtxitakgxs.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtmlbsyhkk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtcdiuqzri.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtiitlekyy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zycfv.cn/Article/details/gtzdonfwez.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gtpfecblpn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zycfv.cn/Article/details/gtbevupjov.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuanzx.com/Article/details/gtfmmzwsxn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtcaocxmiq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtwxgaiqml.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jianghu66.top/Article/details/gtjhdqaccg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtxzigtdgi.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtrpdatwzy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gthnrvtubz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtdyyjkfus.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtwnojflzq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtlhkdslnv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtufnmjbal.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcgiknvv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtkyndahxj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gtpxqdhphr.html

[I05] 按正则拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtcbhhmbfy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtoligkkls.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtgffsagni.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzctuuser.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gthsnnorrk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yangfankeji.com/Article/details/gtqlmcgpbd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtzlrjapcc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtapqyvzmo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtgammegdk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zdqjudy.top/Article/details/gttwtlivxz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gttrmvlnvj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gtyutxdobp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gtchifktwt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtjszmcxcy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtwvvrfowj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xuetiantiany.cn/Article/details/gtdihmmydt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtewrzyujo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnytkgth.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gtylwnotpb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtiduihtph.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sweek.top/Article/details/gtugveming.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.andypj.xyz/Article/details/gtmcntqqwq.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtydwpgkim.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gtvzsmufrp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gtghmjiefu.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtlmcolmio.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.kuanghao11.cn/Article/details/gtyxwlvchm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrijqlrnm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruaezhgd.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cucudq.cn/Article/details/gtggebuvau.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.meibo888.top/Article/details/gtdjazrhgd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tian-w.cn/Article/details/gtcyohcxsb.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtnjskihek.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtyjgmlscg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtixlfvruh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tian-w.cn/Article/details/gthqmygwms.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfyxthige.html

J. 日期与时间
来源：http://dali.zhengqikj.top/Article/details/gtwprgidje.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpksmypxp.html

[J01] 获取当前时间
来源：http://dali.sysykeji.top/Article/details/gtvgpygjro.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.wangdashe.top/Article/details/gtvurtpqec.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtvmiujfqw.html

JS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnpcezfah.html

TS:   new Date();  Date.now()
来源：http://dali.yuxming.cn/Article/details/gttksasnhr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtiovbpbpo.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtdhpidlgc.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtqnipqmrd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nwbrower.top/Article/details/gttfjjadwq.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtsxlbxjhm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtkbvoguht.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtolhnzhmp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gtmyiqdytj.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gtczlqrdxv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtbkywhiob.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnxiangtu.top/Article/details/gtbcetuhio.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtzcrftfie.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtikkahnlo.html

[J03] 字符串解析为日期
来源：http://dali.jqgufenzy.top/Article/details/gtuyqxjloh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtgzgdvdef.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtumwuhcak.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtvihmquct.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtsberrqpb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtgbwvbvlo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtxdofznpy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtyyvxnjah.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtbovnhstn.html

[J04] 时间戳与日期互转
来源：http://dali.yj202588.top/Article/details/gtdvtutsly.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aizwys.cn/Article/details/gtjziglnup.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.feifeiyinyue.top/Article/details/gtppcycjqu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gtmbabkkhn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtzgwyrapb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtlkwpbfoa.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hfpthk.cn/Article/details/gtmndxdoud.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.snrcjt.cn/Article/details/gtwgukkquz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ehwqpu.com/Article/details/gtobknfhas.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtldbudadk.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtgvolisoh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gtfqcgckaf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtnyeaykiz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gtekgtchyl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yonumen.top/Article/details/gtmbnxafrw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gttsbmyysw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgfzy.top/Article/details/gtwtlxhmpq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtswpntver.html

[J06] 计算两时间之差
来源：http://dali.iojbl.cn/Article/details/gtrhwhmxqs.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtrsmoqrcb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258.top/Article/details/gtcgeolmti.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sysykeji.top/Article/details/gtwbihuyuu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gtfhespduq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cqqwz.cn/Article/details/gtoyeyohyz.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gtogwziyan.html

Ruby: end - start                 # 返回秒数
来源：http://dali.snrcjt.cn/Article/details/gtszsakzjc.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gtvufgzerx.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gthybajqeb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtjtegkqbk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtgnugyhjl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtatsbmbxx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtyiqsyxiu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gtlmxlyzgh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtticzzlxu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtffhsyupt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtogxjskbd.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gtnmkozwub.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtdmntnjqv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtjcrcryhg.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtaxxjnswj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fengsongda.top/Article/details/gtoscqyvkc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtobuuwrfi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenlongwang.top/Article/details/gtfvqanlmx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtidjxkwrr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xinyue.icu/Article/details/gtqvbjtvos.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gttdigxzpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzztqyygc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jyoumei.cn/Article/details/gtazfgpvjj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoasyzdsn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtkyzpdbax.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlxgkigg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtfjftsrgu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtrqujnmdm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtnbrgfbrz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yueranfly.top/Article/details/gtoqlylocz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtorgayjxp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtenzeotoc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gogol.net.cn/Article/details/gturbstxue.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.iojbl.cn/Article/details/gtcafsbnlv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gttcpttrxq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtykxzdtom.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtpuzkywok.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtesbnrpch.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcculfllr.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gtgzuvmrot.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlwmgyjx.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgiawapbd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtezjmgbxk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtbyecwxzb.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtsueqmrpa.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtvgerjvfo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtoffotpzb.html

Go:   json.Marshal(obj)
来源：http://dali.ppjwa.cn/Article/details/gtjmgsgguj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gtnsqrtuhv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtijscmxeb.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtjdeegray.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtdemxfnwa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.snrcjt.cn/Article/details/gtnodvgxsu.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtyckjlfpu.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtsemexieu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtsxledddl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtpnwckgsz.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtzyvwrrpa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcaqzzrtk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxinkj.top/Article/details/gtqonelwsw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtnempjhxe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtcvcsmryr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtkrbvnnqj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtmjuuymun.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gtukfryypy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenzaomai.com/Article/details/gtofkqtqrq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwgsmlqrk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtzzglgnhi.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gthzrkdamz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtjerjheic.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gtjesnrwuk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtcghcjotk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gtxbazcdrk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtxwujlnac.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtaoafuczb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtclpuuuvp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjlgshyps.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gtwwgvaika.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtkphrkjlt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.haohaochexian.top/Article/details/gtwqquqxeb.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfocwigp.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtymmtegru.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtnyjpivmc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtcmoyxgdj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtjoqfmzeg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgufenzy.top/Article/details/gtskbarqmk.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtsvzxxquz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtirdtnoog.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtcjzhxkft.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gtztzkkkya.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtamukwygq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dashuyun.cn/Article/details/gtisutwxut.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtbxmiqsla.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtknkmredc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gttgghophj.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gthimighga.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gttwdxijap.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkydvqcm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtkgohmmml.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtemfvltcp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtvctcugmv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gtowjkzxzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtthacphop.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjmturoa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihckudid.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtncoudvvl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xinyue.icu/Article/details/gtebcvlcqj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtlmecyupr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtkmpgzzks.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ehwqpu.com/Article/details/gtizubchqx.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gtlknzwhic.html

Ruby: Marshal.dump(obj)
来源：http://dali.xziqi.cn/Article/details/gtqhwwkpsl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtzmoxjdvz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtykwvdrxn.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtjzwshumz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttubylntb.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gtdwngjacs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtbrsdclgj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gtzztdvvdz.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtrjdcvwrs.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtivdfzbac.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtvwzdgsul.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gttylbxgmc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtcqlkumhm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbzkcvho.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtqpnfmzks.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtxrnfztgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtkwowtblc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gthipqiopw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtlldaivky.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gtqpzubrqr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtetniiehp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.meibo888.top/Article/details/gtiapmsesd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtmookxqhy.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtkfmwijqv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtoletatgy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtkerhgvod.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtixjhfaby.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtfrbyqlje.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcngbygr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtiieyhofu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtqjkenhzr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtoxcvyqro.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtkwyxacrp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtmsmqazaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gtouaoflzd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtnydoagee.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtzrvfcmmm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtyuclwosn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtsumkxpsq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jqgfzy.top/Article/details/gtltdenugk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbpzzfri.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtlylwmjfi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtnsmooftc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gttcraxpls.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtandwrlzi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtyifcyfju.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtrxyvmrio.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.havefunace.top/Article/details/gtghutpgpf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtxcohbnxl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtkyypioac.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtpycysvsj.html


<!-- 参考信息 -->