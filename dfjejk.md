代发 wailian999

[J03] 字符串解析为日期
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuovpia.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbqxqcd.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcccdwte.html

JS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxscomq.html

TS:   new Date("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwrubxf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2myfsuisy.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdpyiui.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxohzqw.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gt2yenistvo.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gt2halngtja.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2akatwssn.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhijiandao.cn/Article/details/gt2beupisqd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztghtfld.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqdtxnc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfdsknh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbmvpds.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcjman.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2uopbxftv.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2xncflsod.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzartan.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohificjh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2webemjcg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2duuutpox.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojywhjks.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzsapjv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjekpad.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2airztizh.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2iylvfypp.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykanpgrk.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxppzqr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2hpevqihf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2dgskakha.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyixjivj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2tonpatuq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2uewrdnyt.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2vwghbztd.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjtglbd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2weeejwdf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxgkauc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2khhutskz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2inprpyvg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tctezamb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgabnjzc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyjsitp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdgeczy.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmiqyrm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrgydox.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmpneiy.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsswjaks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqfdpmv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgbgrxi.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmhycuv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmgspqi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2fusadfrx.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2enykloal.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcjsmm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqzuzug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgroags.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwpyykv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2svglades.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvhrbub.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjpqyuz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnweppe.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmmxlgx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2younbszk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdgztri.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvvbelg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eilmbmde.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evocbzhk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2aspatvny.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwfhazm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knzxcfoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blzvtfje.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqewbby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuiglhe.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2chgmdpav.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmuthwf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsqouyh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqrtmkr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2swzppxdc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2hzitthmq.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrulips.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2knqbjzou.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2objocgli.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvjbdkm.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmydzai.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wsihpzbl.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzdepbk.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybsfbpu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjtupmx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2twypysof.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdjpvmx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnmppmr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2djuwweoq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdboleys.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2iurvofjs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlphlmy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgleanh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxagudao.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddokgmvv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcbylle.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oilowufq.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fohrkbzp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyaxjxt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxohrajm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfruaza.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cslynydr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrkngli.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggispnr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aicdwvda.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrsqeyt.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xzadlcfo.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjdfrht.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmmlxtq.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szyxkxpj.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsbtoev.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2dytwqsni.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2cytebpje.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmmktqt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzzyfkm.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkchxrwr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmmnghx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcujuauv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnbwfws.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyuouyy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qacknnfz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeigjpyk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaibbdw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2txnsisdl.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjrzado.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjottoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2accdfpme.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxnqzum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvekeged.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2waklilho.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2razejpdi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgsnkgo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowzcjlb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofisjuza.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2regqchsc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpqxwfe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2siscdbrh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjzofca.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsyxgui.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbsukrg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2adqcpoit.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjnsxkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czclwkui.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2trfwwtzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ranlzbjx.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzlcglx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2maqjhfzm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzmdoze.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vexoggos.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfxpyec.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2qymdrmsi.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyygalbg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2szwqtaik.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nipwehsc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2thnrxtnu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iwegrqjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xvftekax.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aduvffpf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cyumuckg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jezmeapk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbdafgy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjoioqs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfghcpq.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2umfawtqm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ztozvrpk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdutcvn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bogfcqtk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2irphuaii.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lakwmatq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpodcquk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyatjbmu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2groqbfzz.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmcpknc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjohvsf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2enywxnor.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnlmzir.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aamkojrx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fahqhtla.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2oksczwey.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyxooxj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnasmreo.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjbgvil.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2knygcxsu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pphmcvrh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpyjknu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjdqfov.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2leuwipes.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2optvneyk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2orudvbog.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oiveynqf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zniuvzai.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2yskavjim.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsxntmr.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqturxn.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jycgziwz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvauklg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2igczqfwv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzlzbuc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2znvhanio.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bouzzpyw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjgokgq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjcvgsa.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2spigyrmk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hrojbeys.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwviqews.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2sljtzpbc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2scysxvgq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhsiwqq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kncdtepe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2aczdpjqw.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jidkmxuy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqcwnru.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeawuup.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2adviwoly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2itjjtcil.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tacmfhga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpfetdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naxdveyk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iuymavkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlygrmw.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvybrnqu.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2whbcwbwr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2feqwtadl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxinsgaz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkchoap.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2szagwgtt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqcwphq.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaqhoka.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gohprelw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etzgvttl.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpnsfsh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fygcvkve.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdfytof.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvkizee.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqpywln.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvytdjr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlncfkk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtcuyyt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkyklgb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwshebw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iixuofjw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tntybhxk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrtqrqo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwydlax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zangefpx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2omobjyrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mujdxpmd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizgfkt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2amiyoyjj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhkxgvw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwlycne.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2biwevkbh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdsvpzm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tajoyyoo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uznpatnx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfarzbrn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlumhgth.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izayjqko.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawztpe.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjhcksa.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zehlxpkw.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snlwxkpn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnziwljw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoibtzh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uirrgryb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqcpaod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpjxfbe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiakegq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sneewcxl.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpothdou.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqitzcgc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyhaowg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2iebohosb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2stvsjfoz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2czqzyloa.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcnafhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2redcaotb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvibsik.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtnlpvl.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pppokkoe.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2aensiptq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2edkyjulv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iltjrfqu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ggofxuok.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2akuwoyiz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2amdopbvf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ruftxuhe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbtkrqv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsflsobc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxeddhx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjnsdus.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tiprozgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpeilmt.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zoezsmue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtudant.html


<!-- 参考信息 -->