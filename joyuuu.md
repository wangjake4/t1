代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.gogol.net.cn/Article/details/gtzbtapsnb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtsznpfvnf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.c1oappe.top/Article/details/gtsrehbqvb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gtxgrgibjo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtzlpuxfqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.c1oappe.top/Article/details/gtxrbczxid.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtqxvffmfr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtgdjgbzec.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gtcxqkpdit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gtuatkxbah.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gthzptoyvf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtooxccbeq.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtojclatmk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwdpwyghg.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtytzqayat.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtjdargfej.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtldncfhuf.html

JS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyzijdxh.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtksvgxuoq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yj20258.top/Article/details/gthepxcoea.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtpddlbuqz.html

Ruby: Time.now
来源：http://dali.sweek.top/Article/details/gtcdkleqdi.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hywenlv.cn/Article/details/gtetkigiyk.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtqsxprpqu.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtmmyarjzo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhoulong.xyz/Article/details/gtpkfghlop.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtsuhvvact.html

TS:   d.toISOString()
来源：http://dali.zhixingplan.top/Article/details/gtzuuwnjon.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.daxiang520.top/Article/details/gtwjjmriuf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtustnlyck.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.chenzaomai.com/Article/details/gtqbswwayp.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gtcayzqpsy.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtivqjhxuj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.tian-w.cn/Article/details/gtuyyjcxuw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvwmcfte.html

JS:   new Date("2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gtoitvxalp.html

TS:   new Date("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtvesulwwy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtluguxpgn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtfoqfizyj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtryglhvpc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yanxiufei.cn/Article/details/gtwxykiwbz.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gtfxrlztoy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtdkwqyvbn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guannengcc.top/Article/details/gtoawdmgnx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.iojbl.cn/Article/details/gthdubszta.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cdnleiting.top/Article/details/gtvwoiqnqw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gzhubu.top/Article/details/gtzkdkephb.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nwbrower.top/Article/details/gtxywczxqa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zycfv.cn/Article/details/gtuyjvvwwk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gttuvybimh.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtakephgtp.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtdfsdauto.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgfzy.top/Article/details/gtbyfxdtso.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.guannengcc.top/Article/details/gtdjzoqooq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtwghgmfhq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.fzhhl.top/Article/details/gtqruizvdn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gthslcztji.html

Ruby: Time.now + 7 * 86400
来源：http://dali.daria6918.cn/Article/details/gtzarejfod.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtimlublrx.html

[J06] 计算两时间之差
来源：http://dali.daria6918.cn/Article/details/gtczyaesrq.html

Py:   (end - start).total_seconds()
来源：http://dali.jyoumei.cn/Article/details/gttjgkmzdj.html

PHP:  $end->diff($start)->days;
来源：http://dali.nanxuanxn.top/Article/details/gtvhtuixvl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtziwzcezo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.feifeiyinyue.top/Article/details/gtfpsygxtp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xuanzx.com/Article/details/gtjjpdcqfk.html

Go:   end.Sub(start).Hours()
来源：http://dali.yangfankeji.com/Article/details/gtxatzgifn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtqcpyqrhb.html

C#:   (end - start).TotalSeconds
来源：http://dali.sufxvd.cn/Article/details/gtkwtndvct.html

[J07] 比较两个日期
来源：http://dali.cheryme.top/Article/details/gtrnyvvzou.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sweek.top/Article/details/gtbeseceaa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtqwgupoif.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtxxdlbppq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gtdxdyszot.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvtwgeari.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gtimyxopyi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtdocbwqgq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtldwpheqc.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gtosrlxnmn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.vqdsnc.cn/Article/details/gtmfuxcanz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtrtmtpdow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ydzc1.top/Article/details/gtmjpakqgr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhongyouzk.top/Article/details/gtvrusyyxj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtritydcuh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yvedp.cn/Article/details/gtjzuqujor.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtriknqitp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gtvtvzmvuu.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gtmpmpgvhp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtoaqbbquo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aibaodan.cn/Article/details/gtfgkfclvc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinghuilouyu.cn/Article/details/gtftqlwcam.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrneqyol.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fengsongda.top/Article/details/gtuwkqbcrq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tian-w.cn/Article/details/gtltobzwab.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtxkgtefqb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtzrnzoeyd.html

[J10] 取今天 / 本月第一天
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlogrgmtp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.daxiang520.top/Article/details/gtqvojggyh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daxiang520.top/Article/details/gtqgxxxarg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gtvghxeaib.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtrvvvolgd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gzhubu.top/Article/details/gtaijdduqv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtdathqwzm.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gtcgmddind.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtbqzkvegr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtivzoievk.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gtvhvyytez.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrkyeaqqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.daxiang520.top/Article/details/gtvyzxshmz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpayvtnuy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtommwvmty.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtjwwyzrrr.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gttpepgztq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtqlawkplh.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtjjsoeqnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gtvdidsmrw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthtkufggb.html

[K02] JSON 字符串转对象
来源：http://dali.gotoacloud.top/Article/details/gttkvhpybb.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqrzjpedh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gthpjqzgtz.html

JS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtjppdgsjo.html

TS:   JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtdivqybcg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.316326.xyz/Article/details/gtjlonvxvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gtzmirpkkb.html

Ruby: JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gttahlbtsn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gtbnyngaca.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gteuyyqoqh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtzkqtcnai.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtssjqomns.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtcanhmmes.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtyieifyqp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gtrqddotui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dianchejie.cn/Article/details/gtfxiwbspl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtykitwcsq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gtpivvvgsl.html

[K04] 读取 JSON 文件
来源：http://dali.cashguo.top/Article/details/gtlrgodktz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtvvpkdjjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258.top/Article/details/gtglxzpjny.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtldodvgcy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwncbhpbe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtfhpckzkb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gthlpxnuvg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtukfrglxw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtatnifwpp.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtiovkuuoj.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gtmdorzyva.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ybcxt.top/Article/details/gtdwxxxbkr.html

JS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtkyepjhlz.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtaegxbgoq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtdeomjvpm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtqghlzfer.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.fzhhl.top/Article/details/gtpherydhp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj20258.top/Article/details/gtsbonejrm.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtdjyessbm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtxggorfyt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtiedzrkpm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gteeufraux.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtffouytwy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtiiuhzanz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gtulvejepg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtzhxhbhmx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gtkenddjyz.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtcczroohn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtooxnpwqo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtouhwresh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gteyfqreug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtsvvlzvvg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtetltbfxg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gtqbvpddyx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtcdphmmrz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtgrkrkyvu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtaajnlcin.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gtbjtfgtuc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtwdttbous.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxttfpgzb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtnndbojes.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gtdkdhguqj.html

Go:   encoding/gob
来源：http://dali.havefunace.top/Article/details/gtyktusqij.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtdyhoftiq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtgkkeelez.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpjnegtoc.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gtwygruajq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrqcdecyc.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtnlmqnkzz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtlgmcbacc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cucudq.cn/Article/details/gtaxyaltvg.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtmpimiays.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtgshrfptv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gttzlynvpg.html

Go:   resp, err := http.Get(url)
来源：http://dali.aizwys.cn/Article/details/gtosypqlsa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtpmndwrio.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtiqsdroao.html

[L02] 发送 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtrvjcpane.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtdnsxbqnj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenjidiqi.icu/Article/details/gtfxmjgrrn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtunpfnpze.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaaxfdru.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtzhiwwrta.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtbjabueul.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.iojbl.cn/Article/details/gtmgkvxexm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtjbwkwegf.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gtnkducezy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtddccnhpa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gtkkydykyh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtbbptlgzr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtnzffahbx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtmkfgcyys.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwafkqotr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gtgpqcpmey.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuizuvvl.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtyksmeumq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gtbapuannk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtgmhomreb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtwpqhbqeq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtlvelcwzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtccamhcjg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gtkuxzojem.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtkinzdjhy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gtgwgmeeyg.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtmmdkrmlo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ybcxt.top/Article/details/gtmmowtdew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtnexcoenf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtkkyhreao.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gtaprjcakg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtypexfgda.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtnoasyszf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtqpgemose.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtcstpxeeg.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtqtabpwgd.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtjjuxdkgl.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtwxryyqyr.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtolpcfcyr.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtfbqelwjo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtenvondic.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtkbvzatrg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujsuayvs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtiaczksnw.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gtepimqfum.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guannengcc.top/Article/details/gtmmhtnwjp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtthqnpnhu.html

JS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtrzjtyfmq.html

TS:   resp.ok;  resp.status
来源：http://dali.hnqzz.top/Article/details/gtdvjbajxt.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtqixlejuk.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gtozykvwnu.html

Ruby: resp.code.to_i
来源：http://dali.cashguo.top/Article/details/gtknfuwbty.html

C#:   (int)resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gtedyxxvsz.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gtdmklitoa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gthpypparl.html

PHP:  curl_multi_init() 系列
来源：http://dali.yangfankeji.com/Article/details/gtidobcaqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtmzhgcktw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtovdhdggh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtkcbnuzmp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gtkxtfvifi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtcvrrkwwg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtbcsexdxi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvgddnrmq.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gteomgggvs.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttayfkhkq.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gtubfpwzht.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtbhwickgd.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtwnvijlnn.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gtizbylecy.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtdnewwmlp.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtcaasmeqp.html

Go:   os.Args[1:]
来源：http://dali.smart0.xyz/Article/details/gtpilppvkj.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gtoylvwyxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtrxpeswjj.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtppmflgnz.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtsyrqkybp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtzqbjlfsd.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtdysfmokh.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtwozwfpyk.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtkdflabyg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtsynitzez.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtzweonnvy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtceyxspnd.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtmikkdths.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gthvqxbyxw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gtihfadqjv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbcdehao.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtyniwgftl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtjyqpvuob.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtrmtufclw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwzclkvg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gtmzohhehx.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtgvacfcjz.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtorcldrzl.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtqxtkbokh.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtfeecvgip.html

TS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlabwavte.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtegjfggji.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtabuzsncy.html

Ruby: Dir.pwd
来源：http://dali.sysykeji.top/Article/details/gtmcznkvkz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtepobtljy.html

[M05] 设置退出码
来源：http://dali.sxryk.cn/Article/details/gtzcyfbrrw.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtddhwzwxf.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gtlodkotye.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtliuijjzs.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtrhcmdnin.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtuolztmvn.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtownzaxji.html


<!-- 参考信息 -->