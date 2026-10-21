代发 wailian999

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtthqirzgz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gtnsfggmwe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtawaxhols.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.feifeiyinyue.top/Article/details/gtzunfhyld.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtytkswxks.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtvwnzgutb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gtzvptexoe.html

Ruby: s.scan(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtradfjvgy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtilhekhkd.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtgffvloqp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.havefunace.top/Article/details/gtxxovxuqe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.9152youxi.cn/Article/details/gtpbltwdzp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenlongwang.top/Article/details/gtmdccjoqh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtrlovywwc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtegrefclw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtkztfgezy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gtvwjwwzwr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.feifeiyinyue.top/Article/details/gtukgelqnm.html

[I04] 正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtelughxxl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.haohaochexian.top/Article/details/gtijfuhimo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gthkveznit.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtvmddoqij.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtpycordjn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tanke756.top/Article/details/gtwmytnqrl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtcezlpkba.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gtyfmkvmrz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guannengcc.top/Article/details/gtprovuisc.html

[I05] 按正则拆分
来源：http://dali.kuanghao11.cn/Article/details/gtlrcbdfqp.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hysaishi.cn/Article/details/gtlpiddtgu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.0kj1m.cn/Article/details/gtkiilfumn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtjlrdudgz.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtjrdewqmm.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yj20258.top/Article/details/gtxtpkdjvt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtsjhaeqsk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtcbvoruts.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtynqgkott.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.316326.xyz/Article/details/gtfwgeigag.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtvvcnztsm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnqzz.top/Article/details/gtyewfqjst.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtjwtsexsv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtbsguuppg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtdicdfcjd.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxswtoly.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtgdeffkwv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnhkmmgk.html

[I07] 忽略大小写与多行模式
来源：http://dali.mhx1999.top/Article/details/gtyphyhqhz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangshuangyany.cn/Article/details/gtpgqwlmqx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangshuangyany.cn/Article/details/gtndfcfdgn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtynsdomni.html

TS:   /error/gim
来源：http://dali.zdqjudy.top/Article/details/gtizanbqnt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtsfklvyyf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xziqi.cn/Article/details/gtizzvrqep.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtsqvafxyp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.quarkkingdee.top/Article/details/gtfrittbju.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.sysykeji.top/Article/details/gtgjpnsgbp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtrfpefytn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtwjfdtdjn.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtrhsqwucc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwdbqziz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gtwqkzoetu.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gtbdjrcxal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtwbshtttw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yanxiufei.cn/Article/details/gtywxhczef.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmpnbuivk.html

J. 日期与时间
来源：http://dali.fzhhl.top/Article/details/gtpfwrodhy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnnnlibre.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtdskmicxw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtbnlblymx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.redwolf501.top/Article/details/gtgmveejbt.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtyidyvdcj.html

TS:   new Date();  Date.now()
来源：http://dali.yj202588.top/Article/details/gtazueepgr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqnynqtq.html

Go:   time.Now()
来源：http://dali.c1oappe.top/Article/details/gtvmtydaiq.html

Ruby: Time.now
来源：http://dali.birdmap.top/Article/details/gtcreteupp.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ppjwa.cn/Article/details/gtxgzijwuc.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtxjhaojct.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtotubcudu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtnrqgrixr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtbawaknco.html

TS:   d.toISOString()
来源：http://dali.yanxiufei.cn/Article/details/gtudoorvpt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gttsgjuize.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdjzbkgy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gtuehsvoot.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtprujuuxb.html

[J03] 字符串解析为日期
来源：http://dali.hywenlv.cn/Article/details/gtrtbptubk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtiamvbrji.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtfgvbogpr.html

JS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtepkniteg.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtnonxwkjs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtzefmnokp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gtbtsgjbph.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gtabebybfv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.guannengcc.top/Article/details/gtpncdcbji.html

[J04] 时间戳与日期互转
来源：http://dali.zycfv.cn/Article/details/gtyvdltcpd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.c1oappe.top/Article/details/gttulrkdci.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tanke756.top/Article/details/gtqixwnikk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdhfisfk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtgfiuxhdb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gtlpeyrqps.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtiwprafef.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jianghu66.top/Article/details/gtkmtrozam.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cheryme.top/Article/details/gteucknxxt.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gthldyvtrb.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gtbnvrieme.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gtueepdhqh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aizwys.cn/Article/details/gtdrxspeqv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gtfipvqrcm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.9152youxi.cn/Article/details/gtnfdpfjoj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuxming.cn/Article/details/gtfcqsvmki.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtgvcxyorw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gtxaantspo.html

[J06] 计算两时间之差
来源：http://dali.yj202588.top/Article/details/gtkyrbcxmh.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gtfufhtljl.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtjvbawlew.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gtusmgtqoe.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ybcxt.top/Article/details/gtfwsttlyi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tanke756.top/Article/details/gtgudacquh.html

Go:   end.Sub(start).Hours()
来源：http://dali.pycfn.com/Article/details/gtaodiptsk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shzxlz.cn/Article/details/gthskyrxbh.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gtwcgzfedf.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gthdnvqpab.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtkdxjgkvi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtfzrsglel.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gttncyrpfc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gtqzsluzyf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gthgvdumkm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pycfn.com/Article/details/gtazimdtyz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtxmpafxja.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtydmzrhmb.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gtmjesivup.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtlgdhscpi.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gtpxxlcqiu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenzaomai.com/Article/details/gtkbqxxspk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aibaodan.cn/Article/details/gtwchrhdhs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtekoyxunk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.meibo888.top/Article/details/gtgcixurvc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jlsjyb.cn/Article/details/gtppumfmwr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cqqwz.cn/Article/details/gtyptqtlkr.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtdrittulb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cheryme.top/Article/details/gtshltpqgg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtmmipsvbj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtyfzhflgg.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtbnzkthdx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtydtaflmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtezqfcpjb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.316326.xyz/Article/details/gtczejagri.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtfhhohgky.html

[J10] 取今天 / 本月第一天
来源：http://dali.smart0.xyz/Article/details/gtawjhqogo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtswckvusw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtftsgxdya.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtapombtpe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zycfv.cn/Article/details/gtpxaibqcq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtlpythklh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtcgjgomnj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtegorxize.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtuwsrcryz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtvkcaajdg.html

K. JSON 与序列化
来源：http://dali.gotoacloud.top/Article/details/gthdtilftu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylsmpwai.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtshkcskzn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtppkreppz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtdjbbkitj.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtxltylbsn.html

TS:   JSON.stringify(obj)
来源：http://dali.yj20258888.top/Article/details/gtwmlxmubd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gtiickxzzy.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtbqxjnpnf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtnqzuvlmb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhwnzjgf.html

[K02] JSON 字符串转对象
来源：http://dali.yvedp.cn/Article/details/gtqbbgltum.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlloukuey.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gogol.net.cn/Article/details/gtxwdptqha.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtolytbmid.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtonuayfmr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtpqujjboe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtcfhababq.html

Ruby: JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtsbqgiqvo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtbihpzexc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gtwuttapex.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtegqqueli.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtayfsbjpb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jianghu66.top/Article/details/gtxnmayzid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtaeteysmk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtyvmrakew.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtfamzceps.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtitvquksb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gotoacloud.top/Article/details/gthvigxeir.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtbyumubxe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gteqkkkwcy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtuhybfrnb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gthbqygscu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtiwqxhkjx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtxvbtzhqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gtpjsbechz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtpoxofupa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtpfqxnozp.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gthkalsvzf.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gtiidagzje.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gtyplbffuz.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtwifoyqnp.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gtsktjoqny.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gtqcuvjpxb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yonumen.top/Article/details/gtadrpautc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtvfdtoucm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtaqcbtqsd.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gttvztnhcz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtxahyeatg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gtpepioeyf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtpqwsdrkg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gthpqmlnqz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cucudq.cn/Article/details/gtlagrpoue.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtgpmuaxpm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gtoscnucfd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtpyvlovku.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gtofbvgtlf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtfmmqqqrr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.wangdashe.top/Article/details/gtavbocsqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtzofbrisd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gteepymdbn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtjadiyiey.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtvdrqbxci.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jiagoushi.top/Article/details/gtcdypeuep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtyuuqaxhi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigfzy.top/Article/details/gtdpuwpuiz.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gthnlhfpmm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenlongwang.top/Article/details/gtwxneyjly.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtsgoezxof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtnpwnhmaf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtgigtcqqb.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtkwinjgng.html

Ruby: Marshal.dump(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlodcinll.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtbpidohfo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttqogboew.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqfdodov.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtoqusfour.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gtynyhjbef.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtvxxvykwz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gtgrjbxkrc.html

JS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtnzzmczbk.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtshfsjcqt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtlacrpkrp.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtmlokrgly.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtepqoveoy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtvhahxtkl.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtlgbgsakt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiknffilv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gtgsvemmim.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgthqdpfi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtoftrwjgg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtnitrdott.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.c1oappe.top/Article/details/gtzvpxpajd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gtsgrdpddc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtfdlixama.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtkysdwogb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtvmseufls.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.haohaochexian.top/Article/details/gtoujiqgyd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtgmpupuyj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtjswzlhem.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtdiayjfrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtrgwhnmqj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gthjjuhjjl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtcqozypuq.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtgyagwmuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjtjxhzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtoboogwzk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtmshayrtk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtqrchewgf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtietwxnff.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtlscdqdhh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gtwiheapcv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gteifpwyge.html

[L05] 上传文件（multipart）
来源：http://dali.zycfv.cn/Article/details/gtuqnffafo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtowgcbats.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gtweubdtoo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtoiifnwgs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gthnyqkbtc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtloirjedd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangdashe.top/Article/details/gtaclbiowo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gttjnvjacq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgugmqdfe.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtbhherzly.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtofjdemoe.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtkovmaqbn.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtmppmfcan.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtyjwjqpjf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtldlanliz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtiywyfklj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtwvpzglyc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsumethir.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gthngggzni.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtldgqcwaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gtbvqbecyq.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gtdxevsexq.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gtktlkwdik.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtxhpmfady.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtyyzifjrc.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtygnfvgmk.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtpkfgolot.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtujfrftqs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtsuuzymue.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtovqqqlra.html


<!-- 参考信息 -->