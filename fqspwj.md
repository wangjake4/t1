代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2tybtkpus.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2jnudjanv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2ynvxqfia.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcpwyri.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zdqjudy.top/Article/details/gt2sjshkokc.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2kedumeuw.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tizrjgvt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbbuggpf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cheryme.top/Article/details/gt2ythnblef.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gt2xhijiptm.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gt2imcduycd.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2qujzkxrg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gt2xtzmvzlw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2tbuszovj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gt2cvkxjmtn.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmsngemc.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gt2qtaxoklo.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2lwpiptmz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gt2vwmspojg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjzqcsge.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ehwqpu.com/Article/details/gt2wapwcvxr.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gt2hasorsdy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.dashuyun.cn/Article/details/gt2jkgosqxg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sienmskh.html

Ruby: s.scan(/error/i)
来源：http://dali.yuanzhike.top/Article/details/gt2ihfbrcrr.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.svipenyu.cn/Article/details/gt2rxzouzoe.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gt2zbegdxcl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gt2ifvbcmwf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2xhmtmfnk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gt2tuxlnrir.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbvkptvo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gt2oxvtvjch.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gt2pdlljykv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258888.top/Article/details/gt2zjeslpds.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gt2wdrdxieb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2avcaakfy.html

J. 日期与时间
来源：http://dali.tianlin.xyz/Article/details/gt2oocweyad.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rsobqpwa.html

[J01] 获取当前时间
来源：http://dali.ivvv.top/Article/details/gt2jgezpcgw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvsopmx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gt2vgirzuel.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gt2znlnjcge.html

TS:   new Date();  Date.now()
来源：http://dali.wangdashe.top/Article/details/gt2qlsnajhl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gt2lajlrfsj.html

Go:   time.Now()
来源：http://dali.zdqjudy.top/Article/details/gt2tsydyjcs.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gt2thdtesqg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gaohongyu789.top/Article/details/gt2mciwrynz.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2cmjogigk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2jknhvveu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yangfankeji.com/Article/details/gt2gsasohxx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hnxiangtu.top/Article/details/gt2cpawcesl.html

TS:   d.toISOString()
来源：http://dali.zhoulong.xyz/Article/details/gt2zjzzmyyw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zycfv.cn/Article/details/gt2onvxalqe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.haohaochexian.top/Article/details/gt2viaadbiz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2opystsmw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqstxfpt.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gt2gmspmhyu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gt2lglpruuc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gt2xhyjmbmy.html

JS:   new Date("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2griiqars.html

TS:   new Date("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2kxslplsv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2zoqqvsga.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gt2dkhdfmdp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2clgjcvls.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.316326.xyz/Article/details/gt2wvnkydsv.html

[J04] 时间戳与日期互转
来源：http://dali.yuanzhike.top/Article/details/gt2penkmiiv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jplktagj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zycfv.cn/Article/details/gt2trdytiys.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yj20258888.top/Article/details/gt2cwytyevg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yj20258.top/Article/details/gt2kbafvkgn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnppsjvv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gt2xumvvqzb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gt2aorpjmwf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2kddfkpin.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhongyouzk.top/Article/details/gt2sxgxqnax.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gt2hvtenyfb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jianghu66.top/Article/details/gt2quiyfsnv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gt2ydapxdoq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2nctekwbe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbdvhrjj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gt2sljetfke.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gt2akbvcrfc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydlcjudu.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2ablfqgys.html

Py:   (end - start).total_seconds()
来源：http://dali.meibo888.top/Article/details/gt2dnjltfsw.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2mzjftgki.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yvedp.cn/Article/details/gt2gmyvfams.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2tykqpyiw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkvahwxj.html

Go:   end.Sub(start).Hours()
来源：http://dali.0kj1m.cn/Article/details/gt2ddrqmreu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ppjwa.cn/Article/details/gt2gayidgbk.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258.top/Article/details/gt2yiprwdcv.html

[J07] 比较两个日期
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxyporfl.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gotoacloud.top/Article/details/gt2yioiadfn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2eedqrxzd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gt2rairfwwi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmumrnfb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.guannengcc.top/Article/details/gt2odsadfzk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.iojbl.cn/Article/details/gt2aisnrhlg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccmrsxcv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yj20258888.top/Article/details/gt2yqunrgeg.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2rrpkwtgc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gt2uijsrmrr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2wivwgnwd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2faciezkt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hfpthk.cn/Article/details/gt2rvqfougl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinqigfzy.top/Article/details/gt2dbxkgeyb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gt2fncfjtoc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gt2iondoxsd.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gt2iybpzicj.html

[J09] 时区处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qenycpkh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gt2zdjfgrya.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sxryk.cn/Article/details/gt2gehhmaia.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gt2ompiyvci.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gt2jsewvaai.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2lylgrbmf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2hgramrja.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2irzjqvko.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gt2hogpcrzc.html

[J10] 取今天 / 本月第一天
来源：http://dali.meibo888.top/Article/details/gt2bczrpwrz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gt2phmofpcd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gt2gzkoxzpn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.316326.xyz/Article/details/gt2vluvvhwu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvafqajf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gt2oiqzssvy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2klcrrpcc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gt2ehuuibup.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2btthqlgp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bsmxksan.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gt2eojxxvmg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2nwsqcygz.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2xdshhzqw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sthwjnlm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2uydnfewu.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2rngnlsma.html

TS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gt2mygplwgf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrxafsvr.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2kwcblzxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhixingplan.top/Article/details/gt2sugudlsg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guannengcc.top/Article/details/gt2clclvjio.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gt2letqgdcp.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2kdephhbp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gt2gvrvnumi.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxfcpsan.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2pvkobkym.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gt2sozojhpn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2apzyfesy.html

Ruby: JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gt2heifglcq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttikhuwn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2ywrllhru.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2zgjlvjri.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byahltar.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2bnyxioae.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2acfdlhdd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qcssrthp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyxatlmp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2oifbnchz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.tanke756.top/Article/details/gt2ojpudmsm.html

[K04] 读取 JSON 文件
来源：http://dali.shuidangran.top/Article/details/gt2gcpvbftc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gt2arhxaqld.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gt2rsmrhmrk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnqzz.top/Article/details/gt2wlanwhuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.dianchejie.cn/Article/details/gt2pqseqzhw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2tyqafcfn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2ysvkcvze.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sxryk.cn/Article/details/gt2wlvmcdkn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2jcxqzkqd.html

[K05] 深拷贝对象
来源：http://dali.yj20258.top/Article/details/gt2lvraqdol.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2hdxgztha.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gt2pexwhxrn.html

JS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2zxaprmcq.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gt2kofgqxiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gt2xjudfljl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2mhhnvaid.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2wbtjdtno.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gt2heivafhn.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gt2brqnkurp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2jywxyunr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whciqmna.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gt2iecyindk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2pbtbokgx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2ewgizpwt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gt2yhyrcygs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2xdlttdbl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2rdaxwzrn.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2ongojagg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uagxjxoo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2totrqwqn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2sndpnrro.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2vhetxvtn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2btdjzyuq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yanxiufei.cn/Article/details/gt2ezvemckz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gt2ekwvkgpe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2syetuhyu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2jrfzniud.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ynymjmwr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2xbguolmh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2slzsgamm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2pakybskr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nwbrower.top/Article/details/gt2auspgffp.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2zdgxjncx.html

Ruby: Marshal.dump(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbbggtua.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efddmayh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mvulgotf.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gt2huzmemkl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2moszrzgy.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gt2mzxrjetw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvweqjjt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.kuanghao11.cn/Article/details/gt2osvrizhf.html

JS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2orcougnp.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2dtmxekxd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gt2xqzdtira.html

Go:   resp, err := http.Get(url)
来源：http://dali.xinyue.icu/Article/details/gt2ovzoaoop.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwpjnkgj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2tldeghmo.html

[L02] 发送 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2yindoift.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2nqcmpjcr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gt2azejljtd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2gtglxmtw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2xbrxlshr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gt2ptoospnp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gt2zujnbssu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nwbrower.top/Article/details/gt2ttvdqeub.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbfdgwps.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2knbwibxr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gt2bdpdjpcy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gt2szdwpipu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2nmjzblri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2zdubztov.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gt2kljdcsej.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2owdrcyxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2bqxniyvn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2uefybomj.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2pmcyvzqy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvspstnp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2gazvnkqb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2becvfhtl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2vosijaib.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vgpgxxun.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gt2xmrwwica.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuwtikyf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gt2tbwiohau.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2wgvpqivz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzttbixo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2qbxchutz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2ewjflgbe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2jxgfyqen.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2jqvgymwt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gt2dqrweenn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gt2adxiauie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2jbrnkpnu.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2mitarfsn.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnjsjckj.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gt2isqhoxhb.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2rbxaciqe.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2vwbrteha.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2ihedfcsv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yangfankeji.com/Article/details/gt2kgmfsoag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbuqdouk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiaoiwpl.html

[L07] 处理 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjxhbdqw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2evjcwlsc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmgupvie.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxinkj.top/Article/details/gt2xuhdodhp.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2ptvqqunq.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2mecfcpsw.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2lfsbntxp.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2lzyeptqt.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2pglnimsb.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2rgtrnwzo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gt2gomctcii.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gt2kspchgrq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gt2tcjidgmd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gt2iangkqvu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2ksymuzvd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdjtljkp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrwdohe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aambjrff.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2lfmsnqwy.html

M. 命令行 / 进程 / 环境
来源：http://dali.yanxiufei.cn/Article/details/gt2dmwswxrf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2dvrlabnc.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gt2bsgfoexm.html

Py:   sys.argv[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2gwabbdju.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2fzrrjtjv.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2fmuewbse.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2hoaamzir.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmtnzbhz.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upkvovol.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2uafhxlwd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2dsslttoo.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gt2txyiemcy.html

Py:   os.environ.get("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2kywpdfuz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2dzxobsuw.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2ruyewakn.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2hvjgyriv.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2opfaajld.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2zkboupay.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2sjokonhh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2fophqdaq.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2bumfpyrw.html


<!-- 参考信息 -->