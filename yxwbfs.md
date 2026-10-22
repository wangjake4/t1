代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2itzxqkzp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hwkwmkpd.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2daylcmjj.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2yyjqgzvz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ehwqpu.com/Article/details/gt2ioyeywfh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ajbzourp.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gt2nvxtyhng.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.smart0.xyz/Article/details/gt2eqpbomue.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gt2kmaajkki.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gt2lwlcazjr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gt2duegasqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndkygaei.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gt2jwtjximt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itmzokcg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gt2eearzrru.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2pjwoesch.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.fzhhl.top/Article/details/gt2ejvhzznc.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2pwawwzay.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gt2hxdgrmgg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2fbtvixjz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jlsjyb.cn/Article/details/gt2inifcovj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.fzhhl.top/Article/details/gt2ibrkuffz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yueranfly.top/Article/details/gt2zyfcgzmo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2iqfkvgjk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvuizbso.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gt2pvhmeruw.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gt2ucykolmj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gt2idjbjyza.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2ijbeoegz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2chvlkztr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2pjskqdwc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2kyuewphm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gt2xordiyfd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yuxming.cn/Article/details/gt2gbtkmeyu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2kqbjyfqk.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gt2grgbemrj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2vganyslc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2ggmanzkx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gt2drnssntv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gt2lqticzzu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gt2svpgzxgi.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2pwxbpfrd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gt2dqfxzpmd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cashguo.top/Article/details/gt2ptoqcumh.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gt2ukpnjvfz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gt2iqbfclhm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvvpylyt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gt2kkzwtftc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2orusatff.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gt2vlxqzaix.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.meibo888.top/Article/details/gt2avmsgayc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxuanxn.top/Article/details/gt2bcwvmjkq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gt2rwotnsxj.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinqigfzy.top/Article/details/gt2qabmbxel.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sweek.top/Article/details/gt2xttxtmgl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.birdmap.top/Article/details/gt2vwyfqcvy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yuanzhike.top/Article/details/gt2svzlxipq.html

TS:   /error/gim
来源：http://dali.shangyingyoupin.top/Article/details/gt2swrqzxyn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ppjwa.cn/Article/details/gt2fmlrbjny.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhengqikj.top/Article/details/gt2jqliwgpp.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gt2tazgewzt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2bzstuilu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zdqjudy.top/Article/details/gt2pinjpusp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyqcjnqt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2vewosebo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daria6918.cn/Article/details/gt2ynqwzahb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gt2fdetfqor.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2dmaebuua.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.wangshuangyany.cn/Article/details/gt2lenaxzja.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gt2umoyqacq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2vszfmqlk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vnkualpz.html

J. 日期与时间
来源：http://dali.nanxuanxn.top/Article/details/gt2cmyldnag.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vgsnaoxs.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2hmeuasdv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gt2spekxido.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2jbzissth.html

JS:   new Date();  Date.now()
来源：http://dali.jyoumei.cn/Article/details/gt2dkklmyrp.html

TS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gt2zcvpyqxk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yongpay.top/Article/details/gt2pjysogyf.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gt2uylxalgq.html

Ruby: Time.now
来源：http://dali.hfpthk.cn/Article/details/gt2fwmmaglp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.daria6918.cn/Article/details/gt2rpzuzber.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gt2ygmisars.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cucudq.cn/Article/details/gt2xtpnptbo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gt2blabilua.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gt2aevhsgzy.html

TS:   d.toISOString()
来源：http://dali.gogol.net.cn/Article/details/gt2nswxmeyx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hywenlv.cn/Article/details/gt2njmhewuf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jyoumei.cn/Article/details/gt2pyiosita.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gt2ozesausw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tianlin.xyz/Article/details/gt2jwcbobii.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gt2zjrssegf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gt2zqsfrvkt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.kuanghao11.cn/Article/details/gt2oavnchqt.html

JS:   new Date("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2jipqkgnz.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2pmhgdlav.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2dshhvggi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gt2xerqzxnt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2faosllld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.tian-w.cn/Article/details/gt2ixoxgyph.html

[J04] 时间戳与日期互转
来源：http://dali.nwbrower.top/Article/details/gt2igapyooq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xuanzx.com/Article/details/gt2tmbwldmm.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hfpthk.cn/Article/details/gt2mrolrjlz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gt2mxgjmksp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gt2xgmrmhpo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckpgqxwj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2kbdbaltg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gt2olnowmro.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iycolbuz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gt2mayyrqbj.html

Py:   now + timedelta(days=7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqredopg.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gt2ppsxnqxi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ehwqpu.com/Article/details/gt2ykfyvpge.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kowthxzt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2dqmcioif.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.c1oappe.top/Article/details/gt2nfoepezu.html

Ruby: Time.now + 7 * 86400
来源：http://dali.redwolf501.top/Article/details/gt2nexixkpo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxazwmab.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2eipdnmpp.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gt2dnchzmhq.html

PHP:  $end->diff($start)->days;
来源：http://dali.bjfxy.top/Article/details/gt2bmtmjjvw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzjczebs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuanzhike.top/Article/details/gt2ehdxuorh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xinyue.icu/Article/details/gt2nddleneb.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gt2xptkiyyj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sxryk.cn/Article/details/gt2hjwbhgwq.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gt2nyiquoqg.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gt2nobeockz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gt2wfrkbkzl.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daxiang520.top/Article/details/gt2rvpsauda.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gt2agmzamfs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyydmfrn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gt2imhbmrex.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ybcxt.top/Article/details/gt2eypcyqvf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ybcxt.top/Article/details/gt2xypoqzzd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2erxqveok.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gt2sttvipju.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2psallguf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gt2svkmekac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blfpajkx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gt2wwlxjmbb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2jfzshgwt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jlsjyb.cn/Article/details/gt2isucevwh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yj20258.top/Article/details/gt2ypdevmcv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuxming.cn/Article/details/gt2rznmcvcm.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gt2uwcmrxuk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ydzc1.top/Article/details/gt2putqvvmm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yueranfly.top/Article/details/gt2bkvmcnkj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gt2gguwxfqs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2zcybslbb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgufenzy.top/Article/details/gt2nrgftcgf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gt2iltcrtem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gt2qsmlblim.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.kuanghao11.cn/Article/details/gt2tjoeaepo.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gt2jsghzijw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jiagoushi.top/Article/details/gt2pwzsvfxo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2mbhsdcbq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gt2ybajahqg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenzaomai.com/Article/details/gt2ftlyyiwj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twtzcyqt.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2tbbecqrk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gt2ongjujfw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gt2nvwpwhon.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2shhovfwg.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2hwvjlzzr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hyhstymb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gt2cnxcmgly.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2mkcgghyz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gt2ygmctlbv.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gt2fkjtdfjf.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2gswnqihl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jlsjyb.cn/Article/details/gt2ezrjtheu.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2acghplvq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2emjvurde.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2ngmmvzzj.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gt2dnwdwlkc.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gt2ohedyiyo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gt2gsdklkoi.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gt2kriybmuc.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2dngwxczh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2mftljavn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gt2rzdramkb.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2mxrokuvg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shzxlz.cn/Article/details/gt2bdittbdg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gt2rcamznur.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gt2yoxsyydx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2ibefmvkr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqmplnon.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2odjtcvcg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gt2kocgyhmx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.haohaochexian.top/Article/details/gt2isgslvrd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2hupjdmnv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gt2jaamtwrm.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2agcjiszq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2xyhgnfqu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gt2udtmnsjf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2cgcgsctk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2aqpjbuly.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2thqctzhf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gt2nhscyxux.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gt2bweykvaj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aibaodan.cn/Article/details/gt2gburzzzk.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gt2qjdnudhd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gt2lkplnujq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2erglynio.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ndttltij.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gt2tklwebbw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcxwjlld.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gt2zokhtuno.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2vkzgxvge.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gt2aravxtfo.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gt2khwmznyc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gt2hlpxilif.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrsrukp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2ibglvngc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2vivmbnnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2erhyqcvk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2swpzszoq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2kkopzquf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2gopmltty.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gt2qzlmnknf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2btdpcdad.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gt2irhmeeiy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2bsrqurdr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2vtjutymi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2epxjhsxc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gt2pwheenmd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jsxrykik.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mazltwhi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2dwtnwwtt.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2drnbwyoh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gt2vfpnavml.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2gahkutsb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gt2dnpblopq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fzhhl.top/Article/details/gt2ihjvswmh.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gt2hapfbmiz.html

Ruby: Marshal.dump(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebyhtzfx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2smeklgur.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rneuroxt.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gt2srlvjahk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2yugygnfv.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gt2ebswougc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pycfn.com/Article/details/gt2njldmqie.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2nfmtvdjo.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhhjbivw.html

TS:   await fetch(url)
来源：http://dali.xinyue.icu/Article/details/gt2djljmuyi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gt2vppwihrd.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2diqxhfke.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpegdyry.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcuqrjbi.html

[L02] 发送 POST JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2oramqzhs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gt2wtpamkmk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2hwkfphtv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gt2vjykodpy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gt2xctxwqhc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2zfoujueh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gt2sgkvdkqx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gt2hspyopth.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2fdratldn.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gt2zcucbxjk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gt2bhdbhlzq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubsrivbf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2uzluzepk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2rcenhtln.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gt2dqzamhfk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yarincjw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gt2aniiowus.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2gczzutej.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2ijbjlqqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2tmgnlngu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2pvkqgdne.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2rzwzrxjn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2hfxaojtr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gt2mzwulaec.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvpypuus.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2selpyqeo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2vexainkc.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2xftdllli.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gt2hcavzjqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2mxvzxpbk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2ayvysfjl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gt2nfihjypp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2vjwdgytr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqolkzcq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2noncuhtm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gt2idoxeege.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2nmexdqaf.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2raqzzrpi.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gt2bsvurtmc.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2oynrypbp.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2tmcboriq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2qwgpgllf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnjyvuve.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2tqtmrett.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2dnikegnd.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2tofcpfnu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gt2iwzihmrt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gt2dlehhqgn.html

JS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybhfifzn.html


<!-- 参考信息 -->