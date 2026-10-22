代发 wailian999

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gtqqsrfmpg.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gtczklhfhf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gthcokgizl.html

[J02] 格式化输出
来源：http://dali.yj20258888.top/Article/details/gtqyiozgwm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhixingplan.top/Article/details/gtverbiadp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gttfjciwwj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guannengcc.top/Article/details/gtqgtnnrxi.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtdsqhmlqw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jqgfzy.top/Article/details/gtrtghamyf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtkbdxnlzk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtbmaonggc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.gzhubu.top/Article/details/gteyhfdlvk.html

[J03] 字符串解析为日期
来源：http://dali.aizwys.cn/Article/details/gtyqpealed.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.smart0.xyz/Article/details/gtjdkdbkuo.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gzhubu.top/Article/details/gtwmqxcupb.html

JS:   new Date("2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtkykgbnbf.html

TS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtesykvogo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtuljwmuwl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtrirpspvc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtktwipvod.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.pengpengdd.cyou/Article/details/gtsvudiyug.html

[J04] 时间戳与日期互转
来源：http://dali.jinqigufen.top/Article/details/gtybpiksuy.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jiagoushi.top/Article/details/gtnvcdkzei.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hnqzz.top/Article/details/gtnjovywfv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtxtqoyqrl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gtkabneibx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtgpufyswq.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkhdwugc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohapeedq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gtinvfkchi.html

[J05] 时间加减（加 7 天）
来源：http://dali.cheryme.top/Article/details/gticmmsqzd.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtjdtneefo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cucudq.cn/Article/details/gtijefveck.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gttmcqdawu.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtudndhqfa.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shzxlz.cn/Article/details/gthgefghdy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.birdmap.top/Article/details/gtbrppcgad.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtzfkwannr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangdashe.top/Article/details/gtnixpebwc.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtjcgrsque.html

Py:   (end - start).total_seconds()
来源：http://dali.pycfn.com/Article/details/gtuwbafrqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.xziqi.cn/Article/details/gtcqipaqwp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.guannengcc.top/Article/details/gtkjgnmjdx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtosqemeii.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sufxvd.cn/Article/details/gtdunmedvi.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuanzx.com/Article/details/gtcfydienz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.chenzaomai.com/Article/details/gtmhyygmjl.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtqreuraat.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtjkxppkpo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtakscpdrq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtlbtjovoq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sysykeji.top/Article/details/gtoogsrxxa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gttqpnfnzc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.fengsongda.top/Article/details/gtibaaosra.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj202588.top/Article/details/gtubimvnqw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gteyfjqltl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtdnsllgka.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gthpuqpvhd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ydzc1.top/Article/details/gtizpuhrmy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtzqzsgrmv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.feifeiyinyue.top/Article/details/gtixuztsyr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtcfhjraxx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aizwys.cn/Article/details/gtlztybywe.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gtbzropano.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jiagoushi.top/Article/details/gtfesddlbz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gtecgggrej.html

[J09] 时区处理
来源：http://dali.yanxiufei.cn/Article/details/gtqhzijhty.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jiagoushi.top/Article/details/gtzsuqgsvc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gtertnpltz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtbbznqwuc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gtdnobplsw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtuxqihrjm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtnlkkmoyi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gtvdiptxoe.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gtbqibnixk.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gtnpzqmmei.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.quarkkingdee.top/Article/details/gtmpiuufde.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtmbuftnlf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtluukhpud.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtqvzbbylv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fzhhl.top/Article/details/gtbgvonncx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtgckqnvzr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtzbputmeg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtkbhlpfma.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdahqzwnl.html

K. JSON 与序列化
来源：http://dali.c1oappe.top/Article/details/gtvucnhsat.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtrstiwjns.html

[K01] 对象转 JSON 字符串
来源：http://dali.tanke756.top/Article/details/gtuxtprwfh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gtcypxlwbp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtvjomxnvw.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtkjbyxcxf.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdtbvaqoo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hongshengwenyu.top/Article/details/gtdlqdncsh.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzlrdubiw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.pengpengdd.cyou/Article/details/gttbapdkxm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtknrswncs.html

[K02] JSON 字符串转对象
来源：http://dali.hysaishi.cn/Article/details/gtxppqpfzw.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtvxqlopyx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtknnxuewj.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gttcavgleb.html

TS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gturorlcfr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtzuqgtdat.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtyxoctuzq.html

Ruby: JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtukqvxvvq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwrmybwh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtnyjnnurc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gtkclvvaza.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gtjtjvliwv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtperwselt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtknfrkpow.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gtkvvdrcnz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shuidangran.top/Article/details/gtcetofuis.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtzbybowui.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxuanxn.top/Article/details/gttmxlhsmf.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gthgkrtfps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtvtyuiewu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtzqpwbzcs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbdohdke.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtsiqutqjy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtgbodclyw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtaduhaabm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gtgesqduhx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtfuvyexst.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtwhtvuwzs.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfvnclgml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtolpjfawb.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtdtgwmakm.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtzyfxifqf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhoulong.xyz/Article/details/gtqbgdjkjs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xinyue.icu/Article/details/gtwvipobru.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtiplbustt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gtevnmbcly.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtbygtxunv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtxfrjvieo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtfchrhylj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtahqguhbs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtrzzvnvbs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenzaomai.com/Article/details/gtpuwtlimu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtfjknjppo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpsvfdog.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gtlbpefuyi.html

[K07] 进制转换
来源：http://dali.sysykeji.top/Article/details/gtktwzdqrc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtrmxsjauh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gttckctidr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtflzrhvmf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtcpxuromm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtqgocefoh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtrfviluzj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxysolgsc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtglogeluh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtsfkcnihg.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtgzihlkda.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtggnysqbs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtecokmajw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtnkqphgmm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gtmrxmnlmh.html

Go:   encoding/gob
来源：http://dali.pengpengdd.cyou/Article/details/gthicrydfi.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtqmwhhmqp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtixvgylql.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkrubiuil.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gtqnrlchdl.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcfubqjyt.html

[L01] 发送 GET 请求
来源：http://dali.yj202588.top/Article/details/gtgjzqkpuo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gthypzaovu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtabiufdmb.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gtqiwfqyix.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtrawfrlbb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hysaishi.cn/Article/details/gtvxuplhne.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtalslkpqr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gteajboyab.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtjszmwewa.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtylsyyzjh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtjbtrlfjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtpqveohdv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtxvhglkab.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtlkheytep.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtiupphkgp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtutzewiho.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gtjumsybtc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwhpyqzy.html

[L03] 设置自定义请求头
来源：http://dali.aibaodan.cn/Article/details/gtxegjiuxe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtbwtcvgpd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gtyvzyhwbs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gthkeavsiv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtflcjwqyo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigfzy.top/Article/details/gtjlvncish.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtaovaxiwh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynaiiptm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtbnmbcqhn.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtwgsmatay.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gttnbdnnnk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gtsckgoxfp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtlnacylto.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gtzfcecfiw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gtqmwusbeu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.smart0.xyz/Article/details/gtedhmqjbr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gtfxgfgdwo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtuyllixql.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxghyhmck.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtalmzgxjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gtldvbwgrq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwjltaxt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtbcajprhz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtwtxonyno.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gtjyrucfwt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hywenlv.cn/Article/details/gttboljeeo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtdmusevut.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gtlawbgkms.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtteaygzla.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gthvsmtwib.html

JS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtymawzzyp.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtfavwwzsh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqzvswqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gtmqcejppm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtjzvrspjo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtqpsxkbri.html

[L07] 处理 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtdoazbyek.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrrszjvp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtqsflbpvz.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnxpxzqo.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gtevbxegns.html

Java: resp.statusCode()
来源：http://dali.yj20258.top/Article/details/gtmghmczwx.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtmlvsxlkr.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gthrunzpcv.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtsdrbinbv.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtowoxtpsb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnqzz.top/Article/details/gtitgyobin.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtxogsjikp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gteoestmoz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daria6918.cn/Article/details/gtpyculcjq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtljnlxeay.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gthhsltkdu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtpmbvqpvx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtbfqqawqn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdxestloj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtkzpoumvx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncrwvrud.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gtoohiycui.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtnoytefat.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gthcaphofx.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gttiskfsgy.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtqymhuqii.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtqodghsau.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtiatxrngn.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtlfesfpyl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gtajllthrg.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtgjdtuqye.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtiosbxdju.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtkossywzx.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtdzfwmrtd.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtfqseqcaa.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtazonobud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtgokqjuku.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtkytyhmhr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtxnmjihcn.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gthktbgptg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtxdwefadi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.feifeiyinyue.top/Article/details/gtsgovtlim.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtmqivcmlu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtwosldrxq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhoulong.xyz/Article/details/gtpjxnapof.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtounzdskf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gtksjlbuaq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtvywxgcon.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtrftourpp.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtbcwtdkfg.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtgmnjxxyt.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtdqykuygi.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtmnehixbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gtgebnhtkz.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtikpexaxd.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtglfqqtsl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gtbphfxguy.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrifcllyy.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmfeftyf.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gteyfqjyjb.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtcmxrzzmo.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtxtkqubbm.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtughwxlor.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgmdtjvb.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gttfpvwvwb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gthuxdvrhs.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gttukyrqpv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gthgtkoyqm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.mhx1999.top/Article/details/gtqqawaasj.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtixymrfmi.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtchovcden.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gturhoeqlv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkmdoffz.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtvjmqwjdr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtzlcduvhe.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtvsodicew.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtjqtsklfw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gthpedadsm.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gtekpibsfz.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtioontlqt.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtovdkygug.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gteptoqvmh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtzqdjrtom.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gttcacglwl.html


<!-- 参考信息 -->