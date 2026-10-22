代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzoxft.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyxierq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmghkles.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtxgade.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2owayxlqc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrumszy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2xktfibcc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2mfncxxiu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2amncqerc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqorfww.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmewjxdp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2leqiwlgd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2osqchuqa.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsepslcu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2fytzruwy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgtbvgv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmvmawm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvsfghb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvdmqlr.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2zooauonb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkucrltj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2biubypgw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecifnptb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aquhpqsn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvibcbnj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhcjbjh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2trukjjyi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrugyjms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2falyjykh.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajelkqfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eykmhpof.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvryixu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacniqrf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlkeyzq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2chahxclz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rndndlsn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbckztv.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hresuxqd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjlrrbp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgdftgb.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hskynpmx.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yottpgan.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmceoidn.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnussfgn.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvsrrfc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnovyqia.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsijxbqg.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eczxeujv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixovqfm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2eajmuxdu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmdeace.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2axvyzjne.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iglkxpss.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqwhtkw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnrbtek.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xynbonhn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjyxnwi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzymgkly.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpwvcmg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyqzlhj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjerkvoo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbkdaao.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zveuxdzw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgthrdjw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkblpyk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjcakbh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2blmzalzv.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aifewwrk.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vywovquw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2esxnvkqy.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcmsubj.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwxlbfi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbhruyr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpklayxs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpczpdr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqbrlt.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmydcsxw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcqidtt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbxjpyv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhlcsh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjcaees.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hotftycq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckacuhxx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdtngcy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjplvssc.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btehcnya.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmhmjox.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwktciis.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2udsnheed.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntflguyi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcprqlsd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2juiisubu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaftkkd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mziuledb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmgewan.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwgstkh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgetzcx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cobbedyw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2znlyqkbj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcglxwb.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqigfbs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2amhaqrxw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtoxoky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqktkgt.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yobkgfpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwbyksa.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxgsilc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2slmqopij.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgkwlte.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfqeqhz.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyycmwjf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xwykkaju.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofprsob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekokdxld.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2coduyvze.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2objugigk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2olorjpuk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2bydujhbt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2byvidari.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mefrcdzi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2okuancgz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrlqwws.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2spbavsay.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqitvwbr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2besavzoz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlmhhjt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sypwjbtx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfulrtfo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbngolt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwzyrsd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bilgyvhb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2utwmrcxp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdibjcj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2gncpxzkh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gckyeowt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tygbpcbe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zzndxprd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwcough.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2sflpalek.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2waquikzt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwwtxlz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fayhvbpi.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuuffxr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgezihk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlfsitu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjajgjf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wsczewzz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2oeczkoko.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpksiqpn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjixsyl.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tefffaan.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xapeiliw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdsuaca.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxntdyh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkassdgb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuemfnj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jajfltly.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdlckwd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2roudzwga.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2typdlgys.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqilnyo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyvcdfv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsiyfpc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyziogf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tvguectb.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkgcdqt.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vvluqgbf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2koltldkj.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2epgdkvob.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2kfywqvno.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2girkdjxn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtzunhw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwigppf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsmmsrc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfgsvpp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2uihrumxi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnuydzb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iztabesa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbtuvke.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnwimye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmyovlz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoyqsau.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rerjhxre.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvuysbf.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubmfghn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hibkpyxr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgtxzqw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbsptvb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxtowlc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtjdsu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzhwvwk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpkwcxs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpqjcfg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2brpgaucv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hllxxchf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxlnzqh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhimzobp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfcewsi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjskwexs.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrlaicn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjjskvg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiycwvrw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxslqfco.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsxsxbe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnorcgyo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpquirv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzgfxh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeapmxa.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtqeeut.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyixizv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2nevmscss.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mewoirgg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rztuffyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2crqdcsro.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2plxfpeee.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2grlrhlnz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhalqqi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2uilxjbxp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aibshhbp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2odycwsum.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtizpyn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vclhrlst.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpgvrxj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnyqcqg.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2etjeaxyu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgwujaj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nddozqfd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ageqkeng.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2egrnymdt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuuntql.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbzeslc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuvxncy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcupnfd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2oowhfpts.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrmgzkn.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2websnnko.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzgabjw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwqvduo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjotoqw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tozfdjwg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmybbtq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbrrvmu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2makpeibi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2maoqkcra.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbkvswb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2moyfouoz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2peoojgdk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlhcnvf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cajgavvh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhigwzv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgtgmgv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdlxcog.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gywncarr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cheuvqcq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgsrels.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjhmpal.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aquinbst.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dydbkups.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnddiaw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkqeote.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhhpthg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxreraa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2peanyfpn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2esrjoyuj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfcjurd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcotcsaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrczwina.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdlvyvk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lztiuijo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwixamy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtkaoaq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2svatavba.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pipqvezd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrogzlp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqepjplk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfsdjmv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcuhifu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2omhyybmn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2muqlbtnb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pzteyrca.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvndqix.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqnhimr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hujtgqli.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2yktkaqcq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljyggtp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysquwgso.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixemjwwm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jucdvbel.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhplmos.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozjmyxm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvjmhso.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfzsbtv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2faqybkco.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtimoy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstjrvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edweyhxa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhntsul.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2efdowirl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaggxiz.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eouwvrwt.html


<!-- 参考信息 -->