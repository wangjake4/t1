代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkfxrxv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnwtfcq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2wspewbri.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqufkkm.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2suribduv.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2maxboofj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2lljekhpt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvrhyce.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2qicnoeuj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2klqzaouf.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwmumm.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2hizmqgmm.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2itdvkfnb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuxrqms.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbtuynd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzbdrqr.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbzoiwu.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbuxiyx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvsvxzq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqirrvpn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2kebfsxjq.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbriabd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdrvydk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfuvnao.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2olfyassy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2xugfdwyl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlhhduv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtwwnbq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2txjfklke.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2sptmyxmd.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fepwjmxl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiumybh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjamybqd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2alrzopvz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhifxex.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpypxxbx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoapflv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtdeofv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkkskwc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2avdngnjw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhhxjy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvzoqnk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcjtzhg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2iknpqufd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjngkypq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvndmra.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpxkzpw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqophpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvcwaox.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2gusykdnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbkkaxt.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2laxpvckr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfezuerf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zahicohd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmwtkeq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvdebbc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpqymam.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcjmfqo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxnygqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoeurim.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpyyjro.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2notogwqq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2poxjvppl.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2relmgcty.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybetmmvo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2haugyhte.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvkedve.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtxsyve.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wemohmci.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgnbfug.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukttrole.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwnnhag.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vagxiwxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrdpgge.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgzkde.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjhlpqu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbtydzn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfzjsem.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2simxfbma.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqjpyoi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgzpbwy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpdrwjc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmncawte.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuqmvsu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2chamdbbe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrdorhp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2blwrvisv.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xgokfsli.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsbwupi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdugstm.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtzowfu.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtypvyvl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhhbadm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2idktlxmu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqwnpgw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtmyecm.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpradbr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyvfhgc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flxykxrl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gopczund.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrusorl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tmojwuaj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qszkdwzz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqupkyml.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2twkgohfy.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlpmvyi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxkccxv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2bijqxdfz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchtrqzb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnrjfsm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysskhhpm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2txmimhup.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafzwdga.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbprkhrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2usanjypg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpowttmk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wufbcaok.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2crtawtrl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuygqim.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2egkqsddb.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2enzuemxt.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rulzcbqu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cehadomi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuzzccj.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ceinwezy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orxkzbyt.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbjdvzg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2thjryfsu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2swddacdi.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2evglwvmo.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyysbdjf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwlncro.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtysjth.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhcstak.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qljckmti.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwgsfyp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhmfods.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2wuavvpns.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fonapouj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kumrdhhm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbeebjb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2myasjzly.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dceqredn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hejputtw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2rugfoess.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2giqoawbq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahybqzmv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ormqcpbx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwjiwzs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhymnsl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jliqiupp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2zabywlsk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnlemzq.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoocvdb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgacapkc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsqubuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bndwxuzf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhzqujg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmsbbbb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kborrvwa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpksugay.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvsjfay.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2eswiqrne.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyhkazm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaeuytf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2jgedksef.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xryheqdb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wjifdddt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tezwoevb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmapaof.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iossfrck.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnhrtfn.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnclvyk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzlhscw.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcabpgu.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eultpfhq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgzmlby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgigpcqu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfausah.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsvpmgr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yveclngi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2guhwvwcq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2irocxkhu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzqwzlx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpzvqlx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2umevqxex.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhvlwts.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2oztdedhs.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbkfxvl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnhdyw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnivwiq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhccnoty.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxorojn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2poimdtdi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcdmjwf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgnlxxm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydevcpjw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrifqlim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rialknpr.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdyxwlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoauewa.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozyuod.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pptjzzje.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2barqxpyh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiewywy.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvbbfvz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cahpjnzp.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2agekotcx.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2omjtmsub.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqcvrkf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqubgsk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hquarapu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrlopga.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ryycatdt.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lyycxnmw.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxwdqjk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tymekrfs.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpivyjm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrffpte.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzpzgih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cypmfyqw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2klvjdjay.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2moyrbonz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btsjlvzs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbwjil.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgmlhrd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2oipichga.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyrttlf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrmsevy.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xateycco.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2igkruenn.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdoerzq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dizhdvwn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2adavijbb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewffjgei.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uednjhmu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsgcwxu.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfarhnu.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxhynic.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2trvnyasd.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxgdnit.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpnbsbu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuupwyu.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxtlrxu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbzzmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2gfngetqc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mjntaydh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvuphci.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pngbxasl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjhmanu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmyoxxo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sttcjqqx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2posiozkx.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xesnejaq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbebvsw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xmldodhw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgicnio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jyswtlia.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnhptgm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2amvjtjni.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2glkxyvac.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjapawrc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2fabarmyn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwrxfbs.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hswisrga.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgwnicc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrbhhgt.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqasrch.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjajcgm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtllalo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqywsvkh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bskmggpp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tvphtcdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuxzosm.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2luxlfevf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sobagkpo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjlhufp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqebaodi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclypqkx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2renxpclu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtwzjzr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sowitsyi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zflyxlbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxyxtxz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjoxbzz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hktpzlqo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2esqidezc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjalpnw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafenfu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqeisan.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eruposrg.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpywlads.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yhizzpbv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhgcewh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrodoyt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoxydlo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2exicalzh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbkjhpf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxovtbb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yfozflxl.html


<!-- 参考信息 -->