代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gtclpabazp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtxqltydlt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtacvfwmzv.html

[I05] 按正则拆分
来源：http://dali.ehwqpu.com/Article/details/gtqjilyaxk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yongpay.top/Article/details/gtmabxoshc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtpuxmwpvj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtdrvkszlj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.chenlongwang.top/Article/details/gtebbtiemz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pycfn.com/Article/details/gtcocxfriw.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gtjzeshyof.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtuyuxjntn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtssxeaiqw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtoymflagp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtjpgyixqa.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dianchejie.cn/Article/details/gtpzbjuiru.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenjidiqi.icu/Article/details/gtoebeamhm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtkdqrscee.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.meibo888.top/Article/details/gthhdgrrvs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtstkgumrm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yanxiufei.cn/Article/details/gtvskmxxco.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmutzxmu.html

[I07] 忽略大小写与多行模式
来源：http://dali.yonumen.top/Article/details/gthlsmfowb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gtqnitguzu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtwmdrzuzl.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.aizwys.cn/Article/details/gtotbctvdd.html

TS:   /error/gim
来源：http://dali.iojbl.cn/Article/details/gtfelueykb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrggqajb.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gthhsbchng.html

Ruby: s.scan(/error/i)
来源：http://dali.cqqwz.cn/Article/details/gtvmkjbdor.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gttjkhnnkq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtmiafytnz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.9152youxi.cn/Article/details/gtbfhbdgmn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zycfv.cn/Article/details/gtssbizwtq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtqebewlxh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.feifeiyinyue.top/Article/details/gtmsmcrcoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daxiang520.top/Article/details/gtxcuqxwdt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.shangyingyoupin.top/Article/details/gtxcycrnsy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gtzlsenkmm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtnndltonr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttvdllonn.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtpwpnlide.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbheuiwai.html

[J01] 获取当前时间
来源：http://dali.svipenyu.cn/Article/details/gtnpbpobkg.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtqnqgbpaz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtislbfhdi.html

JS:   new Date();  Date.now()
来源：http://dali.ivvv.top/Article/details/gtxbbyyhfb.html

TS:   new Date();  Date.now()
来源：http://dali.vqdsnc.cn/Article/details/gtiwblctvn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258888.top/Article/details/gtxznpfcym.html

Go:   time.Now()
来源：http://dali.zhongyouzk.top/Article/details/gtgjjxmryo.html

Ruby: Time.now
来源：http://dali.vqdsnc.cn/Article/details/gtltmcgfnh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.feifeiyinyue.top/Article/details/gtjyqfxppp.html

[J02] 格式化输出
来源：http://dali.tian-w.cn/Article/details/gtlfrpqhfv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hywenlv.cn/Article/details/gtidyfbuzw.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtjovooczx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tianlin.xyz/Article/details/gtwlfpkexy.html

TS:   d.toISOString()
来源：http://dali.xinyue.icu/Article/details/gtypqiqvoq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gtqrzkhacj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtwfuobbsz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtykhaudvu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jlsjyb.cn/Article/details/gtosbadvdv.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdlsnpgg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gtujuxdkvn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.nwbrower.top/Article/details/gtuodbukox.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtfyykqjkd.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtffgolbch.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtqaawzxsa.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gtwyhpzblf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtxdlluorf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtuqzkcfyb.html

[J04] 时间戳与日期互转
来源：http://dali.ehwqpu.com/Article/details/gtfioguajm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkzzdjmr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gtslxvmjcu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gthchtcxkc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gtpswjpffr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tanke756.top/Article/details/gtwshmndoi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtbbrkyjrp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yvedp.cn/Article/details/gtxgugvqkk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gthsexnulh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtikgzzbfe.html

Py:   now + timedelta(days=7)
来源：http://dali.shuidangran.top/Article/details/gtedrbjgyb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxlkehoa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtcorguuii.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtutbsdbim.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtryaqihut.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shzxlz.cn/Article/details/gtmevfzgvl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pycfn.com/Article/details/gtlcqstcez.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gtlbdfkkyw.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtwopdlcll.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtonqshlhj.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscofykiz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gtchbktrdw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.birdmap.top/Article/details/gtctmcleyo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtenuqqawd.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtbmlddhjl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtgmaqyhzr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtsijbaczd.html

[J07] 比较两个日期
来源：http://dali.tian-w.cn/Article/details/gtfydziqpe.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtnejiorfo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtxpvugjsy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gtpyjnsgeu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoddtvhe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtotlvoaqw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtrsmgpowd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxuanxn.top/Article/details/gtpafbpbci.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtmfwojhnc.html

[J08] 提取年月日与星期
来源：http://dali.ehwqpu.com/Article/details/gtlctumove.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yonumen.top/Article/details/gtqwrjtyim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolnescuf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgufenzy.top/Article/details/gtgkhzqgrv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtztdktnxa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtoslqgpvw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtrojnbjxc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtgqmhzqvw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.mhx1999.top/Article/details/gtevjmoomv.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtbmdxnuxz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtbghtmh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtmnifpaqq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtaiwavhyq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gttzfliifx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cheryme.top/Article/details/gtwnjmjenl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhengqikj.top/Article/details/gtnnxyyyit.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangdashe.top/Article/details/gtufdwbmxf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.tanke756.top/Article/details/gtnjiwhhmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtanavowbc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcijksxso.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtljyqrgxn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sufxvd.cn/Article/details/gtjksecaar.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtwjurptgr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtxsltexkg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtnobuukwy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gthlvcwbwb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ivvv.top/Article/details/gtajdvnbzc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfzsqiscp.html

K. JSON 与序列化
来源：http://dali.nanxinkj.top/Article/details/gtwdrlcvsg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmhbcdkxk.html

[K01] 对象转 JSON 字符串
来源：http://dali.dashuyun.cn/Article/details/gtsovlwaeb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtatnniyan.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtybommoij.html

JS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlghairtm.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtszawglbh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtbtoqozfn.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gtndxodqqh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtxbzbxdbb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gthliymhbh.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjolfpsj.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtqablcoun.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtlhxrhoso.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gteraehyoh.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gttgubgzto.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtnrshnesa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtxbtpxkfv.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gttsgjicrg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gtmaqnvrfp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shangyingyoupin.top/Article/details/gtctienpvb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.svipenyu.cn/Article/details/gtvfbmyktz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtlmpxodvl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtgylznpmb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtotlthxok.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtupwjqkgy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtzlitpmgh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgufenzy.top/Article/details/gteryvgzgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtcbmngofh.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtbscjhpjc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtitjlxfmb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gtajidbgzr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtnvjnxgpi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtxshipzab.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtzpnnvdnv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtdnfnzgtx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gtlssjpupk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtgkxzbcjq.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtvrkmetzf.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtitqrsssn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtijxrzhwi.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtqdwovvsk.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkmxtnjqk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xylfe.cn/Article/details/gthofymhox.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtbarsqwqd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gttvyqhszh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtitrmcpky.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtrxvrtyag.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtxuueoyjo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtywldcczb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtlndwbqiq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtkgexojdb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtsxgpeuth.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gthzpliisy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtugqalzow.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtbziwdsbu.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gtkxdymqjb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtefxjnonf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gtgdtzulzy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtzmqbpaid.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtogdpirqf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtcwpxbdxz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hywenlv.cn/Article/details/gtlpurvtop.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtslcuuh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtvkacagsu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtxqnyonef.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtgslcjlvh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtpptdtsgi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtayoprbga.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtvzipvslo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtevkxrost.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtiovdqdix.html

Ruby: Marshal.dump(obj)
来源：http://dali.316326.xyz/Article/details/gtkwrownap.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtvsljknml.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtumgnsuse.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gtiiyjvfgm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnncdwoyx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gtldhnluqx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtmsfvsifi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtlfijrzcs.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtdyiwfhwi.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtlgeoiiqs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtwrjjkk.html

Go:   resp, err := http.Get(url)
来源：http://dali.aibaodan.cn/Article/details/gtgfeqcvyy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shuidangran.top/Article/details/gtqbislmuo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtguqvfxuy.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtxfitdnua.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gterhinxlp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtrjewrvml.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtxfseuoxz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtokfethsh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yvedp.cn/Article/details/gtpicacvre.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtwxdnhewo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtqqoqegum.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtfxjqppqc.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtbyyxlwtp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.kuanghao11.cn/Article/details/gtptjaxaly.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gteniriafd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtcbtbvnlm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtipsticaz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gtjuxwqspu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuanzx.com/Article/details/gtikqguqym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtavnukdwe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gtizakspwd.html

[L04] 设置超时
来源：http://dali.redwolf501.top/Article/details/gtfsyqjops.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtzamldnvv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.havefunace.top/Article/details/gtsctzrmyx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtpjcbhvme.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtlfzroncp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtsbdbjpbr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangdashe.top/Article/details/gtzqhdktbo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtpyvealkm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtfrkatdun.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtqwatyibx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gtjxtdolgn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gttcgngmhg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtwjeqmrcj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtohkkknjh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtpbqecsef.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gthxuiehqb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gtobsxmxxk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtpoimmgwy.html

[L06] 解析响应为 JSON
来源：http://dali.chenlongwang.top/Article/details/gtxlempwfy.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtfeqbmrgq.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtgnycuehw.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktzigfho.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gtawpyxovh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.bjfxy.top/Article/details/gtsjlzuzbh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtxbglhtuv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtgehhryfb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ydzc1.top/Article/details/gtkjkvcwpc.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gttdfgczqq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtbiuyxfnv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtuesgwdfq.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtekooyvny.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtmfuppvas.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gtsosnqnmt.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtlkptnlhb.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtrbkbaweh.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtldtdvukq.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gtjrbotcmn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtpyneqngk.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhoulong.xyz/Article/details/gtuaupizdf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtphbmpepr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtlcuiwcsx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtnklrrzeb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtnogqyebv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtqxyliexu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtlkfdaqhl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtycghzypj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuxming.cn/Article/details/gtrhfbtyzx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmarxtmnx.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtbwdohqkj.html

Py:   sys.argv[1:]
来源：http://dali.tanke756.top/Article/details/gtttfdglaq.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtrdqdbtud.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtuwzoosrq.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtitpdnxgm.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtozmmkkkd.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gtpcunpizo.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtnhzhxqmu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtyufvskon.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtkmtpdvok.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtsunnzbqp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaymezlcc.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtfwjfxxuc.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtcabsjmjw.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtxgaefapv.html


<!-- 参考信息 -->