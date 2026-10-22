代发 wailian999

J. 日期与时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdzeutv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blwrjygu.html

[J01] 获取当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqhppfh.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhijiandao.cn/Article/details/gt2anhchepo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncifaurk.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikocxqae.html

TS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubauiztd.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gt2buxkvhzf.html

Go:   time.Now()
来源：http://dali.zhijiandao.cn/Article/details/gt2slgfmzvc.html

Ruby: Time.now
来源：http://dali.zhijiandao.cn/Article/details/gt2pehrxkay.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmxjthm.html

[J02] 格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mamyeaan.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfaddgx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbotjzq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsorup.html

TS:   d.toISOString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbnvxgp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhijiandao.cn/Article/details/gt2youhkxbj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvawweyo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrvxvjz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiwoqcr.html

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtoruoh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkadsmii.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmcdrlj.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoemoyug.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2icasrxom.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokkegs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2znkxvedp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2auhyskrb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibahcorm.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkymwfn.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywvmvlj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2iivtdvoy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2snuasmso.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhowhytg.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoiltpg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ummdbyun.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2vediwiyn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdkttzg.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsnhszs.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmitdsa.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2sevsrmef.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlhdkgi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffmuorh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zavykveq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gacdsnib.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2lntnmome.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjrfpmz.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2jezwzecl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtbpmdb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwtxlyx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2twdevray.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrnkazs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2njdjlmfu.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2afbvvvja.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxbtrum.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrafxgc.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuzeawq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyzkxz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxrtosy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2onexnjby.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtgdayr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqckmdee.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apxufgoe.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaxohmh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2bszerqkb.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2jthoesiy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcbnnik.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2senjdzfx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2qllqxemm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuhbwhw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2esblteaz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmhgdwq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2syfrvagp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvvpxeu.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxqmunb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrbgpxw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbvekze.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkifyber.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnhdmgl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtefwqu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcwdumn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbufezx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrozihc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsjehft.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2udgorieq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2bumhgomx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohmqtli.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvufuun.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyetjvro.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaoyado.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2gctglasn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbehdrrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvconuti.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2etdbjqpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spcdnyqt.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sombqiao.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2yashgjkp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kljzxcsc.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2saiddhnk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2grrfmvpr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqtudwh.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwdeuqd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaxlqjs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdokwsxs.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mafmcxut.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2khesfwzi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhpxuip.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaecrasm.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbplfdog.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqjxsdh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaamacbq.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoygzor.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkotisl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcygnlth.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeoiiqu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lszmjgfe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzznoua.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiptjjfs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjjcyjx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvozqs.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvubktf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xctwceol.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwgfsit.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zeragabh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxalqcym.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfjjtbk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhmyrvl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttotkjum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sojxroih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bagoomin.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2undtiokf.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qbljgbdi.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoxurqh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2rgphpmsi.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqngkbra.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvzpvtc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2srkctupv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrcmssj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2snuwrzpz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhthmgk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdudfsx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkmpzvh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2utduafsd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwkmlht.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwpjyxl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxssbnb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzhlbqq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjdqdtp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmbuhav.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2edynjgan.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eylljvbm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2enaetxhd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbewwat.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwlfauu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2imeblmnm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2voxndxzg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgsbdus.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgneawct.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpamxanu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2copuldvp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ondsxbyk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bektkibc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuvhiwc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqzddzv.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsmwikb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrrbhcy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2emgzrjmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiqccpo.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2foffzvhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqehptc.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ipartmmr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2xutmgxkx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2abyaagcg.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmbxsyx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkjhrnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnxbmji.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpgkayy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbybljnh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfpqpky.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xunutott.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwddlgu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2oehnnmxc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqisanob.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2luasfjzc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkjwjs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjnasuk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdrwvih.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvzekuw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2wnugutff.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ophkvyqf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2covmuoqn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvntqwl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyackzj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbakhda.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wstpxvud.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyocbbvr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfqjeta.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrfobcj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2binewxee.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2meocvbzl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eccrojwi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkmvpbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmciucuk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kacinedr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydolriph.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2psjqpopa.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwkdrcn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbcimcs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmbuwqb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkbvfag.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpijuvv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyaerg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkigzbut.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdxvskq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkauotmd.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jflzvcbr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2srnfexwj.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkgoeua.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxufvbu.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2piwddjmb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxqornw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2oudlsuwa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhmfasd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwczmmgx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgzutls.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiofkcv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bccnknwb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhnyons.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmfvbrf.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohucotjb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsutnci.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcyepwq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2trzcswut.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hhccjomv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ivutwvbm.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfigppi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kknzmkbf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfentsp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmztipe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nldcmomd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsozqzz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2notlruqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoylmjp.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zgejtbph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjtdplm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylatgzmn.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqdqbog.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqikmui.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowdjgta.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcaaryd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsrfiiz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpehybif.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bchqpwem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbmwryt.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhozbuvm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyabbdl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeydunp.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkuylft.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgeuebj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2paagltpi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqruids.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2orxwspik.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cccbbdvc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yappngme.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgpqmul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnoeikp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaoshgi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2isppclyl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiybxtt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bizgntqz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxqrluc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2byctojqa.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhyqomc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oseexzxn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2btaxugrc.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciexypha.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sooflfvy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpfqkle.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdohwfr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ikchdntm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpubvsdi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzndudhr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjgebuw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2encsexzb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaapibdq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzefnss.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hafpapqk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcsjclx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lusqawzu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubejscmn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdskboa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcpshoj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfbyfpz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gycardmz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhjofz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2usypznrd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2skuyyisu.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhehuok.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2btgnyjkf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqhzvja.html


<!-- 参考信息 -->