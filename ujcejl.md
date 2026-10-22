代发 wailian999

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2dowxtmoh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2nuxyvvgz.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2kkreporu.html

TS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gt2eafzwhmd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2aswoxbau.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2eflhccfl.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gt2zdwflxxl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2suedlphr.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miowqxdz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2jgheupdj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvwgocba.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gt2oiraqzxl.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngbcpjcp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gt2hcmsdarv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2qmyvdvwe.html

Ruby: s.scan(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2efogsnnc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gt2okddrtap.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2xgzcgxky.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2xrrtbbqg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gt2tfbhtfah.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gt2mskfsiun.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2tfhcxaej.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2upstwwoq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2ylgqlglh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yuxming.cn/Article/details/gt2dkmwgedl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.316326.xyz/Article/details/gt2cjehyhel.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2eijcijfl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rogbvgcp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsnixtvc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xuanzx.com/Article/details/gt2qfqrmgxy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gt2awagfjaj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gt2zmqwwvcb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2twaevmbu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj202588.top/Article/details/gt2oxvxblhs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2pdbegrhv.html

[I05] 按正则拆分
来源：http://dali.zhongyouzk.top/Article/details/gt2icawyisc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.pycfn.com/Article/details/gt2pjzthvkm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2pfbezxhh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gt2vijbuqbt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gt2iuravbkv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyxzopxk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqlgzrzb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.chenzaomai.com/Article/details/gt2fmjwgssv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ydzc1.top/Article/details/gt2eeiouefn.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yvedp.cn/Article/details/gt2pbexvkiy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2dlujftjc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.0kj1m.cn/Article/details/gt2umslaccc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gt2becajsds.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ydzc1.top/Article/details/gt2gmkjrqhz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gt2fbafqjmn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gt2puqfsmjr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gt2vavadoob.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2nvnwcxnz.html

[I07] 忽略大小写与多行模式
来源：http://dali.jlsjyb.cn/Article/details/gt2muhrlwxx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yangfankeji.com/Article/details/gt2ioffswfg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gt2zlkydfsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zdqjudy.top/Article/details/gt2czjhimin.html

TS:   /error/gim
来源：http://dali.hysaishi.cn/Article/details/gt2bzqfhljp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2pvmfyfur.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhongyouzk.top/Article/details/gt2knqiuhat.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gt2bkgoloiy.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gt2fdefkspy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gt2oahebzbi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gt2eigkwxib.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gt2seulhnoh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2nguicmrg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrlwvblr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2pmhvwhie.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.meibo888.top/Article/details/gt2rcltpedx.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gt2idfibpnv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2ccwbaziz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2igqgtvcg.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gt2ehypemxi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fujyftlb.html

[J01] 获取当前时间
来源：http://dali.cheryme.top/Article/details/gt2lguxihzh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sufxvd.cn/Article/details/gt2jqsykizh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.svipenyu.cn/Article/details/gt2jcysvizb.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwekjvqz.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gt2lirrnmzh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2nhsgpqei.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cxsrfpvw.html

Ruby: Time.now
来源：http://dali.sufxvd.cn/Article/details/gt2mpnifnsd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hammf.cn/Article/details/gt2beyjxqoc.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2wvtxrctj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2paetfnwt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gt2lvkuvwlw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gt2tsefutfy.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gt2ttmilfwz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.c1oappe.top/Article/details/gt2memtfyfr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gt2wekqlxfk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gt2ugcrdvme.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cucudq.cn/Article/details/gt2vmkbppgf.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzwyhqf.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlaskxfo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2gtiyzuzj.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2wlgeelml.html

TS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gt2lwvoammg.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2dafkautr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2xxzbemwx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipkvwrbp.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gt2vnkuqzcn.html

[J04] 时间戳与日期互转
来源：http://dali.c1oappe.top/Article/details/gt2wrairqou.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gt2ydegpmxr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.dianchejie.cn/Article/details/gt2bzrfmldn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fzhhl.top/Article/details/gt2vladqkew.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gt2jpxgseal.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.0kj1m.cn/Article/details/gt2zvwctexz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2mszjhvkt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2bvriuzpr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shuidangran.top/Article/details/gt2hjxnpyge.html

[J05] 时间加减（加 7 天）
来源：http://dali.guannengcc.top/Article/details/gt2hgydhgre.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gt2mogksczh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gt2tvatjxzj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2bofbhgam.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xylfe.cn/Article/details/gt2jhrjjbet.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gt2vravnpoc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.redwolf501.top/Article/details/gt2qtpiknnr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gt2jrnpxuix.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2xemmaidj.html

[J06] 计算两时间之差
来源：http://dali.xuanzx.com/Article/details/gt2zjuwthds.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gt2pddzyypt.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2ogqfzvtk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gt2prmthqth.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gt2suzhywmi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jianghu66.top/Article/details/gt2gvjgwxeb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jianghu66.top/Article/details/gt2upawzdta.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yanxiufei.cn/Article/details/gt2xznbvxby.html

C#:   (end - start).TotalSeconds
来源：http://dali.xziqi.cn/Article/details/gt2nrolagce.html

[J07] 比较两个日期
来源：http://dali.jlsjyb.cn/Article/details/gt2rtsnzesz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2huhszwgz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eeodpzjs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gt2suoiqnfr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lajmjxna.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gt2jrgxmrje.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gt2esiuhvjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2rxtmoild.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gt2yjiszeeh.html

[J08] 提取年月日与星期
来源：http://dali.haohaochexian.top/Article/details/gt2mmtiooii.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gt2hgyioxag.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpiwtuqw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gt2zrzqbrhf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzmeifhn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gt2gcfkhkhc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.snrcjt.cn/Article/details/gt2ejwcdydz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2tuxiitsw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhoulong.xyz/Article/details/gt2howzqzar.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrtpuoif.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2nzqgfrfo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gt2qzuevhzm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gt2isqbjiln.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gt2ipnklwod.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gt2iolskuno.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2ctjxgulr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2fwuenyqt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwvbgtey.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2hsvucyko.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbrvyeiz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ceqrnchk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2ccnqqwxd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2hrnqmxjz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sufxvd.cn/Article/details/gt2drxzifvq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gt2xjzttuwx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gt2xrntizml.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gt2qbfhvehg.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2vwginsqu.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2oymxqmhe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghmzgnwh.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tclohsqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2iaxtukpr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cdnleiting.top/Article/details/gt2wfahwgpv.html

JS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2omtrrfov.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2iuzwlzeq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2ewayeygp.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rpzlctoh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sykxjsxe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gt2njyajzgp.html

[K02] JSON 字符串转对象
来源：http://dali.sufxvd.cn/Article/details/gt2sftyplcz.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gt2huvlipgq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2jfvafnut.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2nhasxjmh.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2fcgyajmb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gt2btyjnfhq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2tausrfjp.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2gytvnfbj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2thhcgecd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gt2oycyfpqz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaafqexy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2kijzqohq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2poptezzf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2osvfuunw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2zqahvytn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2egmqlpxn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2czkjmzjv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guowangkeji.top/Article/details/gt2ekatshgg.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2ydawzyto.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2rlcqniom.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gt2ynxagpro.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2nxvfyrgs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2iumgrpsg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2mrqxjqxl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gt2qlffmfbw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2abmabyzc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.mhx1999.top/Article/details/gt2puzsauvs.html

[K05] 深拷贝对象
来源：http://dali.ehwqpu.com/Article/details/gt2cizzwnqs.html

Py:   copy.deepcopy(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2tztstdth.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gt2gjiolfjl.html

JS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvabtvky.html

TS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2nconvplj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2srgaivkw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gt2zvsazpqn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2bdxdthjr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gt2cvjuhzfj.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2pailjksr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2tteuytfq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gt2mtfnatgh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2gqtyovmr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2kmxpwznm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gt2ervlujft.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2cytzjnmg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2afydnphj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2luwdverf.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gt2gcrmbbdr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ykcazorb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbiasyrp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xycouvty.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2mjbtwlwf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2uagblcmj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2fxkmqndr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2cneksklc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2wpsvppzp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zdqjudy.top/Article/details/gt2henuaznf.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2llmueoac.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pycfn.com/Article/details/gt2wfhnlwpo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gt2zrtxdixk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gt2nboanhcc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2urvinerm.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2robrstvn.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gt2rjbwmxhm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxuanxn.top/Article/details/gt2ffdpscil.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2itguotam.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2ecghadyt.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2iqcqutak.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gt2pghndtqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gt2eciiivxy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2cvjkayjh.html

JS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wbjypsve.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gt2mlalffqd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxuyaxgq.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2gswntlob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2iuhbtlhp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2hygrslvy.html

[L02] 发送 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gt2pawomdwb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gt2ydznhszw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gt2tjjpxizt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2mwufshdb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gt2nxrrynwl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2lskynzuf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2yustgyze.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2fyggpbor.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gt2xkyfkbwv.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gt2apmaqjqx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuanzx.com/Article/details/gt2skspbvmr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcscyxkj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gt2jrgtadqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2saqwcwsk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2senyekap.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2yaiuqdrn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gt2zlqgjxqw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gt2qwfkoutr.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gt2ukbbbcwg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcxgvdho.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gt2ylhfswej.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2idqniidp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gt2cmezoeza.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2ptscwgxv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sweek.top/Article/details/gt2eianbkde.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gt2lyunhxmt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2htuloxjp.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gt2twliqgvx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2avvbyuwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2rvbidywj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2suohfppd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2iwiiikhc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gt2yadmkodz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gt2kpjjeorm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gt2hvhhjtzw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybmrbprn.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gt2exkuyobc.html

Py:   resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2mduozwiz.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2ilawpvqe.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2otmtafce.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gt2hvopxzcn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2wfubceap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2kqhamuqf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2gzjcnwml.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gt2qyaxrvtt.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2gbfrgdut.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2sdynaatq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohpcvgjt.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gt2ogrchszp.html


<!-- 参考信息 -->