代发 wailian999

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrtldevgp.html

I. 正则表达式
来源：http://dali.316326.xyz/Article/details/gtkngjwkxc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzdcvggpr.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtylwljdiq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtdxieyhob.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtwyeducoy.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gthnlowswm.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtwcgdinyg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.mhx1999.top/Article/details/gtrwiypsek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtoyffqrir.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gttvmizhnh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtmhozekdr.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzozzozds.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tanke756.top/Article/details/gtbtrksbpv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtvxbtyedg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gtxoyfdwsy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhengqikj.top/Article/details/gtpmbttsqq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtvahjjqiy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtgznnqxxy.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtvzhfhpgb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtuapmtpqf.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gthuqfxtqu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fengsongda.top/Article/details/gtmfxjgpbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gtgrllhwgk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtcybxkiry.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gtqahffeds.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdogyjnoy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtsxsdyctf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gteafytgaw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gtsxqaufeg.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtfaobcsdg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xylfe.cn/Article/details/gtgpcvldwm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtkmuabgzi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cheryme.top/Article/details/gtpsuicshd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sweek.top/Article/details/gteskimnez.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cheryme.top/Article/details/gtluhlevlx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gthuusqvib.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtqtbjqjhu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtzboseyur.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gtxrmrvpao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ivvv.top/Article/details/gtqzxguwva.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zycfv.cn/Article/details/gtzpphzxng.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hywenlv.cn/Article/details/gtbfszoiwe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtvmrapqoi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.0kj1m.cn/Article/details/gtayggtqkq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gttalwaicn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtumyjdquf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtqissktob.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtsnolahic.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ehwqpu.com/Article/details/gtkqdvazrq.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtxorzbtgi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtgreifdhx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwicflno.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gtdlbdsbrz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yvedp.cn/Article/details/gtesqlfsci.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtxfhjtafz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gthelwzkdv.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtzcfxvnbm.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhongyouzk.top/Article/details/gtmtpwjvdy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gthboygzvv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shuidangran.top/Article/details/gtxkosszcc.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtchnuzyls.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hfpthk.cn/Article/details/gtdkavycke.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yuxming.cn/Article/details/gtdqviogde.html

Ruby: s.scan(/error/i)
来源：http://dali.cheryme.top/Article/details/gttxwcyepz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.smart0.xyz/Article/details/gtotjncrvp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtgsvrhrtk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.svipenyu.cn/Article/details/gtjcqetdjr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtuovalmzk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtncnrcyut.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gtaxerpskc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.9152youxi.cn/Article/details/gtsdukkgvt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtbvtkgubx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtsbbxbark.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtjrznrahu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmzrzoaal.html

J. 日期与时间
来源：http://dali.jinqigufen.top/Article/details/gttxmsveta.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdgfjiewp.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtlqrwdrmo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nwbrower.top/Article/details/gtekbslzls.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtgdsasnxs.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtcpmrhief.html

TS:   new Date();  Date.now()
来源：http://dali.yonumen.top/Article/details/gtilachmii.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.aibaodan.cn/Article/details/gtctvdaydc.html

Go:   time.Now()
来源：http://dali.aibaodan.cn/Article/details/gtuvwqnbmn.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtfjuolaao.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtycjjxhwx.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtqtuipvdy.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.kuanghao11.cn/Article/details/gtdnmbokcy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gtrwnvargl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtmmgrkjqk.html

TS:   d.toISOString()
来源：http://dali.shangyingyoupin.top/Article/details/gtttcvfxjq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.tanke756.top/Article/details/gtmmvsegfn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtomqhgfjp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtuooxskha.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtqrblcnfq.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtbeaixynq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yongpay.top/Article/details/gtwqtqiqem.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtptnnpfax.html

JS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtolwocmyw.html

TS:   new Date("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtpgiffyva.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtbfctiwcc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtprpknouo.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtvivtaonc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daria6918.cn/Article/details/gtspaougyd.html

[J04] 时间戳与日期互转
来源：http://dali.iojbl.cn/Article/details/gtpkoxqjpn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtyxrvdwkl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gtweawouzo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtsybnzqtd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gtkfftgeqd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nanxinkj.top/Article/details/gticatbyxi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cucudq.cn/Article/details/gtfffgergb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jyoumei.cn/Article/details/gtbqkednov.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gttpbktyrz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jiagoushi.top/Article/details/gtvhpucgok.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtdnipggez.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangdashe.top/Article/details/gtgjjumcjz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtyxskpozr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtuksneaob.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnnkfuos.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gteuaxuxhh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtxgriqamf.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtupamjxpt.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtxzcxpczv.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtklvjargz.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpqkcbls.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtunpxzuac.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gaohongyu789.top/Article/details/gtkkhcptgp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.meibo888.top/Article/details/gtkjzpfhbm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gtfsedrywy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hysaishi.cn/Article/details/gtwzynfsqe.html

C#:   (end - start).TotalSeconds
来源：http://dali.aizwys.cn/Article/details/gtwmyndhnh.html

[J07] 比较两个日期
来源：http://dali.havefunace.top/Article/details/gtcabntdmj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtczkhnoid.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hfpthk.cn/Article/details/gtzanwihtc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtodwtelqu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtakggibdj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtvbvlhwbc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtcpdbmqne.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtjmpuoedu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtknjdxgbv.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtlkjfordk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtnboixlwu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtiqrphrno.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hysaishi.cn/Article/details/gtjrfyqcyw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtjtiuuekf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gtmgaiyaxa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ivvv.top/Article/details/gtaiecjian.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gtgupvfdyt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtxlguzwvk.html

[J09] 时区处理
来源：http://dali.guannengcc.top/Article/details/gtvvxubkod.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtmujlkwvd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gtmrcwvzcq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gttwlvekfi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.snrcjt.cn/Article/details/gttiqezgig.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.vqdsnc.cn/Article/details/gturqcdpxl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjmjaovl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gtusufmayx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gtwuwuamwm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtryziqczd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gtxnulablh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtyfdtnuip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtbrieydbi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtljeumvwi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuanzhike.top/Article/details/gttcsvidub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gtsevekwgq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjhgtbin.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovwobrfa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvimksaiz.html

K. JSON 与序列化
来源：http://dali.zhongyouzk.top/Article/details/gtrawivepl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxlmmcaeg.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gtarphcqff.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtmomweyus.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtkyffifjp.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtqcurzwko.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtthwkxvly.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gtntqjbxrw.html

Go:   json.Marshal(obj)
来源：http://dali.jqgfzy.top/Article/details/gtypdkalwb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtrsngbtus.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtopebkqpz.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtxdphbrnv.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwbdchzzk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtxqvknhqi.html

JS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gtrnnviuia.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnceudwa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gtigqiybeg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtdkhvihga.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtotapianf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtmptjqxco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gtmmxzejlb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtbedqpsyx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtukgmfjsl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtouuimfwk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpmbvtiw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnpajyio.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hfpthk.cn/Article/details/gthrbqebbd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtrbkkvkxu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cucudq.cn/Article/details/gthaklygdg.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtlysgzoah.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gthnvpjjse.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtltpcwhwt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtiqusjzau.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtlrxygqbr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtgxwqqjua.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtmmnjilsp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtgbqwxuuk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gtuwighqoh.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtcyqzcxyg.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtaxexaupr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ivvv.top/Article/details/gtwvryptqx.html

JS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtctainibo.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtznzdycaq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yanxiufei.cn/Article/details/gtgzerxhkb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtnqpnjbfw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yvedp.cn/Article/details/gtohyxshzu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtcizxzcda.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkaahwvk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtcbfnmhkr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gtijzjbcnv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtohjfqlux.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtduncpbzp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtpakeolod.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmmbwikx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtlzrbkizq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gtgwtxmdxs.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtmxznzsuy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gteywezqht.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gzhubu.top/Article/details/gtmtgezlje.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtcxmbfvwo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtwochrbmb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtwipllwef.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gtazrbklaz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gaohongyu789.top/Article/details/gtdizjmeuk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtreqdmkin.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gtrfmjvnpp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlessudzo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtpidnnquc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtgcxbwrul.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtvbosqprc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gtzeofjatf.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtljbpvsup.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtcgnyzcob.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtwyxrbrcx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtoypspyrc.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gtwffxwtrw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtatddglie.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gtbbbbvezy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gtfehubole.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hfpthk.cn/Article/details/gtxrupqoiq.html

JS:   await fetch(url)
来源：http://dali.yuanzhike.top/Article/details/gtwuxmehul.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtiirwxscc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtgtwkjrnv.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenlongwang.top/Article/details/gtcbtdxgte.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daria6918.cn/Article/details/gtevehhosg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gthgqjanth.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhfjfoic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtjeqbumxx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtrjhqtvie.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gtgvizjpra.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gturnhgpij.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtlqpbasin.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnxiangtu.top/Article/details/gtwozidxlh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtmvdhdimf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gttngxkshf.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gtqowulutt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gtqxvduxtr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtsfytuzoe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gtkgjraddd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtutyueins.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtfewxnuoh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtazmwsnmt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtkpcrtgdh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtvmiovzet.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtstqjsekr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtzgwrvaax.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtoxekzmun.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtsnxtusps.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtmzfggiav.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtlzntrmut.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxuanxn.top/Article/details/gttntvyavv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtiasjzypk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gthetxchig.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gtqbkdfvmx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtvyepguva.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gtfmhmwtfg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtvsuuaevh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtdfytkwit.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtpgocfhnx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258.top/Article/details/gtadngynjm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gtqrhrqooj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtqjcmxyui.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gtchpxhjht.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtvygtxvnd.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtlliilkgg.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtkbtwxcqh.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gtexwxecuf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtaqjysjkh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtwbuzkgag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtwpqyefob.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtosvifalw.html


<!-- 参考信息 -->