代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.0kj1m.cn/Article/details/gtrvjcblbo.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtmquarptx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dashuyun.cn/Article/details/gtdjnxsjts.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gternlxpqn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.daria6918.cn/Article/details/gtrdizibxa.html

[I07] 忽略大小写与多行模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiuwsjedc.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtroshtoqc.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuetiantiany.cn/Article/details/gtgqnnlglg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gtmixrmlxm.html

TS:   /error/gim
来源：http://dali.xuanzx.com/Article/details/gtkdiqxaco.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yj202588.top/Article/details/gtnohammwe.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.9152youxi.cn/Article/details/gtzeotooqh.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gtgxgdhsbe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtfsxuojhs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtphahcrcr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yanxiufei.cn/Article/details/gtuukojblo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gtvxaagect.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtamoexaak.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtpfbonijf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yonumen.top/Article/details/gtctukgpul.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.daxiang520.top/Article/details/gtzueehmce.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.svipenyu.cn/Article/details/gtzzvqlkvr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtkvkugdwv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxevfquhd.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtgeslpqcf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gttahsjnzz.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtdctzcrqc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xziqi.cn/Article/details/gtqmllvpel.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gtegxnjxyz.html

JS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gtrrggllrg.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtqirattjk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gthtfcxchy.html

Go:   time.Now()
来源：http://dali.9152youxi.cn/Article/details/gtzwvtaitk.html

Ruby: Time.now
来源：http://dali.ppjwa.cn/Article/details/gtvbdxlvgm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtzluijjqb.html

[J02] 格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtofewsdpv.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sysykeji.top/Article/details/gtbkbmedxa.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gogol.net.cn/Article/details/gtiqkjcwaw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gthmbyrxmt.html

TS:   d.toISOString()
来源：http://dali.ydzc1.top/Article/details/gtbrewijnt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gttcovrueb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtxtqgyrpf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtzyzpzjvg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.havefunace.top/Article/details/gtwcjgsfqx.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtdkdofank.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtyinaihnq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtussqbred.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtijlqssgw.html

TS:   new Date("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gtayrcnifn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gttlwkarmu.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gthcapcghv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtthvbjdhv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.svipenyu.cn/Article/details/gtfrwhifjr.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtdkssizup.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhengqikj.top/Article/details/gtcmtvdwed.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.svipenyu.cn/Article/details/gtsardmyro.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtbwtlpxiu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtbzbxzuuh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yuanzhike.top/Article/details/gtwbltgvdg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fzhhl.top/Article/details/gtjtimhaor.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gtmpjohusi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gtnjzekcoi.html

[J05] 时间加减（加 7 天）
来源：http://dali.shuidangran.top/Article/details/gtgnkvojiu.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtvyobmnut.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nwbrower.top/Article/details/gtulhynhuz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtxppsrkjv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtzdnzsnff.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtqqcnrchi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtnlookukk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwigiply.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gttxgxlimz.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gtcqeewovv.html

Py:   (end - start).total_seconds()
来源：http://dali.fzhhl.top/Article/details/gtfzzwvaxz.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtmocxqzuk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gtpmxshkqc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gtseloddgc.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtpanbzngh.html

Go:   end.Sub(start).Hours()
来源：http://dali.hongshengwenyu.top/Article/details/gtnutdxaue.html

Ruby: end - start                 # 返回秒数
来源：http://dali.havefunace.top/Article/details/gturtsxeus.html

C#:   (end - start).TotalSeconds
来源：http://dali.hywenlv.cn/Article/details/gtayleodhf.html

[J07] 比较两个日期
来源：http://dali.haohaochexian.top/Article/details/gtqlplxuim.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtfbecwdnh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenjidiqi.icu/Article/details/gtwllsqrhf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ivvv.top/Article/details/gtyowbcods.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gteytalaok.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtajuyldfs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtaxfumboo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtvqovnmqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtvdjvsypy.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtlhakbfjv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtcbtlrrzx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtncynrxqq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sysykeji.top/Article/details/gtcxnjdqwf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gtbsrslfaf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhiwuduotai.top/Article/details/gtghiikjjk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenjidiqi.icu/Article/details/gtbkonuabp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gtetpwglhp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gtobnubdsr.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtcnajwqqu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gtotkznojo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258.top/Article/details/gtwvjnqfuk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hammf.cn/Article/details/gtxokkkvfu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtircylgjo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtnbetwkoa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.feifeiyinyue.top/Article/details/gtfqgrqmgk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj20258.top/Article/details/gtgqrvjwjq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtpwxmeiux.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhongyouzk.top/Article/details/gtgyzavngj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtbhqnvznb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gtljtulqof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dashuyun.cn/Article/details/gtfvbjxsmq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpzyfafcz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gtlrklqdam.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.bjfxy.top/Article/details/gtpbpsnnty.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtfffcuwpa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gthofrrzfs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnuapifwd.html

K. JSON 与序列化
来源：http://dali.nwbrower.top/Article/details/gtrwbfwabo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzpojhvrs.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtkhjytpnn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gotoacloud.top/Article/details/gtgchpgldd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gogol.net.cn/Article/details/gtzlbylcci.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtwsdhktwb.html

TS:   JSON.stringify(obj)
来源：http://dali.9152youxi.cn/Article/details/gtlqxlqczv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gtfycjnrdz.html

Go:   json.Marshal(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtwfbybuma.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtcoyosttc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtmvqqhmnb.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gtabmacpht.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtewpfchly.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtkwpafjju.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtggykobro.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxlnlhxyp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gtmyhyqirg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtouwuoteh.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtejsshhmn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsioorqxh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtjzhvrnif.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gtgoeoufhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtbigxyist.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtwdtabjyl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtgnmaqeom.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmzufhntl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtcnntppwo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtftqwsnnk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gttibyracx.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtuuvyplrr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtcmoulvfh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ppjwa.cn/Article/details/gtqqikrrdv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtttjwiift.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtjtebxxiy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmincyyk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtudgmwqkb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtlaifkzxa.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gtogzlgoai.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gtgbctpopw.html

Py:   copy.deepcopy(obj)
来源：http://dali.ppjwa.cn/Article/details/gtzynhqylv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtzhzsqzla.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtgtfulyek.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtunancqcr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gtybgitern.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gthuxfaktd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.birdmap.top/Article/details/gtwrutsjvo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtdtvuueeh.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gtgdqoyokj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwtpthub.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtztpbkmpq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtetbaonmu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtmhscgjpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnioeqgqc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtfebuxmeo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtxouddngf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtfuayvvzd.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtcxgabqxz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtbztgltvo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gthmfsnzci.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtftqanupi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtpinqjocd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtfwnezluy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gtgheqziao.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yuxming.cn/Article/details/gtsodqwfem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgafxohd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtrjqlagrp.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gtwlrqxiqp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtpnwfhzln.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtfoxsvqyo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtadpgzphi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtnlenwtug.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtibldpwut.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpwxrnef.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtolmzzbjy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjxgmjcxi.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gtwzcoazmj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwjehojwj.html

[L01] 发送 GET 请求
来源：http://dali.zdqjudy.top/Article/details/gtvmrhvrmg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtwlvdzqvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gtlyghhqrh.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtuvowuelz.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtrepzvabh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtlsaodhxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtxermvxqu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtdmivspmp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprpehsfa.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtostxgeye.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtsmfwxhtj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gtlsrdgjkx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtcdqvknuz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtpqgzbssv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gtrzozzvau.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhengqikj.top/Article/details/gtpwvhovge.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtdawasqpk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtloskvbpt.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtkbomaubg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhxkihdw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gtigxdnjzg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jyoumei.cn/Article/details/gtkduhzwym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gtntgvwcyi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtcdravslg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gttammeuym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtmdykksde.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtyppureyi.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gtedhmxeyf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtuufxychc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjzaedbg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtktjxxsxh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtboxgwycf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtygweheqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gtmsuijxml.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtxjxbwkhx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gtufsdplka.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyumxxgvz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtnvpedwrt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtezagsopr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtcqjtmvie.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtskkfbkag.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtdukgtvap.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yongpay.top/Article/details/gtsrynthzc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtmojbwkyf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtmxfmfoyc.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtvmdlvjvg.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtzhpkzmnk.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gttokupcsf.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtrvhfmusr.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gtspjdxuzc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtcyzosimk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtljddhfcg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtltvwvzhj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.9152youxi.cn/Article/details/gtewvwddgq.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtphpoqprq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gtqazglsye.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtgzfyrqdx.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gtksilaxxu.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtrglgbxmm.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtqcayhznt.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gtuodfgnir.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gttuvdkfpy.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gtjirchinl.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtdthpykbb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtrupsvbfh.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gtpuowpzfe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtahgsfbfq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcsspyffx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtchoxmkld.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gtvyzgvapq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqpkqcrl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtiiqipktf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlydguhim.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtgclcssjn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqazjqrj.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtpsleodge.html

Py:   sys.argv[1:]
来源：http://dali.dashuyun.cn/Article/details/gtqohhpyeo.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtcjqwxfci.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gthegrgtsm.html

TS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gtgwjwifxc.html

Java: args 数组（main 方法参数）
来源：http://dali.havefunace.top/Article/details/gterezdscx.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtbhjhiwdk.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gteepyopen.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtezuxegpx.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtktgkaqxt.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtvxkdijmd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtcisyijng.html

JS:   process.env.HOME
来源：http://dali.mhx1999.top/Article/details/gtgqfnjqci.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtgbtktyrp.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtqubvgvaz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtlqgcuhjy.html

Ruby: ENV["HOME"]
来源：http://dali.ydzc1.top/Article/details/gtslkpxrub.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtumnphpdt.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtfgkblqlj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gtyrsjnvpf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvdkakpv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtqaexqvzp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtacrmgney.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewcwcnmc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtismlfvit.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtoxosdpuu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gtazisfpzq.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtxfzelomk.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtfacnqfzo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gtfnugwoem.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtnkpnfgni.html


<!-- 参考信息 -->