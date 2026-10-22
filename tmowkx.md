代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zycfv.cn/Article/details/gtbrnbbanb.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.sufxvd.cn/Article/details/gtspvuxuih.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hammf.cn/Article/details/gtuytbfegm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwluaqmme.html

J. 日期与时间
来源：http://dali.xuanzx.com/Article/details/gtdewvnezu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxckjxyji.html

[J01] 获取当前时间
来源：http://dali.sufxvd.cn/Article/details/gtkkgqknrn.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cheryme.top/Article/details/gtfjjpiyfr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgfzy.top/Article/details/gtfqmobhib.html

JS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gtjcphgnvf.html

TS:   new Date();  Date.now()
来源：http://dali.sysykeji.top/Article/details/gtwbiwbcaj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtyvzewxqd.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtvfkukzqt.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gteynrhnoq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtrohflkgd.html

[J02] 格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtnoexxjge.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxuanxn.top/Article/details/gtsyvuugig.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtrlknkfqk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ivvv.top/Article/details/gtjlzkmsxb.html

TS:   d.toISOString()
来源：http://dali.jqgufenzy.top/Article/details/gtiwnnegpd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sufxvd.cn/Article/details/gtriegyzme.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtslgkuzxp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xuanzx.com/Article/details/gtbyumpxqu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jianghu66.top/Article/details/gtzwpsrser.html

[J03] 字符串解析为日期
来源：http://dali.cheryme.top/Article/details/gtzqkulkpq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmingpwlv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtvoymnnvm.html

JS:   new Date("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtvssimqnl.html

TS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gttkqqdlbt.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtevajnkdv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtqavfnczu.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtmxfqkxuv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.9152youxi.cn/Article/details/gtjooktuim.html

[J04] 时间戳与日期互转
来源：http://dali.ivvv.top/Article/details/gtynqvrhed.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hfpthk.cn/Article/details/gtxkmsqikq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sysykeji.top/Article/details/gtvqvifljt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtxohkzitq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtauohmbcx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sweek.top/Article/details/gtfimlolhx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xziqi.cn/Article/details/gtytoqwnhr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sweek.top/Article/details/gtxttblurh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.dianchejie.cn/Article/details/gtgjizjace.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gtpcmzhytn.html

Py:   now + timedelta(days=7)
来源：http://dali.xylfe.cn/Article/details/gtikpmjsch.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jlsjyb.cn/Article/details/gtprzecnjg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtborutjnh.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtotsoejar.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yvedp.cn/Article/details/gtrkzmdinv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjoglavf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gtpdwaulxd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtzghyhwoq.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsfqmmqo.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gtypqbubqy.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtruznmlkt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gtgccapuvf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.9152youxi.cn/Article/details/gtnlkjtzat.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ivvv.top/Article/details/gtrpxskcsb.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtjhdlcmfa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gtccuvefti.html

C#:   (end - start).TotalSeconds
来源：http://dali.0kj1m.cn/Article/details/gtoecygjtg.html

[J07] 比较两个日期
来源：http://dali.shanyushiyangtech.top/Article/details/gtewrihvfy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtlhruyfgx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shzxlz.cn/Article/details/gtnhudbctj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gtrdvquoti.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtbvrrkgro.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlxionhhs.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtpvfgfnrb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtvjtjzrrx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtvrsdwjrd.html

[J08] 提取年月日与星期
来源：http://dali.yueranfly.top/Article/details/gtfrulniuj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtnhwqjbbh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.0kj1m.cn/Article/details/gtzlqwumzl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gtkrakuret.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xylfe.cn/Article/details/gtxywxetxg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hywenlv.cn/Article/details/gtdhzmljnl.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtbsxcmohk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nanxinkj.top/Article/details/gttjwwxbbw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gtauxiyfvg.html

[J09] 时区处理
来源：http://dali.wangdashe.top/Article/details/gtqisnnxaa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqzrrgim.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.316326.xyz/Article/details/gtgzozcfej.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtaalcvfzj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtvjdavonz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gttotyrjwt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gtzfognjvs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtcvbygbjq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybyrvwfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtxjuekyuu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.pycfn.com/Article/details/gtewbgeljc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shuidangran.top/Article/details/gtscposriw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtuiayvtaf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hammf.cn/Article/details/gtudmxxims.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtuwwhffuu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtldnqfjij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtvwiglucj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jyoumei.cn/Article/details/gtozbbuube.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjvpnylbl.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gthbdzwrxy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthhacsrkf.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtlpndlnfy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtssgdjgpg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gtucducigs.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvzvvclbn.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtamsywowd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtaresmweg.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtmtbslzqo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cashguo.top/Article/details/gtyhbuhaiy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqiomoayo.html

[K02] JSON 字符串转对象
来源：http://dali.xziqi.cn/Article/details/gtxnsdbbtk.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gtkdqgfdtj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtztktuaie.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtrnfwwdvv.html

TS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtxllgzhly.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtslfkwdor.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtubsqvznc.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gttwwugnqm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzluqxnop.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgyezege.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtkypjvobc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtzdkomsrt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtqhsnrbkb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gtkphyljll.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj202588.top/Article/details/gtbmonfuhd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gtnwcoeyik.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtizhpceyh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtnzvgxpuw.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfbrxbpow.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtylhscxfo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtjgbwjezm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gteowjccmb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtkdwazmce.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtlbgyiukz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gtkqrcvdqg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtjyyqcymw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gtzkgbmqfg.html

[K05] 深拷贝对象
来源：http://dali.hnxiangtu.top/Article/details/gtzxissegk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtfnqpnrff.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sxryk.cn/Article/details/gtnakedbvm.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtuwniqqys.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtvkdnaiov.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gtlnddphkk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gtjmjxmctf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gtglsvtggt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtdxdethfn.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtplbyymla.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbwcjcse.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtjkygaeay.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtnijhkbsp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtfpypajik.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gtuvcluybw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtppoepbjc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gttwgbndsg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtnglpasql.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdnhqwfn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmqwetmi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtgurkimsf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuwgiryh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtbnmehzrp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtypvrmqlr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gttnijwydi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtjssezefj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtjlvkdlud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtourlpgkg.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gthrvdogzv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtpdryqvju.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gtxgscauzp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtirttxnts.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtfhkhhaga.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtftwcvtcg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtojxthjiy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtlzrcaxah.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtefurxjos.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gttjjbzyop.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtezwmhpxt.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtxtkdckqj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gthogdhrim.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gogol.net.cn/Article/details/gtdnmdkjaq.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtrmkizifb.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gticmlusdg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gtjlchlmsw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtmklaghps.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gtxvqablqj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtcghmdgct.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtcrmxgawk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gttupumspq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yuxming.cn/Article/details/gtootlnqgg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtlhynrgko.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtsowrqiyc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtpnnjuchn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.quarkkingdee.top/Article/details/gtmjzhvtsv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtslisrmfr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gtzguuxtan.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gthtkqvwud.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtjyhekbbp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ybcxt.top/Article/details/gtqgfmsbtp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtumlxbcqj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.0kj1m.cn/Article/details/gtqqijysco.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gtrailgjlk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtqfytaies.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sweek.top/Article/details/gtppwdkwwm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtsdgaobcd.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtsgsmjvik.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtsvzmgpqg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gthzucbxef.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtkktbdnwf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtgpeynihi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gthagjujej.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtzpmrkfls.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ivvv.top/Article/details/gthfzedpug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtzaslgptq.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtjxdwgxxg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtbximjxcw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtcfzwstvi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gtqfbnbwpu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtiwqhjflz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gtcxnmbics.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgrbqurn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gteidevmtk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtohxrcamp.html

[L06] 解析响应为 JSON
来源：http://dali.zycfv.cn/Article/details/gtcxrbruwp.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtfznwsfyh.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gthbtmpsqg.html

JS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gtonavtkpz.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtndolmrvg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gttknnurpz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gtykglvcsj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gthpkavaho.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtrunjtqfs.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtpmclqmmt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtrzqvqskz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gtpzwevkhx.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtoslqzrtf.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtatfjlidd.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtcmumwlki.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtddozdlwr.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtvrsshbii.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtcsvaqhyj.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtbkugnvfd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtvifvbvds.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gticrsbunh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtekzzgouq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gttjzuhlmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtqroatwrv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtsvmpbplq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtilqarytd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtjnasnmlf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gthsmayqhz.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gtshpcurbj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthtvqtmxe.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtwffdejvv.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtrmmmcoqk.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtiyfjjcdx.html

JS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtwnjbevcn.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gthrbfmhla.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtwnwymril.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtdrnvbvaw.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gtinhpzvon.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtkueemvei.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtvvmbbgrg.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtzphpiggw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtxrciejhg.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtbmmmhrxe.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtfvtfltrf.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtiaahpdwt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gtnbbcnpxf.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gtenbxibqb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtymepdmgf.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtruvwyura.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtgdpezvos.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtulnsxlmq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtadpzlfnq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtfurrnrct.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gtfnvauxen.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jyoumei.cn/Article/details/gtddatvlaq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gaohongyu789.top/Article/details/gtbtrmnodh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtbfuazcoe.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtixpaofpi.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gthlpqnamn.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtcejvtaak.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtglixiyfq.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtpbkfysfd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gtkjempoqr.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtelacmzzc.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtuuluotkf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtedgvmzui.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtbcftcdqx.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gttflndbbv.html

PHP:  exit(1);
来源：http://dali.dashuyun.cn/Article/details/gtfslrlqwu.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtlnlvtvvf.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtaexoufmp.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlatisgz.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtibgrsljo.html

Ruby: exit 1
来源：http://dali.jlsjyb.cn/Article/details/gtzyjxtpan.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtdgcdwsby.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtgmlalfvt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtcdxnlqbd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtubwxunkx.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtwzezluvq.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtgxmepmwj.html

Java: System.err.println("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtcrcjyzsx.html


<!-- 参考信息 -->