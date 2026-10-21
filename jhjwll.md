代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.mhx1999.top/Article/details/gtxweqmztx.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gttghlbaat.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdlwkqlg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhijiandao.cn/Article/details/gtpxplanrf.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gtjnkswrqj.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhongyouzk.top/Article/details/gtgjtyrpma.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtrearwbkx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hfpthk.cn/Article/details/gtylruqtet.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtmdwloemc.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtgakeicph.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fengsongda.top/Article/details/gtwfyijklp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.redwolf501.top/Article/details/gtpqoabdmr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gtpskuqxav.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yonumen.top/Article/details/gtzfqcmdxi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtngoomfmd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyampusma.html

J. 日期与时间
来源：http://dali.daria6918.cn/Article/details/gtpagscwav.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiquunjq.html

[J01] 获取当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gteiqoruxd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmafsglp.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.quarkkingdee.top/Article/details/gtladjufog.html

JS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gtugplguyr.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtclolardh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ehwqpu.com/Article/details/gtyjfnlbnu.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheqrilgc.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtpwxudupi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shzxlz.cn/Article/details/gtaqpwxuix.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtlrzxtjrl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.quarkkingdee.top/Article/details/gtqaiaifon.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gtmjepvsii.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.andypj.xyz/Article/details/gtpurtkyea.html

TS:   d.toISOString()
来源：http://dali.jinghuilouyu.cn/Article/details/gttskaxmjr.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhengqikj.top/Article/details/gtbffqjpnw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.meibo888.top/Article/details/gtqnzktaag.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pycfn.com/Article/details/gtcyfiyogb.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtermixgrx.html

[J03] 字符串解析为日期
来源：http://dali.daria6918.cn/Article/details/gtlixbzxhb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhiwuduotai.top/Article/details/gtjkliosbw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gtfaeysnzb.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtakbabtot.html

TS:   new Date("2024-01-02")
来源：http://dali.tian-w.cn/Article/details/gteawvoriw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.tianlin.xyz/Article/details/gtwoqmuawc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvvlnbvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gttfrxfujn.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtdincbblc.html

[J04] 时间戳与日期互转
来源：http://dali.hnqzz.top/Article/details/gttniglusa.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtclqagdyz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtehatushx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtzzqtsmqc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ehwqpu.com/Article/details/gtzqfyagae.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yueranfly.top/Article/details/gtofoamxqr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtazjfvpnr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.daxiang520.top/Article/details/gtdhmkdjxz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuanzx.com/Article/details/gtlmtlnoxj.html

[J05] 时间加减（加 7 天）
来源：http://dali.bjfxy.top/Article/details/gttjreccxt.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtyhtqsrdb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fzhhl.top/Article/details/gtpcsemquv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfottsum.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daxiang520.top/Article/details/gthnwtljhj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jianghu66.top/Article/details/gtkpqpygnu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.meibo888.top/Article/details/gturvzryit.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhoulong.xyz/Article/details/gtkdbwpojx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtsxzabyrt.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gthkqlebbt.html

Py:   (end - start).total_seconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtffsuhyam.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuanzhike.top/Article/details/gtdijgedum.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhiwuduotai.top/Article/details/gtduamdtlg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtyvopaapt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.havefunace.top/Article/details/gtqjurlwrc.html

Go:   end.Sub(start).Hours()
来源：http://dali.quarkkingdee.top/Article/details/gtouqzcclq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jiagoushi.top/Article/details/gtrccvmyfb.html

C#:   (end - start).TotalSeconds
来源：http://dali.316326.xyz/Article/details/gtfjwmcghp.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gtryeosgaz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtovqanamx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ybcxt.top/Article/details/gtseipcbnd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtksudczkz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cashguo.top/Article/details/gtjwdfjmoe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xylfe.cn/Article/details/gtjefylcuy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ydzc1.top/Article/details/gtpjndroat.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtyuyycaow.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gthmtctyqa.html

[J08] 提取年月日与星期
来源：http://dali.yj20258888.top/Article/details/gtrgkdttdl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhiwuduotai.top/Article/details/gtzjtsfxsg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hysaishi.cn/Article/details/gtsywcniub.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtjmffmwyb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlxusmum.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtfzuhaytu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.chenzaomai.com/Article/details/gtiwdazbzm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtgtiealqm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.dashuyun.cn/Article/details/gtrczkkguk.html

[J09] 时区处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtltbfpxqw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtmdqmesfq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.bjfxy.top/Article/details/gtvnivnyqq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlahlzcrz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtlgurkgyd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtbnlcdzar.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrordtlkx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cucudq.cn/Article/details/gtjmbspodp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtkqstckwz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gtdrzzngak.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.iojbl.cn/Article/details/gtqmqiugnh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtfhdfszga.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtldaeaood.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jianghu66.top/Article/details/gtsetdeckh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtbssfzjoc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.smart0.xyz/Article/details/gtlezfaxpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yanxiufei.cn/Article/details/gtxtykrbaf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtpurfttzx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlbllgkjn.html

K. JSON 与序列化
来源：http://dali.chenzaomai.com/Article/details/gtgkawxpvl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsxzvmtma.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gtivaaadbv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gthtzjusaq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daria6918.cn/Article/details/gtaesfcunb.html

JS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtlswyupkz.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtymnzlrsf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtrtdnbdwf.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsiwublpn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtarvamkuv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtkvwwphuf.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtxgbrrjvg.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gtxxqeevwu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.kuanghao11.cn/Article/details/gtiggminet.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnknzucd.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtckwrqbbz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtcowcfoep.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtqkwqpxyi.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtgjdmfres.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.snrcjt.cn/Article/details/gtnwwupmdq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtzbdyiiha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtosmiddpp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtfudmcwil.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtovervldr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtqxeotkqm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtggsmyfgy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gttlgyjasw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj20258888.top/Article/details/gtdkqzhdsi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtmaazmesb.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gttqsqdgqg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtiuwgopui.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtxzetzdlc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtrtfjpvpe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtfwslanvp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtnttwkqpu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtmungwlzm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtgoyuzags.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtksitzsti.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gtogpebyco.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtzwwmkreu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbkoaoxs.html

JS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtxcvasdkb.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtbtykouup.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjyoddom.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtrarytozi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtmbrqigxt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.kuanghao11.cn/Article/details/gtesoxwmhj.html

[K06] 解析 URL 查询串
来源：http://dali.guannengcc.top/Article/details/gtgbeckmxf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtbfbhxskz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gtdfzqphfa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtdlmwvggb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtrwkyhrwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gteiawmnrr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtlamxrznq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtznklhtqb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtlrcjzniu.html

[K07] 进制转换
来源：http://dali.gaohongyu789.top/Article/details/gtufhryygh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gtwzqgbcua.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtikyslhoi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtzsxfjgal.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtgyquxavj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtrcyacppa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofdpqiei.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhengqikj.top/Article/details/gtpaxvtskd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtarfoqxgd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtrmgeuuqi.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgrlwrycx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gttatfkdpy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gtjpdlblqr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtsqiesdwp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgfzy.top/Article/details/gtcdbaocdf.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtyknmpubx.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtbnoyizbt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtuaxqapgx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttuzwumxm.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtochuevmn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtunvcvxfh.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtvylqdnxi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtquqwphgn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtcpogmvcg.html

JS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtiilppfhm.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtrmiosyml.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hammf.cn/Article/details/gtioukysob.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gtfclernqj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtlugbdsqh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jianghu66.top/Article/details/gttoilddgq.html

[L02] 发送 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtqzapodiu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtjwgnmywy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtekfgpldm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtdamibsnc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtkpvkzqwn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gtggjjfedb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gteyuuxilf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtagevegms.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtundtdlii.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtfexrdpxj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gogol.net.cn/Article/details/gtyitiptxh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtaminkjjt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtqufdjldb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gtfjgwqaps.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gthsybezyg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtrvwrbikq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyadqidq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtexipuzux.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtdkzsbpwe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfrlomed.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtcjejgnjn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtgaencoiz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tanke756.top/Article/details/gtfpjtfbpp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiulgutn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gteehplmke.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.birdmap.top/Article/details/gtcwifahuh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkugxzenb.html

[L05] 上传文件（multipart）
来源：http://dali.zhongyouzk.top/Article/details/gtemlmfrhw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gtbhpubkgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtpbqolgey.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gttzwaaypv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlondkw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtkpncrwov.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtsxtqzupe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gtlmzhjjzu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtwtwogipq.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtqedeibgd.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gtepqwhguh.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gtockmnvjp.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtaedlwhrh.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtbhfwozzv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gthfluijeg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtdepfuztk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gthuuodsmp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtwauevxeq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtrqatyozc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gtpctgnrup.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpaifiak.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtewlnxhfm.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtlvnghoyw.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gtgtbzwezk.html

Go:   resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gtwurfrjfy.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gtvtaowqrf.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtjsgiwmqm.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gtoedrwhwy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gtwtujcdqn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gtpqfsleua.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtsxvvkphn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtprbfrmla.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gttgkgekcc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shangyingyoupin.top/Article/details/gtupmlixwv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtkrdpcfhr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gtzcwmsist.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgokjgylx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtwmtiwdns.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzohdnukm.html

[M01] 读取命令行参数
来源：http://dali.yueranfly.top/Article/details/gtixuwuoag.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtbgcgtqbq.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtqtftwwmu.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtefwjahwd.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtjrokuimj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtvaczpyxh.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtxiiuncai.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtotuzlfwg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gtrtlasoct.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gttgapiobo.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtuidxqldm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtvrlruwru.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtvrbidxye.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuydwkrv.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtquhffyrl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtkwwkystk.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtejvxwfcc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtcdprvppc.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gtysuafceb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigufen.top/Article/details/gtyprjgsjt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtpbpjkqtf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtclixnybp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtjgdupksd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gtdnwqljoc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtlrtjvuxc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtzlijsdmy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gthdgtckiz.html

[M04] 获取当前工作目录
来源：http://dali.xylfe.cn/Article/details/gtmxwekkrf.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gtjtsfqzty.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtjhdgequy.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtygeikmmz.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtkeyqwplq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtavruxsix.html

Go:   os.Getwd()
来源：http://dali.shzxlz.cn/Article/details/gtarudvuqa.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtubitleiw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gtqgnuingp.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtcfwmmewn.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtvxkbpuwe.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtjbpixqzy.html


<!-- 参考信息 -->