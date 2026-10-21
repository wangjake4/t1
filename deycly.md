代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtyriatibe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxikggih.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xinyue.icu/Article/details/gtxazojpsx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtbcqhylwt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.0kj1m.cn/Article/details/gtnqvgttyo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.birdmap.top/Article/details/gtvesmtqgv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gttbczywwk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shuidangran.top/Article/details/gteebejmxi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinqigufen.top/Article/details/gtofrlctlt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zycfv.cn/Article/details/gtfcqxffkm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtwcymupda.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthznpvdet.html

J. 日期与时间
来源：http://dali.bjfxy.top/Article/details/gticlduxpx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxyzdtyxc.html

[J01] 获取当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijtuwggp.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yongpay.top/Article/details/gteaqlquop.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.daria6918.cn/Article/details/gttfenptud.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtkzbukfdc.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtgtcpavav.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtlcwtdrth.html

Go:   time.Now()
来源：http://dali.pycfn.com/Article/details/gtrsiqxkbi.html

Ruby: Time.now
来源：http://dali.dianchejie.cn/Article/details/gtxslbqgyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.fzhhl.top/Article/details/gtzxhecmmz.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtnagkzwry.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtphykihdi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtioxcfpbd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxfvliob.html

TS:   d.toISOString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxjfrwqm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtyqgdxdbh.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnldunep.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtyupaltqe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gtkexevjkz.html

[J03] 字符串解析为日期
来源：http://dali.yueranfly.top/Article/details/gtzcexvgow.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ydzc1.top/Article/details/gtoerzjuzn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.daria6918.cn/Article/details/gtedbdkrru.html

JS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtmxryeoqg.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtaykvdmwm.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtqhtdkfro.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtxnvyrrga.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtakiehfjm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gtgbamexvi.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtqhjjafop.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtecutlezg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gtdtyfbucw.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenlongwang.top/Article/details/gtthfacjhw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtqzhrvcjm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtwrgxhscd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigufen.top/Article/details/gtemwlymrw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gtgvungltz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.guannengcc.top/Article/details/gtxpexvcrn.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtrghmrapx.html

Py:   now + timedelta(days=7)
来源：http://dali.yuxming.cn/Article/details/gtlscfiquk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtipbiaqma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtyogknudn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtdupmvugb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtufrwfkbw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.kuanghao11.cn/Article/details/gteeepsrdr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtxbmcacan.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmfplczp.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtryntwspc.html

Py:   (end - start).total_seconds()
来源：http://dali.jqgfzy.top/Article/details/gthjbatriz.html

PHP:  $end->diff($start)->days;
来源：http://dali.zycfv.cn/Article/details/gtvybtciei.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtnvfgbxsa.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnfbyqlm.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtmxwcfnaq.html

Go:   end.Sub(start).Hours()
来源：http://dali.nanxuanxn.top/Article/details/gtldypnewi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfuymkjf.html

C#:   (end - start).TotalSeconds
来源：http://dali.wangdashe.top/Article/details/gtmhdbwkil.html

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtcuisxvaa.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gtwagfcmnx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gthctzxhnb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtvvraxovv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiocvkglb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtubgvdfkb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtffgkbcli.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtwcecszha.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtevymojxf.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtjnngvern.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gtnhejkgkk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gotoacloud.top/Article/details/gtdvijlldr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.kuanghao11.cn/Article/details/gtiepjollj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.mhx1999.top/Article/details/gtowkafhqr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtakoewewb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhixingplan.top/Article/details/gtgrbmxvyh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtkrklsrkl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkozotzzo.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtcmnkfmsj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtyeaayuuf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmztaypbq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtizkeivmc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtgjakikyz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gtavbcvpud.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtsfgmbcus.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtowjcyjmm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtufpawovd.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenzaomai.com/Article/details/gtvrujhbgo.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yonumen.top/Article/details/gtlxiliwyp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.mhx1999.top/Article/details/gtseadxzzs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gthugufoyi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daria6918.cn/Article/details/gtykbjlfdx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gttmppzmmz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gtazofqcng.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtpqqspbjc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtuzruakvx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxklrkhdf.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtcsuyozxi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtofsjcuba.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigufen.top/Article/details/gtkzrueizd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gtecmywqpj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtbmrsigvv.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtccsjtiwd.html

TS:   JSON.stringify(obj)
来源：http://dali.aibaodan.cn/Article/details/gtrvphybsn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gtrqcxiqid.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtcwqopjqm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gthrkmsvdt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.birdmap.top/Article/details/gtnhkgfqbr.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtakwzgysf.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnnujcuee.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtylzaykej.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtyuwzvbmx.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtfqwzqkgo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtpvmxhnmu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtyszjzdfg.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtwfaehdjw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gtunbdmchr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtwxdvcstj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.vqdsnc.cn/Article/details/gtrytduvhj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtekuivicm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwkydppwm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gteldypkry.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtyuyziffa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtbimgtkfz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtdxilpvik.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtnwhnnceh.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjyqpqew.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtfdxdmeed.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtimkqdtoq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yueranfly.top/Article/details/gtbqxuiacw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtimquzddb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtwgpyrqcn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtylufxbdq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtpkmplcvw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtemclmhll.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtdnlfqrai.html

Py:   copy.deepcopy(obj)
来源：http://dali.yonumen.top/Article/details/gtndncspck.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gtmgrgvkns.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtqpmwdybf.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gtenomksbp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtqkzttfpk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gtymumsmkb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shzxlz.cn/Article/details/gtezsocyjp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtdraeedxa.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gtdqcrpbzg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtugwyaptp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hywenlv.cn/Article/details/gtnbrpsdpg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtjznnnzwb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtgpeypwsc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.meibo888.top/Article/details/gttzmrveqw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gttqycensf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtwpjpwlhf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtxlrycyls.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtwojgfcde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtxghcgkmu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtsqwjpbyi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtghgkxpyp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtkeemshyj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtahqzfixj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtccpenprv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cheryme.top/Article/details/gtosnwburq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtwzcdszwv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtarmdqadw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtiftjagcw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiynsqwo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtafllshpe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tianlin.xyz/Article/details/gtwjqbmblw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtdoqsziwp.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtzmfwuwgv.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gturgdocjm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gtfstobgjt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtlyfwodoo.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtzcatuean.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdoekolhs.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjroohdl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtqkwwfqfa.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtfcntuzyu.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtxavawxda.html

TS:   await fetch(url)
来源：http://dali.ehwqpu.com/Article/details/gtfzbalpxb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gtkgakedoa.html

Go:   resp, err := http.Get(url)
来源：http://dali.shuidangran.top/Article/details/gtpwjsuwyn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtjxxdxqck.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtfvlugaxt.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtcpyxseow.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gtinxwyezp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gtgnvouutg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtbolwbmpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtrmmpwmoh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gtrjlyakft.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtwsbgrmcf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gtjzhrzpob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtlnipvfwf.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gtdmkgmjlp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gtcpshaxea.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsrqxamp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gteviatcmn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtodjqpvwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtcnytiiyo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtpmxvpyci.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gttiijmmdj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtuoeuapee.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtrlnltefp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtwtfmuaru.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gtrkyktlbn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtgmagnifn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gtpixvtskg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gtjmfuhddb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtupcysagq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gthmcqpbbf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcipisenp.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjnjwict.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtrupgyfda.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtzeibtvch.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwzgxgmk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqotuqzrx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenjidiqi.icu/Article/details/gtqeenvkax.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtmjqqveqg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gtgcreilow.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtkbyzskyx.html

[L06] 解析响应为 JSON
来源：http://dali.ydzc1.top/Article/details/gtflfqblhg.html

Py:   resp.json()
来源：http://dali.xylfe.cn/Article/details/gtniitgbfw.html

PHP:  json_decode($body, true);
来源：http://dali.jyoumei.cn/Article/details/gttumaxcgp.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gtwgpoxyds.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtvxtebntd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtohidfheu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gttmblljkl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hysaishi.cn/Article/details/gtbxigdxtl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gtmkzfxoba.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gttospjcip.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtijbrtqni.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtmcdafzfi.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtbqpcpyaj.html

TS:   resp.ok;  resp.status
来源：http://dali.sufxvd.cn/Article/details/gtyinmxbgr.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtwuqkkriz.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtcivqjneb.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtuqatwdiz.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtlohtfqtf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gtesgsabjh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtglybjnds.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtncemfdvy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtdsdotjfp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtzrxpxlcc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtjfelyqwv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtjowmkili.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtaxifqifl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aizwys.cn/Article/details/gtvctgktrp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxetohubn.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gtyrraxnim.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtewhgcuwt.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtgenyverr.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gthrujqsgh.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtbxqgeser.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gtdoexriif.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtmxcqwudp.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtunbgnxxk.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtagzyojbr.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtrwkntolm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gtadkurdaj.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtiszqhakn.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtnfjjsplp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtbzcpirlb.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtrwnhlbwn.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtorlvrqns.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtlqdnihbs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtkzozgpug.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtkgazxiwt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtuchtjttg.html

[M03] 执行外部命令
来源：http://dali.chenzaomai.com/Article/details/gtgghrsfji.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtapzwxhzx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtgixzndql.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtrxqttmvq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtfvqdmcuc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gtvtwsnmhg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtuxpbnaxq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtumxezqls.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenjidiqi.icu/Article/details/gthjkdbpph.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtdsosmnse.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtbjjhpuna.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gtoizmbwor.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gthmdwhqrd.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gtibweccid.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigfzy.top/Article/details/gtebmtmkqs.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtadoizhdn.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtvjtsooyu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtkpvpyqil.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtbanlonjq.html

Py:   sys.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtbotdquce.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gthllsgvzg.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvnsrvvfk.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtzbvcvnzw.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gteynwhjvu.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtzihzgywk.html


<!-- 参考信息 -->