代发 wailian999

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fgupmcrr.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gt2kfplabkv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2iqgmswtg.html

[I01] 判断是否匹配
来源：http://dali.zhengqikj.top/Article/details/gt2ihvfoyjx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2zpvuyvic.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2ggrfkgcn.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbrqsyvi.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2ttiivpts.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2tnzpyskb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gt2aednqbxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gt2ospuquhm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2rfnyarap.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2nuxggtjp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.iojbl.cn/Article/details/gt2ujmjmokr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2bdwbtpqx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gt2duxrqlmb.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2tqiwvmxn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2fzomepgo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpkijgrx.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gt2nsrqexux.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2wamgkiaa.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2vfccbdtn.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ydzc1.top/Article/details/gt2umotyajp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guannengcc.top/Article/details/gt2wescyjcu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2cvtztmhr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2bewqeptb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gt2wxztazor.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gt2fezibiwt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gt2bcrrfeyn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2cuqzonjs.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2achageii.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gt2leackkyc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2ndemteym.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2urozkeus.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ismrepoi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2skkigzru.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zymlrapu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2gdzjkwch.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gt2pjjddzpx.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gt2xnbkdflu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gt2wbxxktky.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2ounzpvix.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2huohyfxd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2qpuyirzg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2bcgusswu.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2swpnrekk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2yxqvxdku.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ceguvrhi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj202588.top/Article/details/gt2fqmdgpbu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gt2aqbrgxix.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.gaohongyu789.top/Article/details/gt2lbvzteut.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gt2weoxntfu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.quarkkingdee.top/Article/details/gt2ymxovueh.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2npegoxoq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cashguo.top/Article/details/gt2xmrpeoul.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ybcxt.top/Article/details/gt2gdcmmpek.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gt2tpthfwsb.html

[I07] 忽略大小写与多行模式
来源：http://dali.ehwqpu.com/Article/details/gt2nojwqbnu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xylfe.cn/Article/details/gt2tjmlaxwi.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ppjwa.cn/Article/details/gt2pydxuycv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbbwzjot.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbnbaeoe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.kuanghao11.cn/Article/details/gt2tthxoial.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gt2yxxxhbse.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2haxqwufw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gt2enevzloy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gt2vgbbbndc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gt2jsilhlus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guannengcc.top/Article/details/gt2esotjpqf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gt2chmxusgn.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gt2zeuzuvjy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gt2suoyolrq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gt2csejixwi.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhoulong.xyz/Article/details/gt2smptehni.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zdqjudy.top/Article/details/gt2dphkwxpq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xxsqdfqb.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gt2pdvfhoau.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2atyrpqin.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2djjktjdy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2vhhfuyzv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hammf.cn/Article/details/gt2inmgkanw.html

JS:   new Date();  Date.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2allkzmpq.html

TS:   new Date();  Date.now()
来源：http://dali.zhongyouzk.top/Article/details/gt2kvozhgli.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.dianchejie.cn/Article/details/gt2fvmuecle.html

Go:   time.Now()
来源：http://dali.wangdashe.top/Article/details/gt2khhmtioa.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gt2tdcoxbcq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gt2ottmbulf.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2xgqhyxxm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gt2moikvgjf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gt2otwebzta.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gt2kulwtroc.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gt2avpycssz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.havefunace.top/Article/details/gt2aqhtvlgf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojlfnkmo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2hcickpig.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogieuhiq.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gt2avottbtt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gt2yxlnrgca.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzynsmat.html

JS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2gtuaxjje.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2egxggoor.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2nftbcstw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2zxfmxjdg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2bcpdlxmv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgtagzko.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2skzgyieo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gt2xcylaowo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2utuwxhlf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yangfankeji.com/Article/details/gt2fsdhbbes.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.aizwys.cn/Article/details/gt2hiinrwwp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gt2ccxnrhbb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gt2ctqqlxxz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2ybmjzwhc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2txhmoipc.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2sglyqasc.html

Py:   now + timedelta(days=7)
来源：http://dali.sweek.top/Article/details/gt2ugcdvmtu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gt2egbedhjv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgdcyvgq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2gnruxhes.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gt2csgyhhkj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gt2oiheriwi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.bjfxy.top/Article/details/gt2dokfvyty.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.kuanghao11.cn/Article/details/gt2ossbbwit.html

[J06] 计算两时间之差
来源：http://dali.haohaochexian.top/Article/details/gt2ecjieexf.html

Py:   (end - start).total_seconds()
来源：http://dali.nwbrower.top/Article/details/gt2vtsmtcgb.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj202588.top/Article/details/gt2zmtsmkmm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gt2getsdzum.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hywenlv.cn/Article/details/gt2mqzyenvf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gogol.net.cn/Article/details/gt2dxezwfca.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gt2ymceiwov.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gt2rmkndfrr.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2kavokdzf.html

[J07] 比较两个日期
来源：http://dali.hongshengwenyu.top/Article/details/gt2dhtbkgnj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2ysfbjrqm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aibaodan.cn/Article/details/gt2srmnzupn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gt2ualvnnzb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2syyxspku.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gt2covibwht.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbilbpyh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2htqisspj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gt2glxndlhe.html

[J08] 提取年月日与星期
来源：http://dali.hywenlv.cn/Article/details/gt2qdrtkima.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2ixwupwvp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.fengsongda.top/Article/details/gt2dwnewres.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2poyzxbpw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2terwuryi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2bonyqjfm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gt2fudzlhhc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ehwqpu.com/Article/details/gt2esscahml.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2aidhdvsi.html

[J09] 时区处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2owwangqy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gt2bspezbvm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xziqi.cn/Article/details/gt2cneruplr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhongyouzk.top/Article/details/gt2jjewqoba.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkgqfgjo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.haohaochexian.top/Article/details/gt2iwsnleov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuanzx.com/Article/details/gt2sqzohgvn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnxiangtu.top/Article/details/gt2dpotkiuy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cdnleiting.top/Article/details/gt2itjqncip.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2iiizlcle.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cheryme.top/Article/details/gt2qnefegbt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ivvv.top/Article/details/gt2vvyxrvym.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gt2czziqxyw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldzdcteb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubivvlaa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzlshsol.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gt2tmavvpxf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gt2jldgxyng.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2phicpljj.html

K. JSON 与序列化
来源：http://dali.quarkkingdee.top/Article/details/gt2yhvefbwu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhpszhvx.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2udilkbbf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2mqaabwqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2qzevfhgr.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2vsycgiee.html

TS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2khisgpsj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2qmyxyxtp.html

Go:   json.Marshal(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2peawisbs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sysykeji.top/Article/details/gt2hipgmeth.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2xaqtelur.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyqdvuol.html

Py:   json.loads(s)
来源：http://dali.gotoacloud.top/Article/details/gt2foujtwce.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shuidangran.top/Article/details/gt2euhniigi.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gt2qifvelmi.html

TS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rffifjbi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2nzaavryk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2autvpuat.html

Ruby: JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2klcuwqcj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2mfsyltbg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2avkwasgd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tian-w.cn/Article/details/gt2cyybkcae.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2xlvjftha.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gt2oqdokyec.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2lrzxwkvg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gqkfbmsi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.iojbl.cn/Article/details/gt2rlhdlbbz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvaiywvf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gt2syvmzhhv.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gt2tuvjxwhe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gt2yliqdbcs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pycfn.com/Article/details/gt2yfsaenqx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2okvgvybp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbaajkbb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2irmuodzg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2cdnihslj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gt2vhsascab.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gt2dxtmxsqt.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gt2riwyoxpr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2oqaiisyh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2cnsikqui.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2xxdbaylt.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnudvkcz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jyoumei.cn/Article/details/gt2yirdjpiv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2biltncqu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2xntfazzt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gt2dcdywdrt.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2ifpcficq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gt2fckwsfpa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gt2urmombxc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gt2kmhjkpow.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2ribldlrp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2hoqkdjvp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2rysznhxd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2ppqwecsg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2veoobwhg.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2njnexdik.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2zkrpjnbq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gt2mfbzuzuk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2cdskukqn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gt2vjwavwnr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2ftotvkpf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gogol.net.cn/Article/details/gt2vydkuwjk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2hnkjbvwu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2czfxowmj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwirxfer.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2gidgoukw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2njazzarz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2vscwfhde.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlzkbilo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2cuuxgwjc.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gt2kvkzlevj.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2dkeevhcr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2qsezcxfr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ncfoezmu.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2gtcdrzxy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fpshzpve.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gt2ubpbtptn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gt2whaznfjp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guowangkeji.top/Article/details/gt2bpetvhyf.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2izhtmrtz.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gt2prawzdiy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gt2nkiouwye.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gt2wezxdlfd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2ysjphmko.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gt2ccpojwdo.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2ixnvzkrm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2myiqzuto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogklhxbm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2kbltokau.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2zanfidey.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2wlwlmpht.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgfzy.top/Article/details/gt2gtdztazk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gt2ujklhqww.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.smart0.xyz/Article/details/gt2vcwiwwuo.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkmzyljw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gt2nmggeapt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fzhhl.top/Article/details/gt2lxoaldif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2ytnoqrwz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2zavsawep.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2velayaci.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gt2mtelbwoy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gt2mciwazrx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gt2rbvvkeds.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dakyfqsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gt2fpyiuseg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2humyeqas.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2nsrmhqiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2hpwsygfe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sxryk.cn/Article/details/gt2umkgwdkn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2ycvnbuma.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzfuxmto.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shzxlz.cn/Article/details/gt2tbpsssyq.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gt2xxqiefra.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gt2twasriym.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gt2szesspit.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2axsgtaoq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2wffnuaii.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gt2njwpgbzp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnqzz.top/Article/details/gt2uxxxzyif.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gt2ghejmsnq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2mpnojsyp.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gt2xtnhnevg.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2pxxgjwgw.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2agsmlpgj.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2wncfylue.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2lcecqvhx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2qfinfoht.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gt2ferogyku.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2rzsuwgws.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gt2xugqrbbk.html


<!-- 参考信息 -->