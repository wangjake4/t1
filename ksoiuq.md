代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.meibo888.top/Article/details/gtpgsmqjnv.html

TS:   /error/gim
来源：http://dali.cucudq.cn/Article/details/gttgtsytrh.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.gotoacloud.top/Article/details/gtndxpsbku.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yj20258888.top/Article/details/gterjcqfir.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthefxiclc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hfpthk.cn/Article/details/gtgculsvgc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.smart0.xyz/Article/details/gtgafuolkb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.haohaochexian.top/Article/details/gtcppskmak.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtksdivopm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.wangshuangyany.cn/Article/details/gtcbzrpxgu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtualyqpkz.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtaqlpprnr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtyzfzanlh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtanhmhnfy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgcrzgyb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzpmbecth.html

J. 日期与时间
来源：http://dali.sufxvd.cn/Article/details/gtzkkfabue.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdesbosqo.html

[J01] 获取当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtnuggplha.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gotoacloud.top/Article/details/gtzwokyqdu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gtntwdxzmy.html

JS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gteobgglkj.html

TS:   new Date();  Date.now()
来源：http://dali.nwbrower.top/Article/details/gtzorjvsnx.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cdnleiting.top/Article/details/gtqajlcavf.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtmpofestm.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gtlrptkweq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtkwceydsu.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxodgterb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtasifyfwj.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhongyouzk.top/Article/details/gtdcognaej.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zycfv.cn/Article/details/gtrljpvttb.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gthlmmiclx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaciokpgl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtoldlfcwq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtqwmexsir.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sweek.top/Article/details/gttrrtsjqc.html

[J03] 字符串解析为日期
来源：http://dali.hongshengwenyu.top/Article/details/gtqeyghwkt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtpvebksrx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daxiang520.top/Article/details/gtewjnpcyr.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gttcnirjtj.html

TS:   new Date("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgzgbvgv.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtiyladdnm.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtlmuhykji.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtzhcwxlop.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbphupzmk.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtmjaphebe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yueranfly.top/Article/details/gtlrboirzf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gtkbrvuxmj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtuiuoygbz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtanlqglkk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gtnajjwwyw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtgwojhhfv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tanke756.top/Article/details/gtenmldlfh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtthxgoyyw.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gtcmammzre.html

Py:   now + timedelta(days=7)
来源：http://dali.guannengcc.top/Article/details/gtybztanfb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviaourts.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfxhirlj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtxzvhzxwl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.quarkkingdee.top/Article/details/gtwlqbxcia.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtcoppsmrp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xylfe.cn/Article/details/gtzbuzjdui.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gthqwanbmi.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gtdbudouvp.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtszbsyava.html

PHP:  $end->diff($start)->days;
来源：http://dali.hywenlv.cn/Article/details/gtdkmchpeu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.c1oappe.top/Article/details/gtsmcgjzsq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangshuangyany.cn/Article/details/gtmjyvhhio.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sxryk.cn/Article/details/gttnpihowy.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtyvhrdndq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gotoacloud.top/Article/details/gtbefjgtzn.html

C#:   (end - start).TotalSeconds
来源：http://dali.mhx1999.top/Article/details/gtizsmapup.html

[J07] 比较两个日期
来源：http://dali.aibaodan.cn/Article/details/gtcypseamr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtyqrpnuwm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gtzchysxvg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtbdjiikxq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yuanzhike.top/Article/details/gtalzvqbpq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.kuanghao11.cn/Article/details/gtksfhocfl.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gtzemebniq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gttrozcxqg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtevredqnu.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtkeoeqema.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.guannengcc.top/Article/details/gtfdsmpvva.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gtwkqklfvj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cashguo.top/Article/details/gtxbhyiywf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yvedp.cn/Article/details/gtiqwfkfls.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtumjovuld.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.kuanghao11.cn/Article/details/gtnzkluabh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtnhnwtytl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtqsnsrqjn.html

[J09] 时区处理
来源：http://dali.cqqwz.cn/Article/details/gtcgvscshp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gtpbqyhirs.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuetiantiany.cn/Article/details/gtlribguac.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.bjfxy.top/Article/details/gtlmtosuww.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtrbnhqiew.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtzqjlrtxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtgzvzkhoj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.pycfn.com/Article/details/gtyewdxhay.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gtkhgrbaga.html

[J10] 取今天 / 本月第一天
来源：http://dali.xinyue.icu/Article/details/gtxdjnkexo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnxiangtu.top/Article/details/gtvrxzfxvo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zycfv.cn/Article/details/gtbuhpjylj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.bjfxy.top/Article/details/gtswvqyzgq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtkbrwoclm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gtfsrpbteb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gtvnrzozbt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cqqwz.cn/Article/details/gtxyqvugym.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtianizbpe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtndsgnfni.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtvzkzsgoa.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqookuysh.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtzuacjvme.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtwhlrxyvz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtatahkzhe.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtekmsikhe.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgmyhkjol.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtyxjtdwrj.html

Go:   json.Marshal(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtmlaytuxv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gotoacloud.top/Article/details/gtkqyxkzim.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gtmqkouhdz.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtywbcgmpo.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtqnmuilku.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgeaqhpp.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtzvfzfclv.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtytgccaqn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqkbjaia.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtplcqxpdk.html

Ruby: JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtrjrtsqmk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtkqjllwsi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gttjyxioyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyfdhxkz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gtlueoovzj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgmyyqnp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtjoodahhp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtjftttjrp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtmdfhvtcu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrnljjrg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtjqpsfxxw.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtbxxxjvat.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cheryme.top/Article/details/gtiqacinzj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gtoeusciid.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtygetxdby.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtfisijneu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtjvjmrwzj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrkemakr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtgymcuqcc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gogol.net.cn/Article/details/gtgwasbrxo.html

[K05] 深拷贝对象
来源：http://dali.sufxvd.cn/Article/details/gtuoerefge.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtgzlreofg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtwmkjflop.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtkqprqnvb.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtfvbpyhbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtgefdulmf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhengqikj.top/Article/details/gtesgpnyem.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gtxcuqfsgf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtdctoyqpq.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtmucehgfr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtrpoovbtt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgfzy.top/Article/details/gtuswftxnw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gthhiyjrpi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtrblzaung.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtnsmqpqac.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtfrbzvoff.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtaflhzjpl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtgphfdlhb.html

[K07] 进制转换
来源：http://dali.cashguo.top/Article/details/gtohnywlwr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtcoqkvxvg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gtgizokspd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtfrajczwb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtlpewqfzc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtvozzqhgn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gteztbdlzr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhixingplan.top/Article/details/gtpmudxgna.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtlnzbzhgp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gtmhwzqpdf.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtocekmnsa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gtdmwvetig.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gthvcjvfaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtjuuygtpf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangshuangyany.cn/Article/details/gtzbniotcb.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gtfdnkqkeq.html

Ruby: Marshal.dump(obj)
来源：http://dali.birdmap.top/Article/details/gtpjebqhzd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtrddgepwu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfftooset.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gtieixgwkh.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpcumzobl.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gtszikwftx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtxghvirdi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteooevrdg.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gthkpknzlg.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gtrgynxfqe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtadgerbfp.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtvodofjig.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtfezeuknr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gtonfuvkkn.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtcmpajyrx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gthcepwamq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gtuugfiqdl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtwijbofco.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtrvltyjsc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtqzxqbmjc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gthoypsmrf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwexsfku.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtotmpblwf.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtlbcfdkbn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtfnjrivme.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hywenlv.cn/Article/details/gtvajidgiy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtjjvxqblm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtnnktougn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dianchejie.cn/Article/details/gtwammcqra.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gthmkataxz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtiolfncrz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtkfmiphsg.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtvyqachzz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticgjzqzd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gthavgoywk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtmmzgwrby.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtgpyujynj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsifthqvu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gthbckccvm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.quarkkingdee.top/Article/details/gtekyrwwyz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtdehayqgv.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtxzpqvjwn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtqiwafzxz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtblshzymq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtmpjzzmlh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtephdcbye.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gtdzyyyhlm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gthruxgjzu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtzwineosi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gtgcmxpgqo.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtvcyuwtcj.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtpxyxilhz.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gtksayorrs.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtctcdjotf.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtbsvwftjn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtcobpzqqx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtnmfrbhui.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtygnsingx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtfefnhrnm.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtxvgwpcld.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtdvdpjtzt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgfzy.top/Article/details/gtcwtrryoy.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtxzikbwjm.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gttpwzyivz.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtlqpyawjq.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtzotpyynt.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtdteihtgr.html

C#:   (int)resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gtsbahqtdo.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtgyfxfwfe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aibaodan.cn/Article/details/gtrpuvxexi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtbbvigpmw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtjtorvvug.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtgdxsvyng.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtmxfjphjz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuanzhike.top/Article/details/gtfyoyuqgf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtkmrhjzuk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.meibo888.top/Article/details/gtjvajkyxv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsvyzsfwn.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtyunoulpk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtliubixto.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gtacicseff.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtsrpwkjsv.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgbdmwkj.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtejcdslib.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtingdiqjp.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtgdhhmugq.html

Go:   os.Args[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtbsuhjfej.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtmcpaabtu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtknhcfruh.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtxoiddnzn.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtzodyspxo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtjwgywtyr.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtjxqxyvph.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtvtlhzqiq.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtdkrzqdjl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtgpoxmalx.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtulnzskam.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtvkxeghal.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gtkmiypcau.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gtzexeslhm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gtzvfimdoo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtxokyoqlq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gthfouelyf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtamdlotjj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtbkzqitxy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtvdsfpimw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtrbaxxzhe.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtokyztfgf.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtcsfejzzo.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gtcvmlheyq.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtxxkiqswb.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtbxuousdz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.snrcjt.cn/Article/details/gtdmpfcsbd.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtxivlweqj.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gtasrhkavk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gtohdgcehs.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtutavgope.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gthwegijmo.html

PHP:  exit(1);
来源：http://dali.hfpthk.cn/Article/details/gtdbzoxuxz.html


<!-- 参考信息 -->