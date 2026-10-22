代发 wailian999

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2tftswdzw.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2nberbtyo.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2elmbdurf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokzdxu.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzpxgf.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2neyqmvpo.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2knkxuajy.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2slzkjxqj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjftjjxc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgeyizc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbynydll.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2plaeadae.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2qujqbuzf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuelixf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxehgyqo.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnqxebu.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdsuczi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwdxwkf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbknyrv.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2psvzljau.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjgijhe.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbjthgl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtydbanh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2luksavog.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmugtfa.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvsawlg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgrefc.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhhcwu.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtwipvp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfibyyj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzsiqhx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvszezdc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfmisxk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2joxsfbkh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2htabvaqh.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2olafdqic.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxcuspf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjrxwug.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmaubem.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnfpts.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2enfxbcjo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2ixedaicn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ongrdxcr.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2dndvjchv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdekkask.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2epmyejkk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2rohjxtcy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2roswgrok.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibopjpqk.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2klncirsa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuvpdfi.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxgiqid.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkznanz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2chlahwpo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2guyuvrzr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2zffxmsea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxphlqkj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irafvwgt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrtllng.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjoscrs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2trnjlhuf.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbjwyz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqtcoyu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsmovhs.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjymfnj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjouhjt.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwgdeko.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgytoxe.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjvmmmv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvahue.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lumnonvm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuwlixq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsbimex.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwwlkm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeclyzgb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxfnybl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvkzgfy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcwttkh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2zszhlbnk.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2cauylrts.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdnmoxl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2fslfyutl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwqshhr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gewwajyi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mndfhkmk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2niiatvvs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoaatdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziekiziq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoairczi.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjbwhaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axtxbfau.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iibpyscm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2axruqwox.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2aygcrwxq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2klptkqaf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpizyiyw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzmjtwv.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtsvhny.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwcapyh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hydftcut.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmzqtys.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exoowrbi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrvboqm.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyspntl.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmqhpnw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsytzpol.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2epnoiyvd.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oozwkrte.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2movqeukh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2achnvwko.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmokhuc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2onnahtib.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyvxwvn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlodksjq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmnuvjh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeluopab.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yznvclny.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pojatevn.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaejyjj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkesrgh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbvxxgy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdntev.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqkmlre.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrxujoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukewltfp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxilbqh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzuxsmv.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffcbte.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtupgvsg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2kabmtknq.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbenthl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcxdegr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2uboqtiho.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ninpopop.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2htcridzx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2avczakau.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaapzcw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzuphdw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwaitlrq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2oviigbau.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2myyqqfbq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpymyrj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhxwagm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbijyule.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2chpagpxw.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gyojskmu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgvxzma.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcjhciw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuewhihc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtznypg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbbwgal.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabnaozx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyevoagg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcuwqag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpjcgdq.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2urzciycv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfhucmg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiximro.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tygrudrq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2imrddwsu.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhbicrr.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqnkwaa.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2enqwprob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acuijhzl.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmimhvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzettwoh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxdodp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2olcznzxl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpnxjjp.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkyjgrr.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkyatu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bblpgfea.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2owgwcjfi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2skdmvnwa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrpdaej.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rkykufxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kxybxxba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2azsmbpyz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2chzemtxs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzgsumr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvbyeov.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcscpuxz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ignxeisu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnahwbzd.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwgjlje.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnckqis.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqkndxb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgkuzbq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tosndtiq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtavfyf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuylvqmh.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2djrtushv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvzbmue.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2tgioceue.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvkrlzl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eseiyqkb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2codcqfih.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsjxnfo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2knaocxkn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtzbbew.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzbhgpp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gstnhotz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2rltujwqs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2krkqadeg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyserwe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2aowobbuk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjuvshs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqmgrze.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgieird.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhbldxy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsnhqtl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcjtwfx.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikthziur.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbusryv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjegfhw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2aimnebfw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdspqku.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtjyqgl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2frsmrett.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejokbhmy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpkkmpv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnblglwr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2iediroch.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhasflp.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2glzvqmtk.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2birsjaef.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vfljgbzr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoqhnff.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqmdmln.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzerrkr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxjzsjg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwrpyme.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqqukkr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlpiteg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2uwibxujo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2foddtxta.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yieatyhc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2csqeqduv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwofugw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcslvfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aavgdlqx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlstkwi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gocwksuy.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2txwcwnae.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjtxkcx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrbfnyp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lygjauvv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrklmhn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxsbyqd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfrgdap.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmwgvxt.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2euuubyox.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxowhskl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpfwkcw.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydvwfn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwzdqth.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdbcpnd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpnqrmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqprryud.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fcslpmfb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgofgyzt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvdcsqe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlxkfby.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgbdvkz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jozjqyer.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2krcocgho.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ittyicsn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgtmmls.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2logqkivs.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzglzfq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gothrocl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2maufnzgs.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwurzkmz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbpjqwo.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zogeczxo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dmorewnq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2niwgrwmo.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2egjtjnzv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sufmmnhw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwlexlf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdzstb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymvicxs.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatouolx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2guthyitp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbekwaa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wrptpbci.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zysgrxkm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjzixxi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pewnlohi.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdcmpap.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqzhpzm.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgziiaa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fidbdpck.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ythlujdh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jminpswm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vucvnvxj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqnjhjl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxqtwae.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2swxtqetg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkuvztg.html


<!-- 参考信息 -->