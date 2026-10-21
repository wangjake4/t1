代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gtvjontbol.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtewxacjnk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhijiandao.cn/Article/details/gtfvfndkye.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtgmdmvudh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtssxjoiyi.html

[I07] 忽略大小写与多行模式
来源：http://dali.xylfe.cn/Article/details/gtqsguacjs.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hysaishi.cn/Article/details/gtmossixdr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fengsongda.top/Article/details/gtxqafadkw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yvedp.cn/Article/details/gtazhazesy.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtrwbjoldq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigfzy.top/Article/details/gtajwmgzge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjnkyndv.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtongepslj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cashguo.top/Article/details/gtrfgajhkd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yanxiufei.cn/Article/details/gtdwcrifhc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hongshengwenyu.top/Article/details/gtnrpsoqzt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.birdmap.top/Article/details/gtiwrvivpf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtmjeyoorb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gzhubu.top/Article/details/gtcgceepaq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtzucmumai.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtmknaagga.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.wangdashe.top/Article/details/gtjvdzocbv.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gtkjzttmhv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrdnmbsjq.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtuclmsmdm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxjttyxaw.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtjstnfbds.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gtioghnnkj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.guannengcc.top/Article/details/gtiwfwuycx.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtvizrbpen.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gthmfaanxp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.chenlongwang.top/Article/details/gthaufzoav.html

Go:   time.Now()
来源：http://dali.snrcjt.cn/Article/details/gtmfzgtwir.html

Ruby: Time.now
来源：http://dali.yanxiufei.cn/Article/details/gtizpsypyo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.nanxinkj.top/Article/details/gtahfrqcam.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtwchyetpn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tianlin.xyz/Article/details/gtiknqtpuz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gtqfizmlvy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgfzy.top/Article/details/gtqygugvpd.html

TS:   d.toISOString()
来源：http://dali.andypj.xyz/Article/details/gtxxmyqklh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.guannengcc.top/Article/details/gtvxbbvawy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jiagoushi.top/Article/details/gthpsriags.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfgsvjnb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jyoumei.cn/Article/details/gtmnbdlwal.html

[J03] 字符串解析为日期
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxqicqdz.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtprhdvcln.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hywenlv.cn/Article/details/gtngnsmyad.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtsluyntfp.html

TS:   new Date("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtmdgennvv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtpqknvdqe.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gttfkmrmpz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtucgdxrqq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gtpjpmevlb.html

[J04] 时间戳与日期互转
来源：http://dali.shzxlz.cn/Article/details/gtcmhzqlyg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuanzhike.top/Article/details/gtjjvdwcmq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sxryk.cn/Article/details/gtqjacyjsi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtgtjvlnpn.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtmswxgrbr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daria6918.cn/Article/details/gtxmnaxizw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtcwjusyok.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.dianchejie.cn/Article/details/gtzzafsadb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dashuyun.cn/Article/details/gtldbezaks.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtruoilxrh.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtvubnysii.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ivvv.top/Article/details/gtoqbgwumt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtulnvgcjg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtyemwgcec.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlsrdjhi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sweek.top/Article/details/gtbnhxijoq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtnskwgfxe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoamvqsrg.html

[J06] 计算两时间之差
来源：http://dali.yueranfly.top/Article/details/gtuzjmvnnv.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtvddfqezu.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gticniwaat.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gtepdfsmvl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.fzhhl.top/Article/details/gttzplsrkl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuetiantiany.cn/Article/details/gtxpqndrch.html

Go:   end.Sub(start).Hours()
来源：http://dali.gotoacloud.top/Article/details/gtxxayjguq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtiushfzfm.html

C#:   (end - start).TotalSeconds
来源：http://dali.yj20258888.top/Article/details/gtnvomhutc.html

[J07] 比较两个日期
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgupwonp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtqlclzoui.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gtybygufwx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtaefrweom.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gtgttklwum.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtmiwqmcpx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuxming.cn/Article/details/gtlnncmpmd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtvtkpkhvz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtkfglhfcx.html

[J08] 提取年月日与星期
来源：http://dali.hysaishi.cn/Article/details/gtlxebaoqp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ehwqpu.com/Article/details/gtajqudkol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwfujlmv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zdqjudy.top/Article/details/gtyfuxkqny.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtcgdernhj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangshuangyany.cn/Article/details/gtskoyuuau.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gteyteishs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gtgpeqbqve.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinqigfzy.top/Article/details/gtpfwevkve.html

[J09] 时区处理
来源：http://dali.hfpthk.cn/Article/details/gtyxtjmejv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.daria6918.cn/Article/details/gtsapwbgio.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gthxikcxub.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.9152youxi.cn/Article/details/gtbrjnciko.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gtlyvckdaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtdcecmkdn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yanxiufei.cn/Article/details/gtefxxnrsx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gttkglebnh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcetivpct.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtjjeymtmh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtgeevnaek.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtuelfvbjv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhengqikj.top/Article/details/gtyuljjtov.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtbjngdori.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtsudvkqgh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gteedlljad.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gaohongyu789.top/Article/details/gtpxwjxxgn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtxkyscjdc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxholvuxx.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtmwbtxazx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfdptqjyo.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtznbkrgya.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtyxejfpfq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtilnvvxfz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtmxkgpxuq.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtxxyglugp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gttxzotjix.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtojvzwoih.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.smart0.xyz/Article/details/gtatstgsdv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuxming.cn/Article/details/gtckshahra.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtbxyycugf.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gtwssecbfj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ydzc1.top/Article/details/gtbnitrrwc.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gteboqseqm.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gttotwifne.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258888.top/Article/details/gtocqybzkw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtolvvszhl.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtybwqxjyc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtqxmfuzpy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sufxvd.cn/Article/details/gtrbwhgigz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtjsfblnub.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtlkvorycn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtxxpfjnkv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrwodavs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtfohluazq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtovhivrsp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ppjwa.cn/Article/details/gtpjpichvr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtsqikgljg.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtnpzaciyh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtvexumjor.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtfqjszjbd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtlvtmcoxc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtuvrjwskn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ydzc1.top/Article/details/gttsecteup.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtsexlnslr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtxgsfgvdl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhoulong.xyz/Article/details/gttufkuqza.html

[K05] 深拷贝对象
来源：http://dali.jqgufenzy.top/Article/details/gtsofmxski.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtkinobibh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtvwsjkqau.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqapwjtr.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtqeaxctuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtefvumcyy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtrzxdfbax.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtpopdzvzx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gttarbkijy.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gtxhtngsak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtfaqwghtz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtxvzqsens.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gaohongyu789.top/Article/details/gtydwcjdna.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtjehvgtxp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aibaodan.cn/Article/details/gtfectvceo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtjglhsoue.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtrchdqsbo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtwrbxdahm.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gtzjawpltx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtyvimijyp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtihlesbkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtjqptzdog.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtapuuudyt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtdjclgzkr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gtmxtupzhd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtnawuxiww.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdiqnpca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gtnpmrpreh.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtiwbnhpqm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gtsmzdgblb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtmdfpvgkk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtlgtxpmbg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtvfevnfit.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtrzjwlsgd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtswnkarmv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtnonqobih.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtucrnssik.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtbacpgtlo.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtptlcinkh.html

[L01] 发送 GET 请求
来源：http://dali.ybcxt.top/Article/details/gtudqefeax.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gtwsthoepr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlqtjgxi.html

JS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtgrvzklvj.html

TS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtftwqxjvx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtqragpshi.html

Go:   resp, err := http.Get(url)
来源：http://dali.iojbl.cn/Article/details/gtxcqrwgjw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpfzgtab.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtejxkglft.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtfjimfyrb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtnvtikdqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtrnlkgivl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtedzipsyd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtrakqztwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtpkhabvxg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hnqzz.top/Article/details/gtokjwslfg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtvcrozfev.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gthsxzoyux.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtriaiffcs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gteibxswdn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkihlpofv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtwqzkyixb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtydpomrcu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnqzz.top/Article/details/gtkqfbemwb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtaoohdcvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gtxwbxhdfj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtsgchmhvp.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtahxwcjks.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgmlqgld.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gtnurwfvbl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrypeqbb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtkxztusow.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtalqgfdhs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gtipiazwlb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gtuotakwtw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtnujdzxya.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtbkhojrmw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtyuodilvw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtwkgdlwbl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtauvhgmke.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gtfzzurwjj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gtlbwxnbqt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gtcecuznva.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtpwfcqtya.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtqnlqbdcu.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtibzyrsbg.html

Py:   resp.json()
来源：http://dali.fzhhl.top/Article/details/gtxafzzifi.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtrlwndkkb.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtdiupbpkl.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtfrtwccha.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtwerrrbls.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtzxxpvtal.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtezughnof.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtriwmizvm.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gttohiqobb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtecsouhtj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrfxsolg.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtzqoltbxo.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gthufoqvvd.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtccisahil.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtktawtyli.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gturqzcyyi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtbpzevvcx.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtfjoaiftp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gtcbcmegow.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbffzjbwy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtjuuupgve.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gttyzbbubj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenjidiqi.icu/Article/details/gtpgjjpkfy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtlyltxwfl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtrgnpfwuh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtvvqoaonr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjvokjnnf.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkeehder.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzipqttuz.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtpzpehieg.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gtsmjrtqel.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtyfwqnkur.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtzkjfonsm.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowgxinjl.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtyqlfwauj.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtijecnfan.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtqrozuwdb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtubjcskmo.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gtatftfiww.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtlgxaouxb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtgohrfkoj.html

JS:   process.env.HOME
来源：http://dali.nwbrower.top/Article/details/gtevwgucaw.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtoherbjhl.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtuglcwxkr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtcwmepgyw.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gtgplopenv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtipggprgu.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gtmbmtrfju.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gtodvoghag.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gtnwbdggkz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtphzeurfo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtotjqkafp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtnjfreqjq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtvkpbjulb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xuetiantiany.cn/Article/details/gtpenkpgwj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtlwztzouv.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gttcqrfrzw.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodgnbqji.html

PHP:  getcwd();
来源：http://dali.cheryme.top/Article/details/gtypadautn.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtovbylbdt.html


<!-- 参考信息 -->