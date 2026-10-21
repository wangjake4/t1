代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gtrcipqzzq.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258.top/Article/details/gtfwhjxfnf.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gteeqlsghr.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhoulong.xyz/Article/details/gtiuxrqcpg.html

Go:   time.Now()
来源：http://dali.yvedp.cn/Article/details/gtncpaqmuv.html

Ruby: Time.now
来源：http://dali.jinghuilouyu.cn/Article/details/gtsanokhsk.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yanxiufei.cn/Article/details/gtyblwkadc.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtynmarcfd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgfzy.top/Article/details/gttfllzfgu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtzmaqkqtw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj202588.top/Article/details/gtpornshsx.html

TS:   d.toISOString()
来源：http://dali.0kj1m.cn/Article/details/gtfqkwtvgc.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cqqwz.cn/Article/details/gtvjxfhqfm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gtqdqfiiko.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gthiqrqntx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.vqdsnc.cn/Article/details/gtvymyqvqm.html

[J03] 字符串解析为日期
来源：http://dali.chenlongwang.top/Article/details/gtgjdpkemx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenjidiqi.icu/Article/details/gtrnhvqjcz.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jqgufenzy.top/Article/details/gtwdxdlnsb.html

JS:   new Date("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gtfbpytwhv.html

TS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtuupclrzf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjdnhttf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtajlkttvp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtqrxokprv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj20258.top/Article/details/gtwqvhnuvs.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtobnqflqe.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhogonsp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtpqjhqygn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtjywbnwlm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gtrkkerhfr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jianghu66.top/Article/details/gtflbebuvw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.meibo888.top/Article/details/gteqfaugxv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtckgrnywb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtwyuhohsc.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gtcvbkeqok.html

Py:   now + timedelta(days=7)
来源：http://dali.hnqzz.top/Article/details/gttyeqranp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.ydzc1.top/Article/details/gtntqfhmbe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gtntpnzhoa.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahsslluh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hongshengwenyu.top/Article/details/gtshbslxgp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtsagjtxys.html

Ruby: Time.now + 7 * 86400
来源：http://dali.gogol.net.cn/Article/details/gtaqxutjbo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.havefunace.top/Article/details/gtxwryxshs.html

[J06] 计算两时间之差
来源：http://dali.zycfv.cn/Article/details/gtcaqjnlkp.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtxuqsbsuj.html

PHP:  $end->diff($start)->days;
来源：http://dali.xinyue.icu/Article/details/gtdgveqrbj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gttibfkgey.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gtrpbmvtvn.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gthhmxvlvl.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gtkktlybxr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhengqikj.top/Article/details/gtdocvpmhm.html

C#:   (end - start).TotalSeconds
来源：http://dali.jyoumei.cn/Article/details/gtspgdukea.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtxxuhlqsf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogqimohq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtjkrmneej.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gogol.net.cn/Article/details/gtfzvbsitu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cucudq.cn/Article/details/gtouununiv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtrapltorj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zycfv.cn/Article/details/gtadwyqrmx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtpqtxhuqw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gtylwxpthk.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtzomivpqg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gttwwaltts.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxinkj.top/Article/details/gtgseaqlvh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtqmcuxthv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guowangkeji.top/Article/details/gtbscxofii.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.316326.xyz/Article/details/gtqdvpkcde.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.wangdashe.top/Article/details/gtlnsbimdf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.dashuyun.cn/Article/details/gtpbcwagek.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj202588.top/Article/details/gttxgptxml.html

[J09] 时区处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzertxrlq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtpawjypql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinqigufen.top/Article/details/gtbugatarw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtyvzltygm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtblzzxugj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtyanpsvue.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfftgylfw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtmjrtlokz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gtlgovezpn.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gtivaurrit.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmyfmyml.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtzshzqgfh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtoyankudr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtzqcrksvz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtkxvtpyzi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnxiangtu.top/Article/details/gtlkgthpgi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cucudq.cn/Article/details/gtjdtytpaw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gogol.net.cn/Article/details/gtezggkqhs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjwbzbwvk.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtqxtriqju.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqnxzqspf.html

[K01] 对象转 JSON 字符串
来源：http://dali.zdqjudy.top/Article/details/gtrsxnocld.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtlqdrnduy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtxuhwmiku.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gtavuxeqxz.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtyhugmpoi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtcbavgutb.html

Go:   json.Marshal(obj)
来源：http://dali.redwolf501.top/Article/details/gteptkixvi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtkfmlptrf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtwghllktf.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtojkbxtig.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtsulpygrm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guowangkeji.top/Article/details/gtnnlisjph.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtbeospojy.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtwotivsyv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gtmobmixvo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigufen.top/Article/details/gtztzymqsv.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtefuajasx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtlmphkvgb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtqcnocevf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtlhbzqbzw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtsdvpyvhr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlzrpgnag.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxuanxn.top/Article/details/gthiqcypvv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jyoumei.cn/Article/details/gtimjgukah.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hysaishi.cn/Article/details/gtisvnphtr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwedhstou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hongshengwenyu.top/Article/details/gttovhyeyn.html

[K04] 读取 JSON 文件
来源：http://dali.yueranfly.top/Article/details/gtvvqciwqw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gtizrdvzba.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtsbzbeusn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtxicwecwt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtssuhchoq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtcxxfpmct.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtujhtdrhk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtcahbsnwy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtkdofhxhs.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtsjluhqvk.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtlwbqoiwq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtrbabawor.html

JS:   structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbncjkrua.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtsczywiaw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtfyjabgum.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gtporoeeuc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gtjncbduet.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtctpzproq.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtdsnealqe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gthfharrnj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gtosuxeymx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtrijzienp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gteuoarkac.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtnmdeueya.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtslzjcvdo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlvpeiat.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtczfbvqpp.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gtmkofedql.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtttjzafik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtmbagsvff.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtzhotctfh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtinguspug.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtkubajhic.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zdqjudy.top/Article/details/gtwxinkhcw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxinkj.top/Article/details/gtjgakvvvh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtlpqbxsxj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtijyyiydy.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gtgvoiqpxt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gtwkhlbxfw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtlsnhmket.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtnanjktuk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtjhioelvk.html

Go:   encoding/gob
来源：http://dali.zdqjudy.top/Article/details/gtrlsqjatr.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gtgjnbmgww.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gthzzvjktl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtpnlklwod.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gtrivduqjp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpglymiyt.html

[L01] 发送 GET 请求
来源：http://dali.svipenyu.cn/Article/details/gtqfmsrxmc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shangyingyoupin.top/Article/details/gtcvpklzzw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtstkzlmhz.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtqytvjrzh.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtgnmhueqd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gtntzruohw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtazbjtvsb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.0kj1m.cn/Article/details/gtanmsjpod.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtuqlrabxx.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtnkwdbhxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtplcaozcg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gtnjnbzlzh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gturwpbojc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtokgaddkq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gtosxmurpy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gtshdgsmje.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cheryme.top/Article/details/gtconaohkn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtxlkqvkne.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gtvfyttcno.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtnwyranfg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtzsvrlnpr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gtlhvtszwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtarqqeoxt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtpqzgdnbm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtchphvnsa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gtzzlhlexh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtjjpldrqy.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gthbcdbxbv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtqifvvajp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gtketpdmet.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gtqahcjrpl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gtgoiqltgg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigfzy.top/Article/details/gtsysilntw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtuijnpuyl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtfxbnfirh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtpjlkoygp.html

[L05] 上传文件（multipart）
来源：http://dali.gotoacloud.top/Article/details/gtaoxsnbvm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtegjdhcya.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.mhx1999.top/Article/details/gtijgpfhnm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtjbqibxgy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtqarwpewp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaecymqg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtttlnmxqr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtpilklcyv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gtmievxohp.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gtxfxwkana.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtywiqufoz.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtyzqslvpy.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtarevxdhr.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtkzxzfqwp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gttjwkpysw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gtfozcimux.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtxkfeapig.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gttbpjzocr.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtghlqnuue.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangshuangyany.cn/Article/details/gtjvalnynu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gttvhqlncr.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtjqzqeqwb.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtkqdlbocx.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gtzadcmjsc.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtdrzhfots.html

Ruby: resp.code.to_i
来源：http://dali.meibo888.top/Article/details/gtgcjtuavr.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtxziidwhu.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtgjxewmhb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtyhtgjdqt.html

PHP:  curl_multi_init() 系列
来源：http://dali.hongshengwenyu.top/Article/details/gtkdzaqkel.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtciirofaw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtelhqwoih.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.quarkkingdee.top/Article/details/gtouegbsdm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtomxsppqf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtllyoswlh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gthrpobjpx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzbmdkcfn.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtctlalkth.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdyaeyamc.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtfxjvxsyv.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtcbkrxjxs.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtouriicrr.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtjxnixyyu.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtxfbaoyew.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqprxafzi.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtkmqmtzse.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtpcmuwomz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gtlhpcfude.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtdfdzrxuz.html

Py:   os.environ.get("HOME")
来源：http://dali.hnqzz.top/Article/details/gtylbbalbr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnpxnekn.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtjmkpneih.html

TS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtfwksxriw.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtvxkmlkih.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtjewetewh.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtfdyuryll.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtgvusdnjt.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtoyctgvtf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfftpzpmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtngzbfagq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gttntzxfzl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtltyghsoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtxswnvzpx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gtlgvonlhu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtajupjfne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtkcmejjpi.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gtqsyhdnqc.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtopbwwueh.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtlrfxauyl.html

JS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtxpckkkhg.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtnwoclygx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtjwijwedq.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtmjjhjoby.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtcavdijtl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtftgjfwce.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtrukfzptg.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtzfphlgpw.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gtbcyiygqh.html

JS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtqlpfwyun.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttotxkbjw.html

Java: System.exit(1)
来源：http://dali.gzhubu.top/Article/details/gtfbezolqp.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtjzwpamay.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gtpepbdubb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtieyhafdn.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtgkwvhsvz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gthfcypzfx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtghrrmogu.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtndmwripp.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtwvryvnwz.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtbtvlokae.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gthwhccalj.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtmfycyyzd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtgmjtddlg.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gtafpykmpe.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gtepjhbtle.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gttedfidtk.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtnpleitvl.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtychaxyvl.html


<!-- 参考信息 -->