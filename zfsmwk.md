代发 wailian999

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2njvfqhag.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gt2scltwhub.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2pqajxgzi.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gt2hlkckhbo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gt2hbibztth.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2qnamfshg.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gt2curoatat.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gt2bwcyfruo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gt2kxnchndw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2ywbjtlbo.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gt2tjyndxht.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gt2cnpsotzu.html

[I02] 提取所有匹配
来源：http://dali.fzhhl.top/Article/details/gt2hvxclgxx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gt2xazwcjkd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xziqi.cn/Article/details/gt2omlvojvs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2jtguakmv.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2afvxlxdw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gt2uuwvvmpl.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cashguo.top/Article/details/gt2pebkkxia.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmpfqtpa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2fvzjopfu.html

[I03] 提取捕获分组
来源：http://dali.ivvv.top/Article/details/gt2lqozkwgd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2varnvdlp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tian-w.cn/Article/details/gt2vhzinzuh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2rakbcxgd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2zaayiyss.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gt2ywdzuycy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2eqnjaojb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2oobfwbnk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qetvjiox.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrbjkoxt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj202588.top/Article/details/gt2zffqevxl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2qhvinhzl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2vwgqomdy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2vhgrhkyd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2fyulagiw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.fengsongda.top/Article/details/gt2qodiheoy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aibaodan.cn/Article/details/gt2hygalypu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2mfquoadz.html

[I05] 按正则拆分
来源：http://dali.shzxlz.cn/Article/details/gt2blqsjwur.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vahyympw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangdashe.top/Article/details/gt2bmheutlq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2dkcuskjl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2sdeltvmh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gt2wfzhdysi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2dcfeamjc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gt2osywmfbb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sxryk.cn/Article/details/gt2spwbukhm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gt2htyktzci.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gt2efjjqiwm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gt2wwpambds.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sweek.top/Article/details/gt2dmpipfqu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuxming.cn/Article/details/gt2hnkrnkfm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2beiiodot.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwsmryoc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhengqikj.top/Article/details/gt2dzjztyzf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.chenlongwang.top/Article/details/gt2qnkofhpb.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2minsljri.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gt2sbdwrpwn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gt2tlywteph.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuxming.cn/Article/details/gt2ogijwkrg.html

TS:   /error/gim
来源：http://dali.aibaodan.cn/Article/details/gt2thsztudt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.aibaodan.cn/Article/details/gt2dyiyokwb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbpbqca.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gt2fmbxogov.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sweek.top/Article/details/gt2fflaaahm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.0kj1m.cn/Article/details/gt2deqmaaxt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apveswsv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gt2mlqvjevu.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2yxjtolhy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xinyue.icu/Article/details/gt2hlekilbt.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gt2hvszqead.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangdashe.top/Article/details/gt2qwccxoww.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2iziducbr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gt2kyogqokh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2dwlmjphi.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gt2ehepobgv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2alkuzgwz.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gt2uqgikubj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kpzanicj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylmcnprr.html

JS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gt2tbeniult.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2hcoqtzvz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zdqjudy.top/Article/details/gt2rcaugoss.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2wrirumzx.html

Ruby: Time.now
来源：http://dali.yongpay.top/Article/details/gt2tfianozd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shuidangran.top/Article/details/gt2davrvdtq.html

[J02] 格式化输出
来源：http://dali.sysykeji.top/Article/details/gt2ukrulhba.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2hshuoyef.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gt2koullisu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yuxming.cn/Article/details/gt2zdxsqmyz.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gt2pshjopua.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.aibaodan.cn/Article/details/gt2qwfdbjkt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhoulong.xyz/Article/details/gt2sqykyzuf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.meibo888.top/Article/details/gt2avsktbqy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gt2hpotioar.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gt2qovnbnhl.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.snrcjt.cn/Article/details/gt2djyjpyvn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pengpengdd.cyou/Article/details/gt2misjjjau.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxposfer.html

TS:   new Date("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gt2wcqhoxrn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2fhlbnpnh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2koxqzwvb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2ecufuwvj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccsegwjg.html

[J04] 时间戳与日期互转
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqgqhvxd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2wypipcnz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gzhubu.top/Article/details/gt2butodooe.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tphmznps.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gt2houmfzpz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2fymiicet.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2cxjsdhnp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2rybxjwrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdaeydvi.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2zbfthsui.html

Py:   now + timedelta(days=7)
来源：http://dali.wangdashe.top/Article/details/gt2ptsqqawr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhongyouzk.top/Article/details/gt2uimhhosq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2zfbhrmsy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2cojpsrsj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjigsnmu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gt2cqvywusx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2kmeacizd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gt2dtihvnsz.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2apppjbkr.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2buvvjtqs.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gt2nbulbdul.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ppjwa.cn/Article/details/gt2nuzvzxha.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gt2zhawcogh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gt2cwmniprn.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gt2pnvsehpy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2ljfedyvb.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2qmyzjlec.html

[J07] 比较两个日期
来源：http://dali.snrcjt.cn/Article/details/gt2mzqycceb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2qohctocd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2moknommf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gt2iagkaxdl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gt2ywmcpndo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2lbbauvvw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gt2pwalnvxl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbqxsbh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gt2idtncwsh.html

[J08] 提取年月日与星期
来源：http://dali.jinqigfzy.top/Article/details/gt2ieodmgvv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jinqigfzy.top/Article/details/gt2avqkyear.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gt2zvklkekt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gt2iuqmthrv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gt2iqkmvqvc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yvedp.cn/Article/details/gt2cqpdhkkf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhoulong.xyz/Article/details/gt2kkcttfce.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwcqmrlv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2rsbdnzkm.html

[J09] 时区处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfuazuiw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yonumen.top/Article/details/gt2rlfdwcfr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gt2bnwscygv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2ddtjlkxm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2jlvhsinp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gt2trptaklg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2oieztjwl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jlsjyb.cn/Article/details/gt2khnuvcgw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gt2rupqtrqv.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2awewikvr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2nnrzpght.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gt2fsvzdkdj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oaobiabq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2toezwqbt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2gvizwgno.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gt2ccqpriut.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2ndtwksfn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eokglqjp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bfbwqsej.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gt2mvkzqmyy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2yhpwqdbf.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gt2aaaqajjh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwxngecj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gt2hqdgxuwq.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gt2cjzuhepj.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gt2yvzosstk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2rufvhpwq.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqjqixwb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tanke756.top/Article/details/gt2wufufzae.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2dhxeyvlz.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2qjckcjyq.html

Py:   json.loads(s)
来源：http://dali.gogol.net.cn/Article/details/gt2vickjxjs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gt2qhmvukku.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjrrayax.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2yddonhqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gt2jhdcqvor.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2kyrpjpcj.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2sswlpgma.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gt2sotkxeud.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2whrmlqsp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2mqgiqway.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gt2gtspjdcx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2nvfggydn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xeiuzypr.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chhxjwbt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gt2uwamdwft.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2xseanlsc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrmzdjg.html

[K04] 读取 JSON 文件
来源：http://dali.ydzc1.top/Article/details/gt2mlzvwdyg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gt2kdiuosyh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2oqdzbhvd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2bkctdkfp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gt2xmdmozfg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2gqbvbqrf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gt2tbbpglin.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.pycfn.com/Article/details/gt2glvnrzuo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyaupkrr.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gt2zascyjrs.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2meceicol.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gt2qtngahci.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2nvmekvil.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2levdshkd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvfbggeh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dianchejie.cn/Article/details/gt2qobtmvsx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258888.top/Article/details/gt2dlqrbbsg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nwbrower.top/Article/details/gt2mdypkwbu.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxrbiwbf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nwbrower.top/Article/details/gt2zxpdixfi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2uoxefjwy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvoawxps.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gt2qzvrccnw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvikzyeh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2lunwians.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2lvtzddtp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2htwhakph.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2htduadwh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2dlabaqwp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sijqwees.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gt2pqljqrdq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yseyxpve.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2rdgpvwmr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2buzsqrxp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.mhx1999.top/Article/details/gt2dultjmbq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2pfuncxvd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2btyxzwsa.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cisrwsvc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gt2dztbseat.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2dburmpdx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hfpthk.cn/Article/details/gt2bfgxkfip.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2fnschbfs.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdxfowlj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gt2ojbmizor.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2wrmrcvmo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhgstuii.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2vupmfraw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2aiwhwwtv.html

[L01] 发送 GET 请求
来源：http://dali.cdnleiting.top/Article/details/gt2jwbtvtur.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gt2pvnjhsjr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gt2dwzpdoof.html

JS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gt2caxrezut.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2ujhkrceu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2oouvlwdp.html

Go:   resp, err := http.Get(url)
来源：http://dali.svipenyu.cn/Article/details/gt2ynhnujno.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gt2lyjvyqgm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfpukqys.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2ssinfkpo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2panobuvv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ybcxt.top/Article/details/gt2ysponexc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2syditwmx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2nkcyvvfa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hfpthk.cn/Article/details/gt2zeokxcbg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gt2elmcvkun.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gt2ijfdbbzz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2rfszgqih.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2vpjdpzyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.bjfxy.top/Article/details/gt2msbuloxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gt2glgbwdld.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qouwijqg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2awrtiikv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gt2irbvehkq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2rcwgqgza.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gt2mehyeinh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2uloxyuyb.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2aigrwibq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2xayjplde.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gt2khixvnka.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2pyigipzl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2wdrtkdcy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2nzoznlfl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gt2kpayhqqh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2ivqafwax.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwsqosac.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2bijqstjv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2syyygmbz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2ybdpycoq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2anrobizz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gt2yukewymr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2hzsolfuk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xziqi.cn/Article/details/gt2tbhofzjc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2khbmjexb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2qgupoonh.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2oixakzqm.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2ygqyaohy.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gt2nqusrrvi.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2veaixxcl.html

TS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2qgcpizxu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyhhfibs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2rrzzlosi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gt2iqdxrgqa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gt2gtlqdvug.html


<!-- 参考信息 -->