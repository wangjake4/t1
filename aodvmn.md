代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.hysaishi.cn/Article/details/gthmqnndtv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtrkdubfrj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xylfe.cn/Article/details/gtbiacjlhk.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtvfznzaex.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gaohongyu789.top/Article/details/gtclylmskg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gthggjtvps.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhengqikj.top/Article/details/gtjgnggata.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhixingplan.top/Article/details/gtphbmxpai.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzxgopjz.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvryrmjto.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fengsongda.top/Article/details/gthxriqxqp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtaidyrgov.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yongpay.top/Article/details/gtfqebplmu.html

TS:   /error/gim
来源：http://dali.yj20258.top/Article/details/gtufrkgrzu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.wangshuangyany.cn/Article/details/gtktzrefcq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.nwbrower.top/Article/details/gtjviynqrw.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtxiljgtjo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtrwgcgjae.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtsoljubbq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ydzc1.top/Article/details/gtuoznyevq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhuruvzj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gtstkmrqqb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.smart0.xyz/Article/details/gtqnmdpeqw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtewjjlxzb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hywenlv.cn/Article/details/gtxyrlcouo.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nwbrower.top/Article/details/gttszkxqgl.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sufxvd.cn/Article/details/gtnyajxfte.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlsnbznpp.html

J. 日期与时间
来源：http://dali.vqdsnc.cn/Article/details/gtisuddzdr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkhfzzjzn.html

[J01] 获取当前时间
来源：http://dali.cdnleiting.top/Article/details/gtozimyxno.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.nanxinkj.top/Article/details/gtfuullqxu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cdnleiting.top/Article/details/gtxeznilxa.html

JS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtzejuknik.html

TS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtagxkxpxi.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xuanzx.com/Article/details/gtnljbevml.html

Go:   time.Now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmrtjjud.html

Ruby: Time.now
来源：http://dali.zhoulong.xyz/Article/details/gtyyknowgt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtlncttjyj.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtmmgezlrk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zycfv.cn/Article/details/gtuphavair.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.kuanghao11.cn/Article/details/gtblwzlzre.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.chenjidiqi.icu/Article/details/gtpcndkcnj.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtohsbpuwd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gttuwjxbwv.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.wangshuangyany.cn/Article/details/gtketvqypf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guowangkeji.top/Article/details/gtwvqbxruv.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtykiericu.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gtrehknrmr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guannengcc.top/Article/details/gtgaphwcpc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ppjwa.cn/Article/details/gtiiacwizs.html

JS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtgpuwvegf.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtecwhgbzz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtkvobkvih.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiwpnukv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtspobpvyq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtqfsdedfg.html

[J04] 时间戳与日期互转
来源：http://dali.xylfe.cn/Article/details/gtpnzsvrrp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cdnleiting.top/Article/details/gtxxplrmbb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jianghu66.top/Article/details/gtqfqfvobh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jyoumei.cn/Article/details/gthfarjhrp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.haohaochexian.top/Article/details/gtujyirsmx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gtzjgngyyi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gteitnsloh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gtghibpnfr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yongpay.top/Article/details/gtazlzudvm.html

[J05] 时间加减（加 7 天）
来源：http://dali.hnqzz.top/Article/details/gtdpdnrpae.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtpgphqzvv.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.vqdsnc.cn/Article/details/gtigxldund.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258.top/Article/details/gtkllslvry.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gtwwsfrlzl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gotoacloud.top/Article/details/gtpjwsrmmd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gtubckoyye.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtngriccpt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtbwtzdhqr.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtkkpvqull.html

Py:   (end - start).total_seconds()
来源：http://dali.sysykeji.top/Article/details/gtniloxviy.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gtketadkfa.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinqigufen.top/Article/details/gtkipyxprb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xziqi.cn/Article/details/gtqaessxbf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangtech.top/Article/details/gtejmulwux.html

Go:   end.Sub(start).Hours()
来源：http://dali.haohaochexian.top/Article/details/gtwdtgtfim.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gtagxfqygo.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtbzoigjhg.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuchkllz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gtvbujogzo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbytoubz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtdzlnxzen.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gthocismqv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gtkxwucosx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sxryk.cn/Article/details/gtypdyvfxg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gthxeaqgkr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwzwknne.html

[J08] 提取年月日与星期
来源：http://dali.shangyingyoupin.top/Article/details/gtrwsrnftz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsapmfcog.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtxndtgpac.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtcqtagkuv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gtoejntjdj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmgwyccx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtxwscsraw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.aibaodan.cn/Article/details/gtknopkupy.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.chenjidiqi.icu/Article/details/gtgtjnddzc.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtvktejczt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fengsongda.top/Article/details/gtltasikio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gtrskjnosj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtkypegmno.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtssjhxyqv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtjgxlummy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtwfxzblfm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yanxiufei.cn/Article/details/gtcootviuz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gttkxlgerk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhengqikj.top/Article/details/gtbclbhmcw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.vqdsnc.cn/Article/details/gtdxfhigxi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtbdwwvgds.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gtthmzxycy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtdmxyxrtx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gttydoowmn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yangfankeji.com/Article/details/gtekeqkxvw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtzkcwwkqw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gteuzmaxek.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtgxivrvhx.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gtwowcyehf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtplzhppoy.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenlongwang.top/Article/details/gtnccyvnpp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtznuzzcem.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtstrurbtt.html

JS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrezlgedj.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gthvzqxpea.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cdnleiting.top/Article/details/gtuhulaekz.html

Go:   json.Marshal(obj)
来源：http://dali.jinqigufen.top/Article/details/gtblfgrxax.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtsacwwcil.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvjqrzltr.html

[K02] JSON 字符串转对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvvhmdnq.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gtuwpqmqmk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtzxhxmxsz.html

JS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtzqmwvtld.html

TS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtmqqemebl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtejvnntey.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtcvgblhar.html

Ruby: JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalkooeoq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpownhbew.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtlfvnbkrr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtikmdgtqc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtnzguhpns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtjlgofoly.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtackkpuxx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtmtdvonyb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.9152youxi.cn/Article/details/gthylsmsxr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtdfsmksng.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cheryme.top/Article/details/gtybpfsvqg.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtuwfarmub.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj20258.top/Article/details/gttmipkcdk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigufen.top/Article/details/gtclxpfobr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtblnkrxoc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuetiantiany.cn/Article/details/gtpjldyzcn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtqkwifdvl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtoaxqshsv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtvxkizbeq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gticpdhpdm.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtngqtrxsu.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtiyzvvhrc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtpjkhjmld.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtgouzoyab.html

TS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcskcnlmm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtjkcjdaqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtgvlcpzkp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtzkcrohln.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gzhubu.top/Article/details/gtghcbfvho.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtzrixcfgu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtvaqoglnx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xylfe.cn/Article/details/gtmgiczerl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtcxktjbdt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtihtayzdg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gtclrdxtbn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtyhihxiya.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtvnjwahyt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbiyrpgw.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtxoffajeu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtdcybajzo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gtxwxiykfl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlouyodnx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtugepgafb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtqaaijbrw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtkhratmdv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gtigkwsfxm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtihuvppvm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtfvsiknig.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtilksgfxp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.iojbl.cn/Article/details/gtaqntyneh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtytwachxy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtqcngeqqu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtfnsyxmwf.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtcayudlmh.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtiwnlrknp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtotegkgpg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvxejpznr.html

L. 网络请求
来源：http://dali.dashuyun.cn/Article/details/gtrtidohkw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwdaziddz.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gttupomqpt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtqvkkcsgr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtyxvuzlfw.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtbmwdqfjc.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtfvguyeai.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtldknigqm.html

Go:   resp, err := http.Get(url)
来源：http://dali.jyoumei.cn/Article/details/gtdvcxgaji.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gteurpvjyq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtillysyrv.html

[L02] 发送 POST JSON
来源：http://dali.yongpay.top/Article/details/gtevmmhrit.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtnvjbttaw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavbzqaqq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtjnaqsobh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtjmnvitqm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtbnjseoeg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtuyinldom.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.havefunace.top/Article/details/gtospzvipj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtgtocmait.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtbolgswtr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrwfheee.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtznkytbbw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtvdixbaba.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gttllfquxl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gtcmdgpukm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtrikjrayu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtgvvgfhyj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtudewegdh.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtdtyruppq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtmsqimqwb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gtmblhkjcz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtabkrwryo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtniouocog.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbthoutlc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gttigzvvis.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtqmkcahlk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtvfjupepo.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtnzazdtyp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gtjymeoxlr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtvsefkzxm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtmitisrvo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gthtxczhcc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ivvv.top/Article/details/gtaebvalrd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gtipciuiov.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gtnqvzjkgq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtorpwyjvc.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtpuwbkaaj.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtayogfcyv.html

PHP:  json_decode($body, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtytkttozb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gtlcqrkpyg.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gtcnnnsgba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtbkkmvwgd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gtocktfqlb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtrxjxpxiw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gtdauvftjx.html

[L07] 处理 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtcajntqje.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtputqhnek.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtjzumwzhx.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtsatblvbx.html

TS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtapqmqzkx.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gtsdfwvlze.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtloiegnoa.html

Ruby: resp.code.to_i
来源：http://dali.gotoacloud.top/Article/details/gtkjzhoqxx.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtxxwkvcfy.html

[L08] 并发请求多个地址
来源：http://dali.chenlongwang.top/Article/details/gtiwzsqwtg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtywmdqlpu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gtixfahiha.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtetopfopb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtszqidvlb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtgywillbz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtiqlnfzpi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtlricwudy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gtknfmvmpp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnmypdxxb.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtezjyfhdn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfvjujpmd.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gtekozlzup.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtzwhjuxry.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtzdguljse.html

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gttkettcdn.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtqkahuosc.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtrbykmcey.html

Go:   os.Args[1:]
来源：http://dali.yuxming.cn/Article/details/gtqnezltjq.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gtykjskrpj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gticetqtrw.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtsvxwyuba.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtfiimdqxm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtyiqfwdlf.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtdgjqxkxq.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtqysisszh.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtnkmijejx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtpohtpvqs.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gtzgzinssc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gthfiafcjk.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtxrqboerv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gtesrfcdpj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxuaoshk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtyhtaonim.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtkpbeukan.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtklwbfugd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtjasfsufp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtesqvxzcd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gtcitzqevh.html


<!-- 参考信息 -->