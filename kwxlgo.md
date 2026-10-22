代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnpplsg.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgnvzke.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyewwnpi.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2xofougmo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2mouljsfw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsfpgur.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwvqpcw.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2nywnnwog.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgziunae.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjshjlsn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2caszudsb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfctjjb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnfiqky.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2daowqyxe.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2yncxmouv.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbovvbd.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2phucmpox.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeaielx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkkvezs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqecased.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2usxixero.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2diixaihk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyphcfh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtocaga.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjnilt.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2wwatzghv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcqrlrd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwjghhz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaaqxdj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2raobesia.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwwaoax.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2atawfygc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxnniyw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2dlymquox.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgymqzez.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2uprqsjkx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkermyys.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2latrtfnl.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzhkbnm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkngmluy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhypxyxh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoqjknl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2tonkfgcm.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtbakag.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esmzfddn.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2uozkfcdx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfadjour.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhjuawo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqvzfo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2rulpujiy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpacboq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzyuavj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayyjvg.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjmcytj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skjiuhsc.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2orhmylky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2edduvvyn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2snihylgn.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxovqehy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqivcws.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxajkzt.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lercfygu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxbnzix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjchilnu.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzukjui.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2shlzvyvj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2whuwzjcj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdefdsp.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txdeugip.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaldegqg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgrzrio.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkxinza.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbthktpc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjpkjwn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqidgzxy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnetbrtz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyuebsy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzkdpki.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mroosmng.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxdnoxq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvaspj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjazjdq.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbufjpp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmobmri.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddtzbu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2byvfowrr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2famdwxuw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gslomirx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbovwppb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tibyxvpe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2milfmamu.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagarnn.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2toehpkgq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2vngijqch.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtzgxdy.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuquhfmq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2mwizucso.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2nalcqfac.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lyymubxm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqossaa.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2geleqabu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2aejqntvu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2axcwauqd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpdtnpu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uahltzvp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcsfpgg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2oejhhoqk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrzrbex.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhqpeby.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxisshy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvyzgww.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfhrhqh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cekiryvx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgswqihj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwspquis.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqyanh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfsyruy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvvhruf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwyxcnf.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsazfkso.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtghmmp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hgikgfww.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wuydzplo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqoubnb.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyryhtg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbhzvuo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ormofmql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtxukqp.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qezfhthy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjbkoaw.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2guzosrft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2sczznvre.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ietkrrug.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnplujnf.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bloryqbc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jamvrnvi.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwgfsqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsinrvb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkerolk.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbmgkhp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmwbjmr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tdufekbv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rwinfunv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkfdahh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbvpffq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjoykdt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeynqrd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgljyyd.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2imqqcfhx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2znyissmm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzbetei.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2geqogcao.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2lqafdqop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2znrqpfcf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2pomtwhvw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2sixufgyc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlqscxx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vztqpmrv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxtpcni.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtgbmcl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hbreuesv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnjrlhc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorpghi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2saitqqro.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcxplxs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfdqdfq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwczdot.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxprwrt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mufdxqsk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkjjtrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzekkand.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbfuzco.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfndiinv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbyoun.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2epfngorg.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yihujjtw.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhglhrd.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdhomgm.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2raouqlxc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vivgebhe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkacxtqv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylufzqnc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufczia.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrqucne.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjmgooh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2yigdzpuc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2usncbncl.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbmvdpy.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqnzlmt.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fryuqoza.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2htgusebj.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbxvdtv.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2phbuppal.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlknkef.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmsorec.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2sktbzcfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdwxmlh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbzkegu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzjqiec.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2uruzjvvj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaurhebc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxmpfaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igyhsuuq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cuatyzuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjuawet.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2erzzgxio.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2irchekpe.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrztaox.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmtgzrj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrozyuq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvuvipy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvevuny.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iailsjat.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzvcrmx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwymtkh.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrciudnm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dardiiot.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaamvqz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2enxltdgz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2swxkddqc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2chruxsix.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzisfhx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuzdycw.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwnbpjm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvnhgyh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnxtfra.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxefanh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yecmbnyg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqvjnfe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2okmiszdt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfvycye.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2curgwwda.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgqliiv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvubwyay.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2invfjjps.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xztdsofb.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgprhc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgdkouu.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqkbqgr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjnhcdh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkchify.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgrssyz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbalswg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvfnmul.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqudmdk.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbjgrws.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2euvkeqxw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuenrddx.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2scfqfzqb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbdguq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlybqsm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rukcwrpc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2onhrpakw.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpgyvsa.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kodscehx.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2acpludrk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrxmklq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxuiqau.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkzrkuw.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2qwygayuo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2srvkkglj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eofbwvnd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgdehdd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjvyodi.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhpymyl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzihvztn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlhyfon.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfgmyml.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatcacq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2clmdmlrc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ksofsgvu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2chrkkxdl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xsopwrro.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwutdto.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eevaihin.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vxefqfud.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtlcyfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pulhzmzb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hianvcut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbqprta.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmxhteh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfichztf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eylmjaww.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfnvves.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyatqnkz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlkqva.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fukmgzui.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2cewpctfc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnigsnr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2paicycwc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2axgxxkdb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxxfetp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjprnzc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgygkhr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmhugo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2glmbelwu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwldkde.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2weowbdwl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2myldrfam.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpdmdkb.html


<!-- 参考信息 -->