代发 wailian999

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrmczwp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gt2flirgvhl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2faiyqlqh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbkffsn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhpimyq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2wobepdzh.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtbojtr.html

Py:   now + timedelta(days=7)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpujlgrd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqxmret.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnnyctf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2udkgmohw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkntvxpt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbutyxqy.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2qgazdvob.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpintsf.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogezpy.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcadvlcf.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyghkpt.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfpfjyn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2pegyeuru.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdmqsbj.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjanxlyu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2arzemjap.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnfdric.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2nrotnkwr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2lugtiwzs.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucriscou.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceribyvy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2tujqzrmi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xowqeoxg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2utghurom.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjflcfcw.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoafcht.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2skqvuftr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgavspj.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2ausuywsv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2dosxpcsb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqlgmrv.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2nefpbalo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmbwtwz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtuyzac.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvwcilc.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxljwpq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2tylrbvnw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2obfturcr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmxrjnd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2totprxem.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2rprvyzax.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgpslje.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkztgsr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmyitly.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2pywiyyam.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wscjbcfw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtekrshr.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rccrgwxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfmwkbx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuqjypg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnxlrdc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyclhpk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sclotdsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjfphcg.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmuncop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jruyxgsk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszcjgt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlxymzd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfxsiqu.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzgqovk.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiadihz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2okggqqhi.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wddzbzse.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqipllmv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhaaazl.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vltyjqrw.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2traaidch.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqvslgp.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yujxwlpl.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwujwjvf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xouagpif.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeioaco.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvbdsn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbuzmso.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2moemfocu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2npkckkec.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfftdzlr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddayjhks.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmqwhgi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuzvkxr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyxofmd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbcltxr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpsrfkb.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbnoozo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2idzbtpfm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfntbrs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gayykebg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgicrytu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvagclls.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoobnugi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjlgctd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2puvqclbm.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgewdfq.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkxpieb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wgymjfam.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqefwpy.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpfrnxj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwyrern.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2nouzfnga.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbilgie.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqvonsj.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2klqrejjd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjwcqwh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqcfulq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tazqejjr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhibozm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjbfcff.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvivekg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpqpodd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wunzsiiw.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvlvvkl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrkackz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2auwogrmz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiigwwvo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqwgjvw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwmpob.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwacduc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfktbtpf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhirfuyz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbhicfi.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jurmlkkg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zibhzjbx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdxxac.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxxifdo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbgkbbp.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyucvaw.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixarsevc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrcjdgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzldrics.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2inqrjxdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmiryju.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpzvnes.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2gaszxjtt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2nycszfol.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zidaibrg.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcjglhg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gkibxuvy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxbinri.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2satnamkg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhliryno.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2crouneai.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2whzfxnbu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gllbgmyd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhyldzh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqkffzd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkzpgdh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2eukxcxja.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2viacfzis.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oocvtyzn.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2pefkgbqy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjfysv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oijenots.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoymhzt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpfxpzp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrsgsty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xckuqleu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2izvcetoq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbonmaa.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2uurhmjds.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunpbqpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwypqies.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2amupwxye.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvqhmam.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2buvfctzb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2naidsokg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2edooupxa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2grtlruqx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkaabje.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrnffpx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwwbwbq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sumkkkaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyycovw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwgbxnh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoofnvi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjamckk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjloaft.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwblxxy.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaghaab.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xptbfpql.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xurmhvrj.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwommqbu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvkhgll.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqapsbqa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyxkobf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hethhgfy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2frgxdwxz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcywvgan.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfubjbu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xdokorve.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2oyihxvae.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqdryu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwuploj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2hppszxuq.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzlcpq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmsmabu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2stwdbsic.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxycsljc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgnjwce.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2shsxhdda.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2stjjmezc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yofxcwga.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpkzusf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfwknmu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvgwxns.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzmzrut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjgzqqi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aetuzrwp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hajrxoop.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpujqxk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakpfbc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxfapsj.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hivrqvom.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqpypig.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2nhefwyym.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuqotny.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjduuco.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrfodts.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijlhwnq.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwymrko.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wxampwuk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuzzqbi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxclhkao.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2egdohexl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2undptcnw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdridyc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuxdaos.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdxnwmk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2udoiwotb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2naxaozvo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmixjfl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwckkbq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vexlebuh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lluyezom.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eezshjtl.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uisfkviw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxeujsz.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfilqby.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tevfppyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxiwuak.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2djedgfvd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2geuijfon.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxytuaik.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2eboagryg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwtntkt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzihidb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtmzfyc.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mshhseqy.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovexyht.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2badphyvk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgdmisn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtfoqgc.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qydciggn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbyuyyv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2onnmfbwc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyczqwp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxugejge.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnqsrve.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqqoxqe.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjsmori.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvhumgi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2skoxnbes.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2aqftadfx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvwqvzr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnytpk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mlruiqyz.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuzeowy.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhsishu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2dymmbkau.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmewefg.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qomyxnvu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hybtawif.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtjxti.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjchlaq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpxgojg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrxnboy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdgtwxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2smsilxdf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxsqwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tusowhrl.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoxlnjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czlhjvgz.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgjeott.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2unyttfbh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjuplqo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wplkzzhe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcqffxy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmpdshv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dszyqsii.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnnaada.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2anibanbf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2jekswgmv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiatyidf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2juzggqsl.html


<!-- 参考信息 -->