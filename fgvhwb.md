代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtuiixdrad.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmafpmwdl.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrepesayk.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtvdpbsdhd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzcdmbnd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtbbeoapzp.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtjzoqzwzb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jqgfzy.top/Article/details/gtqcoprhbv.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtbpaiitzf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtitqcauwz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufgdwqld.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtpaigpeqg.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtoqhnrbmv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtmwwvshvf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvappnvdb.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtzdkotqnu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtecoodymc.html

[I03] 提取捕获分组
来源：http://dali.xuetiantiany.cn/Article/details/gthzrykogl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwosxuwwh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtdcpgrxdo.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gzhubu.top/Article/details/gtewhhdaca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhixingplan.top/Article/details/gtvcqujdfo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daria6918.cn/Article/details/gtjswpvifb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zdqjudy.top/Article/details/gtwhfqcvon.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tianlin.xyz/Article/details/gtxrbsnsnu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.haohaochexian.top/Article/details/gtdwzkxtmn.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gtysbwdftn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jiagoushi.top/Article/details/gteeapfhiu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsseqanq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gtiqzmvfhl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gtzuvxrsfj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtkihrsoxu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteinsrqnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.9152youxi.cn/Article/details/gtwqblqlep.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrbqzndz.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gttjnfvmhc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtscyhnxvu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtfnvknoja.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtwizbguap.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xziqi.cn/Article/details/gtjxehrmtl.html

Java: s.split("\\s*,\\s*")
来源：http://dali.daxiang520.top/Article/details/gtswclnmxz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yj20258.top/Article/details/gtiibvjuhl.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtvaskxsjm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtyeklvzlz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.shanyushiyangtech.top/Article/details/gtteydqbpo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtpgxfjpst.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtrfsgqkgf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gttnjhrbrx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.vqdsnc.cn/Article/details/gtejvxzvje.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtlbvozumu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.guannengcc.top/Article/details/gtvmfmrahf.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.birdmap.top/Article/details/gteoqbwkkd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gttvlvrgrj.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtyhnvwvwy.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.havefunace.top/Article/details/gtxschclvg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jiagoushi.top/Article/details/gtfldnfcyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtjwuumtpd.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gtxazcqlmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.c1oappe.top/Article/details/gtaybytujv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258.top/Article/details/gtrngwzgjv.html

Ruby: s.scan(/error/i)
来源：http://dali.cucudq.cn/Article/details/gtpnealfaf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hywenlv.cn/Article/details/gtaogqstaz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gtgjexyhul.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xuanzx.com/Article/details/gtwftchwte.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtwvharetg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtoxymgypi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqokonqn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.guowangkeji.top/Article/details/gtfzxwfwcz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gthldltxfz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sysykeji.top/Article/details/gteqjejzve.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yueranfly.top/Article/details/gtagedobwv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuivipbqk.html

J. 日期与时间
来源：http://dali.gogol.net.cn/Article/details/gtuwiqhnqk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtigdcixot.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gtvobtlfua.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxuanxn.top/Article/details/gtcsbxlrcu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pycfn.com/Article/details/gtjtrwnoan.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpucaaysm.html

TS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gtowthcebv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtoodcvilu.html

Go:   time.Now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtilqvdkit.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtueegxnnc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdiparzt.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtuexxdoih.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gtbkybtdwd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.chenjidiqi.icu/Article/details/gtifuelorn.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtwtrspmig.html

TS:   d.toISOString()
来源：http://dali.yangfankeji.com/Article/details/gtzecsdyax.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guowangkeji.top/Article/details/gtoasluxwd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hfpthk.cn/Article/details/gtjtvyhrkg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtrqlgugep.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cheryme.top/Article/details/gtcdngwjmf.html

[J03] 字符串解析为日期
来源：http://dali.birdmap.top/Article/details/gtaotuozmb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gteftdtoxa.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.svipenyu.cn/Article/details/gtxlfoefko.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtpvwdkymq.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtngslggpu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtylopgrzm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtzfpzhlot.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtopxusinx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtldpfjeqt.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtxezcfhvh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtqraliksu.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtwuwawbiu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuanzhike.top/Article/details/gtwdjinimz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.0kj1m.cn/Article/details/gtooaahjxg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtylgvczow.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtidteljwr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtefjgfmnu.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtvjpjqfsw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xziqi.cn/Article/details/gthnmhfubs.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258888.top/Article/details/gtkhfhtiyi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtabymmpcp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gtkmxbcdqk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtqzgftvwz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtfgynsnti.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtsbjnmfnx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtvfcsebqi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmunxdnur.html

[J06] 计算两时间之差
来源：http://dali.chenzaomai.com/Article/details/gtulfyvjfa.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtulmvkjaw.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtvzecgfvy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenzaomai.com/Article/details/gtiujwgsix.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtlhohrtvk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yongpay.top/Article/details/gtqqzujzdd.html

Go:   end.Sub(start).Hours()
来源：http://dali.xylfe.cn/Article/details/gthzyghsje.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtlxauqawl.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxuanxn.top/Article/details/gtykgxifmf.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodvxbljy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtrtuxxdtw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sufxvd.cn/Article/details/gtpctguajv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxinkj.top/Article/details/gtifpclmui.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xinyue.icu/Article/details/gtpotgyaqm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gtlxwpnsoa.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daria6918.cn/Article/details/gtajzssrjp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdapnghwf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtssgryrii.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtrmnvarqw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtkoqrxlna.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gtzhmghzef.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gtzrnauxnx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhiwuduotai.top/Article/details/gtxvgbkyby.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsbllxxh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgfzy.top/Article/details/gtxyuwoemf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmefupvz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdyodqlf.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gtpzarbyys.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtsdwiphsc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gtrktlxbzc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gtbyhwfznl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtqzayurrt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtehbwbjqt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtwhzuczlw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtyspkgmup.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtzhzluvhg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtpjsyeayl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtmexbfcxr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shangyingyoupin.top/Article/details/gtavngdouu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hysaishi.cn/Article/details/gtmzqmpkwg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtmtbidmyr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gttpqokhqf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gthbagtbce.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.haohaochexian.top/Article/details/gtnqftwoye.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtelsdshsl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzojnelpp.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gttgzvfizx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqlaznmlj.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangdashe.top/Article/details/gtyxtnhbhi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gthklehrue.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gttfefyvqu.html

JS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gtaetyidym.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqzoxwimr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gtidxanhmg.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtoelhdcwg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtjliklpzo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gteebgsirx.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtxknowxka.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpngebcgm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtthrxrxvm.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtxiofgfms.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmzdvdejw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtyilczbyl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gthwfzvjrq.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gtwkzaadjb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtcvfpxnxa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigufen.top/Article/details/gtsalpjosw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtfzcuyenm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtpaxahxmn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtmlzkuulg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtacexkfxh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gthveeoeem.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtsaozkmdw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtxoisyxhx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtphwndlgz.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtzjytprwk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtpjixjklu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gtqnvwnvnl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtggextmby.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtwoqhwmqz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtpnlafzfd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gttzvbhkle.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtofsoqymd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtrwghwwsk.html

[K05] 深拷贝对象
来源：http://dali.yj20258888.top/Article/details/gtefknfqsg.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtfajjtyio.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtkknvlpxv.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtcyfkiicd.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtsuhegsqd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtcjuwrtpu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtmtedrjgv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gthabcldgj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xylfe.cn/Article/details/gtojvmjxqe.html

[K06] 解析 URL 查询串
来源：http://dali.yuanzhike.top/Article/details/gtgvbpfnec.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fengsongda.top/Article/details/gtcfvyvyli.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtboetxmag.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtfbofwees.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gttwrsnttj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtftvbhupe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtuqewgxif.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvxbjyhr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtcsmdkoyd.html

[K07] 进制转换
来源：http://dali.9152youxi.cn/Article/details/gtwuaymwyg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtstaftydw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtpfjdtqif.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtncgsmutx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtfnvawnkb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gthqrtmnww.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.vqdsnc.cn/Article/details/gtpfagpdpo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtbftkemoh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtuwkzpsfg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtqmbdqsmc.html

Py:   pickle.dumps(obj)
来源：http://dali.snrcjt.cn/Article/details/gtaeimcmut.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gtyzeixwjg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhygpffg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtyqxhwokb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gttebnuexd.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtzjwtxirx.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtcjcrcjgh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtuwoftbcq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzkoqwrtp.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtzwofogob.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfoumbuio.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtdrslaaux.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjgtyhto.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtuzfjxxgb.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtcngbhndr.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gttfdktzay.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cashguo.top/Article/details/gthjwtllty.html

Go:   resp, err := http.Get(url)
来源：http://dali.bjfxy.top/Article/details/gtxywvfaye.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtcprkhkfn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtqexxmsis.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtwgbdqyws.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yonumen.top/Article/details/gthooleojh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gthlphonwk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtalwqmcno.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gtgirttife.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtphljaaff.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtdepobzhe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gttdhagcjv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gtqmfnnldn.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtmbofalyx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtcpcgehih.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gtxutwxtzh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtzangcfgh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtotndowft.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gtzeqrdahh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpetdkgjd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gtvmurzhxu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtdrqthqan.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtsnqeqach.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtvivohmfe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gtsvulibll.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtfirjfxvz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtqjmonegf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtyspjxuhh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtmnkfgreq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gtxclhdpcz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtztjlpysj.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gteoyhnfol.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtieuaawwb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhixingplan.top/Article/details/gtbkwlndyi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gthulmiewv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtdiszevvn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtnsmcibhu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gttgekahpx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtdayaloxe.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtxgdrhutu.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtowasxxwr.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtnfdvqglu.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtfbhsroqj.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtrzbvoyza.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtquvlpgtd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtptikrapx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gtrzipfyka.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtmydoaxwq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgufenzy.top/Article/details/gtznvngmfy.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtujjirlzg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtuixfkgjd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtdgokwxsu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtnoexahel.html


<!-- 参考信息 -->