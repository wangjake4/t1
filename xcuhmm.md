代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtlevjdxib.html

[I07] 忽略大小写与多行模式
来源：http://dali.hnqzz.top/Article/details/gtkcxtecdz.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gttjihdeui.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.iojbl.cn/Article/details/gttiwycskz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nanxinkj.top/Article/details/gtashowzej.html

TS:   /error/gim
来源：http://dali.wangshuangyany.cn/Article/details/gtpbhlgmzf.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtnwseyuvk.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cashguo.top/Article/details/gtgicricbi.html

Ruby: s.scan(/error/i)
来源：http://dali.hammf.cn/Article/details/gtrmipippx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtddqefzsi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guowangkeji.top/Article/details/gtilqobhax.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.havefunace.top/Article/details/gtiyntnkqa.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtpwoanydh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gtsejlhipw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtprtfry.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xylfe.cn/Article/details/gtdngjoine.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.cdnleiting.top/Article/details/gtyvtlzxal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hammf.cn/Article/details/gtgsrigbvc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtbscbmhre.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtmgtxbtik.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtsudwtunx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtggqfecyt.html

[J01] 获取当前时间
来源：http://dali.jiagoushi.top/Article/details/gtaanacvul.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gtnohaqxdb.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gtdtsaqofu.html

JS:   new Date();  Date.now()
来源：http://dali.daxiang520.top/Article/details/gtieovyidg.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtpmowgiyq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhengqikj.top/Article/details/gtxbqyxiyh.html

Go:   time.Now()
来源：http://dali.wangshuangyany.cn/Article/details/gtndkoeazc.html

Ruby: Time.now
来源：http://dali.zhongyouzk.top/Article/details/gtdxiucssr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gtlzmjiolc.html

[J02] 格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtohiazcfu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cheryme.top/Article/details/gtddjjmueq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtirzgjnjo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtbmqslxzz.html

TS:   d.toISOString()
来源：http://dali.cashguo.top/Article/details/gtktatqkto.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ydzc1.top/Article/details/gtzydptrbt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xuetiantiany.cn/Article/details/gtzmicdmkx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtjlrabiwu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258.top/Article/details/gtnwnvmqva.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtzuivhuvi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.shzxlz.cn/Article/details/gtllcammfk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqygwqafv.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtnglvkhjb.html

TS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gtgcaixppp.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtcgfnapuk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gtnrqpvabl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtutrvkvqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.c1oappe.top/Article/details/gtkhurytyb.html

[J04] 时间戳与日期互转
来源：http://dali.haohaochexian.top/Article/details/gtgenwsfvp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtpvwgbpbd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtzzdlsqei.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgfzy.top/Article/details/gtnpsqzxqh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.birdmap.top/Article/details/gtpbjlmhlj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtjxcstqyu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.redwolf501.top/Article/details/gtzgzopmut.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.316326.xyz/Article/details/gtczwcwdtm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtuuvkkqfx.html

[J05] 时间加减（加 7 天）
来源：http://dali.hammf.cn/Article/details/gtcfxtukqk.html

Py:   now + timedelta(days=7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuemmhox.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtlnwmdisf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtqgntcjbf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtqtpxdsfl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtpnhpxwcu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtjrsndbxr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gtvtbbgfdz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtjmwrryya.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gtzkmpdnol.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gtxijgrpsb.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gtwhrjeklc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gttutyubkq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.mhx1999.top/Article/details/gtikqftmnw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyzdcqjz.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnqzz.top/Article/details/gtwmsqurfu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtcruldwhs.html

C#:   (end - start).TotalSeconds
来源：http://dali.nanxinkj.top/Article/details/gtaxkcanfr.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gttzgnswum.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gtpcmxsgif.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.kuanghao11.cn/Article/details/gtkoaxqics.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtdsfbkhza.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cdnleiting.top/Article/details/gtvhzsepiz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuxming.cn/Article/details/gtrhbonaxc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtnwtabppb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtlmcdarov.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shzxlz.cn/Article/details/gtymfhvmkz.html

[J08] 提取年月日与星期
来源：http://dali.zdqjudy.top/Article/details/gtigdskpmv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtnpsrlnol.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtqmluqzag.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.sufxvd.cn/Article/details/gtxqufeddj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tianlin.xyz/Article/details/gtdcqcfpfj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gthimhqcza.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonsrppwo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkbkteqg.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtomerdzvr.html

[J09] 时区处理
来源：http://dali.zhengqikj.top/Article/details/gtmwsawmai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtvygdxszb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ydzc1.top/Article/details/gtufxaihsw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtyeqfwkyv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gttztchndv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.feifeiyinyue.top/Article/details/gtwrbrtits.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhixingplan.top/Article/details/gtgzoreuqu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtzsgaqpwb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gteyikxxdv.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtxjvxugll.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gtkfciqead.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yuxming.cn/Article/details/gtlackaczd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhkuwpma.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtqyhwubux.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gtwcozxybg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtjtfgclrh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gthexdocpd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtqceeifvv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvccpfgbv.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtisajhlkb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtriypqnxs.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gtzdtpkawg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtmkfapaqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtqtykgfwy.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtzrnbgxfy.html

TS:   JSON.stringify(obj)
来源：http://dali.sysykeji.top/Article/details/gtadiyovgh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sxryk.cn/Article/details/gtmxypzjxg.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtrxamwtzi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtgmhbzqgn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtbisroemi.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gttiohgeot.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtxgymtuxh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gtoaeuvmfo.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtdrwvznyl.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtkdzrnhfx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtmryogkjl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtncrhjizb.html

Ruby: JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtextbojzm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gttpmonxdy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtflrgbfsl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenlongwang.top/Article/details/gtvlhgrgki.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuxming.cn/Article/details/gtdhstgwbx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtchwwsknm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtdmuaxsjs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtqkfikqrp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtdzscsxkq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangdashe.top/Article/details/gtplmyodkq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gtmahfetre.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtxdfedgxg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtiwnvbgtz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtohlzszsw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtsplvvjeb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gtnmavhftn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtyktkfbpo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gtkqfylpuj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtcztibhcj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sweek.top/Article/details/gtmbbnpaqt.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtraoxqxsu.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtbavlpsvl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtkglbtzfp.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuqycwhqu.html

TS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqwxbjwjj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fzhhl.top/Article/details/gtenyxmbth.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gtvsbkaudo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtmvpfekft.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtjwwifhvt.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfmgobsm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtvrvcvzvm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shangyingyoupin.top/Article/details/gtqbqwwibx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtgcfecbkj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gtfxuwgtfp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtjjgajtwl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqexoene.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtpyqeskjp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtajladbtq.html

[K07] 进制转换
来源：http://dali.jianghu66.top/Article/details/gttgsnlpwi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtakuyrllk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gtdxnfqtok.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtzxmxgysd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtcukjqszw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtuiplkkjh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtgntvtgkx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gtumtdbofc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtvjgthias.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nwbrower.top/Article/details/gtmhqhngvy.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtacnpdoox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtlojvnvck.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtgbqczljl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gttsxoamul.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtdrzxeens.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtesgutcid.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtzisrbflw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtgsupkptj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvwgpaigk.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gtagbxfknh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtodhjkysd.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtbxmcdszk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daria6918.cn/Article/details/gtexqdedrc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gthktyqagm.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtuxnoxspt.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gthymlncbh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtdoextoee.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtuqocgitp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gthcrkhyix.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtsxycwapv.html

[L02] 发送 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtonmtxjoz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gtazlzzdmt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sweek.top/Article/details/gtabmihejk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteghtiygw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtduohvkdm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijckpkoz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gthpmddsqn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtdvldlcfr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtateklbrh.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtpkettlsf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtaezpmiwz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtonwwwvwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtgfjtqrco.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtcqqsyymi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gtlmiayfop.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtryqifirb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.316326.xyz/Article/details/gtbamveaes.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtqymzoxay.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gtyhqhkyph.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtaxbaakvz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtezujxujw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtnewppnms.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtevlcntwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtmuigfknr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtpsovpica.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtfpkxzuuc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gtjqmvunfz.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtvbnszcnn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtbqkskkzj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.snrcjt.cn/Article/details/gtqwmkksic.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtumehuobd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gthutkbcnx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnxiangtu.top/Article/details/gtbhdoykkd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gttmaqjqoe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gtefebwcxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtvmwigzwg.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtanczgncw.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtqfamwyya.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtxdysibnn.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtkhowwwmv.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtkjbhzlcv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtfuiobbio.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gthmywdjwb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gtrhmiavbm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtqeqqspjg.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtvqhetdih.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gtfwracbdv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gtnfcpcwsw.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtqtyoxjpp.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gtywoavrac.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtdnwrtgpx.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gttrpxfngj.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtcgknfpya.html

C#:   (int)resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gteertsjwt.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtbbylxvme.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gttdbxknqb.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtuxrndgyo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtxeaipaob.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtitrskxbj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtusxwigjn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilbogptk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtolmmxpzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtfdedkjwt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttddfwtyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gtdomxsjno.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtaafmzcmx.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjukbxwlk.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtsnrhwkkr.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtaikaesja.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtxhukdbap.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtfknteblo.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gthanmdpzr.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtwkxbctfb.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gttekmlvvh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztbbqzuz.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtzryfnevg.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtdpevxmij.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtwwmnmytt.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gtgbzoihwz.html

TS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtfxzlrlyk.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtuptxmebg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtlceozicb.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtjioolcpt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtdupcwkox.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtegcwftku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gttgxdnzea.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gteoqqrpkq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtsuaaqcfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtluxsxyqt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gtyufsafuz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtvfmzbnyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gtmkaezlgi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sweek.top/Article/details/gtveyzlpks.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtamklppyv.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gtzxzzlopm.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtpngksvxi.html

JS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtgbiezhlk.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtqmwdufgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gthuxbwlct.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtnpqovgxt.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfhutzlm.html


<!-- 参考信息 -->