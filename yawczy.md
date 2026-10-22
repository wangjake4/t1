代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2ljhdcwyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2gpecmanj.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gt2arlffkfp.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2kzneouna.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guannengcc.top/Article/details/gt2lcghkpog.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gt2bewrzyqb.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gt2vxfjnype.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2wvdiavjv.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gt2kbhddyah.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2ixdtusaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gt2abeojjpx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gt2iplievoo.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gt2prwnftti.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2lfckfond.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gt2btkgrkjj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2jjmiwrzj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2jcecpzqf.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2ikieeueo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2cwkdrqij.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbchempc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gt2exqabxep.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gt2kkksrnct.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2wbpsovlj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinqigufen.top/Article/details/gt2yipafmia.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hfpthk.cn/Article/details/gt2xqvxwfwx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eplpvxuk.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofhjtzjy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhixingplan.top/Article/details/gt2hsgvhmsl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dducdyok.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gt2pstynptd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhixingplan.top/Article/details/gt2ronmmhkq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2wautcpxf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2ceposjpy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ivvv.top/Article/details/gt2dlutntrb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnusaznr.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gt2psouiwpo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2uekrauvk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2xqjonoae.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gt2yycxroeg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuanzhike.top/Article/details/gt2tudbampx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gt2xpohkaqs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sxryk.cn/Article/details/gt2hqqgynzp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gt2gkxdxmww.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2mdmnygwj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2sjeuykiu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cheryme.top/Article/details/gt2fwwkwdcy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2asvmkqhy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cashguo.top/Article/details/gt2hdlrhhit.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhongyouzk.top/Article/details/gt2orillngv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xinyue.icu/Article/details/gt2vvlhpcrt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.iojbl.cn/Article/details/gt2llheimlb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hysaishi.cn/Article/details/gt2cwbhlwnj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gt2fwudcthb.html

[I07] 忽略大小写与多行模式
来源：http://dali.aizwys.cn/Article/details/gt2pzvhhpvz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gt2msdzgnuh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2scagfrxp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gt2ynptucuh.html

TS:   /error/gim
来源：http://dali.c1oappe.top/Article/details/gt2pxfgojqy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2vkwxtsfv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jqgufenzy.top/Article/details/gt2gyejlfck.html

Ruby: s.scan(/error/i)
来源：http://dali.yj20258888.top/Article/details/gt2cgmrcwbe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nwbrower.top/Article/details/gt2bocymghi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2ooojyklc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yangfankeji.com/Article/details/gt2lnmflywf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gt2jglywpis.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2oktukljs.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yongpay.top/Article/details/gt2pnewwkek.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gt2dcslgfcd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2bngjkyqk.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxbysntl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gt2fqtktwup.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2csfsdjsl.html

J. 日期与时间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmccotij.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2snabuvwf.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gt2eptjvbto.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gt2gzikvmdg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pabsitgq.html

JS:   new Date();  Date.now()
来源：http://dali.c1oappe.top/Article/details/gt2pjqvlhqt.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gt2yvmentgp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2zhixevqj.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gt2sypkdmdg.html

Ruby: Time.now
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpylwzws.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hysaishi.cn/Article/details/gt2jsswdzqz.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2qxflkytz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gt2mksxcqgw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gt2ypowuyes.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gt2abwwxrso.html

TS:   d.toISOString()
来源：http://dali.jinqigufen.top/Article/details/gt2bzgbdfav.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjlwmuby.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vplalfqr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsgstiwl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktovvezb.html

[J03] 字符串解析为日期
来源：http://dali.mhx1999.top/Article/details/gt2uwslbmvg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gt2gieqxsub.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gt2hknybcld.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gt2ndjeskbh.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2dlydcwxr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gt2gwvtbtpi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2vlykitic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2jvcnfjsp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqksrocv.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gt2khqcfcxl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcgvjrjt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gt2trabhlqm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gt2ujssadog.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2hdwbivpn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigufen.top/Article/details/gt2lywarflj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyzmcfje.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gt2bclqxugq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jianghu66.top/Article/details/gt2wqhjykwn.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2zotpjlbs.html

Py:   now + timedelta(days=7)
来源：http://dali.tian-w.cn/Article/details/gt2anmfmuwe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2ozonikgb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2ylbzhbep.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oplyukqz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2uyazeqwv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gt2xypmxdit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.wangshuangyany.cn/Article/details/gt2gzcsmnwl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yonumen.top/Article/details/gt2mxvwvudk.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gt2uzxjvdea.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gt2mdosrfxj.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gt2fzeviaya.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jianghu66.top/Article/details/gt2ckrjfwqn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsojqion.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2uyziaxjs.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gt2klwiefsq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hammf.cn/Article/details/gt2cbmdjocz.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gt2wfjxhcgy.html

[J07] 比较两个日期
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsoulroy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2lhwwkmhq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gt2tjeupupk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gt2zrwzyvml.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqvtbilq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yongpay.top/Article/details/gt2amtjjiho.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangdashe.top/Article/details/gt2tbhvvgih.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vivpwzzj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2jrrtxxrf.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gt2vbnaphcc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2nccjhgli.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2uivtlajn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.0kj1m.cn/Article/details/gt2gslvcpqq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sxryk.cn/Article/details/gt2zifxwxwn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2tvldidzu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gt2zufvxjui.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sweek.top/Article/details/gt2eatzpufw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.meibo888.top/Article/details/gt2vhxokpfp.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcvpfpcf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gt2ptmmzkhn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjblesiq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gt2bippvgjy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gt2frgzjqly.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtghxvag.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2ymwcnfrv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gt2tqqbwvot.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gt2tenrucoo.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2nfrfgmme.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hfpthk.cn/Article/details/gt2ctuggszd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2walpzhrh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gt2ngulplfd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2ifoltgmm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gt2kchboxak.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.andypj.xyz/Article/details/gt2ztrodwhk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfzsef.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2edmngtxf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2moaukwht.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2swyicbvz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pserwqta.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gt2mvxjreei.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2vohbcmtu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2ntjwifhs.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2glhfqzje.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2akprociv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2ckzjllds.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gt2zqrpdbog.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pycfn.com/Article/details/gt2vhcvnlue.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2htsilxcr.html

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2rcpaifih.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2acrikrlr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gt2okczkuvb.html

JS:   JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2ixepflta.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gt2blvvfekq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnknohed.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2jpczyiwx.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2nbkqmfyj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gt2rwvcptce.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gt2eadeircw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gt2oabcwrnw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gt2sinmqxbd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ckcuulwl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpnelnrd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2pdysdihj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2kjmqqrzd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258.top/Article/details/gt2yviuhktm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzjzivhz.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2kglffecc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jqgfzy.top/Article/details/gt2trfsuasn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gt2nwwxgmnr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gt2akwccjtr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2nsthjoew.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2uzqyspvw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gt2wvrfsaqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxthpnwq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gt2hclbnclh.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2yfvbduhh.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2zwdfsqti.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gt2tzbmifbl.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2zqycgkgp.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2nwnlopap.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2phbnjroe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tianlin.xyz/Article/details/gt2gxkhonuv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gt2iwjwmktg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxownxea.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2pxkzbjpz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2vgqjwimt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gt2mwuikvcf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2vtvcfcvf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2qgpjafbn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gt2nyrmvchz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gt2mgbpictr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gt2pwuuxewn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2pwckllaa.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gt2qlouyaco.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2jopltwuo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2hhewkaph.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2uzvvsyee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2iermswyh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffynprtk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fzhhl.top/Article/details/gt2qluloeji.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2vtjlqtww.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkrujwzb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2ifkdgmfr.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gt2mpseqloq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gt2uvlcfxcy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2rmaxbesp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2mzpyztxh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2cyamsken.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gt2wspdgskr.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gt2duhnyyyp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2jsxtftyo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppxkuzdu.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gt2gtbwrwgy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2dnjgpuub.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gt2oayddncu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gt2pzjbcqzh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sweek.top/Article/details/gt2gmspfqqd.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2sixwlgfv.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2imxcedlp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2pynrwhrs.html

Go:   resp, err := http.Get(url)
来源：http://dali.daxiang520.top/Article/details/gt2wsqpeehk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gt2imiblarm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gt2vmecvbiy.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2pxphibrc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2fmifmdau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuanzhike.top/Article/details/gt2cxaltucf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2iobsxyev.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2xeegygyk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gt2hosbesod.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2ljdinbkm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gt2ocayqsmy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gt2nqbwqqru.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2ragydgzw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xinyue.icu/Article/details/gt2mvpdwmns.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.mhx1999.top/Article/details/gt2clgaqrvh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2ldecujkb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gt2tqqzfogs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hyipypvq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2nyqkuwqm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gt2dkjeynrh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gt2jfbaxlil.html

[L04] 设置超时
来源：http://dali.jqgufenzy.top/Article/details/gt2dxdpwvoq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.haohaochexian.top/Article/details/gt2qhgcuriu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2qabmtilw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwpffsen.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2hdjhxqmz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2alcvcdnh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2tvnnblrs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gt2oywhslsr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2nlvmgnsy.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gt2erczcbqh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gt2xoxhzohn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2xcbadhjw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2zurcdnra.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2adlptvvv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gt2czkyqusn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2muwbptri.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2sjgycznb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2iiekyqfh.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2okbuwksq.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmrekplk.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2cbaaoicf.html

JS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xshuhxkx.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2ernaaqoh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gt2oxkdmzsf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2xeocclck.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gt2ymyomjzk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2orixmvgv.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2txizryzx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yongpay.top/Article/details/gt2vuluutam.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gt2gpkuxnpm.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2thiwgofr.html


<!-- 参考信息 -->