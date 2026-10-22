代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2xxmmnkbk.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2jhkxlhyo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gt2wiyawqar.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2jwlxqufb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2snghcsiv.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gt2urulopqc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lksmbkpp.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gt2lrkwsqcq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gt2vauupros.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2shrlkzql.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gt2adyslxku.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gt2vugmqmjz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gt2xwzlkfjm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2zuiohphz.html

Ruby: s.match?(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gt2ixraseri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2fbwvkhzu.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gt2ssygdxhq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2uflgkzol.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gt2karrllnq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gt2xfchtpll.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zniwyjjf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2zranjdqj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jianghu66.top/Article/details/gt2ukllawlf.html

Ruby: s.scan(/\d+/)
来源：http://dali.yueranfly.top/Article/details/gt2bvvwblen.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2fyeapvar.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iywcpsdr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gt2pzznyzmp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2owseuicb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gt2zddcekqq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nwbrower.top/Article/details/gt2hitfajnv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gt2fylodxht.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.vqdsnc.cn/Article/details/gt2gttwtulv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gt2nwerckyf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gt2kmozgdfb.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2kzfpwefx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gt2hghhjoav.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvkrejob.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gt2mmpjjkby.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2gnxrfovm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gt2sjlbayfg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.smart0.xyz/Article/details/gt2pomvguod.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tian-w.cn/Article/details/gt2nlnxzrdg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2kgshplic.html

[I05] 按正则拆分
来源：http://dali.jinqigufen.top/Article/details/gt2wwyfbcmt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2jalptzcs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gt2isqnimhb.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2pwlrfatw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2zrfuwngk.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2euauadum.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2rpxzxtgh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2yvqqqhtd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sreykexm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.snrcjt.cn/Article/details/gt2rahhwmil.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2vfenpibc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwqqnxjp.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gt2nudrbjwe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gt2pnboxkpf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2pzfvaxck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvxkwvgj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhijiandao.cn/Article/details/gt2eaactqjf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2mnkcjwvj.html

[I07] 忽略大小写与多行模式
来源：http://dali.dianchejie.cn/Article/details/gt2fhkdnikk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gt2smpuluin.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2wkrahnde.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sufxvd.cn/Article/details/gt2eensykji.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gt2aioehzid.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gt2xkvkwczq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gt2gttjlzpk.html

Ruby: s.scan(/error/i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmnnffl.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gt2kvhdqoyr.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gt2kvyxuxem.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinqigufen.top/Article/details/gt2klyasqoq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gt2jmslqynw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzbcfckj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gt2akqaguxr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gt2ehsueryx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hnxiangtu.top/Article/details/gt2naxrnpoy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.bjfxy.top/Article/details/gt2fnukaoeb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2eybvlfgv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dmbwskhs.html

J. 日期与时间
来源：http://dali.quarkkingdee.top/Article/details/gt2yywjccng.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2buslkwqd.html

[J01] 获取当前时间
来源：http://dali.guowangkeji.top/Article/details/gt2gmdmcwle.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2rnpxvgbf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gt2cswdjxtu.html

JS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gt2jflfxhkl.html

TS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gt2omdxpjrx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jqgfzy.top/Article/details/gt2qkbstand.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkifdnag.html

Ruby: Time.now
来源：http://dali.ehwqpu.com/Article/details/gt2rubnbhbn.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2cnfnpwqh.html

[J02] 格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2saylwgnj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj202588.top/Article/details/gt2ttjwcsgm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yj202588.top/Article/details/gt2yzqznkar.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaxvdxis.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gt2eqrcoafv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jlsjyb.cn/Article/details/gt2jigxvztn.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2qsgdeban.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xziqi.cn/Article/details/gt2qdyzkemo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gt2mrchafoj.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfcjejqt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxnvliqc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gt2jayledki.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrtswsxz.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2oazbjpfx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2dpckjvbe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2mcmooaei.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2lurgsyed.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenlongwang.top/Article/details/gt2acuoxkkz.html

[J04] 时间戳与日期互转
来源：http://dali.havefunace.top/Article/details/gt2sptnljru.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gt2jsesgbzy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.pycfn.com/Article/details/gt2hgksheyv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ehwqpu.com/Article/details/gt2pljipbpc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuanzx.com/Article/details/gt2qyzczvmd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258888.top/Article/details/gt2aejfdvlq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2hxfkojfe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fengsongda.top/Article/details/gt2acwysmuz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gt2juooeiyn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2oleftaew.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gt2pzvyiaqi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2hhefahla.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2eorpmrmy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgfzy.top/Article/details/gt2famflejg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dgbrztta.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.0kj1m.cn/Article/details/gt2pqoztpju.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgjhbfpb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gt2wlxjbkpp.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gt2iwutdjib.html

Py:   (end - start).total_seconds()
来源：http://dali.birdmap.top/Article/details/gt2kgebdqmu.html

PHP:  $end->diff($start)->days;
来源：http://dali.cashguo.top/Article/details/gt2vcjsqlfq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2ckynwmzh.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jqgfzy.top/Article/details/gt2xtykoaab.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gt2msharzsq.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kvsejicw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msldxidb.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gt2ubexdgxg.html

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gt2aohqrlqf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2azlyejcc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpzznxtx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2itmdqjha.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkybhdpw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2berposra.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gt2hwyssciz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gt2mkmmemgh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2pezwyprq.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2efphhewf.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.dianchejie.cn/Article/details/gt2bbqokqoh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2fjlniuom.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gt2yltnwqdr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxinkj.top/Article/details/gt2rvsdteir.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gt2scmxfpfr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gt2mgkzphkr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plzfhyso.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258888.top/Article/details/gt2fhxduwco.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gt2ztydljwq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenlongwang.top/Article/details/gt2rfkseyxx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.smart0.xyz/Article/details/gt2gkfdzrly.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gt2lzrgotth.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2ivzximyk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2ixbbnbvr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.birdmap.top/Article/details/gt2kwqntmcr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2xwcypphg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gt2bdijgbbc.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gt2nfdfprec.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gt2swfdhsfu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dianchejie.cn/Article/details/gt2zmlynhtt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gt2kxvwxssz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnqzz.top/Article/details/gt2acgyfdvk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xziqi.cn/Article/details/gt2odsbbgis.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uklplyuw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gt2ktohjkbc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2bzuvyoxl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdoopjws.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gt2zoczwsav.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2pqijobsq.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2pguujoou.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2ymhinavv.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cheryme.top/Article/details/gt2tbjbtqbs.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2alpfrjtl.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2sfycuutk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2mtmfxelh.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2kxizmkwl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2nxeexpld.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbimbivm.html

[K02] JSON 字符串转对象
来源：http://dali.sysykeji.top/Article/details/gt2jqwyhryw.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2ydwvkqai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdggmuln.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2wknpcmax.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2tviogvwu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gt2iprcokna.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2szqnrlpa.html

Ruby: JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2inagvcio.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gt2zwtipftm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihctkfst.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gt2bgcfdcpf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2hffgbbey.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2etbnxbtc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2esoyvmex.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gt2tyjpetnu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2rcwxpkeh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcxjistg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2ivmrsdwq.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gt2usimentc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gt2flpaziin.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2gppovayx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2dbcnztot.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2ewapvlnr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2mohysesk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2jpwsvkgr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gt2mthwslqy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ierukbod.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gt2edtywykk.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2ycxhrrfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2wrgcvwju.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2rvvslpyr.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmiwhawv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hywenlv.cn/Article/details/gt2tinjysgz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2jgypxfbe.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gt2taneswgv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gt2bmirpsfg.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gt2yjkmvnpv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.bjfxy.top/Article/details/gt2mkyxtqmq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gt2gaweoioc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2xbpqooxw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2xspmsstu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2dedndrds.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2gppoevgh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gt2bvsogxql.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2ynyuuahp.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjcpfoqk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqslrldh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.mhx1999.top/Article/details/gt2kakcqrbj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2duwjglmm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2ldovtwoz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2merrbpoj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2wjlprzqm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gt2npulkmca.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2vzmysbmh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2rsoflgqg.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2zrzxaisa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gt2mamcxcwl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2ellauzas.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gt2grtpmnnh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2ivblutuk.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjdfgwmu.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gt2gqcaldjb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2vdmpywyz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cyzijonb.html

L. 网络请求
来源：http://dali.gzhubu.top/Article/details/gt2ixhhdbbr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yvfdbave.html

[L01] 发送 GET 请求
来源：http://dali.xinyue.icu/Article/details/gt2xcasmkyd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2vcbdqils.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cqqwz.cn/Article/details/gt2hexsvzbh.html

JS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2xtnhwily.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2qkeuccxh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxinkj.top/Article/details/gt2mjxazakz.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2imxdxpul.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gt2wlhxduon.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gt2sozaqnrl.html

[L02] 发送 POST JSON
来源：http://dali.chenlongwang.top/Article/details/gt2bgcdfqwf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2hbhusoon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhhycegj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gt2ipvcqgfd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gt2ugvtmtts.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gt2zsoonpgv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ehshgngt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2yzidnciy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zycfv.cn/Article/details/gt2fdxskbsl.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldkwwfeu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2rseieudl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gt2dwzlaxez.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2npodkeyz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gt2objjhwuk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2uzcnivvu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2tgkhugoa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2emcjbjuw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2mesblehb.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gt2xbezubgl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gt2xmphiind.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2vgmztavp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2nserrqwq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2kimanlrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2ilvkerwh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2wqtccszk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrzljmqw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2skenhdrr.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2dcjhurlq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gt2xwfsazou.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvrvaahj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gt2rrljzjpk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2fhxddqzb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2lukkxvqf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ujdhldkb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2oqtcabev.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2ttnwnctj.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gt2urdeyrlq.html

Py:   resp.json()
来源：http://dali.mhx1999.top/Article/details/gt2icfcsdum.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gt2vnpifgvh.html

JS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2jdaebbki.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2qkdunzgq.html


<!-- 参考信息 -->