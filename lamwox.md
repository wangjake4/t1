代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcafrah.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2fnykloch.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaymlzm.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcmmagl.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2obgxbznq.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgklrcqy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2dzacxfdb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxhhwao.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzlccyq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjqoiru.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjpocf.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2fygwpeja.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2sktfyrch.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwprtnop.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokdflrr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwinecn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaetwfl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhuupdf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyycozup.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyonhhkr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2asrxzlqi.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2izyqelgp.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2plplryis.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2shkhnvyx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2klclifrt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2fquwkjpe.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogovwthy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2odpvxecx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnpmml.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2sngflsdk.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aafympio.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokxkabu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxgqbjw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjbwmum.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzelqgta.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhlcozl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqsplqf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2iflltcat.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2goeueapv.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcoobem.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obgcpozg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhzevjn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgepcyw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggdunkm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcclphr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2gldzesww.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2vacstteh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxebktq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqrcdtq.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlyzhun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtpkeak.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsbgaei.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfvkier.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjyurlm.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sguzzigi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiztrwf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyefuiz.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nccjqpjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2joripklr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2arrussxv.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2utxdhzsw.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2taxqbjsp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pohdpynt.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2remaohvb.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xekijovn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogeuqah.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhegdjee.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdaetut.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcfppuz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2eknuvbsk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfexluby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2azdmaorn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqycutl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyrbbpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmhtzji.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrwyucn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfopcnq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dlarbncx.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmcrnlw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbiefax.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdyshgk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyechpre.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjzvjjd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkkojlh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkexvod.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tesoxwhj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2koxrmjjj.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2opuazdrz.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzndffwj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2bozoyrxa.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmkjxie.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtupasl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2stjuplda.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2qklcrimv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2brhnizlc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkajgji.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxzulsh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lgytlqhf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bznyrueq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdchshz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfhdasc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eafmslhz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uswqmhay.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyijqkok.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlviimq.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwmgguf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhwgqvw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqhgtlz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpwqtzl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiqkobk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowuxjny.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbvoph.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsoines.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhfvuan.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnbupgb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjjugqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2effdskdt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyarumv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyicraj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2unduumxe.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2idifaeza.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyzqyzp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dnazcwea.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxdneeu.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmcpunb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uljsylns.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zfehhnvk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2kjytviiv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2oarwpgdc.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxppnie.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbneiolk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwgudbk.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsynpxxk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2gikbwqst.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzfltxo.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2huogwefb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eovkicxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tiijmlvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykorxdsf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbxdtfn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2doogwoht.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrznmva.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2besdsygc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyazefk.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2acsgusqj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2zbweynxe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbmkuwi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2psfmkmtx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lounjxpn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxokbmq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhzhwvy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2joupfhdv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lquhmxnt.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxhgago.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaonyfv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2isqyrhzp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ammpjybl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpvypvp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjqqgvb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkohzlx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqzqrsm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrrmtgf.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoagzkz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2eaonkxzv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phewxwzy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrkuxvo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqfpyas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2yayeiwjx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehysvnxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxxleln.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2efaclpox.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtmisgb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdiposxf.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcvsdup.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsvzwpa.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2siuioivu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mopaetjk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2goozagur.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2diajvkdo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2adplgian.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnbacuk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptctsghx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfeuepb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2msfnqgjc.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2mozuyrfp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgsmeij.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2oarqzcfg.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxjmcrx.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2npcrxpzn.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dljhgoaw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfoufn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2scasrsfp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjiyvxp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2idrirnai.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakonou.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzierit.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yldrponc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2icixsjyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoicsbv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtxhprh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etdxvjxx.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lndjbdoe.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuckccj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcvjppa.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2psflgpjs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxibplij.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaxsgxp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsndqvl.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkqbvbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mndwglng.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2smschymf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rygdtpae.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqsrdbl.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ifljqtkm.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2trajexdg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjajcwe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nekyoqfr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hcktjlho.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrtwpjp.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtitykz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbtbhfa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwewlxa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtzupuu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcxdkjq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjargjox.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtpqcqp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxlvppq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfloynu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxpcpvv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yajknilu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2trpkqika.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2trcyiwzi.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2whspqvzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jueldamp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdedfcny.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpqska.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qftnkyds.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yltmgrff.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkfxaeh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pckufbgx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpmtoqa.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjprmpac.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2youtekzv.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fybhswrd.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2btrimifh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2abtnpgep.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmevzya.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqabuitt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2stjivtvj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2blcnhccm.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtyibhc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtosxl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmkpapk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgdjyev.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqjpfsb.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2yfymmnrj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2llmqavcc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lqscffxc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xngfvyke.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfothjr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkshxhvh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzjwqnx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2elzrvyzb.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpswwql.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaopdjb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2idpulhyc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2curactkt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvjbtvf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kycluinv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2sagrufgm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlacjfmh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbwnsoa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zktgkucn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrhzchv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2vekzrbtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdizwmow.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2udockdvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hobafjcy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucztkeu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiimviju.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkzwizb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxcvxfj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmmhcfu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqofops.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eonwdjlj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2heogmtwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tndxmeui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oktkbwrl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdewkqw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2najurntm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2oafvazmp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkctrycr.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwmuidq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsrlfud.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbhawhk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uadyjswp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrcamtd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hutxlyhu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2npvgqoaf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfxiuqw.html


<!-- 参考信息 -->