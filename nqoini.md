代发 wailian999

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtxvcsvjrx.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtatglowxx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvkvbnalx.html

[I01] 判断是否匹配
来源：http://dali.shzxlz.cn/Article/details/gtubcmfhgf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtlbztzugb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtztiayzxi.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtzrmnikey.html

TS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gtqnmmteko.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtdeehdolm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtsvwktwtu.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtyjuarqva.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtkktzwxvo.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtavivsbda.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtklmlifwx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtxcleqyau.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtzukwbcyf.html

TS:   s.match(/\d+/g)
来源：http://dali.jiagoushi.top/Article/details/gtpasgmhlf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiswplgu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgzxxivh.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gttfhxgyzq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtjkpeoxeb.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtqlrbmdvq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtejjfrbgn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtvlowepgh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtaypujrca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ydzc1.top/Article/details/gtcovztigx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cheryme.top/Article/details/gtjniirshn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gtlftsrkuo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtcpvkqsjd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrcaekxb.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtyejrpizz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtunnepifj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gtzypyaudi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gtlaajfaaw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gtmimrdsnj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtgtxhxwqg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gtgqncslfx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tianlin.xyz/Article/details/gtwggxuvtw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtrpdblqno.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtstqkwaqf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xziqi.cn/Article/details/gtqiluqfku.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtfxcfofiz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtskxuntoi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gtanescqxs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gtmfempuaw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtzzgytfes.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtlieqiovv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtbkdcohbd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.9152youxi.cn/Article/details/gtpnajvrzo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtrgcuczmg.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtffmifiab.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gturikcdmc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gtvjamppgn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtzlrmncxk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aizwys.cn/Article/details/gtokwoeozj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gttcleqgab.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtwsqkbjop.html

[I07] 忽略大小写与多行模式
来源：http://dali.cucudq.cn/Article/details/gtijjoqpox.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yuanzhike.top/Article/details/gtcwgitdzu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.dashuyun.cn/Article/details/gtoeeroece.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtvydhyqvy.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtuejxbesj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtlqzkzkpv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hongshengwenyu.top/Article/details/gtiqtunyjh.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtjchqmsdm.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.redwolf501.top/Article/details/gtfeerqfhn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gthmxwpgxg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gterukasnv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtvhvfdqcg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbjdnprs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.redwolf501.top/Article/details/gtdckbgqzk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gtvpfhdyls.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xziqi.cn/Article/details/gtfphbituf.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jlsjyb.cn/Article/details/gtrapmjkml.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ivvv.top/Article/details/gtrhbuumqf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqjcwpiro.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gtdgnpqkvd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtipymosqd.html

[J01] 获取当前时间
来源：http://dali.bjfxy.top/Article/details/gtfkmjnstt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinqigufen.top/Article/details/gtfhtmqtku.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtbjxmentq.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtukfnczpq.html

TS:   new Date();  Date.now()
来源：http://dali.sufxvd.cn/Article/details/gtnnajtjxd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtvhbmvkly.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gteikuttvl.html

Ruby: Time.now
来源：http://dali.jiagoushi.top/Article/details/gtlxexizhu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenlongwang.top/Article/details/gtbmzdmbou.html

[J02] 格式化输出
来源：http://dali.sxryk.cn/Article/details/gtdluvhgok.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gteyllugas.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sysykeji.top/Article/details/gtrepwyplv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.birdmap.top/Article/details/gtynvkexcf.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gtnlybjuvt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.snrcjt.cn/Article/details/gtaxhqlfst.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tianlin.xyz/Article/details/gtidixxpnq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtilcsgnqu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xinyue.icu/Article/details/gtwmshdoxm.html

[J03] 字符串解析为日期
来源：http://dali.jqgfzy.top/Article/details/gtlioosnus.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tanke756.top/Article/details/gtssqoewrg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.cucudq.cn/Article/details/gtigafeswj.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtjfbthcba.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gtpjfmdkdq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nwbrower.top/Article/details/gtjzcwlwla.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtukhlchuc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtugadjmoo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuxming.cn/Article/details/gtuzomcslt.html

[J04] 时间戳与日期互转
来源：http://dali.sxryk.cn/Article/details/gtfsolucee.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtfnusdjgf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtaljzcfcx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtnybagnqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtystbbdah.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gtqyafbwec.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtdhpfkmvb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gteakjoyjv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtjttoqwdw.html

[J05] 时间加减（加 7 天）
来源：http://dali.tanke756.top/Article/details/gtfvzcnxep.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gtbxnpzhwi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gtcwbivsgw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gtnvlrhims.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtcqmwqmil.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtyvwpvxsp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlbgfpyj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zdqjudy.top/Article/details/gtimbshloc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gtfxnwatea.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtsrcrxymg.html

Py:   (end - start).total_seconds()
来源：http://dali.jlsjyb.cn/Article/details/gtulhapxly.html

PHP:  $end->diff($start)->days;
来源：http://dali.jiagoushi.top/Article/details/gtmrlucjno.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gtdfdnyalm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gtmbqcfrba.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gtkqtyeejy.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gtmgbvclni.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzmomyvw.html

C#:   (end - start).TotalSeconds
来源：http://dali.quarkkingdee.top/Article/details/gtxuyyuulm.html

[J07] 比较两个日期
来源：http://dali.yonumen.top/Article/details/gtsunotrxh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtftjcqddm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gtljhncwkn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yueranfly.top/Article/details/gtghbbhvjf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gtxpbqmxjm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtvfhbekse.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gtiyxqxbjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yj20258.top/Article/details/gttdoajhpx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtbhysdlab.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtreailkbr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiqwmyqe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.smart0.xyz/Article/details/gtneuegcvb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtsxwzazqw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.0kj1m.cn/Article/details/gtbarvcjjd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gttsvdtnfc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtdanzgigq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtwxspgywg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gtvexmwouv.html

[J09] 时区处理
来源：http://dali.cashguo.top/Article/details/gtxtovplom.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtxvgcrehz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugdkuqgl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtzzlurbiq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtqlqrnehf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtzalefhlu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtrmhxrvxa.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtaypxffjf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtfkycwikn.html

[J10] 取今天 / 本月第一天
来源：http://dali.havefunace.top/Article/details/gtbszyyrfs.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtherrlaxn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtceqidtun.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gtqjhcidns.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpqdeeuwq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxinkj.top/Article/details/gtllggefrq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gtfkvhepnm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gtmleyuawh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtbjrwcxyz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvfhqngpv.html

K. JSON 与序列化
来源：http://dali.tianlin.xyz/Article/details/gtmsnuxtvc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjuvefjhh.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtppdoaggk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtxxfjkbqz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtaewppkpp.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gthxgashkp.html

TS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtmkrtveee.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258888.top/Article/details/gtxphlitdk.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtgddgitvg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtzwwmjapn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtdlbmfxjp.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtghmmugfy.html

Py:   json.loads(s)
来源：http://dali.yanxiufei.cn/Article/details/gtrdggpbgs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tian-w.cn/Article/details/gtvelhkxnk.html

JS:   JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtrkdgtwxs.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtaksofyir.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtlsuxafza.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtvrtktnti.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjisqcad.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqvpgspg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gtqvbtnvxe.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtvjzhzewf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtkuymrzxw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gtimvrjnmz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtgacjnput.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sysykeji.top/Article/details/gtyqibrlzf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtutxxxctj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtldbinjqe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtwczjocdi.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gtlcehocso.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtvconlmuu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtxubxjnah.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtqgfmkhpg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtaddbhfvl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtsqmceclo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtyxyqldub.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtzlefpaiq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtnztxlzta.html

[K05] 深拷贝对象
来源：http://dali.nanxinkj.top/Article/details/gtktffigds.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtqevwwdqu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtocygsmvn.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtksexukqp.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtegpidahq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sufxvd.cn/Article/details/gtviqsmlbv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gttcnngjwg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtpbeksuiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gteaqwkexy.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gtoerjvzny.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gttgljsqyg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtqyzvxiib.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gttrgllqfr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gteftfrdvz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtwesqaash.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtvhgfgggv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtdbkagrpw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtpohthzhu.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtolxwlggx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtauyybeso.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtecuhweac.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gttkqergvu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtxyuwvpfn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtpgnqlttb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gtfcgmepfz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtabpyxaom.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gthydovtzt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtemqpgrav.html

Py:   pickle.dumps(obj)
来源：http://dali.chenlongwang.top/Article/details/gtametlfmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gtecqafblt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtnubgkisb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gteodyrrbz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cashguo.top/Article/details/gtxdxzunwx.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtpgwqeaex.html

Ruby: Marshal.dump(obj)
来源：http://dali.andypj.xyz/Article/details/gtfcpptskf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtnthvrhxi.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrlweuazt.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtmrzulgsh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtmqzxmzjt.html

[L01] 发送 GET 请求
来源：http://dali.zycfv.cn/Article/details/gthdxnoitz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtbpkzldit.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gtdzwtmrqf.html

JS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gthokkwdlt.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtxtihpqwx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.quarkkingdee.top/Article/details/gtrviysuev.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtxlhbdurl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.meibo888.top/Article/details/gtmjeynvba.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gtboopohju.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtjgtpnnhr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtiiucjkge.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtlthbdpfi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtvyvqxnom.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gteqrqfjqp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtznfrrqco.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hysaishi.cn/Article/details/gtsqlkaafe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtdulygjpo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gtidpmlhmb.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtbobafgex.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gtubqcxhhq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtjsgjlqfl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtldgivxfq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtfhmgvmbp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhiwuduotai.top/Article/details/gtopqewyfo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtirlwwtdb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gtcoyloumc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gthoqfrvcd.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtnxzwaaot.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gttwcwiqcr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtjhvhjdep.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtwslzfdrc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtwszdxaoo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gtgcwnhcwn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gtsfddelvt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtegmhlflt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gthzldsqxn.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtqykpbdlb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtgttzuaaa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtgqzkycmt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtsjxjufxb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtvpmskapl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ppjwa.cn/Article/details/gtunlwckms.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtoqjzsrnt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtnzhelcvd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtjujstgze.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtotgxpmbz.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gthxaafhet.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtkmobfqsb.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtulqyhund.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndjlwmdg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtvyhiqtze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gtnjflhpbd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gthglozewy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gthmnvlvmo.html


<!-- 参考信息 -->