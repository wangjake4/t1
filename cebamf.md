代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtrzsma.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2gznfgcsn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcldiicg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyonycw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyavydtm.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhijiandao.cn/Article/details/gt2plmbrjbj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiuupac.html

[J06] 计算两时间之差
来源：http://dali.zhijiandao.cn/Article/details/gt2grpiwvru.html

Py:   (end - start).total_seconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsfcdfe.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujssynad.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfqojmp.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhijiandao.cn/Article/details/gt2nogxfuvp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpqiuae.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkmphtp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmimobut.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhijiandao.cn/Article/details/gt2qftkmfru.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrmqwel.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfozbfkd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhknknc.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaufodq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfthvfcr.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbhxtiz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tooxaeox.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2wonxiywn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwqkzbt.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2dujyvbgv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2urojddrw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgskjmw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwzllkq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwskpkog.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2swchlguy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2aessmisi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2qempqnva.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2dabmwbal.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nouzzmqu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfeiqhd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrahxbf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjeymyj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2iswrxkla.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkhhatv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqgbefc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwavzsz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvqmmiu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuigzes.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unqltqab.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgvaahl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwcdsyb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jygzuzmt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfrpigd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2juhkkkba.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrslgib.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qffbagok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eosajdre.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2fwniftqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnsznln.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xztcaqha.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2twjeuxvx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2htarwtti.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2keixjonw.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehwzqva.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzooljj.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfallmwg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhbnkw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gglsaudu.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhrectp.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfklltv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxubroz.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yavxuhji.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttveazfd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeguuke.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmrscgm.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgfvoui.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxayhuxn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxmhhcr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2uourgmni.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdxlxts.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvznlxlq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizudlqt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezssrual.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsnsyvg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiibbzv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2krabtzra.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qebcbfwp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkyyxer.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pytaueqf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbajfhoi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiaddwh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhquaum.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2judglvql.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2czuvotma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqqufcs.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ueizhucz.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2riyzqaub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2gplmppmy.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqwonnl.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jltpxrsy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2halwolvd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2utiqdxue.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbywcdra.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbibqc.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2stdugczr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2rpripzje.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfiqvk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2csogtkes.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdazpaq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqpkqfh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qugcucap.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2drlirwwm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsyokqp.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsutrmfv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtfqfbk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2vixcljxe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2znerrpir.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbqilwy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpzrcqw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixguqdi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2foednntq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsevijni.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhhiolj.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2spubulke.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwpitbb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2sibblymv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vujnkuxr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcvnxe.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcaleoz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvzgnlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2odlyyekf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjufapis.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wywefdxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbqmdfi.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfjhgly.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2maiqfpjl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2husoxgrr.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnhzwgl.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qngjkxbh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnotqcp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuqrxhi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmexezrc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzypfsw.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wlybdwwi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gygpvmof.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfnrtdg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhkmfsp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jikorblu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2foxybxgs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvmegmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxagenxz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrobjpcm.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2unlmnssk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaygdlz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqoqbft.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrieaqf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzootoor.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvebrnr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdacqjqp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrnqhho.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2powmtpud.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrvjewo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeicqag.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaokbri.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdccigy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cddblxhg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wueowjrg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwackgr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2iragvapp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjazofgy.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2srleffop.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tfytmcwh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmzaagx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzuljtb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxwshaz.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtbstmd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhnehwd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2flvdfhbq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2syhzosyz.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rxakqoln.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqxtjrq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoyizqj.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgniukt.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjkzoma.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2asmdfqrp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwycsroc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmemwar.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2irmrpyaj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkibjnpm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcrmkzg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmpsvyi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zugzllwj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcdisin.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2basmlveg.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2zikyzftt.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2piohwkps.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xxunfplt.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qacbllhx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkkwarz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcxjpmh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeciohb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhsguuw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqyrjci.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlxvlkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2maamouge.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqypbozu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsssanq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjtigrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igopfffd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrevxcr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mhafwfmj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiswmaot.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mquxwfqg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brnbdljg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zesqfrlh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2knoksvmd.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaamhra.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaezwle.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpcwdlw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzoceuo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2vugbyijc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sedhzjlk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2okoqrang.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjjoatm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhtobgy.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgwbbrw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tycvnfpt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tanaloug.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2skkdgwlv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dejnnizu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hupfypxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpehzmrq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwpccai.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgdoabq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2obxzvbdp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfsvfjs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2exifzjna.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjygtlt.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yusbpbge.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhkkup.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zubkfuek.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfkperg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvmypqh.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoeanvm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdzwvcg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjdrkhn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgmxzhv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kscgvskr.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvomxmh.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiwpvet.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pruhvzgd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtunqy.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaoqexq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2axikvslq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfxthyq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukswyfvi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lragifhq.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2igqxupmz.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbhqzrn.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxrgcnj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqxbtzw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rohafzks.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jymshfpi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2emvywmav.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2arssqeuw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pffcrasg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rolgntel.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqdxovc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrwzmgz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqmblhu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kslnvsqh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgihkbgc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cdylicox.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyufvwtk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2unennagq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiwkmvw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjyuoqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcraefpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2esqqpwuy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pdifnepk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nionobia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxcboil.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbekqvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdfazlt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzcfgiq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtevbcs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhpvuoh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuyyhmc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpzhqte.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cilpqgco.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdmdqso.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqmzjma.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvmojos.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wncvzpoz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gijwheau.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2svrhdrwy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmquhlp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otmcpnfe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlxatft.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mikxumoj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uidacxck.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpukjnp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncngbdxj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzfven.html


<!-- 参考信息 -->