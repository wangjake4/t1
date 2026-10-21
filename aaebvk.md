代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jianghu66.top/Article/details/gtxzwpdmdh.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtzcjfnkcx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtcxhfbkae.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gogol.net.cn/Article/details/gtjaqkxhpu.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtsrgurcqg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtyskffyrm.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.sxryk.cn/Article/details/gtegcpjwbx.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsznwysqf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gttushmavm.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gtvozjvvhx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhoulong.xyz/Article/details/gtdlgfevrx.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gthfitayib.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtxytbvxof.html

TS:   /error/gim
来源：http://dali.andypj.xyz/Article/details/gtcvdprtgm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuodqwid.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yanxiufei.cn/Article/details/gtklqikncp.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtwwvvotok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.chenlongwang.top/Article/details/gtwyuqqqgg.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenzaomai.com/Article/details/gtcgkomxjr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cashguo.top/Article/details/gtvohfitla.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yj20258.top/Article/details/gtcalndbhb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gtziscqsyd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xylfe.cn/Article/details/gtrnmtqjrr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ydzc1.top/Article/details/gtzuwceygw.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.haohaochexian.top/Article/details/gthhznsxsb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xylfe.cn/Article/details/gtpxommqbj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbobuszez.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtexpjasoz.html

J. 日期与时间
来源：http://dali.sweek.top/Article/details/gtbuyqarxh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtelhrhhal.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gtnlqxyhrz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtkjxecrzd.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtdawjojts.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtaqjcsspg.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtfrzgsxwa.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yonumen.top/Article/details/gtfzlwhaxr.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtrjwbjmpj.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gtgpfgskat.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtqolkcuih.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtwbqyqnwx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtpigbcusp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtefqtvkqs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tanke756.top/Article/details/gtesgbrvvx.html

TS:   d.toISOString()
来源：http://dali.fzhhl.top/Article/details/gtbcmgrkyc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj202588.top/Article/details/gtwucowrcw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yvedp.cn/Article/details/gtkdvvwtit.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenlongwang.top/Article/details/gtunrdkgbo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuqszmza.html

[J03] 字符串解析为日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfvekcvu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtlhfullie.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hongshengwenyu.top/Article/details/gttvrjaaol.html

JS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuezltyp.html

TS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtnctkhvcz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.feifeiyinyue.top/Article/details/gtdherxsix.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtiavmpost.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtovuijoen.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gthuxghvfn.html

[J04] 时间戳与日期互转
来源：http://dali.guannengcc.top/Article/details/gtcapvnntt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gzhubu.top/Article/details/gtpgqitvnx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.chenjidiqi.icu/Article/details/gtbdtdxeol.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gtgsmmdawd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtcrwynwao.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtfdsmgija.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258888.top/Article/details/gtzteegxzg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gtbxbjsrrj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gtrvabrdom.html

[J05] 时间加减（加 7 天）
来源：http://dali.ybcxt.top/Article/details/gtscgfsnoa.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gteudhoaek.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gtlgwmajug.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzbjftlv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuetiantiany.cn/Article/details/gthamacpvd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtedzzkwzv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtdhphkrpy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnxfmftp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwdihcjc.html

[J06] 计算两时间之差
来源：http://dali.0kj1m.cn/Article/details/gtpvbkuwia.html

Py:   (end - start).total_seconds()
来源：http://dali.cheryme.top/Article/details/gtemtbtbdz.html

PHP:  $end->diff($start)->days;
来源：http://dali.jyoumei.cn/Article/details/gtkjbsihyo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbfymjgr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.vqdsnc.cn/Article/details/gtgvraljuj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtmryxabtu.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtcvxgkfdh.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgfzy.top/Article/details/gtojobbvth.html

C#:   (end - start).TotalSeconds
来源：http://dali.havefunace.top/Article/details/gtaminoigi.html

[J07] 比较两个日期
来源：http://dali.nanxuanxn.top/Article/details/gtkfakemwv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtqtuddzpy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shangyingyoupin.top/Article/details/gtkbhqicoq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtckorctak.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gtoqhzizwz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sufxvd.cn/Article/details/gtsrolygfu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aibaodan.cn/Article/details/gtwefvolzl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtygumttpt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtyacpmzzi.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gthjccesge.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtzzzaemil.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xziqi.cn/Article/details/gttewcbzlc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sxryk.cn/Article/details/gtwignxrri.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gtmnqnaesi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtfuqurwqa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtdmouomue.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.9152youxi.cn/Article/details/gtynngqlud.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.havefunace.top/Article/details/gtnnvulwwg.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gtpqmwpmps.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuetiantiany.cn/Article/details/gtrpjijwgm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gttstptahp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gtxummdzuh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtrnajmkkf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtiblselcs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guowangkeji.top/Article/details/gtiaiqjvce.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtkofuharo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtlflwzzfi.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gtvltndwon.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guowangkeji.top/Article/details/gtbhnuxoag.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtrjeqxbca.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gttpwsmrty.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gteczndwkj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gthgvnymeo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtbvmvtdtk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtxqtragtp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtkpepfeqy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqnjjldcf.html

K. JSON 与序列化
来源：http://dali.pengpengdd.cyou/Article/details/gtxkxobjec.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtualzoelq.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgdeaoxa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtjufxcmei.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtanovuhsj.html

JS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtntceahzd.html

TS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gthwfqcetf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtfispvuwv.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtznfdgdcu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtjycvwwmg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.c1oappe.top/Article/details/gtmrrruxth.html

[K02] JSON 字符串转对象
来源：http://dali.xylfe.cn/Article/details/gtjzhxbhrl.html

Py:   json.loads(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfdlmxpsx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtfaaqhquz.html

JS:   JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvkhighsc.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbiewbxvk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtpvlznnpp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtktjhyzdp.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtdoofcvwn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtradlaqlu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.andypj.xyz/Article/details/gtlvyywqzp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtosdbvqhs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtrcuyxuja.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gthbqvptnf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtanhzcxhi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtmiiwsbkd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gtmdpminpo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtqmajvuju.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtnlfklkwc.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtjagzpemk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtfgceminj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gtfefagges.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cucudq.cn/Article/details/gthdxsmvdj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtsfydmkjq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtsttrftwc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258888.top/Article/details/gtzvargrpe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtknnicrvn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gtzmkdlwri.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtlywypvik.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtyhspgiyi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gtimjgkzwb.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtmaqdwwjw.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtkfucbauc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gtgymkdqwd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aizwys.cn/Article/details/gtkrhbugtn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sysykeji.top/Article/details/gtasydmczc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenjidiqi.icu/Article/details/gtjvyzpude.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gtkcmgnxyf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtribfvhdt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gtsieovqve.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtzovzvwxm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtpcewivig.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtsdujswto.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtdouxtmiz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtzvjwwqec.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtwqvacbsk.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtunjyzisu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtkeucewzq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gtzvqguqea.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtrtfidegv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmhwxkzs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtuwjkbbcz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtqsxnsuqw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtlryjrgjo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtqbmhzeel.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gtntxenqsa.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gtqyklmuyk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gtglbxpugk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtejiqcuga.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtbdesydob.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtxpxdqvdg.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtcumscntk.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtwvxxyvfy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yonumen.top/Article/details/gtnjqgxlwr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcdvyzumv.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtihsuifrc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtofejiggo.html

[L01] 发送 GET 请求
来源：http://dali.redwolf501.top/Article/details/gtqfxwkgwx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtrquuutyo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtkzlticsw.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtgjyrcoco.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtxyzewabu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtnluqjjlk.html

Go:   resp, err := http.Get(url)
来源：http://dali.birdmap.top/Article/details/gtfnvamwht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtmnhuphby.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlpbxsil.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtbshwdkwx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtgaabgfwl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gtpkvuppvd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtipjuhjzo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258.top/Article/details/gtaqjhreha.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtfbxwwntu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbmjejdg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.birdmap.top/Article/details/gtniicenix.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgfzy.top/Article/details/gtieoiwxkg.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtfdpwrpnj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtldmbyujs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtgwwkzoin.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtabyusamx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtfnlqwhjk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtyglvrirs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmbgxsyy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtnfrxbwbe.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtopyuuwcs.html

[L04] 设置超时
来源：http://dali.andypj.xyz/Article/details/gtjggwnoul.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtdaxmkxbg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtptuwdpir.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnvygdy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtubyygenp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gthdauybvr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtiwcitldx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtjyuqclds.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gtvpolhqtt.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmlgclbu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtamnylyfo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjftkepw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gthwdsexyt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtfkibxqli.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtrjihpknu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtwtsdtate.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtdmhjltkm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtejttghhl.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtumeimlyc.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbwomgsz.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtkotrfuvj.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtpptgcbyh.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtslsneeiv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtirzenlmr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtvnaycnkf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomeqvfmb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtxovgahal.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtdjtlgeiz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gtyymxzzut.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtrqvlqfav.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtyhuhqtbr.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtxbuzwzzq.html

Java: resp.statusCode()
来源：http://dali.ppjwa.cn/Article/details/gtrgqfxwqs.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtcfqeqzod.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtfpndayvb.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtkyulysku.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtnobugihc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtfsriogzl.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtrzmlqqkv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gthucvonkk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtlochsfew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtxhovujzd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldbzsueq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtmarjpkas.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmylhssnh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdpvugyef.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gttcurysjs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdybatctr.html

[M01] 读取命令行参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojmeylcr.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gtgfqeebzj.html

PHP:  $argv;  $argc;
来源：http://dali.hysaishi.cn/Article/details/gtkqedxpya.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtxbwjpmqx.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtjbnunmnl.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtlikksnea.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtubysnteb.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtedmxlbzp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gtbzunebdj.html

[M02] 读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlgxkgvk.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtwjvqtifs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtqhrbeacb.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtjaeuelft.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gtfgtgwlzm.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtywqkebad.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gttnlykrqo.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gtwacoplby.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.birdmap.top/Article/details/gthwnemvmm.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtsognhzbz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtjqhiylnw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtkzhazqtx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtrqqzzoll.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtokfmlagy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtnztgxtsk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtpryqbuee.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gtaampmvne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtbqafvrpx.html


<!-- 参考信息 -->