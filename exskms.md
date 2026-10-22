代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sxryk.cn/Article/details/gtpuvubhcl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj20258888.top/Article/details/gtpujnhbby.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtjiqvsmqg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtjhmahpix.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gtkokiawrd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cucudq.cn/Article/details/gturftdozx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemyywtzg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.quarkkingdee.top/Article/details/gtaaewwuwk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtbcyexnzd.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtdbxuohby.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sweek.top/Article/details/gtyzfuoemm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtxizorocw.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtlhkmiruq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gtppbtyxsa.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtwvsdbolj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ivvv.top/Article/details/gtzycghdyp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtgjfbzvuk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtktuqrnnu.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sysykeji.top/Article/details/gtyxoqyivz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtueppqpeb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.dianchejie.cn/Article/details/gtznolgrjj.html

TS:   /error/gim
来源：http://dali.0kj1m.cn/Article/details/gtfeficjbs.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtxjfmzqdp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtramtiolt.html

Ruby: s.scan(/error/i)
来源：http://dali.birdmap.top/Article/details/gtnfcehzof.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yangfankeji.com/Article/details/gtpjiconlm.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.fzhhl.top/Article/details/gtenilzwar.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yueranfly.top/Article/details/gttswxtssc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtecsmawfp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfjmfncy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.havefunace.top/Article/details/gtszrstvur.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtcszhdusk.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.mhx1999.top/Article/details/gtkhavtnlb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ehwqpu.com/Article/details/gtzizqyapp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtwxgsugxw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtqymuqhly.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gtucrfyhca.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvjhyinzf.html

[J01] 获取当前时间
来源：http://dali.hnqzz.top/Article/details/gtdniqnoko.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jiagoushi.top/Article/details/gtljnpuxxu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jlsjyb.cn/Article/details/gtkgyjxqmu.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsvcupov.html

TS:   new Date();  Date.now()
来源：http://dali.hammf.cn/Article/details/gtsdsrwgbv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojyinsav.html

Go:   time.Now()
来源：http://dali.tanke756.top/Article/details/gttadvqeyn.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gtnctjybag.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gtmoyfgoxf.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtmxenwvzj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtdidqpjmz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gtgrpipadf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ehwqpu.com/Article/details/gtpmjntswo.html

TS:   d.toISOString()
来源：http://dali.yvedp.cn/Article/details/gtehvrqlww.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtfsloawkk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtncundpwk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtuhhtytdz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shangyingyoupin.top/Article/details/gtvbsifotd.html

[J03] 字符串解析为日期
来源：http://dali.daxiang520.top/Article/details/gtmeoduurc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.redwolf501.top/Article/details/gtiwclunmh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gtoywqevmo.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtlnalmawl.html

TS:   new Date("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gthvcedncc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gtpetxgbwm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtmjlgvhsl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrfenckf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtehlytpqw.html

[J04] 时间戳与日期互转
来源：http://dali.gogol.net.cn/Article/details/gtanpkixgn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yangfankeji.com/Article/details/gtlcnwcdrh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtnsfpbemp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.aizwys.cn/Article/details/gtdzyawqfc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.316326.xyz/Article/details/gtxsdsonsx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gtywwjtuaz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jyoumei.cn/Article/details/gtgmxvltwi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dashuyun.cn/Article/details/gtgcvsjasd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gteqqqnfjy.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgufenzy.top/Article/details/gthbmntrzr.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtunmyvimq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tanke756.top/Article/details/gthfhnjgmf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreqjfhza.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dashuyun.cn/Article/details/gtqxhfpwiq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.sysykeji.top/Article/details/gtmognhjkp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yangfankeji.com/Article/details/gtwtcezqiq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbhcnzab.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtmaufhqcj.html

[J06] 计算两时间之差
来源：http://dali.cashguo.top/Article/details/gtfgkcosat.html

Py:   (end - start).total_seconds()
来源：http://dali.xuanzx.com/Article/details/gttfitanau.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gtcltegjhx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jlsjyb.cn/Article/details/gtdluwvstr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtnrjgpywy.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.bjfxy.top/Article/details/gtaorntpkc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cheryme.top/Article/details/gtdfnkflkb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtqywjcivj.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtwhzttews.html

[J07] 比较两个日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqivvwsr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbogkqlth.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtzdjydigt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hfpthk.cn/Article/details/gtsxdkvyva.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtxoywfgkj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhengqikj.top/Article/details/gtbiolbvcm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtugepaxdl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnxiangtu.top/Article/details/gtocoecndf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtdgxpzrnj.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtsfksjrac.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gttanbgsog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtoacvijnw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ehwqpu.com/Article/details/gtsmmmkuco.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnuleduh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtxoaqsonc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gtiuuibjpt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbomgrhv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gticarpfww.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtsumbjmas.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shangyingyoupin.top/Article/details/gtjmltnath.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtmvlxxlky.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtfdnvhshf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytefcive.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gthcxpoial.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yueranfly.top/Article/details/gtjulnpyon.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjudevdo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtwffumuui.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gtdglljpjr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgufenzy.top/Article/details/gtcmqmwgwe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtrnbbmsof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gtpddwhykh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtrswtmgzi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jqgufenzy.top/Article/details/gtgdthlbvs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sysykeji.top/Article/details/gtxpnodqpq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtmhroimdr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgtvkancd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttvuebgla.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtdimcthxb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtjtsbtjzt.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gteqoiaaot.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtdfbsibgi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtzmmqacxb.html

JS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtasgkadlg.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtlejkyhcj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ivvv.top/Article/details/gtiquhfmle.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gtxiyxiuzb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtyamcrspe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnpgpfyr.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbxzeiwa.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gteyosamur.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtqwambzdq.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtmzdzqoyf.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtldvjlmqs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtkgsbltrv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtqnwfuxhk.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtokfxflpq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtxzpaslem.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtmawtfnel.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtsgedimtx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtdczhcgiu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gtphepdvnk.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtgcafsaju.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtnykzmnpd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtamnqfqpr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtlospwmvc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtbtprbakf.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gtuuphcukw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gtwyelqtna.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtxiqbwlmq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtohvlfcnm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtbfoilnwu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtylbzzvao.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtebnukekq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtobomljlr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtykbkwzng.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtgdiapbrf.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gthuewcftg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtaepcqrsl.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtaspkodnc.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtklknrucp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtltxscqbe.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtfhqhplji.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gturlrcfrx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtadkmvetr.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtxioeunii.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gtbkvdhurl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtfwkkribg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gtlfqmqfpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtqmyloivv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnnnsfnd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtueiadmgp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtvwluhjwl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtmgqngbvh.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtypeorplo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtpbwtreas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtgzpjgocz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtlpmvfqtx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtpmnacaao.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtqyeashhk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxuanxn.top/Article/details/gteptajmws.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtejhbiwob.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunbbjglh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtlhvbuimw.html

Py:   pickle.dumps(obj)
来源：http://dali.yuxming.cn/Article/details/gtbelawgtk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yongpay.top/Article/details/gtvkgvnera.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gtolwiowur.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtofikkcbk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtexezvpgr.html

Go:   encoding/gob
来源：http://dali.pycfn.com/Article/details/gtxmuyksnl.html

Ruby: Marshal.dump(obj)
来源：http://dali.fengsongda.top/Article/details/gthhzkdbbq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gtucdnoylr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gthkgoucas.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gtkihsucxc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtzdihncbn.html

[L01] 发送 GET 请求
来源：http://dali.fengsongda.top/Article/details/gtkwsnctun.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtwtnitjxn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsbwwqro.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gtsifrnsgk.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvsdxygs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtzmemjfjb.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gtfjstplhh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtamrbmoaa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtoibpddgf.html

[L02] 发送 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtagabzjat.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtiaaejifp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtzniivofv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtimmryohu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gttmfckrto.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gtsdezbfdn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtwwlnlfkm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gtjsdjhaxe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtvdkhoiap.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gttcxwsope.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gtdqsjsllm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtmkxuoexx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtjnwbsaer.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtragumzcq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtgbnfpxjn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gttouaimyr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigfzy.top/Article/details/gtjqfphcuh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeujcbsd.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gtjxxgwtvc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shuidangran.top/Article/details/gtjwifkjwv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtlkwcveqn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtqxavwsrm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtobaertbz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fzhhl.top/Article/details/gtpkdsfyyq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaquwfjwn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.bjfxy.top/Article/details/gtuazigxqr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtmvcxspdf.html

[L05] 上传文件（multipart）
来源：http://dali.fzhhl.top/Article/details/gtglzqnpyw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtcwvogxnf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtemkallgq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtiblbhzij.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtuohpnufs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gtbnwvtrem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.quarkkingdee.top/Article/details/gtlgynazfh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jianghu66.top/Article/details/gtcbyecumu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtfmahhtua.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtfkxslqea.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtoykxqibx.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtiagrrqgu.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gtaizcwlup.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtwzzhsyyc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtsoftuehw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtvougsuam.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangdashe.top/Article/details/gtyvlajqhn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtkecanihx.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtlonmrprd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtogjpicvk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtpologvdo.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtfkwoaolf.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtlkxgfvie.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gthlegdzhv.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtvyjaursv.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtbueghwdw.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtchahhxay.html

[L08] 并发请求多个地址
来源：http://dali.snrcjt.cn/Article/details/gtznvslifj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtqnirrhcd.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gtbgsoupie.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gtcwtptpgz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtgmushcls.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtztsmnhnb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gtohofilpq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gtezbngotj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwmhakfz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthtgdwjnn.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvlcuunl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqkeeowdy.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtxtprnwxr.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gtvnpgfkqv.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtxnhrohvw.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtyvtjgiyd.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gttxpanxud.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtbgxhbihi.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gtblchkdrt.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gtoziiyzdl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gteobqldep.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtltigqkle.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gteilxejpo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtfcyogmut.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtbguxrfaa.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtuvwmeavd.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtwbwgtamg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuetauesc.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtxskekhnx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtessvfnpb.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtbsuczckr.html


<!-- 参考信息 -->