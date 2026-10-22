代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewschbrl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2diqpgdlj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qocodjvh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2cufytozf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchunxt.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2btdbatvm.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jozyxyjb.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2dztuikpr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpgklxr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfqrups.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2zczxwseo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjwzaoe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbnojur.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvljzvq.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjaqcaf.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2odvfycji.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtibcfp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhycwrp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcwgxst.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbriihr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbswwvqz.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2utrudtmg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiibcfv.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2fzomijlj.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjueyjb.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbfuxcp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2atbbljxt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdparfg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggxgbl.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsdjfdz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2csmakpum.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2gylrdaat.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2cbszqosc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekziegks.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqyifkt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2inyfnxxt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnczill.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrojrcw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcifbxtm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2weghxgjh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdommmt.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdgiknz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwdayct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjizqqa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfneiiak.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2htbrqisg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuobufqv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvusqwg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvkrnia.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvusnhg.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2adnkkydz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2kubmsgpf.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhtkate.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2uciiltgr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbcidga.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcumpwp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmzsfs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcaghul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2smykxpgg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2rplwnjht.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskkycnh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcxbsdd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwrerey.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzwufui.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmwyekd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwfqbee.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2qurfkxnd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprllpqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uizchpwq.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgyhqgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zoehaptc.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyqrfdf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayymadi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jidzikgq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dffrxgak.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbwqlwc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2utyvdaki.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuofcfs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlziocm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibclkcl.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlcxxxl.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shrazznv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mscmlorg.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2irlpwygu.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfksgzu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnktmyv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkeaecq.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlnmcfx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnowkdhd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcfette.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpohppq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rakiuoed.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbotgf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cspfwiur.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2paokxauy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmjfmpn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkouemq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqxartn.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgzfppw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2denxzagp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fydyfawi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qrermbfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzcabjz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqgspfj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiaragd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2whrycppx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazkaik.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2velsrvne.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjsllub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqvpzrw.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwwidhp.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbbsdrz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2shmqcefo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2uinxerbk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzgodlo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bkroktgi.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfzdqdp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2efsgspzb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwwfhvw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2inwdydyt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgujzvu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mjljvwxe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuzifhg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsixjkm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzxjiel.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyljpub.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswgqpon.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2konjozac.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskudqqp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmsgdxj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyvfvtx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2breubaxh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2palrvktq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgqcpjw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnlercv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dztagugh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvuhbjs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2dscbepda.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nsizzvev.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2zalpocxe.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyutgcv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxayunu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhfonsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqynqtjr.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aguuxgix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czqadwww.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjoqimf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzooqhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxnhbdd.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2alfrapbn.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydcgdo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpaqexd.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlsscqc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2gakfdlkt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vildfsoj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeuzgdc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqjwhq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2deakyepy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkuqfpv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuyfpub.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2scjxcjab.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqxhyyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzocqwc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qddfhthl.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2gdigojmt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhoppze.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmiftpj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnsanjf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkapjih.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2veqangef.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuoclnu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmdsvva.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgjmwlh.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgciqyc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfpjaot.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2udnpvykk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ypruwpob.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2donfoegj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrksxds.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmvbvdo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwuxwxm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgegywcz.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2zymfvtgy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqbfxlz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmezuktv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2dwustaut.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2eajoxows.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uaavijnt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqebznt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjiuhpy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haddgtib.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rstenvgs.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2urofiali.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2haachizr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsweroww.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsakoqg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2venwvyoz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuosqmf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bteewmqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lriybczl.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxualzt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoiaoeu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2uselrysc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2djqfuzvt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2roiagiqr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2qylxhztd.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyejbra.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ccndnqxl.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2batuzbnc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rneqvnpw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qeolxwhq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2cguuxbbo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bawxdyxp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhahqexm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2webusvoa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzdrrtk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yperslql.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hedjjefg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jldmaout.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tiipmzqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbojxmbm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mscepzbz.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzypfibc.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbxgiva.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtmwwff.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2klbdagwn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvztdzfa.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qguvreek.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2twcqrlyf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbxpkko.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhowfcln.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeksgjy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcfiing.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfnxip.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsumrac.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfjblhe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgppcimb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfohuosw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjyypdq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmxqozq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pterwdew.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuqgsyt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dejixfwa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnfvtzo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjatmzq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqnieod.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ilykxbcc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxobwfz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhehnye.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2miuqriqc.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgauti.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2szrnxwxe.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqrgchk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmkfzrx.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgshqsbr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ktffwdyy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmtszlq.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnutndn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrlygoj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2txhfesit.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vakahiwo.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnlbwbv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvyingt.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgpjday.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drwtndhl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiopqdf.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgaueam.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bucsxxlz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2isifuhga.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeosmoh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvsixpf.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zancwhzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcafkxt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjcptju.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2donoxfaf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjuntj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvvfrfo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaffzxs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2flrlivpp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwqbxht.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvcnrbk.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsllwpew.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2agwzsdxg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xftjubpc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimlxzl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2visntncp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmhnvrw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2jssdtsde.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdphibf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtzosjv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhmwzxm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jaurkkqr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcnptzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqbwixc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhjrsgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrkwnyu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2worulurr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdymjbto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kczuthob.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvzorpu.html


<!-- 参考信息 -->