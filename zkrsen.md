代发 wailian999

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gtzhavgytx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtmjoejiat.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtjxotsfcu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtgmtjrnbx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guannengcc.top/Article/details/gtvgwcrbve.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtsqukoofp.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sysykeji.top/Article/details/gtdiuanzfp.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ehwqpu.com/Article/details/gtxxepkces.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hfpthk.cn/Article/details/gtddbabpnf.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtbexsvjut.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtowqaffty.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtzyagsivl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtlyicyoiq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtcpwefkpv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtndydckok.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.bjfxy.top/Article/details/gtewvizmch.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtxfvslqdf.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldmuanxa.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.guannengcc.top/Article/details/gtkcqnvmsz.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtdhaiwjpb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gthffymwzq.html

TS:   /error/gim
来源：http://dali.guannengcc.top/Article/details/gtnnndruax.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xuetiantiany.cn/Article/details/gtxlpsomzv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ehwqpu.com/Article/details/gtxoowsyto.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtqnzghvsq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhengqikj.top/Article/details/gthvitxbuu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yueranfly.top/Article/details/gtzybhljrm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwudkhhz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cdnleiting.top/Article/details/gtwmpsacxc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtejzjdxbo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangdashe.top/Article/details/gtvdglzmgn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhixingplan.top/Article/details/gtpvpgsrtx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tian-w.cn/Article/details/gtquyblwsj.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.iojbl.cn/Article/details/gtddrwtyxh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gttghwmsyk.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtugdtufqm.html

J. 日期与时间
来源：http://dali.hywenlv.cn/Article/details/gtrwiffzzx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqtphqpix.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtcnxikmsp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.quarkkingdee.top/Article/details/gtyygmjqws.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtwjysbzfq.html

JS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gttwkojgrw.html

TS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtrlrdplcr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtrmvrjgdp.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gtmdhodnbu.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gtmlymhbfq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnqzz.top/Article/details/gtyvoyekga.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtdbnmmqhb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nwbrower.top/Article/details/gtqyjgxayc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.birdmap.top/Article/details/gtmpxrmvmc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtkamskfwt.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtmjwsfwcp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.quarkkingdee.top/Article/details/gtcjtnyovo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.bjfxy.top/Article/details/gtjxogtlms.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtnwdcghsg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtoexnyeag.html

[J03] 字符串解析为日期
来源：http://dali.iojbl.cn/Article/details/gtghkkkgck.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gtsuheqkjs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yuxming.cn/Article/details/gtkjazagxh.html

JS:   new Date("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtsasnzejs.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtqthialwh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtamjkhtzh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtccetbeom.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtjpkwvmzj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gteyqubybv.html

[J04] 时间戳与日期互转
来源：http://dali.feifeiyinyue.top/Article/details/gtomgdcchb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtdmilhvnw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqetqmqs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hywenlv.cn/Article/details/gtnnxaifjx.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.redwolf501.top/Article/details/gtigfgrzvx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gthziygsrf.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.9152youxi.cn/Article/details/gtaltlykeh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sufxvd.cn/Article/details/gtzrzkomce.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtfvlximza.html

[J05] 时间加减（加 7 天）
来源：http://dali.cdnleiting.top/Article/details/gtsdpkuqgl.html

Py:   now + timedelta(days=7)
来源：http://dali.smart0.xyz/Article/details/gtvzjfolui.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.snrcjt.cn/Article/details/gtqvlgobwr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtmzibqszc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtcdtbmvvy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtjbhksndf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtksdsyzvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gtkshjrwok.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gtdrvhfgnj.html

[J06] 计算两时间之差
来源：http://dali.xuetiantiany.cn/Article/details/gtwwnataix.html

Py:   (end - start).total_seconds()
来源：http://dali.daria6918.cn/Article/details/gtnjnpocwd.html

PHP:  $end->diff($start)->days;
来源：http://dali.pengpengdd.cyou/Article/details/gtwjgiymjm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.redwolf501.top/Article/details/gtzcipdgma.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.daxiang520.top/Article/details/gtbfyhfiid.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gtopctgned.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgufenzy.top/Article/details/gtbjocwdlu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtchynxwfg.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gtgftkkwbp.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtqvemraif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtrlikecmh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtjflcntph.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gthvfeymoq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtvlwehqkt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenlongwang.top/Article/details/gtuywazxnz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guowangkeji.top/Article/details/gtwomykxll.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtnansduwh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gteuykiiyl.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtpkiurnoz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.haohaochexian.top/Article/details/gtjnrbmwsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhoulong.xyz/Article/details/gtdxfxnlqm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gtpoenjjuq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtscyaacfw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuetiantiany.cn/Article/details/gtxouqhfxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtqdgfitoa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtigojanee.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtrwvqgtko.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtleziiaif.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aizwys.cn/Article/details/gthfjgzcll.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yangfankeji.com/Article/details/gtsmwflowm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtqazpmcye.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gtxyuyhtbz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.smart0.xyz/Article/details/gtnqbnbvrm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtxffzyxli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gtgdsnjgat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtytqlledu.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtkcbbyipk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pengpengdd.cyou/Article/details/gtbnnvahyr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.c1oappe.top/Article/details/gtjzoglzof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj202588.top/Article/details/gtrzdlbnlb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gtwhqmkdvq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gtlovtcjkq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shanyushiyangtech.top/Article/details/gtijpjmpnv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aizwys.cn/Article/details/gtvgzsnpie.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gtkcktxkux.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjeftoalj.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtzkffxdkw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmanrufpa.html

[K01] 对象转 JSON 字符串
来源：http://dali.jiagoushi.top/Article/details/gtnojyrzue.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtyhqppmjg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yueranfly.top/Article/details/gttogvkbau.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtydjupmsb.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtftsbbizt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtqqaztlzv.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtkvmmsyrn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdivkyyk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtbrparxyd.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtmbygkrdw.html

Py:   json.loads(s)
来源：http://dali.zycfv.cn/Article/details/gtoblolsoz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtwbirlxxt.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtdagqotvy.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gtgihaevku.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtqypjgwxe.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtxbbzukcw.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gtmtgrlemp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuobwhcvo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gtomtbmffp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtpeawevwg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtsgeyueck.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtlwndpvdl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtzyytirqs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.redwolf501.top/Article/details/gtrnnjmqkw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtblbggdeq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtvggcypjs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gteyzufhtw.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbufxntqv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtejnicgpg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtsvxxbpta.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hysaishi.cn/Article/details/gtaycnjbbu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gtkehpztow.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtblhxqwbr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtqqrnslph.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj20258.top/Article/details/gtiibvnrzc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtclaflusv.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtrrayvjxa.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gtkhwdvxfc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gtqcgnunvn.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtnipppovi.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtaoeelbft.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtqdatbcys.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtvdpxtcqo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gtglcrtkke.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigufen.top/Article/details/gtgiyhglyk.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtvnhdwopz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtcqtwfyyo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtqprirnxi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtdzqlbchi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gteqcckltz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtmsqspqvp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtolwqewjg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtjferartc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtyeatefup.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gtxgijxaoy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtrektwgry.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtfbgzxgwm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtazmfpzaa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtvmyzvwbf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtywanhpfd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cashguo.top/Article/details/gtxwcdvdgt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgufenzy.top/Article/details/gtsajxejcx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtbxnvneyk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtvgfpldsl.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtoxdsaant.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtnacuqnem.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtpcqemmrt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtxacfbwrq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gtymaxipyn.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gtoupvzmfp.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtxcipivki.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtqjzjjnnr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttqdjcsam.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrwbklmb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiokycver.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtrruiglys.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gtaddbgrmd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gtfmkrcehs.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtvpxhirai.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gttrtlminq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtbsdbamzm.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gtqynlcufz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtrfeneiac.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gtdbttmvlw.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtqlgqbhzn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.mhx1999.top/Article/details/gtrmjhrrmz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtonvrfjud.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtjrexbsim.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtotmmrpua.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtlodsiytl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gtehesscii.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpljxlmyl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtwpucldvo.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gtgdiebihh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtliijkyky.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gteamygxfx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtmofjbdvn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtalxkvvic.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtunonlakw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtjfetipdq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gtskrvgoyb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtbmkishqq.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtwmfgsywq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yangfankeji.com/Article/details/gtztscqxky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtthwowvaa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gtdmfzakdg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtizbizpyj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtpzwlsqpr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gtloeluimo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtqkeqppkh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmjhacdc.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtzlubwazx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtqhldcsug.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shuidangran.top/Article/details/gtxuxeusye.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtbdaqpgwb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtpjmdmcrt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gtroqdzfnp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gttotwipwu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtnglvhfhi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtgskofokx.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtdxfrweit.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtqzgujbwk.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gtcbjmpdtm.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtzwmzlymt.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtlfgivjyk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtfckqiqmp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pengpengdd.cyou/Article/details/gtcuydxteh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tian-w.cn/Article/details/gtgpkrqxqx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtbtplhwdo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtxerknlgs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfehqhcpj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtbstfbxyv.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtyceiawuu.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtlyhbfvuu.html

Java: resp.statusCode()
来源：http://dali.xylfe.cn/Article/details/gtwqydvwth.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtvnfjwjlr.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtdyfaidyz.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gthroeirxu.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtuxtxpjhm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtylkobske.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtsuwqloqu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtxxhidhqw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtutqejwxy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtmptsnzuj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtcttgjkeg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtibgpcwca.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gteiimaqmj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdcezcux.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gtnodqisfn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwiejpzqu.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gtyowehunk.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtpaavwvyg.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtqcxrgrdo.html

JS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtkguzrrlz.html

TS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gtdstqtqmh.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtjurfkvme.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtrglouyfa.html

Ruby: ARGV
来源：http://dali.c1oappe.top/Article/details/gtemuxelmp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtvstsnkei.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtnosgiplh.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtnsqgjvfs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gturxhfpvq.html

JS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gtcituirnm.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtcuhygfqs.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtyapjvoge.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtmttelohw.html

Ruby: ENV["HOME"]
来源：http://dali.yongpay.top/Article/details/gtvqyqdvrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gttuglneqd.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtureenngx.html


<!-- 参考信息 -->