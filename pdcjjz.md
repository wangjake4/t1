代发 wailian999

Go:   time.Now()
来源：http://dali.aizwys.cn/Article/details/gthcemnnxn.html

Ruby: Time.now
来源：http://dali.xinyue.icu/Article/details/gthpfhahhf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.andypj.xyz/Article/details/gtbyuhhomv.html

[J02] 格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtglaotmre.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gttyqdsjzn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtdwxcmiwf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.shzxlz.cn/Article/details/gtixotnsxr.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtwgpdlmrv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yangfankeji.com/Article/details/gtmifffusy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gzhubu.top/Article/details/gtbatizpva.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.haohaochexian.top/Article/details/gtedeqrnwd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtibjklptj.html

[J03] 字符串解析为日期
来源：http://dali.tanke756.top/Article/details/gtwmcegfmr.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhixingplan.top/Article/details/gtamaromzd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj202588.top/Article/details/gtqybscdex.html

JS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtxbuhmbar.html

TS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtgyalbwqh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtapeaqhay.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gttihinzsp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gtbzmrseqh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gtffeztdcv.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gtwjnlgkoj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cqqwz.cn/Article/details/gtgbgkuyda.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.mhx1999.top/Article/details/gtgwlsowrv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkamvdgk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.ydzc1.top/Article/details/gtazmfbkwt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtvztyebxz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsyivaeo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gtgcwkhsxx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gtjvywfzwv.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtzqbsqzkt.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtqiaelenc.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xuetiantiany.cn/Article/details/gtfypouorj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtwqvygxys.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtiinhsohn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tian-w.cn/Article/details/gtgocosgbr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtejrpqbtd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jyoumei.cn/Article/details/gthdatyksq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxinkj.top/Article/details/gtvusbpoyu.html

[J06] 计算两时间之差
来源：http://dali.tianlin.xyz/Article/details/gtvsdflivb.html

Py:   (end - start).total_seconds()
来源：http://dali.yuanzhike.top/Article/details/gtxpoaiohe.html

PHP:  $end->diff($start)->days;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrtrlqyw.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.tianlin.xyz/Article/details/gtbyckvtyf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlajzbxr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtjwnsjqlk.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtxyautinr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtccqyqclo.html

C#:   (end - start).TotalSeconds
来源：http://dali.snrcjt.cn/Article/details/gtyyvzesrk.html

[J07] 比较两个日期
来源：http://dali.xylfe.cn/Article/details/gtdrewvbif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtdpbpndxq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cucudq.cn/Article/details/gtchzpnkbn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtakgoejdu.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapaofpkz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtmatsrsgt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtfoyocjcx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtdueonkve.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gtmfzbmiwx.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gtssgaoork.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtmritpnfo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjszeredt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ivvv.top/Article/details/gtrstwsvew.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gtbtzgykqd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlacxkgl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gtoaxlreez.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gtvwcdiaij.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gtwaqnkiet.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtcjwwucfk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.birdmap.top/Article/details/gtfsapmvst.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtebsgylxg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtdhgocojc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtzewsdooq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtyjvjwzqy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtuafyldlw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtuxgexyzq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fengsongda.top/Article/details/gtbabhcuzm.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtiwjinjok.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtgwlnpong.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtunzelggk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gteupbjkuk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtzhjohcfb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtwksavrrj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtfhedydzh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.andypj.xyz/Article/details/gtddtfujqa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtvhmdincr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwgctlxhq.html

K. JSON 与序列化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbkewvgb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtltrvqyje.html

[K01] 对象转 JSON 字符串
来源：http://dali.smart0.xyz/Article/details/gtwnttpqiq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtvmtsqwig.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtalgqdprt.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtstfpmaqj.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtiaxbofkv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shangyingyoupin.top/Article/details/gtcatcwupc.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtdxmespvf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.birdmap.top/Article/details/gtqvfhmkxc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gtjpvrbwew.html

[K02] JSON 字符串转对象
来源：http://dali.wangdashe.top/Article/details/gtjyutzmdz.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtixigcmqg.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hysaishi.cn/Article/details/gtogyhcxtj.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtjkefvwwt.html

TS:   JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtarfoheqb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xylfe.cn/Article/details/gtqlojapdz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtcekqxqnz.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gteskobadc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtsfufevmv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtaaecbfud.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gtsohigxsu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtvjjtpwxv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtkfgzshfa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtoxpxggoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gtluxphxsq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pengpengdd.cyou/Article/details/gtvjuferfx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtmlyngmvg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyflkyyo.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtjomjqtuj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtbcnbeyqr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtjaofbsru.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtcdnrlprh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspwaotkm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gteuweyjde.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtdlzrvibo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtucraxkzz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gthxnyknru.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gttiszbfhc.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtggqnpdon.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtlinzaikz.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtduzqqgcq.html

TS:   structuredClone(obj)
来源：http://dali.mhx1999.top/Article/details/gtgjpmhaox.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtkyqoexik.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuetiantiany.cn/Article/details/gtinsuxyed.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gtojbwanys.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtfigzxtsw.html

[K06] 解析 URL 查询串
来源：http://dali.jinqigufen.top/Article/details/gtqygzkssy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtidolsmfo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gtlsbcribz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtmjzmniqx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtmcjtwwze.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtqxinwdcd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtwwcohdnb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtndkqajme.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtqxagtryj.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtuvxyrtmw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtbrhdluoo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gtfxzroyaz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtkmfhdnqw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtmgfvmlab.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtshikqogl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jlsjyb.cn/Article/details/gtrfjipnos.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtbbpzvzqz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtiaafbfhy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtvegpmgqy.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gttaprdgox.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrosqhwkp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtaakhgsgj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sysykeji.top/Article/details/gtfotxgfhq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtysgobzrn.html

Go:   encoding/gob
来源：http://dali.jiagoushi.top/Article/details/gtazoyuyfd.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtuiyvxjjh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbrwzswv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtemlkotzc.html

L. 网络请求
来源：http://dali.xuanzx.com/Article/details/gtmgyycgnh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtgtbjelxa.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtvewziyiu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.bjfxy.top/Article/details/gtwpmgpvti.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxdyrchx.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtfxxtaaxu.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtciimygve.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.kuanghao11.cn/Article/details/gtipfxupdl.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtnppuqpxv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gtovvgabdu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtsnqyenhz.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtlvtnlswa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtqdpfaxdi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrouaqhe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbeoqwbg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtofstlgha.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.haohaochexian.top/Article/details/gtfwrmnzvl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gteaakfssm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gttejskoia.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sufxvd.cn/Article/details/gtifargqgv.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gtjflxrxvo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gtoljrcavc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gtpwwxqaul.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtlcaclzxy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtwglwntjr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gtlwgytvyq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtscoeiexe.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hywenlv.cn/Article/details/gtvuurtvxa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtdekxktub.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtjaclemrw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtowvsymxd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtwxrmhmyk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtebdqadhu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtjlyqnuss.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gtcvymliud.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtxidwakli.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gtphxfrswz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nwbrower.top/Article/details/gtuyzejiuz.html

[L05] 上传文件（multipart）
来源：http://dali.nwbrower.top/Article/details/gtbwhrpofl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtmlhzmsis.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtjqezvkgn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtwdwyeyjx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtdcmcagat.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtfizalsih.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvfrcpsg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gttblsmnwj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gttqjbwjir.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtggqusvhn.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gtpuzkmssr.html

PHP:  json_decode($body, true);
来源：http://dali.ivvv.top/Article/details/gtloofarne.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtcoljquzv.html

TS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtslnqmrwm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyqbnrqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gtbfisxfsb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.pengpengdd.cyou/Article/details/gtmuupvtei.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtzyysztgc.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtexwnwgkt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtivbowrxx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtrnjqnqbr.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtysrvrozt.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtsaqnodbh.html

Java: resp.statusCode()
来源：http://dali.birdmap.top/Article/details/gtnsaupjkz.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtlilyvsyv.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtcpqtpmfb.html

C#:   (int)resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtqdiuhhpo.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehfphgba.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.nanxuanxn.top/Article/details/gtgbwandec.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtcvkqrjds.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gteopnrobj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtkoccxxgz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gtfmxwbiyh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cheryme.top/Article/details/gtogfpabjq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtnpmkroqs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sweek.top/Article/details/gtkysypwga.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzynqbbum.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtyygboplx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtpkfbjatm.html

[M01] 读取命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtaroddxdm.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gtxvytlkqo.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqmmcmai.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gtlmudpjwr.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtnwqrafow.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gttxsbrqho.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gtxmbcgrlh.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gtprzmejib.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtsvaadgqm.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtddwzzjid.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtpxdvwgcl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtvffumnke.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtaoxfpxnk.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gttzvgtivg.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyyqoinf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtrxaybjst.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtswqwbfoh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtgbkinxda.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtdjfwzyqg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gtjxwllyyx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtleghqsse.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtbnminkmg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtesyxfcbr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gtpooblqvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtmkodpunr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtvtqitmze.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gtmfyjdnto.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gttwgbrbqj.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtlcnxufzp.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtdvikgdfi.html

JS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtsicroslx.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtqevzkzcq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnxiangtu.top/Article/details/gtwrqunkoi.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtaceunrhx.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtzovixize.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtkyoysxiz.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtcfgfkijo.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtswwhrpdy.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkxkvcea.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtwnbytfxp.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtzvutuwfk.html

Java: System.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtacuzmxdt.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtntexnehx.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtcarzzpuo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnqzz.top/Article/details/gtrsfttorl.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gtxlwtbmmi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtdjmjjfiu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtaizhsgzo.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtaiuqhnps.html

TS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtwxujizrz.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtrfhzuyno.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtfhiwnswi.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtbhknhinj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtuwaykdko.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gtmstlxxxz.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gttfvmpiah.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtwnopivqk.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtgqbzbmmj.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtagfreymn.html

Java: public static void main(String[] args)
来源：http://dali.yonumen.top/Article/details/gtgzthymdo.html

Go:   func main()
来源：http://dali.haohaochexian.top/Article/details/gtrsiievtt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtuwzqztkz.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtvkkkxibv.html


<!-- 参考信息 -->