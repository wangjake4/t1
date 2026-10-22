代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhijiandao.cn/Article/details/gt2xywmkwei.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbktytr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhijiandao.cn/Article/details/gt2mezpuvdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tejljotk.html

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbftjcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rohhtiae.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rehrczcc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbkpcfg.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxieeur.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmjizqn.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqqnvhh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoqbirl.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwvihnk.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2epcbwdjy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kbujnjxe.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzodsta.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2orjbyibb.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2yivuxmro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2urvqwxks.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcqirlz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgorhgg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkdbnxv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsslukpg.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzlrnaz.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjdkxel.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjspzxoy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjcxmmz.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkysbsev.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqsutyj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrnygeg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrvsyjf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgykdaw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2txihywks.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nsybtlnk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiocwfwi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynudfiqq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqebvcxo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoduxepo.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwvmjnj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmiwygg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgdfobw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbakuoct.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjlvuxj.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsvftnx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiucqelx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hospeorf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgshedp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmgdbzg.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsnbrvm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqlfjnw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzegzwq.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2rujxnnct.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2hisqoyil.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkmyqgr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2cncclowu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2vlknkbsz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqazsymg.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhruax.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxwucxs.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2ubinkmbj.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2uebuddjn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2lutlaxwb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2spupayta.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2panuwche.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2hndwfneu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sksowvug.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfuvzwk.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzefvvcc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxxrhxd.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgjrjik.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhgqfea.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyuiwtr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrzcpfw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2btefbbtz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgahgxmo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtcrhfm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzxtwrz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrcpevx.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjplhzau.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkwojha.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyvgxkz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuaqlik.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlehzpp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2qltpxvwb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpiyvig.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtpstns.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxrjezm.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmbkvlb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyxffpw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2cohrgtyz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phdmbiyg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kskruymk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfksxxm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkceqpt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2ajayqlat.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmrzqvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dapeoizq.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvbopwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gskcixgy.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vorenvsg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnzjxrb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgyvlf.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbmbxcm.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yccmptme.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2becwgnat.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsiddls.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdskhcx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhnqwux.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2usiqefqv.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkvewos.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jzblslxh.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrmxrnf.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhysqmz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2igidrmbf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnefznx.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pccnajbh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eirgosed.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkfwlum.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2hncwpsgo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2atyttmca.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxlzmjv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aftmpoqu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmvzets.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fekbiihr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2okoyexaw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rshitiee.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kozkqzkw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbdezd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfurhxy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kswkvmwh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxnbxfw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuhgvsr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dncesnzr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2etxdxmfv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzfxwtc.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfhbajl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uluqwmzf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2osfabszn.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aslvhllb.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2slfcfqhx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcahajz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqnrrfu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcileszx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ordffxup.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2edjwtyfs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2dhetsjak.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2brfvayya.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2buwaysam.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tihtsbap.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfqrero.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrdtint.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvcxup.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmcearb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftywhdbl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdurcibf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpwkojv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsdminf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdeulif.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnwxwud.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurworbt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyswkbm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiclhdov.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2veatobaj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxdyalr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpscmbuq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsmlbst.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2swxisnbi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2hedmrpek.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2adbucqng.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lunnqxgs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkcytsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaviqyn.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnvzfmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brsmikih.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gyceherr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2lkykbyre.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2rrndiwen.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycaoxyxd.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uylffszi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdsoocp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2icjijwzt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdmqgaj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvleihbq.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2idmuciyu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsptnxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2jupaasdm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjklrfe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzampwnn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lynlxbma.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzvsuyv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2xabaioml.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnpxxld.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdnghtw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdhapwj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbukiuvy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2eficwquu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebklfvrw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2roswvppb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhbzsju.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hubhdbre.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyxnmhy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnnkjyt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwogescz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlspekvb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkfcmdk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iferpmkh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wagbhqlj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2trxucnqk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzgrrea.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2olxbzzlm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkrcasw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2oupabywt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2miabodev.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yofudmwv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzufptwa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2smkredib.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jltqmqkl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgdtkgo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfbwsj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfsdsvp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxqbfld.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbcejhb.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pegazmny.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiphfqd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2egezsbhu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstdawat.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfffgjc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkogsyw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gdblxybo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgnmvfq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2raawceof.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcpndzh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2szbumolk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiflqcho.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jontlwxc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ljunkedp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvjokin.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2xromalyp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2nmaqxazg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2knbyrtph.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2terpickd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gihybgwg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfyjcl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmwxvyg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaprzdpg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifakyocx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urfvuxra.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsropyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbhbzlj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlbqhwo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2aihvymqc.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoowiny.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntyuxlf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2auocowor.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2iktxgjuu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wouszkcy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzbtiy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzemhp.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvclmmgt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wundnynh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsszsrf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnclvty.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbqrixt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmpcaeo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqamvjco.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhpqynv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfdzzwj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkfrjmh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuqqbtw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfdnvwh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxskcgba.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkcpvwp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jszeamzg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqyabow.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mkoclurk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnubsd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aahytwyd.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcxxfni.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnhoetw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gknubczx.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzlbcbf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jypyygzj.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkdmuup.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzsityb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxdwewc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxwiepr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxibpff.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plhzzsts.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsarfdjv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqynybf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npgssfxz.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzjbepj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiiokst.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtwuwcb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bkarqlwy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcbrqfk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtgjasl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtgapcd.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmkmthu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2chufvixs.html


<!-- 参考信息 -->