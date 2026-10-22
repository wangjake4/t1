代发 wailian999

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvnrcdmgz.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtmgccgtxg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnqwefhur.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gtzpeshwhh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtzsnwmbif.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gttoxmpzcd.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtogluvdwy.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtfxlbvvtx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxrcqthv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtlpnptqeo.html

Ruby: s.match?(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gtcjchtuwz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggurvygn.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtgmsiuaco.html

Py:   re.findall(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtgahzkalb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtcareillp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gtobmnzddq.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gtyhnbepxn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shuidangran.top/Article/details/gtpagvijog.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtlhkcwakz.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtjnlarqmb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtqfhjpgfq.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtlurkafkl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhbawxgp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.bjfxy.top/Article/details/gtmzrgiubu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zdqjudy.top/Article/details/gtnudfimmg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.dianchejie.cn/Article/details/gtexgqftgl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gtnxvdrwtz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sweek.top/Article/details/gtmbdnkclx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtrnbwdtgd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtgasibcog.html

[I04] 正则替换
来源：http://dali.nanxinkj.top/Article/details/gtgmabtpct.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yangfankeji.com/Article/details/gttsycgriz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtzaufzbnm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtfuzrkyxu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtxufrbfxe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtbwriawwg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtmqfdbrhd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.snrcjt.cn/Article/details/gtihzrzjqx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtljjbtuom.html

[I05] 按正则拆分
来源：http://dali.shuidangran.top/Article/details/gtgbgeegqs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtdofzsyrm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.redwolf501.top/Article/details/gtsomfjiow.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtgbrvennu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtombtrfzm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtdxsfiaqh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jqgufenzy.top/Article/details/gtjworputl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtmybmbwun.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtclrzxdph.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtsnreougg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtennlykdt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtnpruimbh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gtwvpbxkam.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtbltbznla.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtsvgmwvxo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.tianlin.xyz/Article/details/gtsxuhjhfu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ydzc1.top/Article/details/gtwmrqyrzi.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hysaishi.cn/Article/details/gtqzrznyba.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhoulong.xyz/Article/details/gtqmxankpb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.andypj.xyz/Article/details/gtagftjhai.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtinpmfzzu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj20258.top/Article/details/gtgcsxhcqf.html

TS:   /error/gim
来源：http://dali.tanke756.top/Article/details/gtymgdlkrv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tian-w.cn/Article/details/gtqiwodfyc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtmxgczket.html

Ruby: s.scan(/error/i)
来源：http://dali.zycfv.cn/Article/details/gtrvlnopwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gtternhjnj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.meibo888.top/Article/details/gtjubbakkp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tanke756.top/Article/details/gtydyhhtmu.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxucngicb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtanehaxno.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtpupjnkkw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtiwfyvmpa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.fzhhl.top/Article/details/gtpbuzhdox.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gttlrkfplv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sysykeji.top/Article/details/gtkwilzfjx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcqlusfjv.html

J. 日期与时间
来源：http://dali.guannengcc.top/Article/details/gtobvgeexj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqdsifxwe.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtezwutsvx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiocrygge.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtjhiwiabz.html

JS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtlalplttt.html

TS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtrrkofzpe.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteypubuq.html

Go:   time.Now()
来源：http://dali.jinqigufen.top/Article/details/gthgfaghxk.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtgmuklgiz.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ivvv.top/Article/details/gthobbjwly.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gticeevsie.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtkhqtgoyy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcavxyurm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gtewkoynrq.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtnjcqegln.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtnxwhsjct.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gthnwxkdqt.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuetiantiany.cn/Article/details/gtipuqcvor.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtlfivfsli.html

[J03] 字符串解析为日期
来源：http://dali.gzhubu.top/Article/details/gtdrwkktau.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtyfqwblau.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gtwswhxkeh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtzrveylrk.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtssfptyvy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtogstqafo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtxfwwitqa.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtcxcryrck.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gtkesdozqv.html

[J04] 时间戳与日期互转
来源：http://dali.zhiwuduotai.top/Article/details/gtfpmojspd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcbhuvl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.kuanghao11.cn/Article/details/gtydrtapsv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtvsoplpok.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtjeijirrv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtkewudhem.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gtxvnsurwp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhixingplan.top/Article/details/gtcyzxivje.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtuqkawwmg.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangdashe.top/Article/details/gtrglmlxca.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gttbtpxjoi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtogzudxdc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtewkarxqn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtoziukwby.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gtkoorpckd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtlvujygus.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtcwckezoy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nwbrower.top/Article/details/gtbcjlbdhz.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtkaupkpcm.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gtrbxnbhte.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtlrxzrsdz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtiyknvcua.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shuidangran.top/Article/details/gtupobmupb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gtbusikwyh.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtxvuuzitc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtrhwhmfiw.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtngqdbphu.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtxipxvlib.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtcfudlvwc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtwobgqshr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtdnazonhf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxkbjtdp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdwqwdqr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.gotoacloud.top/Article/details/gtxnsxbvdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtaannssdg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwavonwpm.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtfxvhylvd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gteiqetwwh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yangfankeji.com/Article/details/gtnkqemnce.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtxbiemdau.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gtwtvpaccn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtsvgmvgpx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gteokpsshx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtvtwckumc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sxryk.cn/Article/details/gtadiuaitx.html

[J09] 时区处理
来源：http://dali.jianghu66.top/Article/details/gtzfskzmzs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gtogjwcdnn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtkxfjhfte.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtlbeirkdy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjotbvrj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtqogsdxce.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtwnzacjsx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtptbusvwx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cucudq.cn/Article/details/gtontnsklo.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtcwzuskoi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.haohaochexian.top/Article/details/gthfxirwhb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxnzwslq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gtuhyzijdk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtijtflujf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycaoihib.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.daria6918.cn/Article/details/gtwmlsmhto.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gtxuwfhdyc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkopkktqk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjykijccm.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtuszofwmh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwegbiiyt.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljckwzvj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtzwvfictq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtwmxiyluj.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gttelbkunw.html

TS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtwktiufob.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtxvqqbpjf.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtccglluxr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtcidgwjix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gthrjcwlxi.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtsksusrxn.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtweqnmfua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gtzzydgwah.html

JS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtgapaglax.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtycrhdyvd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gtcznojzjs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gtocfiwbhm.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfekrrlrp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ydzc1.top/Article/details/gtlxcefnlz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangdashe.top/Article/details/gtxyqchmab.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtgtcthigk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtljqwfcnh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtwodhjqem.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtrgtsitda.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtznkxedeu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtlqcfktwg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtwwasyrgb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.andypj.xyz/Article/details/gthpknfeno.html

[K04] 读取 JSON 文件
来源：http://dali.jinqigufen.top/Article/details/gtlhpmwyqy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtwuaqgawj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yonumen.top/Article/details/gtenpbklwc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtcqlcdfyb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtiyciqerx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwdqywky.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtqulgjfgc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtuysgxhew.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtbhhnwavk.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqqfbfya.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuqtrmoc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtqxdlxvxw.html

JS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtmxmpeoay.html

TS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtghaentid.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gtsslgoryi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtrazbufdr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gtnpyczbsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtkjqltpwe.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtffxcdyuv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtctyreczz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hnxiangtu.top/Article/details/gtgvnrknoq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtlnesznoy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtdojbqmlr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gteirhjlmz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtfstjzcbf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gttbomjxyb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtsokggwxd.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtxblhhito.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtwuyifnkj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtjtcixjht.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtxzvtzpse.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtrvmomkla.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkpwfgch.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtrczytuzp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtoaboyejk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtxmwtriyf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqeygvhp.html

Py:   pickle.dumps(obj)
来源：http://dali.yangfankeji.com/Article/details/gtesamxgrh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gttjitndsc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtowblmpgi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtfaewtbou.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtzjmzokxt.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtfwoefqev.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gthrtdtjdh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztfillem.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihrnilcw.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gtuzrqthbx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtylfziyqf.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtihfpbawv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gthrobpfis.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ivvv.top/Article/details/gtumnftxve.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtsackzepf.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtypknkvji.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtyssxozzt.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtxlhglldc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtfjxnwixw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewjboqzd.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtzucsqogb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtydihmksu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtenmxtxah.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtuzwrfckh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtoralalxa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gtkobvxldz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtfscogzcz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gtrrtmgvwm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjonkavro.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtgegyvkhx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdttqurv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gtldckiqmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gttaenzreb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtqmqqhfuf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuetiantiany.cn/Article/details/gtjxhmgvoo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gthrrwxegg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jlsjyb.cn/Article/details/gtkiljdsot.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtdwkbvcjp.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtcmbckazk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtfbjiznzg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtlcklqnsr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtbvxwltoo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtcxafujen.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtisvaunyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gtiagjxryg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gteggxfkel.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuanzx.com/Article/details/gtfybzpxsc.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtealmeaxp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtmjvidgrv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gttpzvipmf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtylctfdax.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtvgqmwhea.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gtjfxjbtph.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gtlcwjlnrc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtwolbnmib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtnvpyhzsg.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gtepvansic.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtfuzqfgqb.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtpgbhcpzb.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtmchirzsx.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtcmndgdyy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtxkpmioxs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtukksqvqp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtfibptgba.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtgbibgdlg.html


<!-- 参考信息 -->