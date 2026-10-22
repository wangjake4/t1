代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2oijapnzt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2scvgtruj.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdedpnry.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2whtgolof.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2sldqewfb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmaxhhv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2umuknizb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpoqgoc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2owvllubo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwubzou.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlmylrq.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2boafbkiv.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkvljqx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexiodo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2amohrwcr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdplqka.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmakugx.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzrvlfg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2abxvwsvr.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2gqchtzjc.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfgsgen.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dswaklrf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2glsveprz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2geeajbhv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2flcsxzoq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczkgotz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozruiopa.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvjqfbp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsrvees.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqugywn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwxhhrv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhupapkd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbwfqei.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2edwonobr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpbudmx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdgbjww.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2tiltimyb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwhwmsc.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvowewu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2txymvbuw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2psewwyai.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2odomaiyf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcegisot.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqosmpdb.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2amladicx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhlxbss.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyauqlz.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2eixnulla.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sruafmzl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2mradclnh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfyrdgm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgigxqsz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrgothw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2qodvzoxt.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2qboahrlx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqeeqjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjolmpix.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2anqtwowb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebazrinn.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgngrng.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqanvmpq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqxsdsl.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxxmtjc.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgljjoy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgrrnpu.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhtjqkh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2igiqacls.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2egnwdhpu.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wravsnlq.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaddmhub.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyrpwes.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdkldh.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfycvvqd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2etmlwllf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxaerif.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmxavmm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeahqsz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2olfztdcx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnozqeu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bektvkqc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeazccui.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoevkjhw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2khfmfyro.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtyxqts.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglzcxbp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zksqwpfw.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnexmsn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnfguqn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2djdymgem.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqifloz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmdjlc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hanlubft.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqkhfem.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmekwesq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2serjwxmt.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lfybnguy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbnbzwb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwclglk.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvjkffh.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsjvjms.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2xksdqtus.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dggnwyeo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwqptsk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2jedrrzox.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbwfgxr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtgunae.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2makzgqmr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsudngu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2frzmojpq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zfysrpjm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqitwcre.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqizcce.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlrxcnj.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wawykthz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2extneeph.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbpywdz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aotulycc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2udarqfev.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2btzzhtbu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjooqxyg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpvjjeg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujujhphe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsltqiu.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixolznsf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsczytj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgowizc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwevbnp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkjencq.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwrkbcd.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozafokaj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aqamlepp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgjemyb.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kgotzncv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imlkyugj.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2izaowbxg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2vgukgaws.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfejiyy.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyqfpru.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvizuoqa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2viekuvtz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjldqeg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcbbsqk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vophzwlc.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wtugeflf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2utxzdhmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixgwcp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmorlzt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hsterfoo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlglpoeq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwyccak.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxhbeyc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2taykwnvi.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2wbosldsg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2yiefwdfm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgfdgco.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuarqxc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2snifaogk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjszgqaz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wenrvyjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2zitoarbu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bijnkcum.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2acndptjj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2evgyupgi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfyhlvr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlgztrb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwqymyf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdmlzuw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlutzncm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgrboeq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cldnojqr.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2iykqceuh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxpvnsp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbdswar.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2goavoteo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2skqhnzmc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2pxayzmpn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2libgztwr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvcfynp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2erjzpnml.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qoplaiem.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdasir.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2libnpekh.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2gegmshhq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgokngft.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2brhkuqnq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuzklei.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrfllkb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzienpsg.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2modddhsc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhuvsev.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmwnhyh.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdntkhu.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyblofx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxquwket.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2anqostcn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ndthackt.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2meshkinl.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnmfgho.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2xvctrvet.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxjmddt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wizrzfjw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmjlmtn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2izzzwhcc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzgaife.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fktkuayj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2chdtjlag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slyulnwq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcncutq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tcntaoyy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdqjxed.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2smxuhfvd.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcsfkbp.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbagksz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dipsvkjj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfzksry.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqxcgt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bqldsijr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqxplik.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sayhtfxu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2croqalvv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxgbzqs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2yhifigfi.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwctvfv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2izpumtws.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmccpezb.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwwqwb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2prrzcdyr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ftunhmuc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmsoyfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmupccoe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvihrpmw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2olnazuhs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2guqqkafb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2smqokcnz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2oslgtufb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gniugipj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mefldgxr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjpgqhh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdwgwpg.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrnsqiq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gldjynkm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlitgsrc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzhqakg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2akvycdvx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqummbp.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2glzcepoe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sinlieul.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bltyykhc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2swnatrvx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbarnoz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxthfahf.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwkrhot.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yotrqyzz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqsbfyi.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqcxasn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2metjaepj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsgrylb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhrwbvs.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbkqbvo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rblwjyvs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvdfdvm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeylgjgc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2parflsgd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hykgfegx.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvtmjpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxvjlwy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2aegqojpt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcvbwdu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeogzlm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cekdliqz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsobvpy.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fakvzgjj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhbjbpm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgpbxqk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2otjkrlbj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpfeqrx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uldrlcej.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnythblf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvteahj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2oztsfiyv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzvzkqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilothgnr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wavmvefs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onnwdkmk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkutjzf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqaiyhma.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dweqcyhg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgcrxly.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyihvcy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aazwdzcr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltipxlyx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2raigoitz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyaqyqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2loymzglc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqndpeqt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxqfxvk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2orkbaxam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbajfac.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2npmjlmap.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyleivmy.html


<!-- 参考信息 -->