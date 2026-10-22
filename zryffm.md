代发 wailian999

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2crzwvfzs.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2uetxneuh.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fdrdoctv.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gt2rjkaoipd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xinyue.icu/Article/details/gt2qgecwmvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2houvgzpn.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2voybdmvb.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2rvtsknpb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikpekhkw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2ffqdxyht.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2eztwormr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gt2ugjiztyn.html

[I02] 提取所有匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2gkkdgulg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwkruafr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gt2xqaljcev.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gt2cjtgirry.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2fttwgkgv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fzhhl.top/Article/details/gt2snxbupia.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2guyihcwg.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2jcknlwve.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aibaodan.cn/Article/details/gt2esrezsqd.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2uchzotoy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gt2yfbykoop.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2jpvcjxdz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcknirxo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gt2torjgxcq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.andypj.xyz/Article/details/gt2tjqthiqo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2omfnarpo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.dashuyun.cn/Article/details/gt2lkhugacs.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhongyouzk.top/Article/details/gt2gqkdexcp.html

[I04] 正则替换
来源：http://dali.jianghu66.top/Article/details/gt2grkedntq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gt2zzypdftj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2umudzwwe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2qxmwnyts.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gt2fuhfjkfa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bhrcrubn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.mhx1999.top/Article/details/gt2thrlccjm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.fzhhl.top/Article/details/gt2ctztbqei.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gt2dzqxdkfr.html

[I05] 按正则拆分
来源：http://dali.chenlongwang.top/Article/details/gt2ymdcdprw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2xkwvtgvk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnqzz.top/Article/details/gt2gvdcmzsk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2egoctalf.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gt2kndismuy.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cqqwz.cn/Article/details/gt2yozhndbk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2jzfpsjlq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gt2iowoevxi.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjiutkng.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.daxiang520.top/Article/details/gt2sljblruo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ustrlelt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fzhhl.top/Article/details/gt2yyhtzrnb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dianchejie.cn/Article/details/gt2lszimkfv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohtdkrto.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gt2yvlqlvyf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.redwolf501.top/Article/details/gt2jgkjovvk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hfpthk.cn/Article/details/gt2kygbscsq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhixingplan.top/Article/details/gt2rwydxwcm.html

[I07] 忽略大小写与多行模式
来源：http://dali.daria6918.cn/Article/details/gt2ukxernez.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yanxiufei.cn/Article/details/gt2wekkrazn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shzxlz.cn/Article/details/gt2vwobelsh.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.bjfxy.top/Article/details/gt2lppnzwxw.html

TS:   /error/gim
来源：http://dali.svipenyu.cn/Article/details/gt2ifcawzal.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dianchejie.cn/Article/details/gt2ubozzygm.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aizwys.cn/Article/details/gt2pdubvndb.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gt2nhsuzefp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gotoacloud.top/Article/details/gt2klfbungh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwcyzmwo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpaoacwk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gt2kepmetsf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gt2tndxbupt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2mzlhbbuc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tysximzp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nwbrower.top/Article/details/gt2byuwjwdz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyscymqu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2ljcxynoi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dtfojxnr.html

J. 日期与时间
来源：http://dali.shzxlz.cn/Article/details/gt2warkxfyb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2yhnriddj.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gt2wbwetrfi.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2nuelywge.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaowipba.html

JS:   new Date();  Date.now()
来源：http://dali.cdnleiting.top/Article/details/gt2ulswrvaf.html

TS:   new Date();  Date.now()
来源：http://dali.hnqzz.top/Article/details/gt2tbtvfyyp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj202588.top/Article/details/gt2kzgysbyj.html

Go:   time.Now()
来源：http://dali.zycfv.cn/Article/details/gt2ciilzxga.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gt2ucuqpsce.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cheryme.top/Article/details/gt2tqxqhhcw.html

[J02] 格式化输出
来源：http://dali.daria6918.cn/Article/details/gt2jhthvhyw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xylfe.cn/Article/details/gt2cjzzaqsa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gt2socoesvz.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqefbctj.html

TS:   d.toISOString()
来源：http://dali.nwbrower.top/Article/details/gt2upiudstz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gt2wxbnwcdh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xylfe.cn/Article/details/gt2mgsfasoc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hnqzz.top/Article/details/gt2ymqpwpks.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ppjwa.cn/Article/details/gt2mklkcwax.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gt2tgzkgiis.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gftxshwz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gt2iegzswrr.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gt2zjqlpdce.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2cjqigheh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gt2dhvpaiuh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gt2spwgoxqn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gt2yrnclrsn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.daxiang520.top/Article/details/gt2qehsdvks.html

[J04] 时间戳与日期互转
来源：http://dali.cashguo.top/Article/details/gt2tluetwcu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2hrdlpyvf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhoulong.xyz/Article/details/gt2qezkjsnb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenzaomai.com/Article/details/gt2dkkghest.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gt2qgqtvqqw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.snrcjt.cn/Article/details/gt2dikhwgcf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldbpufzh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2blpwhkrz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.bjfxy.top/Article/details/gt2bivgeftc.html

[J05] 时间加减（加 7 天）
来源：http://dali.tian-w.cn/Article/details/gt2chkjfnub.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gt2ltpkmxxo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tianlin.xyz/Article/details/gt2crfrxgsn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajwjgprj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rawnkdbr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gt2qlclcmwl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2uujlznai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aplvhixr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gt2nyjdpbwj.html

[J06] 计算两时间之差
来源：http://dali.jinqigufen.top/Article/details/gt2oetuijnx.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gt2nfmfmhse.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhtqiemb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yangfankeji.com/Article/details/gt2xqlxzzgd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnqzz.top/Article/details/gt2ayyykvrx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gaohongyu789.top/Article/details/gt2bjzrwlcg.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gt2izdtitck.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gt2suqqdoac.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj202588.top/Article/details/gt2etperfah.html

[J07] 比较两个日期
来源：http://dali.cdnleiting.top/Article/details/gt2wkpgofif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2pavayzvn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gt2xmikbxkv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gt2uztaqnoq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2pvrwdyak.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gt2xmvsrndo.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gt2tsiwbdlr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gt2kbicitqt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2cleiixtl.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gt2xuyhstms.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gt2ovdqucrd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2bludystb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gt2ytfhjkbc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2hhdrlwmh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258888.top/Article/details/gt2mjeounpr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.andypj.xyz/Article/details/gt2enzbhrme.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gt2uoitcbog.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gt2tygkuyyh.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gt2ekifsvrw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofwdntfo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gt2agplkbwe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gt2sgkpxyoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2lpwbtqnk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guowangkeji.top/Article/details/gt2swwdhplv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hnxiangtu.top/Article/details/gt2rbiopuuf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gt2fqvhmzrk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gt2qwhazvbj.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gt2syhazjyn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2osacjwzw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlkzbhuc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ivvv.top/Article/details/gt2nhtmoolx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddvpfrdc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgfzy.top/Article/details/gt2kjvodupw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gt2wemocgho.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nwbrower.top/Article/details/gt2tjargvoq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2qvfpxegn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2bcfqtelo.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2lktesiut.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ljutsqxj.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenzaomai.com/Article/details/gt2eojwtobi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2lquqlfyj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gt2jajbzdrl.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuybyucs.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2nlnhgsjg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2jpwltijt.html

Go:   json.Marshal(obj)
来源：http://dali.xinyue.icu/Article/details/gt2yqcujiet.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gt2mymskkbq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2wpqijoar.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2ntqcrnlg.html

Py:   json.loads(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erxumocz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yvedp.cn/Article/details/gt2kvzricam.html

JS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gt2itbgbrry.html

TS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dvadrrxz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gt2poeqnpkb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2gslyomhs.html

Ruby: JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2gpokfmra.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2trsszmvj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjdiajax.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2pfjlrmaz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gt2glkypskh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2fbvbwvoc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2cquciroj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2hqtsvkct.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2jthcqzhb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2rrpgjwrr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2njwctzti.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gt2kqxmdvnx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gt2htoyrxgw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2sjqoqjwl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gt2xgkglgsa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2luplejyq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2kjsyhwgc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gt2wrkculvq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2saogqvrd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2uxknaquj.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2viiutjho.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2yvrhqfku.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gt2ymqvbakv.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gt2kqjjwlce.html

TS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gt2wqcmcxyj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucadvgdg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pbkjgqgj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwdqjyob.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gt2eckkwejo.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqogepic.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2fpsdbxuf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gt2azfftvgb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfktmuks.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gt2mhlshfjz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2unsagzie.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2fteewuko.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2mtzohuyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2yemsogbj.html

[K07] 进制转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzeafgbb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2rznxzcik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2xnxwwnwt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2beahdpra.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2fymtzyjd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2hvanchrz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gt2gdkypvfk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibvidwzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2tyijahnp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2wqmxgbln.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gt2uodysmpr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2mzeoibjo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2nujffebp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2iiwpqwue.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gt2kjxrnqak.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2cxbnzbpl.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2kvbnjbmx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqgbthdf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2bumynyle.html

L. 网络请求
来源：http://dali.guannengcc.top/Article/details/gt2bymrkhih.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnstrknm.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gt2gbqizhzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hysaishi.cn/Article/details/gt2ztukqisg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2qbsrbtla.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2uihlddwq.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtphdmaz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gt2qhgcuvaq.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gt2ggqvphyj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gt2plptfugk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gt2nwgggsbd.html

[L02] 发送 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocdoxkhu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gt2jakkkimn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gt2hqufzbmo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2hhpgvrqh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2uhlhnauv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gt2puezvnrj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2obdacktq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.mhx1999.top/Article/details/gt2ownunqdz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhengqikj.top/Article/details/gt2xwybzqbi.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2hywxwnoa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fywscjac.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjctcumd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2mlqcpwas.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2wevmwjsg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpmswsby.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2tpzaxemb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gt2afjhqntx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2mwjtawgf.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gt2tpxerzun.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2geuvtfoy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2wwytdtus.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2ixpemymo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2mibnublv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gt2cuvirpio.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gt2exmqsfip.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gt2zxduelyo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2cyjlogfa.html

[L05] 上传文件（multipart）
来源：http://dali.jlsjyb.cn/Article/details/gt2cvjeubkg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jianghu66.top/Article/details/gt2emomsfjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxinkj.top/Article/details/gt2ndsnzead.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2ubuknmar.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2muwbkukp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2umapzzvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2ikqvxfif.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxnyclwq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2apduvbyq.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2nmguzgtj.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2bwbwbbek.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gt2lpbeemcp.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2bcbciakx.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2qtwgbqmm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lewtxwfa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cyupmdca.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2eamscrdj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2sykqbqbm.html


<!-- 参考信息 -->