代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtthtsr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kppahzzn.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdguyua.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfnzunm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2bknncsnp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpayrbc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnakdmt.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvpyenm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjdmruk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2ieotisyy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxqppbu.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2ybksaaxx.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2udextftc.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcagfozi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2geydgajl.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjoahax.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgkuhaw.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvjycbt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdbxfir.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2uaggcaqi.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2cufmlrjo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixypwfsz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cllxnthx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuilovy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdgznhn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgmcrpv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkocavti.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfykbwyw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzptgrhf.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrpviqx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbdweyu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnajvdjh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgieukpy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrffrvf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmgywtq.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2sabtcbnc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvxjvcx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2cthqghpo.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkqnpw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2adjdgwci.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudphgt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqmbrwv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkrrhk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsdpbvf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkowunx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2rshivqqd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpiivzh.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2ficmapfp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpqvkak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2fycwncwv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2boscyxho.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnoaibc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2selilvpc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2chqiuwyi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrcgtuf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjaplpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuusids.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2xllfkmjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odvmtitm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2djvoyxzw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2quvidyng.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2scukxsut.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvzcdgr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2chdnlikv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2lmozfvwj.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaelbgpl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqpdppn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdiyxvi.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhgmiiv.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxpeyth.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsphacjj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdszpvl.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aptrhurw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsqyajk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tafawjvv.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaxjqva.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxvqyzi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqitcbn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbwaqms.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2epozjskv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmoklhe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdrtuan.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflwzjba.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqazecz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyqfblx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvsiyfx.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unyqactb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkyatt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlqpoab.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bogdsqug.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdtyans.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2allmwcye.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmigmf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuhbysx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwveqjaf.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2finuqgoy.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlxuhnd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaghbgz.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcekywcz.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2riytxhmc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpktvcl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlewqca.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lamugrur.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmbqqdx.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmxiaok.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfsgsfe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eywyhfss.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhpvtdo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcgroiy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sgobujtz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgpoetu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqglhtk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzhjbcx.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2poqsetub.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahaqzdy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2weztcmfi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2noxfwgsk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzcrtba.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgtcnng.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlsenoi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ontiphlv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiwsgie.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwvihcv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcdqtvk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgsnphs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2asgxdgmy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpkfuoz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2zacoiwnl.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2konzzcqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzghktb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfbwnec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgfkwng.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ezacnzmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaqyizi.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpqiqru.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2rlblzhph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2apizpbdl.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodydrpx.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2twispwys.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2aozogzbx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cexdfain.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrnikbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccywphcm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvfgefj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2oywiwphy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2filhuedc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqfliig.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2urrwiwmr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tubhcsie.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2sglqlxzg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnbdosx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiqcqnf.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwpxiai.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tuezfzkr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2udbjbzkq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkuokjp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2enaehyfl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2iknaqxdf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdtocoo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbglodyk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzopyobo.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2txvszzwg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqhihfl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukedltuo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2utbahlfx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrgwmvx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyyxnmx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpxfjci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmfhiyh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhafgrl.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwndwmrl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqwxryo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiqnyjk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zztxctin.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsvylll.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlxgobr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbfvlhl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbxhawm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioklrcex.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjivqcw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2towlxddn.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmvvict.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfokmtlw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2clyinzdv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pitbmnuw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaubmnf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxpplvc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2alfbgkth.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2boqzrlma.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2viwbylcu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2smqxllnf.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeotlvh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkrpevp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdubwqch.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zjodlaex.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ffujgurd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwaszo.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2uauifcmy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtsorpl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxszies.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzclcfab.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lknodjpz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvniqtg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfxesbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyzjuzu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwogyun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwpdval.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzcragj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otvniklc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fybmztcp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yaebbqqj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuumhkpv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npglmxhf.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsxgscs.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtquqdx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hmimyjcu.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgalhpf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2znuyibgc.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaoigij.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2owjyhioh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdasvkoj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2pyagozup.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2auaqvnrf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoswyid.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfwpqut.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2kdapprsh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtmdbrh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2catsxitq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlnndco.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdnbbuj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fszlosoz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvygwgt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2noaxczkj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbpmfbb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2htveauuz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wycxqkrn.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuszsod.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqtliq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgervue.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2inogzlsq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbvcdnj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptynvqr.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkfjvcc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrdzzav.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbdbsqx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xogptkab.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koksoesw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrhrpmg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jazpgvph.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxfgskv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwkzojk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsnafta.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyoxilu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2iptmsdoe.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgbefyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoprybvu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uanptdfl.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sticdkbz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnjxfne.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlprnjny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2scfmslrq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwdmmvr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxptgd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2garxrmwb.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhdrwaj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2deehvoph.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsjwpeo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2avcwtfnr.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnonesd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwjlnsq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnjayqc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuwovlt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bujtfasm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwqmwwn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcooslp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zakapwur.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fypjjghs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2dibycgnu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjbhdp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2irtnpqmi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpbxtil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exrukydy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaebmsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vapgmxyu.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjltmyy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oniikuak.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmfvhyc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlsnmnb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wotfqqup.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnlfsar.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbdfcwq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxkjshj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dltkvzao.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbumxxan.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnncklqi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2snrcjqwl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xolatnxv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhapgziw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2olrowuvy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbrmhu.html


<!-- 参考信息 -->