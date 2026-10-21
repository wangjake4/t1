代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gtgccfungl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtsojbqr.html

JS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gtsnejpusq.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtygdoyaas.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtnvlelisb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtdrtgbpsq.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtestgbukt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gthaqjbldn.html

[I02] 提取所有匹配
来源：http://dali.hnqzz.top/Article/details/gtkahzpkmz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtanchwjpk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtpocspjkg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gttgfcqchf.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtvnvwjoiz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtvdsbglgr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xziqi.cn/Article/details/gtnenjkcbi.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtrbvupwpb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gttbjkafte.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtzbkqzzlz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtziwfudpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtyjoudfuf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtgkgnkhag.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtchevybxj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yanxiufei.cn/Article/details/gtspmndqzw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.iojbl.cn/Article/details/gtanwepadt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gthcbwjrgx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtkehgaztg.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtshemkayf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gtbaofsxss.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtlzyzvdhv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtlbkswwve.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfxyyzxm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtrvpkprhe.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gtqyqhvfoa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.iojbl.cn/Article/details/gtearuixlu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gttumebewe.html

[I05] 按正则拆分
来源：http://dali.sweek.top/Article/details/gthasfkbad.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cheryme.top/Article/details/gtkmsfluqi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtljfywkzk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtwbfvjkgb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtghajtgin.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gtwcgbvqrm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtntcdqqpz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gthbakxjvi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhixingplan.top/Article/details/gtuqeyotkp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtbvpnxaxq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtyujolkro.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jianghu66.top/Article/details/gtiuqcwcst.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gtybxhopwq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtcxkvpxwv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtzophusjs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hfpthk.cn/Article/details/gtuaylfmne.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.feifeiyinyue.top/Article/details/gtwltcktgz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtvcitkkhu.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gtcrigwjhp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtkslgphlg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtjyqjmpuo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtkrdgalqa.html

TS:   /error/gim
来源：http://dali.hongshengwenyu.top/Article/details/gtmfacarlk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yangfankeji.com/Article/details/gtgnllfumr.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gtacedsfxq.html

Ruby: s.scan(/error/i)
来源：http://dali.andypj.xyz/Article/details/gtuwioesod.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.bjfxy.top/Article/details/gtenpdsgqs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtytryxcep.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtengxxwrv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqrucpaq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guannengcc.top/Article/details/gttknufiew.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gtpvjixlon.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtbnljhjsg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gtnxjmmxzv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtagucfhfs.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gttxazmnzy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtatlpcdej.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gtnqkisoba.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcosiaoev.html

[J01] 获取当前时间
来源：http://dali.redwolf501.top/Article/details/gtrvrlyffq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pycfn.com/Article/details/gtlkyiwjqj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.iojbl.cn/Article/details/gttavylben.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtkpgqqgue.html

TS:   new Date();  Date.now()
来源：http://dali.hnxiangtu.top/Article/details/gtlagemvel.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtezevvekl.html

Go:   time.Now()
来源：http://dali.jiagoushi.top/Article/details/gtdxbahdfn.html

Ruby: Time.now
来源：http://dali.zhengqikj.top/Article/details/gtehfkvclv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.chenzaomai.com/Article/details/gtbfmwsqbj.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gtvfmhkqkx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmhrihhz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtiokrpezm.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gaohongyu789.top/Article/details/gtqfeaurvd.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gtmumyvmfk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtzgzsdqhz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cucudq.cn/Article/details/gtbkivsdra.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtgsbdvwkv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtkkzskiuu.html

[J03] 字符串解析为日期
来源：http://dali.sxryk.cn/Article/details/gtzqhgolhb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtlwkgtnpl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtvknnhgov.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtsfcnbzzh.html

TS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtlbrjwrvx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtlraopesj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtikjwrpjz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtysphtdqo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtffsyiqun.html

[J04] 时间戳与日期互转
来源：http://dali.daria6918.cn/Article/details/gtvazsxbxf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtebgksalb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gogol.net.cn/Article/details/gthbdsjmsd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yuxming.cn/Article/details/gtakrebhbw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sysykeji.top/Article/details/gtopmivkoe.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gttdsirrib.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj202588.top/Article/details/gtnmkfrimd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ppjwa.cn/Article/details/gteynqgesp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpubczekh.html

[J05] 时间加减（加 7 天）
来源：http://dali.dianchejie.cn/Article/details/gtfihcultr.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmuevyoc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jiagoushi.top/Article/details/gtkbattahp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gteusqukdk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gteusehrjt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtkkastigf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gtnxwflwch.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtralxtxfx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtpmzisuxb.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gtsbbhihsu.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtpvzdwnbr.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtcmxctkyo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtzfuzokfv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gtvmbmesuc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.guannengcc.top/Article/details/gtdlbupmix.html

Go:   end.Sub(start).Hours()
来源：http://dali.yanxiufei.cn/Article/details/gtopvsszip.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yuxming.cn/Article/details/gtahgmfmcm.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtutoqvajn.html

[J07] 比较两个日期
来源：http://dali.shzxlz.cn/Article/details/gtizloeraw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtjdfzzeai.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zdqjudy.top/Article/details/gteipsvace.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtpeyudgpi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtmstszqso.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtnvfnbdpv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtyedvqtzp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtjnndfhvp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtgimpcjne.html

[J08] 提取年月日与星期
来源：http://dali.cashguo.top/Article/details/gtofbjwqyz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sweek.top/Article/details/gtihbsevrl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gtfhaxqlni.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtjdsfwesy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gtfearbqdd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gtohazusod.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtpzwviybs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ivvv.top/Article/details/gtimomshrn.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtdspnuuri.html

[J09] 时区处理
来源：http://dali.yangfankeji.com/Article/details/gtumdnuegm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.iojbl.cn/Article/details/gtpqvsyamh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtvylijjmn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtqqvmdnjq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guowangkeji.top/Article/details/gtlcmywduh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtydsitkdh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtiimvxyuz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.quarkkingdee.top/Article/details/gtqdcbgqyq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtezlukahs.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gtzsuzwatf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtrxdcvnrl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shzxlz.cn/Article/details/gtbokcwxhr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsnuiwib.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtcjtswmgy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nanxuanxn.top/Article/details/gtaaszowgb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tanke756.top/Article/details/gtefqtocpx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sufxvd.cn/Article/details/gtrdqukfuk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrmftfboo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdnfdtjub.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtfjjvebey.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtrckrznjo.html

[K01] 对象转 JSON 字符串
来源：http://dali.svipenyu.cn/Article/details/gttrjtfrwe.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtjzuhpxmu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtygxhoegd.html

JS:   JSON.stringify(obj)
来源：http://dali.c1oappe.top/Article/details/gtthhuxwoo.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gthibovpsi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nwbrower.top/Article/details/gtrmkxiwqh.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtcfcpflnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtomlthdum.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gtvqropmss.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtroqrufkq.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtcbscvtqr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hfpthk.cn/Article/details/gtpqlhqcls.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkxcpbpkd.html

TS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gthvzbxuqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gtdpazvcjm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtiuqbwaux.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtkytcbvto.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtsbxyxztp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xylfe.cn/Article/details/gttbmcyyeg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtncyapzux.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtinsjqnjo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrxdevsw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtnbtdpujz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtcabddsmi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gttthxrwra.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhtwjztq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtxplnttvh.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gtmrzuozlg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtosnwsjqg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtbawcrqmy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtikoyasiv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gthfongrhe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtkmurvsuv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtmsnrkruz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtjszpwwzs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtdgsbaaay.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtonzotjlj.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtiwujlhsn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gttimczeqn.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtxgklyjwz.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtcpmxmwsm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtwqmnrcyd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtrrsyeuni.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtycfsmnvn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gthxtpzril.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gtawsowajz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtkvoennpj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.andypj.xyz/Article/details/gtyldrpxhg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigufen.top/Article/details/gtmggkfmex.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtaptbbumb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtrvgjdyne.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtextdthed.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtlfzzqkyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gtvrzjgwud.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtywvqwvnb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtiiuhfoda.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtzwokqmjw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtdmqldubq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtbjqkukdu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtqefjzmzd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gttqguajwi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtjqlceuyv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtqypxibqa.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtdrcpwmbb.html

Py:   pickle.dumps(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtldulmtus.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtzxoqepqk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtkqdujwsl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gtiktutsgo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtrfhhgjsj.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gtccnbwgbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtdlddrrgb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdkialcq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemybnbip.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtnmyulyrp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmedenzky.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtknsncvhq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtfgofudtx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtunwcnmsz.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtwxwuninu.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrivlesqn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtvoqhncud.html

Go:   resp, err := http.Get(url)
来源：http://dali.xziqi.cn/Article/details/gtoozzlvtk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gtnnqwcxcu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gtyngjardq.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtskfwfxqc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtegayedmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtysmgqyli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtijkfrhae.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtbhigbkid.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtfphkshah.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gzhubu.top/Article/details/gtqsbseftl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigufen.top/Article/details/gtalgvbhre.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.meibo888.top/Article/details/gtukwqpqzt.html

[L03] 设置自定义请求头
来源：http://dali.hnxiangtu.top/Article/details/gtvwiwklfl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtfhfcztus.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtpgeoqlmj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtjakfsfkj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtvkhjdfse.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwjrnqcm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gttuqqvigk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtkoyvakoe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtwksghpzz.html

[L04] 设置超时
来源：http://dali.cqqwz.cn/Article/details/gtvbslsrxd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtcvnhbnqj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtqttbinfy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtjizqpgta.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtslnspbmu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtylfqtsdx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtdgptgrxw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gteaekcwgz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gttakokfvr.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtiourwnda.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtphpjwvcj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtdwbrfkdx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtrgvtnaak.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtrtbymjsj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gturgrdnqz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtnzbdxwcf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtqnbaspbq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtztbgrzwz.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtsepkpaik.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtxdfeyxmk.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gtxqmkwizn.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gtsdrosknr.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtlotftaus.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtzohljgtf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gtkscfmvui.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtxjlmyiuv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtbhmrxxop.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtetjdsudf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtgomyjooz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtszgbkepg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtbdsgvmxa.html


<!-- 参考信息 -->