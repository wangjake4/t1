代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.tianlin.xyz/Article/details/gtszmlbrok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cqqwz.cn/Article/details/gtujdungyv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cashguo.top/Article/details/gtuuzxoynv.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yj20258888.top/Article/details/gtytrlibcj.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhijiandao.cn/Article/details/gtjzounnvr.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtkvvtqdxf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtwpmxdrtq.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yvedp.cn/Article/details/gteyqwvxhc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtidhxyqho.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gttzgkvbcr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gtqrfidyfr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmzlnaadu.html

J. 日期与时间
来源：http://dali.mhx1999.top/Article/details/gttrdpksco.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthknppwkl.html

[J01] 获取当前时间
来源：http://dali.9152youxi.cn/Article/details/gtxosaghbw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.snrcjt.cn/Article/details/gtvyqjfvei.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtjdlsckne.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqdbzrws.html

TS:   new Date();  Date.now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyffvrhn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuycniouk.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtfvniishx.html

Ruby: Time.now
来源：http://dali.havefunace.top/Article/details/gtoaldshsu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj202588.top/Article/details/gtjzytnyqr.html

[J02] 格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtndjiqhlr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aizwys.cn/Article/details/gtqqpayyey.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtfppezxif.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.316326.xyz/Article/details/gtzhpjabwg.html

TS:   d.toISOString()
来源：http://dali.zhiwuduotai.top/Article/details/gthnfyaehc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtxkdbecfh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tanke756.top/Article/details/gtvwkkpayn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258888.top/Article/details/gtybfypioi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhiwuduotai.top/Article/details/gtkddtojfd.html

[J03] 字符串解析为日期
来源：http://dali.hfpthk.cn/Article/details/gtfxktlmgt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daria6918.cn/Article/details/gtrmzklbnc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtohyiiicu.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtumrjtewj.html

TS:   new Date("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtzibruydk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gteqduoass.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtfbysryva.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtkopktoql.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtcllljvco.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtwbmjbzpq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtpiutbhzx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yj20258888.top/Article/details/gtphpmzkwu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gtythhzqaa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigufen.top/Article/details/gtasowoesa.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtinjjhvkd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gtniveffnr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xziqi.cn/Article/details/gtppaajmuo.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ppjwa.cn/Article/details/gtknugbygk.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtprpcviib.html

Py:   now + timedelta(days=7)
来源：http://dali.jlsjyb.cn/Article/details/gtrfdhzosc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.c1oappe.top/Article/details/gtraqyrgyt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gthulxhxah.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gtrejdulwd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.daxiang520.top/Article/details/gtoqgpkkrz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yongpay.top/Article/details/gtfptdousx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwepaznx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtvaciafnu.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gtobkibmqq.html

Py:   (end - start).total_seconds()
来源：http://dali.yvedp.cn/Article/details/gtvncyxiuh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnygtxtgn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtuliosysv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnqwdayz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jqgfzy.top/Article/details/gtaoypirem.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtmacraodj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cqqwz.cn/Article/details/gtsyskamuq.html

C#:   (end - start).TotalSeconds
来源：http://dali.aibaodan.cn/Article/details/gthxvqrgrm.html

[J07] 比较两个日期
来源：http://dali.gzhubu.top/Article/details/gtfqoawtqw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gtyyjxhfjx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gtubevnchg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtsqnsuhbv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtwofeshfv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.iojbl.cn/Article/details/gtqnpwqjkt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jlsjyb.cn/Article/details/gtclsvqsfi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nanxinkj.top/Article/details/gtnwyzkmul.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.svipenyu.cn/Article/details/gtzleozucy.html

[J08] 提取年月日与星期
来源：http://dali.gaohongyu789.top/Article/details/gtptvnzatn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aibaodan.cn/Article/details/gtmjjlohtg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtoapooggw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtjnmjtpap.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gtsktefasu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hnxiangtu.top/Article/details/gtzvelzccc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ydzc1.top/Article/details/gtntmihadd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangdashe.top/Article/details/gtsucmsboi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtqmkgrqxe.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtxssgsdem.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gzhubu.top/Article/details/gtkuxpqfks.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gttgfomgot.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtgheoeyyk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtntdweauj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yangfankeji.com/Article/details/gteihcdjbt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtjqiyaerb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.havefunace.top/Article/details/gtgsmpyidl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258888.top/Article/details/gtivslvunp.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenlongwang.top/Article/details/gtkxmzrzsn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hammf.cn/Article/details/gtlgvufuao.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangdashe.top/Article/details/gtqhxjmogh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gthqttftlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtqcovflfz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtvtpmofhp.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtnoziobni.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtuwoijfyz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtlgzjcwto.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjimlvusl.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtddfrducm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdflhyxur.html

[K01] 对象转 JSON 字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwjeylwex.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtnwswrmjm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gtddlvelnl.html

JS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtosuwuzpy.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gtcflabyro.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxinkj.top/Article/details/gtktaiyouy.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtowtmgkti.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtjwdnowow.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpzyohtqq.html

[K02] JSON 字符串转对象
来源：http://dali.yj202588.top/Article/details/gtoqxufcyz.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtpjgcxnrq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gtgpihedmb.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtokhbdwlf.html

TS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gthmnnobry.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtxypuqums.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxnuxnzi.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtzlmcocli.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeymxjhe.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gtwlybpezu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtkcfktvwu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtwybzkviu.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtgpqeddfb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtpqzmtowd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtmxooabdi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtikbphxro.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gtqogmhzfh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtmskqvrkj.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtmthcaajz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtdbefqdvv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtvtlscoue.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnkcljkw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtmlnqlwvn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtndgxbbdc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtunrhtbky.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtfuxdqukh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sxryk.cn/Article/details/gttkkzsvbf.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtihxztvfm.html

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gtugzbggbn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pycfn.com/Article/details/gtkvmnhexq.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtwozdxicw.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gtixlnleke.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtlmkuygkx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtbmwimuth.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtronelqwr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtsuygarle.html

[K06] 解析 URL 查询串
来源：http://dali.jiagoushi.top/Article/details/gtxjschfxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtxakitdgm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtgournakk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtgpiztiso.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhixingplan.top/Article/details/gtfmedcubi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.smart0.xyz/Article/details/gtfrvbzpgb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtuurucurp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtinyswqdx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtydlnifhr.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtnkjjpfyg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtveitnypj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtbiololzz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtxcnthxyc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtzuukkmda.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtwqqjnkbs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gthjvbcbgc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnmsacui.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtpowpfpze.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtzbfiwfsr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtnndinurp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cdnleiting.top/Article/details/gtatpxemph.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtfxubidxr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtuteiwijt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtpwyedqfg.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtvekmlqcs.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtcwtwkuzn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtdsmagnnf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gteztgzlxt.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gtdkngyomt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkttmustg.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtjeothexo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtstnxgvyu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtkojuhssf.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gtcafeirna.html

TS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gthnjrvomh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nwbrower.top/Article/details/gthbzhazjp.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtpamwwnjw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gtowjjoxxl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtmhehhzqa.html

[L02] 发送 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtemjsttav.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtpiowizwx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtdkmcmjbt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtnrzifcbc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtpeutorkt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gttvawmply.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtyajqckbw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtviymcvag.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtgtkeydwx.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtypildygf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtwsezvvmd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnxiangtu.top/Article/details/gtgiwkjuhq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtcpzcniyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtfwjbykxl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtcdneynom.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtkhudqwrs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fengsongda.top/Article/details/gtuuiumpcb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtyhhoplhd.html

[L04] 设置超时
来源：http://dali.wangshuangyany.cn/Article/details/gtdsjcaiiq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtkvtsimop.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtzpkbsvyf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gtskuhfivf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtkithisyw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ivvv.top/Article/details/gttdpbfozz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtnjzxhrly.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtvnpngmwi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtbdvtucmd.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtzsaevxlu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gtfdqvdzfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.0kj1m.cn/Article/details/gtfvbtlzzj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtdjcunklh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gtlnysjojf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtyllrwlpv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jlsjyb.cn/Article/details/gtiowyvqch.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtdctnnhoy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gthuuppwpn.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtubfjfmpf.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtocigwzuh.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtmcdraenw.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtdsritclq.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtymardyul.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtgfbuignq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtttzgyzgl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yanxiufei.cn/Article/details/gtnjpfqmjc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gttezdihcb.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtvgxnblma.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaaxavlp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gtlkfozxsa.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtrjgbgquz.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtumohjxho.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtzhynkryj.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gteyqaehii.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtfcspsghj.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gtzpagerjz.html

[L08] 并发请求多个地址
来源：http://dali.zhoulong.xyz/Article/details/gtwkmdwfop.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtdwflgtzu.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtgmmteuwu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gttennwtlj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yongpay.top/Article/details/gtbszowtkt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yongpay.top/Article/details/gtmbukryzv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gteooajqfh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtbakcpsbh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtuqvtdcjs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjmlaqwev.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtrjnxfpnw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrwugoqbt.html

[M01] 读取命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnqwohtgi.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtwzmbyyzk.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtmtbhmotk.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtnuktrele.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gthsxzbbmi.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwriusupk.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gtwfjhvvbj.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtsvcejqxc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtqdzzfkvl.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtovqfaiyy.html

Py:   os.environ.get("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtuegjcmfw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtineroajt.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtddgxwibq.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtswqvbhzz.html

Java: System.getenv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtjlzvvgfu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtknhdflgr.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtyrtugxhw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtbakzbcrb.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtlnfaflmk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtwofyhaxe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gtojbejubo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gthjzkyjkv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtsvmzpqdu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtpexegsdy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtexioltpb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtdqdrmjnv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.bjfxy.top/Article/details/gtilmcpfjz.html

[M04] 获取当前工作目录
来源：http://dali.jinqigfzy.top/Article/details/gtxkpqxnov.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtmpralkly.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtyvwnsnna.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtipinryfr.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtftbqswxp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gtzattmrxq.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiowhrah.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtogqxajcr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtyjwvvmku.html

[M05] 设置退出码
来源：http://dali.hnxiangtu.top/Article/details/gtwumykthh.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gthcilrukd.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtwgxkvwsn.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtofoagmln.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtyfecyijf.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdquambwq.html

Go:   os.Exit(1)
来源：http://dali.tanke756.top/Article/details/gtxfterqke.html


<!-- 参考信息 -->