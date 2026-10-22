代发 wailian999

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2dlvhytjr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gt2zcrvklqx.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2wobxzgas.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gt2sksxruri.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sglgcqub.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2sybpcwim.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gt2pdrgkzxn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2qtyoemyk.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2gnyvkhpy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2gmzmysnv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2olssaaxx.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2nibdapqj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2bxshgubz.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkoxuvlr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gt2apbzbapq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2elqcuqnr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cdnleiting.top/Article/details/gt2kuubyuny.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gt2utxkceve.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gt2jwadllai.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwjenapj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2fstnpkfv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gt2szvkkaxk.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gt2agzqgvpr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gt2gujhzufp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2dzuuvdyn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqcpxebh.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgbrayba.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gt2iijrjqsx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2tzuneqbk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2tkmfckqf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.meibo888.top/Article/details/gt2gejnptdo.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gt2mfbwvdaq.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gt2qaczfsba.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2lwsxbrxc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.svipenyu.cn/Article/details/gt2obytndzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2edykkqhh.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2alqevnit.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2dzdkrwgi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2fcgwrtwu.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2yctfquok.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.smart0.xyz/Article/details/gt2lvwqhalj.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangdashe.top/Article/details/gt2hfgeffcv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyfgsnar.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.c1oappe.top/Article/details/gt2prdwwlaz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gt2zawdfijl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hfpthk.cn/Article/details/gt2vwltsofu.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xziqi.cn/Article/details/gt2lqoxhkpz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shzxlz.cn/Article/details/gt2flhuxtgf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gt2atumwtit.html

[I07] 忽略大小写与多行模式
来源：http://dali.sweek.top/Article/details/gt2ezzharrb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxbdeayh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cobrrcyc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shzxlz.cn/Article/details/gt2gfvyktav.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfuuxnfj.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.pycfn.com/Article/details/gt2etfhkjhx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gt2vvyykpfk.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rayqplbi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.tianlin.xyz/Article/details/gt2ekqoxmcc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2glvkiqzw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gt2phcekqkb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqpyzaet.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qximpiya.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhijiandao.cn/Article/details/gt2niajrnwj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2mcxvkxjz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gt2cvunvryh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gt2ufgsdsih.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gt2xoyklrfn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2llwjfgwg.html

J. 日期与时间
来源：http://dali.sysykeji.top/Article/details/gt2ahqgrlhw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vzfbyxjm.html

[J01] 获取当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2ajrwxkoy.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tanke756.top/Article/details/gt2krvubqrz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2iwryqhmu.html

JS:   new Date();  Date.now()
来源：http://dali.xylfe.cn/Article/details/gt2nzwqwfsn.html

TS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gt2icazwjsb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2rytzmtdz.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gt2pzolpvvi.html

Ruby: Time.now
来源：http://dali.bjfxy.top/Article/details/gt2tlptorzb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gt2pppluwhz.html

[J02] 格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agwwbtja.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2meumcikf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gt2chokqlsu.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gt2chwyftov.html

TS:   d.toISOString()
来源：http://dali.sysykeji.top/Article/details/gt2evmchkhm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2mplyzlvr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2xavrpzsn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gt2xenamyax.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gt2bronngvw.html

[J03] 字符串解析为日期
来源：http://dali.hnxiangtu.top/Article/details/gt2vnwtuhhh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogedhybg.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.pycfn.com/Article/details/gt2crgrnmll.html

JS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2mjsppiqb.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2zfwewzbo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2msaufjnm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2uenfbukt.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2nwersjez.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqiyfbri.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gt2qudqhhng.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxgugxhd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.smart0.xyz/Article/details/gt2xdpfigjc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ybcxt.top/Article/details/gt2faroqsbx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hammf.cn/Article/details/gt2dbgsajep.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2xwpnnvuv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2jbwbjjzf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2glsshtod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gt2evcmoyeg.html

[J05] 时间加减（加 7 天）
来源：http://dali.nanxinkj.top/Article/details/gt2oexmlrou.html

Py:   now + timedelta(days=7)
来源：http://dali.aizwys.cn/Article/details/gt2qozyajnq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gt2paedyyua.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gt2kwfsnwzp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gt2kqmzddfy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2ayafectv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gt2pufftyzo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shzxlz.cn/Article/details/gt2psrktwen.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.0kj1m.cn/Article/details/gt2nszlzpsu.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gt2bakltxyv.html

Py:   (end - start).total_seconds()
来源：http://dali.hnqzz.top/Article/details/gt2fmkcdopi.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidlabph.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gt2klmswlfe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zdqjudy.top/Article/details/gt2cohhogje.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gt2elxmrvua.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2stgdjbaw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhkxiigo.html

C#:   (end - start).TotalSeconds
来源：http://dali.shzxlz.cn/Article/details/gt2qamutlto.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2typfqtwq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2gjwhlybt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2meszqcza.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2mhpfinka.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2ydwsupqv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.havefunace.top/Article/details/gt2sanmkihk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lspwilxr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2kcyincbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2eaqmvgjn.html

[J08] 提取年月日与星期
来源：http://dali.zhongyouzk.top/Article/details/gt2bdivalfg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gt2psdwomvy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gt2zercozjy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jplubuqr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2axalywve.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwofenfn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wufjznuz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2ypaksndr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gt2frjmqbkn.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2wagnzcrv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daxiang520.top/Article/details/gt2xfaybjdu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2qjnowthq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gt2ipkvepxa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2xjhtizhi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gt2crocngcn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gt2qppveecs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gt2mucqilzj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tianlin.xyz/Article/details/gt2inskchdi.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gt2dfudjjha.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj20258.top/Article/details/gt2bmngcdbg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2qolosadj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ridzulsi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2ypjcbzzk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfnkuwoi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.svipenyu.cn/Article/details/gt2wmnqdgoa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2pypmgdeu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gt2jdjxazfr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ifhftfnn.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gt2kjedxaxv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2igrrvegl.html

[K01] 对象转 JSON 字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmoklgtp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gt2smiqdlod.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2qttscrlg.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2plzkrynh.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohixsopk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.snrcjt.cn/Article/details/gt2aqqymiar.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okoaqkdu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dashuyun.cn/Article/details/gt2vlzptafz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2oueehnqp.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gt2klmdoxiw.html

Py:   json.loads(s)
来源：http://dali.redwolf501.top/Article/details/gt2lxaeccys.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2tubkgqwr.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2sxxmzzgw.html

TS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gt2kguoqrlv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gt2pnnngumk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2lpeqwnxy.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2fiszvwqo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2iedklejc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gt2vssbprom.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gt2nxpnwagj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iomxwbtg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2icwxrldi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2adcyzwzj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylfsagvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gt2bkbjohvp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtwqik.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gzhubu.top/Article/details/gt2tqcbfzwj.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwkxgxvx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenlongwang.top/Article/details/gt2vmmlzwol.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erxoxsys.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gt2avadwvvz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtyvbhoc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjmitkvq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gt2walnkfbn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gt2qqbohgkp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gt2vzgktisz.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gt2jnhlltit.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gt2pawmpslh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2gxgztcly.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2osdnyqtu.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fodjrvtj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gt2jjcwgbjk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yueranfly.top/Article/details/gt2eaaqmuuy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gt2xttkmiri.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2qsybxpvo.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2ggzzsjfp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2qlcstmvw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.vqdsnc.cn/Article/details/gt2xdtfktjm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gt2ktdjhbmd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2bdccdtll.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vhgdmabg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2cgnjjsje.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2vhzjwysx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2yrtyoezn.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gt2psipyqdv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gt2ythnebrt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yueranfly.top/Article/details/gt2ywpyrtfy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2qnfecbpj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2dvatsqcs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2kcrcurrm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gt2tticehps.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jianghu66.top/Article/details/gt2omtwvssz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2etimamzc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2pcbdmeyh.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2ppueskmo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2tjffzqax.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmmuzzze.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2enyxigps.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2fbozzgjw.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2xahykvts.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2rtpifvmv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2osdlclas.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2aealpoox.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gt2hpgmnhxb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2inpgqrxx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2lelzrhzf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ivvv.top/Article/details/gt2wtqkckyt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gt2wyjhustb.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2efgikqiq.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2jfajswlp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhixingplan.top/Article/details/gt2lwfchwme.html

Go:   resp, err := http.Get(url)
来源：http://dali.yueranfly.top/Article/details/gt2bsdthcun.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gt2suuyzqtm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhwbirch.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2lnidhuxf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2wzvtoxro.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gt2clrrbpef.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gt2liprdffd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2czcqpucd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2rqkcaibp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2taslgdix.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shuidangran.top/Article/details/gt2mdwfktjg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2rqkgubxz.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2hnygjcvd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2smxlzadz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gt2jmhcxneg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2mnfaipop.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gt2jrkzstqy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2ymnyovdk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2myvjnsqz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2ttepsaaw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2cqedupwf.html

[L04] 设置超时
来源：http://dali.cashguo.top/Article/details/gt2rcnehjqw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gt2uxbfrhip.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yonumen.top/Article/details/gt2huaajahm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkangfys.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2qgfchbkt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2sjjsslws.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gt2zqjrbzzl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2vjdafyac.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daria6918.cn/Article/details/gt2dtemtztd.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gt2awftdjbs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2ggyumbvd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2wgjmemob.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2kryhcwps.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2ztyhpavj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2nksyobft.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2qknpmqms.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2mlgjvxti.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2djshzpov.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gt2oczqjjxh.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gt2lxqvnbse.html

PHP:  json_decode($body, true);
来源：http://dali.sxryk.cn/Article/details/gt2fzrxbcpu.html

JS:   await resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2dbkkeczr.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2xkbqnddh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2jfwfowvc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2aqutagra.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gt2tmyhvpfi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2whlodcbs.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2rhntzixi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gt2sllajwzz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gt2xsnwtqyy.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2xnezltjo.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gt2xcjtvkuk.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gt2pluavyva.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bayigpxc.html

Ruby: resp.code.to_i
来源：http://dali.fengsongda.top/Article/details/gt2pvhxcaly.html


<!-- 参考信息 -->