代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2boqlccqv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hywenlv.cn/Article/details/gt2ubwqlgwb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gt2cnjxrofp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gt2ualncfac.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.birdmap.top/Article/details/gt2oaktvtjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ppjwa.cn/Article/details/gt2ndyoieej.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.0kj1m.cn/Article/details/gt2xpjocidm.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2lfcjwddx.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ixmebsep.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gqkfwaus.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2drqevfjq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gt2qmtviabw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shzxlz.cn/Article/details/gt2ojbwfpvz.html

JS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gt2smteqlxd.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gt2ghscwtdp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sufxvd.cn/Article/details/gt2aqyqawwh.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gt2xgdnduvt.html

Ruby: Time.now
来源：http://dali.iojbl.cn/Article/details/gt2tyuvkipa.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2guiubanf.html

[J02] 格式化输出
来源：http://dali.ydzc1.top/Article/details/gt2pnvllpbq.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gt2zrvabrlg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xuanzx.com/Article/details/gt2pjtdbgqv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.havefunace.top/Article/details/gt2cbdofodz.html

TS:   d.toISOString()
来源：http://dali.hywenlv.cn/Article/details/gt2oxohnpzy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gt2entcwduz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2xwyvtkyv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2gpkvvfok.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gt2xiqqnhus.html

[J03] 字符串解析为日期
来源：http://dali.aibaodan.cn/Article/details/gt2lzcjudar.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yanxiufei.cn/Article/details/gt2aenlnhat.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gt2atopczvl.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2hvanxzwj.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2jlnylqoz.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yvedp.cn/Article/details/gt2tbpemqls.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ivvv.top/Article/details/gt2rjenbhrr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gt2xeexljvb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2owjewjje.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gt2sadsdqrm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yongpay.top/Article/details/gt2eajelnsb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.guowangkeji.top/Article/details/gt2zdklbnoi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2tqiuvwoc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sepaifrv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2xqezgnwr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2kylqhwfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2ppimzwho.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gt2wpoouuzb.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2vurjirdu.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gt2efigwwsk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gt2svfvyomn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gt2qexbatds.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gt2bbaswzqv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2dteaimmf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.dianchejie.cn/Article/details/gt2rvaxozil.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gt2zxbokwxu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258888.top/Article/details/gt2vljedgwc.html

[J06] 计算两时间之差
来源：http://dali.zhongyouzk.top/Article/details/gt2jmgambpl.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2abjkpqkk.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynxxxxzo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.iojbl.cn/Article/details/gt2ifpnnzrx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtfxtkbs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yangfankeji.com/Article/details/gt2trrquock.html

Go:   end.Sub(start).Hours()
来源：http://dali.yj20258888.top/Article/details/gt2vublemxr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gt2drboadjm.html

C#:   (end - start).TotalSeconds
来源：http://dali.c1oappe.top/Article/details/gt2fhdroaem.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2wtayzcvy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gt2xiyapepx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.iojbl.cn/Article/details/gt2enncgbfg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gt2olcrfkqs.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gt2mghxyrnz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gt2dfqarenk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ohababxg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gt2cuegicrl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2ivetyvvh.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gt2bawzunfb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gt2wzmhvvwe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cashguo.top/Article/details/gt2vchxkght.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ybcxt.top/Article/details/gt2xneeztyc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gt2qysiiird.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gt2eivqsuju.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wevxognb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2skytvcrf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekhbbyjg.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gt2iudobhcf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.havefunace.top/Article/details/gt2aoktiqub.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dianchejie.cn/Article/details/gt2cjdchwbe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigfzy.top/Article/details/gt2qftumspp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctthxqwe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2wzpvrbga.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pycfn.com/Article/details/gt2aehwcsro.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.redwolf501.top/Article/details/gt2pgjfmfrj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ehwqpu.com/Article/details/gt2mldkwuqz.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gt2zblfeyvg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jqgfzy.top/Article/details/gt2pdesoibs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gt2nevxmhjj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.iojbl.cn/Article/details/gt2fglomcdp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.birdmap.top/Article/details/gt2jmucbonw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qzlnoltq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gt2zddjctvz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shzxlz.cn/Article/details/gt2siftisja.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.havefunace.top/Article/details/gt2pdcjsoun.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2uimntkoz.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gt2lnagtuza.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2aioothft.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gt2jeasamaa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gt2yjfkzids.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2lnorvrfl.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2xiwjwfow.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2cwzoiimh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gt2ybudinvl.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2nvzrdmoy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gt2kijkrwvv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jianghu66.top/Article/details/gt2dxigvlmw.html

[K02] JSON 字符串转对象
来源：http://dali.havefunace.top/Article/details/gt2jjbgpjjg.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2qrxdhdyg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.redwolf501.top/Article/details/gt2fkugxrkt.html

JS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2vcokszwt.html

TS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2jostegnc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gt2dftuglnr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2klqrwgst.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2exvvxggl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gt2dapqgiza.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzmrqaiw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gt2ghxpnbas.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gt2olduhuzs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2xspbqmkn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yznsldii.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cheryme.top/Article/details/gt2rshucygh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmyjwpaq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2qiqxzeqh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2cepyrxxa.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2yasmapdc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gt2pneyvayp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gt2lgylkgzu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gt2hjbcjkqe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2qnzdcxac.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2mjeoyjcr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2engtpiln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gt2egiincfw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2rzhmvdfc.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gt2dffaesok.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbufiyhp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gt2hohldlns.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znzmreio.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gt2virchijx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2iovtgmln.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gt2kwatlvro.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gt2cfhftbeh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tian-w.cn/Article/details/gt2onjgaamh.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gt2qxnolapn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivcbyhzt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2kxjlhriy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2rbdfpmzh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gt2kktrnxhn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2msuhttts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2zssflvql.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2ettntbro.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2lcxerlny.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gt2ozhvbtho.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdzsvfef.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.316326.xyz/Article/details/gt2pphdrjhx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2vlglwljs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2oyszpkjb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qclenzys.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gt2pfyfdmbr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258.top/Article/details/gt2kpdashtr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2jhucjmhz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gt2ddwwdhzb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wossvukk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2odsiwzwp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uybhiori.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2uddlunxp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gt2iyfbgpqz.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gt2ngvjcpjt.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2xlngrbyp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2oqnhbgol.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zomogxlq.html

L. 网络请求
来源：http://dali.andypj.xyz/Article/details/gt2cahluwqk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rumlyksl.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gt2jzxpknao.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gt2shwedblb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2vnrtcwdg.html

JS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gt2olzutass.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ridigbmy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbhbcqaq.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2gknnqymw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrpzgyne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2asdlivsd.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gt2vebwhvcv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2qfiwqivr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gt2cfeppdla.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2tqvforph.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2cdpffcez.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2kbqqsctj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gt2spuwaerh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xinyue.icu/Article/details/gt2hycobwkx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2cwpcuxur.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gt2upfhydts.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gt2drcrhhsj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.0kj1m.cn/Article/details/gt2cyekafcw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2oyyrqtqv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gt2penwodao.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2wqptnvvs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gt2zcbwfjut.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2tadwngta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2dlgwvgsh.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2csajyoon.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cupwfvwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2finqjseh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gt2mfiqhsej.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2kahmfggm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gt2mddwqbmd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gt2fzwoncxd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2wdfwyixn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gt2fkzswisl.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2phpcbdst.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhpjvylv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gt2ppyucthg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gt2tctjaejq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2zdjdcckb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2kyblkoyi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gt2hyxnbtas.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2velukdnv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2gcmavaua.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2mkatxtpy.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2fvznqipu.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2antghdrn.html

JS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2qqbijgrp.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2zphxppjq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2dqpbwalb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gt2joiwjijp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnmpawmm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2przkyylz.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gt2vaujtclx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2fruadkur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gt2unfknlyr.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2bbkvsyet.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2ptxqqfch.html

Java: resp.statusCode()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmhrcspu.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2bogopltm.html

Ruby: resp.code.to_i
来源：http://dali.zhixingplan.top/Article/details/gt2kyoxigde.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2rezhgtvm.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdkgdjdu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2kvrvstng.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2kxpumnhp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2unojmiwy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2gjddugxf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gt2lbqxslsy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gt2yjtryiqt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2mbrdwsef.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gt2ntbzfzfo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlsduurw.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2idwiwblf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nngqoycr.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdjnmmnb.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2xyhfkayv.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2wyynwweo.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdmjsvkh.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbqnqall.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2umqopcuv.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2enhqwdfx.html

Ruby: ARGV
来源：http://dali.sweek.top/Article/details/gt2akuoembx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gt2opkscouk.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2wgpuyyyu.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2jihmtehc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpwltrvv.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2qqhwlmry.html

TS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gt2jmauhsyk.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2ofnaohkj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2siyksqye.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gt2zutalrna.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2zvyqdtcg.html

[M03] 执行外部命令
来源：http://dali.yuxming.cn/Article/details/gt2umsdrhuu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dianchejie.cn/Article/details/gt2bsbckgfj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fagpzbkh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gt2xunhxgsg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dynhnjsh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yanxiufei.cn/Article/details/gt2jdqbkdsn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2ygqvxhnu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2jbnzdhlo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsawvgzh.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvnmeydh.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gt2adufqwsz.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gt2ylhvhwqi.html

JS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gt2beynekvh.html

TS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2uhgojqzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2agtofqxr.html

Go:   os.Getwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjkixyue.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2sdpljsuk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gt2womkjexc.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esxmnfsu.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2zwiuppvz.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gt2jmfkpfnp.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2svjanyin.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2zpnzwqiq.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2xjlnhsnw.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptrqznwg.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gt2pwtdjsim.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gt2jzfbboxt.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2glemvbps.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2xfbzwfcm.html


<!-- 参考信息 -->