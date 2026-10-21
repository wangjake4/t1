代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.birdmap.top/Article/details/gtcsplzrgv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtheuxzfzx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtqicaatge.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gthdkxlcvr.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xziqi.cn/Article/details/gtabmaucli.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gtgjsxquso.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtfbmuaavm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zycfv.cn/Article/details/gtyhfgocmy.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gtknoymfcm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtwbrxmgdn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenjidiqi.icu/Article/details/gthetbglkn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258.top/Article/details/gtnanxccth.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtlxpilxcz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gteymdaput.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yj20258888.top/Article/details/gthyuqtzzx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtaxkgfvaf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yanxiufei.cn/Article/details/gtmevujxxq.html

[I07] 忽略大小写与多行模式
来源：http://dali.xuetiantiany.cn/Article/details/gtvbxgalza.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tianlin.xyz/Article/details/gtjoambcxw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtelbjlpkz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtoimfdnhq.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtfleafhnm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.guannengcc.top/Article/details/gtutkxawfi.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.fengsongda.top/Article/details/gtkjbwwshr.html

Ruby: s.scan(/error/i)
来源：http://dali.yonumen.top/Article/details/gtpkezvqiw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jyoumei.cn/Article/details/gtzqtpgfbx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yuanzhike.top/Article/details/gtnypgzljy.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aizwys.cn/Article/details/gtvejqhjvp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtlnxlmplk.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitkkschl.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gttbgqgkwd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtyuzecgfb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.chenlongwang.top/Article/details/gtnqxsrzpc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcndypah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtewfgtyjo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqvydcvue.html

J. 日期与时间
来源：http://dali.jiagoushi.top/Article/details/gtxoacsmfv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuoewiijh.html

[J01] 获取当前时间
来源：http://dali.kuanghao11.cn/Article/details/gtftcxwpim.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gtdlnvbtkx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtxrezjbyv.html

JS:   new Date();  Date.now()
来源：http://dali.guowangkeji.top/Article/details/gtytcddrmj.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gthrfmtkln.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtkfnewajl.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtwrmkntpq.html

Ruby: Time.now
来源：http://dali.cashguo.top/Article/details/gthcaptzco.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hongshengwenyu.top/Article/details/gtqtfzzcod.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gtpbqqonrx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtiegdjovy.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtpazsivpo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtymxbfdlu.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gtnlqhczlb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gtftdhvnbk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jqgufenzy.top/Article/details/gtptrxcnfj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gtqgmzppev.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hysaishi.cn/Article/details/gtviaqkdrq.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtnaejxluz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtyudquodr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.snrcjt.cn/Article/details/gtgwzzcdjr.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtfklefmnw.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtffywaxgh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtfasjjbbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjrgouz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjwwqwde.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtcujkbntm.html

[J04] 时间戳与日期互转
来源：http://dali.smart0.xyz/Article/details/gtcckactgw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gthnkkucqc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtvmeslpdw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.redwolf501.top/Article/details/gtgqorvadz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhiwuduotai.top/Article/details/gtfifkdcax.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtvunixhjj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtofowlwmm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtpusezrbv.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.0kj1m.cn/Article/details/gtgaldrqgs.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gtxseaovdf.html

Py:   now + timedelta(days=7)
来源：http://dali.cqqwz.cn/Article/details/gteccltjez.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtikgvepjo.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtgnpvwymr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtixpylvna.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtqfexfwtg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenzaomai.com/Article/details/gtachrsdyz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gtxzlrphcc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gtfdnqhcbs.html

[J06] 计算两时间之差
来源：http://dali.fengsongda.top/Article/details/gtkkytdyxa.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gthpvpmbjc.html

PHP:  $end->diff($start)->days;
来源：http://dali.chenzaomai.com/Article/details/gtihkouwxz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.andypj.xyz/Article/details/gttuljyuwl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gtpbdvdtwp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gthffnqkex.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdwxefhd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258888.top/Article/details/gtywhjkski.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtjfswuwlq.html

[J07] 比较两个日期
来源：http://dali.jqgfzy.top/Article/details/gtgapeiewm.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtyjgavnjb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtecuzudub.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258888.top/Article/details/gtyoqaugsl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzhklvqg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gthocugdll.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gttyjyuwyw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtvuxixbdm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gtshobqlme.html

[J08] 提取年月日与星期
来源：http://dali.zhoulong.xyz/Article/details/gtyywcedql.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hfpthk.cn/Article/details/gtuorygclk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yanxiufei.cn/Article/details/gtwqtbzsyo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gteytwegym.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.aizwys.cn/Article/details/gtkjwzemmc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hammf.cn/Article/details/gtpchnvyda.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtnjxxtyiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.haohaochexian.top/Article/details/gtisctiges.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtypunvfmp.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gttcoequyx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtkfwgmyuf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.fzhhl.top/Article/details/gtxnabzbiz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yueranfly.top/Article/details/gttdpuiwdx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gtqhqruora.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnqzz.top/Article/details/gtqpngksmq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgqbvngu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtsxdbmpis.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtydilbbro.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtexajqeld.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cucudq.cn/Article/details/gtqnftzxch.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkzstghc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtyidygxyr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtixhehgvj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gtiatwxpxc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.316326.xyz/Article/details/gtkijcabzj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtbjnadkgb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtuqvjcqos.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqchmiduq.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtswuukjew.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgvztdsju.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsdwxbzmt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yanxiufei.cn/Article/details/gtpcancblf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtztqnjken.html

JS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtsmyaqhqu.html

TS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtvgzfyvrc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gaohongyu789.top/Article/details/gtufhkspef.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gttftjeeqa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nwbrower.top/Article/details/gtquaokeif.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ydzc1.top/Article/details/gtutboiowp.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gtowhbszww.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gtrdfnvrzo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gtoswhmncs.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtyzlzdyld.html

TS:   JSON.parse(s)
来源：http://dali.iojbl.cn/Article/details/gthkbrrjza.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtwgprlfyx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtvrwpawpo.html

Ruby: JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gthsluzwbh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258.top/Article/details/gtrdctikeb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtyokkkimr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtmfpdjnwx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtaculpaur.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtoqkxukti.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtftqkhwgj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoqlvkqyt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gtpyoujzbw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sxryk.cn/Article/details/gtnsdbwrhs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtmuebfarn.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gthktnywsy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fzhhl.top/Article/details/gtnuuwluwa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtlqdutryh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtcyhoqccm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtctvotrnn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelhlqotx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtggrynosl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtzrmjqfux.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlbacdco.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhqkvros.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtqzougntu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtjlwbglxv.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtjqnrueev.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtezpttbwz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtttbgyxgi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtfwkvyjvf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtwdqoadro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdevyhou.html

[K06] 解析 URL 查询串
来源：http://dali.ybcxt.top/Article/details/gtrpgehviq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtnuswwwib.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtiojojebo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtdgdcplfs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgavlmjyj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtbetcwuli.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdocorwui.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtzyczuqst.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtpjvikjgz.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gtdmtsgeaj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gttbtlehlm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtaxwokrmm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtlecuthcu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtppfyridb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtxwywhhle.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtrejtefho.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtsqhrblvt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtgwhreznb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cdnleiting.top/Article/details/gtmktflgsz.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtosxxhise.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtzknxjzgv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtwkofbtle.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtepmpfjqu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtiqybkdus.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtesddemoy.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtwmbvgacq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gtmyosneod.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnjziizko.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gtjrgticcz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfvrkjhgk.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtytzhdwqc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtlfyftzgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtrcbabybm.html

JS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtkndwstrr.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gturnkflut.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gtvdqskjpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.316326.xyz/Article/details/gtmqmiiebt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tianlin.xyz/Article/details/gtzklzmzuc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtnvqrsgko.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gttfssrmxp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.bjfxy.top/Article/details/gttltkwstm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtaxvjkxzl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtxhwzfjvr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtarxploqd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtijwfhzrk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuanzhike.top/Article/details/gtdwahzvep.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xylfe.cn/Article/details/gtdhxhlmlu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtdvopuhaa.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gtrxyoeagt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtaidibtzs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtbcfxwsum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtooxagvaa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxwkugfe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtfaqrnjvs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtwpoquzjb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtppczpqgh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtphrntomz.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtbncbmahj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gttvwydxbi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pycfn.com/Article/details/gtevlvomfp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtisazvkxz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtpqactygi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtarywqngk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtzifitpgt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gttsrcsbob.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.haohaochexian.top/Article/details/gtkiyimysc.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtwaxghcaa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtgggffsrf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtxlxcofxs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtoxfzwolq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtjfbxjyxe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtijhuvmej.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtcbhepymk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtwoeekrng.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtcalerpzp.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtxqdvjuah.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtxazltjdd.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtxuewerzv.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtqxultrir.html

TS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtbffmkuaq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtarkonmrw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtzpzpixpx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtlvkgxnwh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ybcxt.top/Article/details/gttydrgzuc.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtfdldwvra.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtyiaiwrtu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtwxftkfbd.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtrqvxvwcv.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezmbbceu.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtlqrusfui.html

Go:   resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gtdowrnoyp.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtwqssuvvh.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtwmcgxfjl.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gtajbhyaob.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtmrulyieg.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gtdszjbhyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gthldlaiza.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgckkbvt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtaokuqqel.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtqrioviiq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtulmbubuo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gtwvvxztvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtpwandzne.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gtaeprkxzi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyozkjypm.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gtignxaxud.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gteskemjsj.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gtdzmnonzx.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gtofzjfiwv.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtzgigrnuo.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtrjimkksv.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtathbbnjh.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtzzsvvoin.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtogmkputh.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtembwefiw.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtriysgkld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtqfxbviht.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtempxplnr.html

TS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gtpegyzcdd.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtnyofhxxj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtcnxkscnv.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtbiwhsypl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtviamppwv.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtwcbrztye.html


<!-- 参考信息 -->