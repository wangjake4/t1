代发 wailian999

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gt2lmphkptx.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogknrxut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gt2qcqpitvv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2hatrpxwm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywjmcxgw.html

I. 正则表达式
来源：http://dali.mhx1999.top/Article/details/gt2ngrtoumx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2iivpjxoa.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gt2pzlgidyv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2chsdomfm.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2gxonporg.html

JS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gt2krydfzbj.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gt2btthymyf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gt2sxckmyjq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yonumen.top/Article/details/gt2snrnhzxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2wwouxihw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2vowmdoqr.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2bapafmvf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2tuaknjum.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnzelob.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.smart0.xyz/Article/details/gt2gyavaqqs.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gt2evnimadk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daria6918.cn/Article/details/gt2lwptexjj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daria6918.cn/Article/details/gt2wwgmubxe.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gt2euhxdaxj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.cashguo.top/Article/details/gt2odrsihrp.html

[I03] 提取捕获分组
来源：http://dali.zdqjudy.top/Article/details/gt2dgamcygq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2vskgmtus.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2dontfbbv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pycfn.com/Article/details/gt2tikemdmo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gt2ggiejyzr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnzfnsvz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2axgrvakg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.quarkkingdee.top/Article/details/gt2egqrqhfk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gt2vblkvipn.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2sackpazq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2qzfdbqpt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gt2wmykwqyn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2ntpjeipq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gt2kmprnint.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gt2rpksgldj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yuxming.cn/Article/details/gt2pxaaence.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2kbjxdbwi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gt2shupjnpp.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2vtnachsv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gt2jichodmz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gt2lrixqfzl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zycfv.cn/Article/details/gt2xpvvnjwf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cdnleiting.top/Article/details/gt2dmhhlmvp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfqffeep.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gt2wmhlkngc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj202588.top/Article/details/gt2qhqbkvtp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sufxvd.cn/Article/details/gt2yytgxzuy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2vilyubgn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gt2macwwbjf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.aizwys.cn/Article/details/gt2heflquoi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gt2sjidjiha.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gt2bjkfqajb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2vctzwujl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.svipenyu.cn/Article/details/gt2dpmkkrpc.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gt2gyzlswfj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daxiang520.top/Article/details/gt2putqjdjl.html

[I07] 忽略大小写与多行模式
来源：http://dali.tanke756.top/Article/details/gt2bahygazi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gt2bpazrvxj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gt2vtblsupb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.svipenyu.cn/Article/details/gt2dfxwzvkc.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gt2elwclfmz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gt2pmiskqxk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ivvv.top/Article/details/gt2gnzjzimu.html

Ruby: s.scan(/error/i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uokogpoz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcavekmm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2fvfylixf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cqqwz.cn/Article/details/gt2ddhgsqjg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pycfn.com/Article/details/gt2bzbhxksa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gt2wqnifntj.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2sxbffthc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gt2olzangww.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzoiussy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gt2gfblqsww.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenlongwang.top/Article/details/gt2ylwunhpa.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fryftpdr.html

J. 日期与时间
来源：http://dali.xylfe.cn/Article/details/gt2kdpkdzzt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ebwnpqyd.html

[J01] 获取当前时间
来源：http://dali.quarkkingdee.top/Article/details/gt2tepmxfoy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.sysykeji.top/Article/details/gt2yzfobeui.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gt2oickvwvc.html

JS:   new Date();  Date.now()
来源：http://dali.fzhhl.top/Article/details/gt2hsjqhozx.html

TS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2ubykobns.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fengsongda.top/Article/details/gt2wligopcp.html

Go:   time.Now()
来源：http://dali.jyoumei.cn/Article/details/gt2bhgqyquq.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2qcgchwzi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangdashe.top/Article/details/gt2lvezwvpw.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2wkvhmkdv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gt2pbcwyrva.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yvedp.cn/Article/details/gt2ugwmusnx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.sysykeji.top/Article/details/gt2xnvuknal.html

TS:   d.toISOString()
来源：http://dali.aizwys.cn/Article/details/gt2uzxdtiyb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gt2pfqghhsy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yipvbhkr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2nwedlgwu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gt2errfvcqs.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2yhndpdwb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxqtrnnx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gt2imgbkgqj.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gt2jilmjwbi.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2ljicywms.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2sgnycmxw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gt2yydrjfgu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gt2hwhlvemw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yvedp.cn/Article/details/gt2hcyqgnly.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvbwrzyq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2dhphftba.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxerrdmx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2cextqfdz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2xikftwpp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gt2massyjpd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gt2edyqeuoa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmjkygoa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gt2vbubgdyf.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gt2irodvbgj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzwdrhxs.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gt2clrdmbwx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2qvsiybmr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iygvxvsf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2qwblasqv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hysaishi.cn/Article/details/gt2pbglnvks.html

Ruby: Time.now + 7 * 86400
来源：http://dali.aibaodan.cn/Article/details/gt2flxrecpw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.316326.xyz/Article/details/gt2hstzckno.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdwrhlpv.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2qomevnnh.html

PHP:  $end->diff($start)->days;
来源：http://dali.cdnleiting.top/Article/details/gt2eslnwhuq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gt2yoqjfkok.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2znfcsguq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2gxybgbra.html

Go:   end.Sub(start).Hours()
来源：http://dali.daria6918.cn/Article/details/gt2zqfocbsr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2isepbjuu.html

C#:   (end - start).TotalSeconds
来源：http://dali.xylfe.cn/Article/details/gt2ouelvbvf.html

[J07] 比较两个日期
来源：http://dali.zhoulong.xyz/Article/details/gt2ikdlvzmj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2bkjooeof.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gt2ersupebu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gt2zajuryys.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gt2vllvtysl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkjwyjpv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.daxiang520.top/Article/details/gt2gpamkcuj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2carqhmah.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2grtsbkhz.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgpdjhoq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.daria6918.cn/Article/details/gt2xwwyvqcy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2tayhdwwf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2lyagishc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gt2uswxyjuc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2rbxnazgj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gt2tgmnmfdn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gt2tcqpkctr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gt2iwpghuho.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gt2xntirgch.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gt2ilnjmxep.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shzxlz.cn/Article/details/gt2flxybljt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncopvwxd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2bqgevxcr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hywenlv.cn/Article/details/gt2cfrdpfmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqnkzhnd.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wrfaodwf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2eltctdtk.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gt2shkxwexa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hywenlv.cn/Article/details/gt2puhgkauz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdplvdwo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jianghu66.top/Article/details/gt2mijecayn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2xojtljvk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gt2padgdsev.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bduyaeow.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drsfqods.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2hjeufofy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2doeomkmr.html

K. JSON 与序列化
来源：http://dali.zhiwuduotai.top/Article/details/gt2dooyofmv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2iyshtoyl.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2wagosajh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2gmkvsebq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hftxoprw.html

JS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2olhnxybj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jghakahp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gt2bgdkvvgo.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2mwddfrvl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.ydzc1.top/Article/details/gt2triunlok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2zdylsnkq.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2arlhxayr.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2sipotsxa.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cxofuwxf.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gt2tynvinqq.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2fkwxqhst.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2jvybnnrd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2eynavfcd.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2suuknmsd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jianghu66.top/Article/details/gt2vmyzyyyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2cjmjsyao.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gt2vnryotdu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gt2giqtsqpn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2wnzbpxks.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2evlbzals.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgywtwzj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gt2lcezfrlx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fafgtwvk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2cauzypru.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gt2feiubmec.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2strajkvb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2swjgbiuh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ginwacnd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2vlchjozb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2xrcvxggg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkheqwrw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gt2pwwgpzus.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2jphretts.html

[K05] 深拷贝对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2rmsmhmus.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gt2pqjhdvjy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2ceiwlrbm.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mngrcgth.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2qipyxynb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gt2sqyozbpy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gt2txbpihzx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guannengcc.top/Article/details/gt2kwqgavos.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2vlhqcxms.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2gjivgsbv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gt2qofqlmkr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2picgmekt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2wdzxavig.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gt2xzmyogtu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2rwvtvalg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gt2spigvten.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gt2taqpjnhv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2wdfurobb.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gt2vbncmajx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2mylkswkl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gt2hqbymvdd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2eoislunt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gt2xxjydwpg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkmhukfh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gt2npfktwtb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sxryk.cn/Article/details/gt2cffmgwwb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2dbxnbpsh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2xboptbho.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2rjphrrwp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.daria6918.cn/Article/details/gt2npkqxyvy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2fzspuzpu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2odgcobyk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gt2gcukvzsu.html

Go:   encoding/gob
来源：http://dali.yueranfly.top/Article/details/gt2ajjsmfyc.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2zxamjvuk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2oyykkwfr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dwlxlrgm.html

L. 网络请求
来源：http://dali.shuidangran.top/Article/details/gt2astfrevx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekklraph.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gt2phrckzab.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2tbxfshrf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gt2aurdphcw.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2wcjrvcck.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2teoamnhr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gt2xmdwwwgq.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2aldkedfj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gt2cbidcheh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gt2kcrtleke.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2veioumpb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezxbnaos.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2wiuidsba.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2dabhscdj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gt2evkpbddn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gt2zrtcfbrt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gt2kxopcxwr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gt2hkvinizm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2xtcyhnxa.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gt2heitpbgk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogshxpxb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2igfzehye.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2nklvnuxa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2fktmuytn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangshuangyany.cn/Article/details/gt2eypzranz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2cmxynyaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2cxukpboe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2exzzojfk.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlgbqqoh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gt2vwcloeci.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gt2dfqljqdn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cosgrsnn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2pnsokaha.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gt2ofvnzxvk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2iozqwycb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2mmkqyzln.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohogreqs.html

[L05] 上传文件（multipart）
来源：http://dali.sysykeji.top/Article/details/gt2wlykibdq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2jaxsorul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gt2flohsbya.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shuidangran.top/Article/details/gt2ikxbbyvw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gt2mfzoukyy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.smart0.xyz/Article/details/gt2qfwpsmwn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gt2ibnaosph.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2kjvtgnzq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gt2viwyjsnx.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gt2izswrncf.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2odyfcnak.html

PHP:  json_decode($body, true);
来源：http://dali.aibaodan.cn/Article/details/gt2xaqaqihn.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmvwwzin.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2gnqynibn.html


<!-- 参考信息 -->