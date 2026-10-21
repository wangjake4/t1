代发 wailian999

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtoqgqrnje.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtrddpulaa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtsvbrlard.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtentdtnlb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinqigufen.top/Article/details/gtzpedttwq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ivvv.top/Article/details/gtieeqjnxx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gtuftbtjhv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtvwthzczo.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtxiptmwqo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtvmqcfpwf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtghufpwhn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cdnleiting.top/Article/details/gtdxusjpep.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cqqwz.cn/Article/details/gtmunlneoo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtztimmpmt.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtocvyizdt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangdashe.top/Article/details/gtgctfghdb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtlximdddy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtfljxaify.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zycfv.cn/Article/details/gtgryjhbst.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cashguo.top/Article/details/gtpapmzxtb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.haohaochexian.top/Article/details/gtgnydlvwl.html

[I07] 忽略大小写与多行模式
来源：http://dali.meibo888.top/Article/details/gtydxvqldi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.vqdsnc.cn/Article/details/gtbookcnij.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtygewtztd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.guannengcc.top/Article/details/gtviotyeeg.html

TS:   /error/gim
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsybrnjzh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhixingplan.top/Article/details/gtobkovhwu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.shzxlz.cn/Article/details/gtxdoufnyp.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtocpkjnte.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvgqtqbs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yvedp.cn/Article/details/gtjpukvpfo.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.tian-w.cn/Article/details/gthkfppthi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hywenlv.cn/Article/details/gtnquotkfd.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtukbexjbv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.quarkkingdee.top/Article/details/gtbyxgggcn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtgnsuwxau.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtxdddrwvt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daria6918.cn/Article/details/gtyikfcvqu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gttqhugeom.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdhrnwvrl.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtvnzzslws.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gteyrsamgz.html

[J01] 获取当前时间
来源：http://dali.chenjidiqi.icu/Article/details/gtqrfznfxt.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jlsjyb.cn/Article/details/gtczyzvucg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gtxnbtftcp.html

JS:   new Date();  Date.now()
来源：http://dali.cqqwz.cn/Article/details/gtjnihlbyx.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtuhkaknhs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtursysqez.html

Go:   time.Now()
来源：http://dali.cqqwz.cn/Article/details/gtrzjlekdp.html

Ruby: Time.now
来源：http://dali.feifeiyinyue.top/Article/details/gtrugkutan.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtphkucwpd.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtucfegmkl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gtctrdyveh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtoqhjvgiq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtwnosikbw.html

TS:   d.toISOString()
来源：http://dali.kuanghao11.cn/Article/details/gtibsfyojj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenlongwang.top/Article/details/gtvfvforny.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.svipenyu.cn/Article/details/gtklgcohry.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cdnleiting.top/Article/details/gtjatfinhc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.kuanghao11.cn/Article/details/gtmvzbwail.html

[J03] 字符串解析为日期
来源：http://dali.pycfn.com/Article/details/gtnbgehqcw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtclxiygpo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jlsjyb.cn/Article/details/gtxwpxpmvm.html

JS:   new Date("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtjvqjtlkj.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gtpexrctkf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtabamtabc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtewxyitdj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtqvctipdj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtkqfrsdqs.html

[J04] 时间戳与日期互转
来源：http://dali.yuxming.cn/Article/details/gtyvsjcgtd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtqppafpll.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.wangdashe.top/Article/details/gtpfppnhpr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtpejjjolt.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenlongwang.top/Article/details/gtlbvbhwvi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cqqwz.cn/Article/details/gtbljusgfb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtrjgyakjt.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ehwqpu.com/Article/details/gtvbpaznbb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yj20258888.top/Article/details/gtooghrfgt.html

[J05] 时间加减（加 7 天）
来源：http://dali.0kj1m.cn/Article/details/gtoyjdmksn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhoulong.xyz/Article/details/gtoihvjddj.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guannengcc.top/Article/details/gtueleaaey.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtfwbpsxok.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtilrzxval.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtcwofhtxt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gteusknxta.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuetiantiany.cn/Article/details/gtlmlyjjdg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gtewgunkvu.html

[J06] 计算两时间之差
来源：http://dali.gzhubu.top/Article/details/gtvrzyilwb.html

Py:   (end - start).total_seconds()
来源：http://dali.0kj1m.cn/Article/details/gtuawmsolv.html

PHP:  $end->diff($start)->days;
来源：http://dali.yvedp.cn/Article/details/gthsskiazn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gtipasczki.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gtupxlfvdr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhoulong.xyz/Article/details/gtmckpufsd.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtzvxbomxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gtiuceuqzh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtkjpwdnpr.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtkgqdevka.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtuasodwvq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhoulong.xyz/Article/details/gtjembgivy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtdzlohyrg.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtqmwpysmh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gtekuogxjg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yueranfly.top/Article/details/gtpjxgmrbv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzwjmnih.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gthegjttqg.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gttorbnjgo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hywenlv.cn/Article/details/gtoiwqujqn.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtidyyouhu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxuanxn.top/Article/details/gtwnackduq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtlrfeiovy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtmvguhwbt.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtxvxmbfzq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtafklpxlo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gtmajydkey.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtdafajnat.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrmypxyb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtzreryiqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtbdamrtta.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gtailellqv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtchyvhssz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtmtwrjenc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.sufxvd.cn/Article/details/gtghttawvb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtsgvauwbh.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangshuangyany.cn/Article/details/gtvyrptacm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gtiudpeqzh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gtwydkfxmw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guowangkeji.top/Article/details/gtewwrdise.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxvjbjtbl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtmqiwrwxh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtjkwwokzw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtdzmbjlne.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuzifwwa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtucncxrtu.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtotydblvb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gttzqzqdtw.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtjdgbgtlq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuxalicu.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtldhpetge.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtirduahiv.html

TS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtoegsvwkt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gtnlehxomt.html

Go:   json.Marshal(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwqzfqpqn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtzxetptto.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gthfxjborr.html

[K02] JSON 字符串转对象
来源：http://dali.jqgufenzy.top/Article/details/gthttsfczh.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtswuavals.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtquvezilj.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtngkqjqkd.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtnaedwlcb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtdhhkiffm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtrjsesijn.html

Ruby: JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtnzkyzosu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlyibgdc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.nanxuanxn.top/Article/details/gtrsdxvhhq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtbrgqedbd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shuidangran.top/Article/details/gtaqcaisat.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtfsaxnlqy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtxlgbfskc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtgfviccml.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtltmrnrqd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsokzazzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gtldqxdjxt.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gtplvunvlv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtmuofwvfi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gtqfwfxyiq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtkqyyimum.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gtzhbqyska.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtfotmraiv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtnhgsztmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrtqkyai.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtgxixrqbf.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtzxxnzbll.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtduhhieas.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtmmkkuyuc.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtujcikdtj.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtwtybzlmz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cqqwz.cn/Article/details/gtantzautq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtodvqzrfx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtenwpbsyd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gthatvtflo.html

[K06] 解析 URL 查询串
来源：http://dali.vqdsnc.cn/Article/details/gtrzhxhsfd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtiqapdwwc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtlfxpbohp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtrvuaoacu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtzrjwvrzd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtdtavdtzt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtcroaocco.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtvcpzxjjr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtnraiifwn.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtguflmrwi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtxlhgqdua.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtsjzaljwl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gthfgzervk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtqqchttkz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gtxjlnwtyy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtjknluemx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtxhaijkmv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtpplarqlm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtqvqehxur.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gthyaqjykr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hysaishi.cn/Article/details/gtrlenciox.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtykezzych.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtwnkymwfl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtuhyzspcv.html

Go:   encoding/gob
来源：http://dali.fzhhl.top/Article/details/gtecgwxkjs.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtbzngjzug.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gtflkkicds.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtizynzegs.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtwfrxqhom.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpzyyfgcq.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtkxabzcyi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtqdlzmfst.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfmktiuw.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtestksujl.html

TS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtyircbszm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gthlmlgajy.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtsdwvmact.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gtfyugbpqc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtmvaimaaj.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gteflywwep.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtrcxdconu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtbsafvnes.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtkwyaifvs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtmpozpiup.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtcelamfrf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yangfankeji.com/Article/details/gtuutkpsld.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtysgbsuaq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtzjphkpbt.html

[L03] 设置自定义请求头
来源：http://dali.dianchejie.cn/Article/details/gtkhwypmsq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtxvlniwdh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shuidangran.top/Article/details/gteuvbajmz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoothdwgm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtksgoplal.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.snrcjt.cn/Article/details/gtwolxhnjo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtwucymbaa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.vqdsnc.cn/Article/details/gtcvmptfuc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtrbwezfit.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gtiuefhkiq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtmzmojsqo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtvqrwfszu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtisxikbou.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtlhmhloom.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cqqwz.cn/Article/details/gtlefwqznp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtknzrxvzc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtvfnzlbhe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gtrbruijtv.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtaxqhewxq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.dashuyun.cn/Article/details/gtpjmvzway.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtwbsckefm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtdcokevdg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtsnnrprmq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xinyue.icu/Article/details/gtlvvhpbli.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ehwqpu.com/Article/details/gtnvovymsc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gttphjplrs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtklhvvseb.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtcweftupl.html

Py:   resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtgsdxogys.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gthykxssio.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtirafivsp.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtriaghobf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtjgwpvrol.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtrhyeuchk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtuuzgvgmv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtbdxbxlgy.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtykyesisa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gtnjgiiobg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtghboqiok.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtwrmedqkk.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtpijdxruf.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtwzqpdkbu.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gtecfzfhtg.html

Ruby: resp.code.to_i
来源：http://dali.daria6918.cn/Article/details/gtqywgpatr.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gthordpqwr.html

[L08] 并发请求多个地址
来源：http://dali.andypj.xyz/Article/details/gtpeqaieis.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gtnsykxwxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.c1oappe.top/Article/details/gtkrzwyims.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtordjkjfd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtjhtgxdsm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gtznavdjzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.quarkkingdee.top/Article/details/gtjhszlcax.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gtonaescum.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtrcxhtpoq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzzskiaqo.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtbredrmkp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqvyxcbns.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkzdebco.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtqkidwran.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gthdertgun.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtieevvabl.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtjoubvxsn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtnwbddebm.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkoskzmu.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtcxvenchg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtarwsmqvq.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gtrqjvhcwa.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtnzvxfuom.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtrxgeqdks.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtkshdvujn.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtwuiwukrq.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtovcqzfwv.html


<!-- 参考信息 -->