代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2fackuphh.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzpprnh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2zahoiqpz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2owaixitg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ketvimns.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsidccuc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2sskurhjc.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2arbkbujl.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmnikfi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2pavqixte.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlevdke.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxchoqpa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsbqglo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaxizrh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhbjod.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwjklzx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2zovdkbzz.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtrdqql.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2jljtiwrq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwrjujq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzvbexh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwrxzoa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbxubsw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqcmuqg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpjzvgb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqjxomh.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2giwijeai.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnriksgm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkqnowm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2zomfwxhe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzidhvyi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqfuuj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2opqkqhtm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvrxipm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2iszwztfa.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbbrmio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkxfpit.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqzuwie.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiyydwv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpfgtfd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eswglpzz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqgrwee.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgqistj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezihckzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfepzele.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2xkguuymd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umsjyfwv.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2suryzdag.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvosypcx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bspyhlvl.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsbihyq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpcsapu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlspkru.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2owloslja.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejxeij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuzjuni.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcwvhua.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfekvmws.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2olpupgwz.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fheddvvo.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkzlrcx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrfbxem.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiigbpck.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkyvdnp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlywyyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2jylemdja.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxdggld.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbkpfdo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkksayhj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgyybjg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyurper.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhzcgqh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdjozan.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmbtzal.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuxcbdr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzymfypq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnaebcn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkrwdex.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qithtvqd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bblabvyl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsifahjg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdallpfm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjsjpif.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwxoibt.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckapetdv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2oduzuxdn.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrlxksj.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhusrqb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnhfnlw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkkqhgq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgzflxv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxwqhk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2gavuoqjm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eivvmeig.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfapnbw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsxwyct.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfqvkjs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2krothdts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbkoped.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2retjyeia.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpgwold.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnrrscq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldpnjbs.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqqyjfh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemtkooh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqxujgc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgppwsa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2roqdiozg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrigzaj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbcojkk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2omnccycl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbjpjan.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sevrajvo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2agalcgnm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2crdabugq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtcadjj.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvqraib.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjeoyxe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2giuwlwdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twasgbtm.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sdptnjjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlddlulp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvingxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2sragvajf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyjtvcl.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvvemkz.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxusdte.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitavsb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikikyksy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2liztzeuk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rknulepf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhylmjy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eloksliv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mumwyuki.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fggjpgit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2masmxbgp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrkbmxq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2kabahnuv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqncemxb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfufamk.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2mlejkpsy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2uatpbdjr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2anomavgb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcftxam.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkffjy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2emvubvfs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiohrkd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjjalzg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzljfdf.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vglcvqsw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lklaqomb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2smktfwrf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaodwok.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzbwdzs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvoymrw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfsrxjv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmiivgk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvrofwa.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2owjpustf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmidnvs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmlvvgd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaqqhfl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwgprsn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyqvaaz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwcbmas.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2glncehao.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixshgfkp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmwqsmb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaimknb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjdyjld.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2htqhzbjh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwassqpk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyabgtsp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmtasbq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogblecta.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2obtzlefc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2avdlmobo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2otbnivto.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vygsjrky.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qhllkvdt.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzrhzfu.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ielqizhb.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zozeihkl.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2eefuqvhh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyphqjk.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbycefa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsqzqvh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbgjqhb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmtlapb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqqrhhg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvwkzok.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ouejovzm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowivypg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmjtbqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcydhfi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eyegxnkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pskjvsgn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbzpuse.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtejxqo.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkbtieo.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrmsjrj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsvvfuw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyltyyz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrcekjr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzmsvhd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2iktvrnge.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ynblpzjq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsxmvgd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrworsaa.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqbhmqu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdqzcyj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsgjvye.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2arqczyxq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoamltx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmyyekc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgiiuku.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2erstdqmd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxapsxyy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaghoaa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyextjc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnksqdi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjmsyfj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2dudzuyze.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwgjclf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzroqpve.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqluxhw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2osvbpotl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tanpfjux.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmiygij.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2buufysmb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sapjkvyh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fldzagdv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcbxai.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2djtqzmiy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sowvqrjg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvawsrnb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nohvtiaj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijoinza.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwxjrl.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynatudsi.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2atstszsz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2uisgkqkd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2orsjzdol.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrsmrlc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2frlwspcy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbpyona.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2intedxcz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qduvirlz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2soquqynk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsbpjgs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpckfzo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnvqvpq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yekwgojd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpchujs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnqxam.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lnolexsm.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbybpsp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2odityuqn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhpmgyg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyspbbfr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vfofjnwy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sflcsdtm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyagysy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xptncjec.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zynxhbej.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsnsfix.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzmtygm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqouzwy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2okoegufu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csatzqqk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdoloxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ciflmnsb.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkzrfs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbucjgm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpqwdfy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhbsyuf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvmtkti.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbgskpo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlodlvqk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2bimfdzsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2enxtblro.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2enndskva.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvunuem.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxkgaza.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztpwmek.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rivkfzbd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlamzui.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxibctkg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbaqlak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ambzgrim.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2soypfoyw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vynggynh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2rblebnwm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2byuupvnm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2itaoglgb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpwngne.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdcnjds.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfpyojm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ibckuboi.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxidjetr.html


<!-- 参考信息 -->