代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2quggegiq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbihewl.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zirhjhst.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbxksb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2towbrpab.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkthwry.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2jclinjmm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghodjwyq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibaqvvut.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2kixsiwiu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmpmpvs.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2msucubzi.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelolfmf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrutkqf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jctlutef.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuacxyye.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nystoxdd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhdzedr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmqoupu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2codxplwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tufbexlp.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxfodfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnahqht.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kdziiefx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2mitobwxr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjndroi.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsauvhyu.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2talompms.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2piuqjalr.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyyzmfw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgadavo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljckhzo.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zrevrujt.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2daigphwf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrptcsag.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exaopsgj.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzexfwgy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnmjueg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dknjqnzi.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngorkveq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vahpowsj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2grnwaiqf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlmupir.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmcsbah.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbxcahj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyvaqus.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2skssggus.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2zngqxjta.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2skncqwns.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cknxzjxu.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpzpmsu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxffcir.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mibeopkm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwahbhda.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khfpyyms.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2acietzsi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2aizravhy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiascma.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeaqcbk.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ycumvfyb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpngxgaw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2beumpuuh.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyrjkrk.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2csgynjye.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgvyqaf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2akhxiufv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcnclsq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2icmphacn.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2riyfvrbb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyeyhcq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vftltotn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyisuxue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnydeujf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2poffzrfr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmmocds.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtbzsmr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcyivqh.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxohrpr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqueelnb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfededfr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fepdyuhy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdbxxmq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyqblci.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzvkdpo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnktxtr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcecnxyo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2lybydfvv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcopjse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2riezijru.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hazkpusn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuijzsm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhmrbvs.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2izlyaqno.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ionjcmcp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwrwfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmsirti.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdiavbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqxhgfx.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpyeyfl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyzcipv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2uprcwmud.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfyfodt.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2azsewavv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbgivvy.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzjmofl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2koxtgztn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2istjlfga.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtjtlrj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoxootl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhqztay.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhgqvlq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2stuogino.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhtiihq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmruvthg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2sankhmcr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjaaafh.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzuoubl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhhlrra.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dacauprh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dnifgkgf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbomhzyy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqcfevb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2amwqbbud.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxkincr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpffuwjy.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtholxz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2merxtlxj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpeouyu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2barcstfm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjreol.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhelvml.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ettfuwry.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2srwxbjnu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cihlkxck.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2qckxkitz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtracez.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgjkuxx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtyhcay.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cizqqgcq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2oaumbvyg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrmjzta.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rdihrahq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbovewj.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxlzjpj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zziqvylu.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jumblhgf.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbleznw.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqylavc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhwjydn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgeyvyt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqyptal.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcxjeuw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pekswjwp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdobjqhb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouibidap.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvrlcww.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjtidor.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbihyvw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vevwrnnn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfbvpjm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjacafd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgjurow.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmgaquz.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2whhckunr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lghgytjn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqeidsa.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2nutulrve.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsxorwy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwehlei.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oydtcqmx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frpuhfuo.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fudrcggc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lykbtfcz.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2erszqmqk.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyfvkxr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaqopdl.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooditqsn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adcvzdms.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzobazx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdgfbfc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2mevppzfj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgqzhiu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwtvzyv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2acrsydzi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvnshtw.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2goyfudiv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqcpyqk.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbfcvmh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ushcqemg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfkhqwn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnxhgbo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcvegak.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlrnzev.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnifwozd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2urfbeaoh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhbpqst.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvadusgv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyluxry.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwixwpm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxmnmds.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kuznbanh.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqfmczf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zeazgpgi.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaxcaqk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcokjenk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsilvspd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaupitn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqkrvrh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtwmgwx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bobpgykn.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yascfyrj.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gommjqma.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmctgoah.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftchibic.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdsfthy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojrtcai.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yughcumw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuegblg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqwpbik.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wffvaqie.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdnrcys.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlotocdx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cputjmqw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbroixj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mllslvts.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaxoaog.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfpkpgm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dejxnkzt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdfzosa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbmlhzy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhcppav.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsjlovc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxvcjgl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjvlqfz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2urglqafr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgjijqp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjqipnl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcymtcf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2latqgier.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2janodghv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qejfljne.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwdsffq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrirzmjx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeiypcz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnvnvnw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jemyomhd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmrsshr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqcgexa.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuutbbj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxexpa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2feprawof.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtglwad.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2isczxzfo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbdmjtc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmhiaka.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyvvmdc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uafpgtks.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2zginwudr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2miegmvaq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpujmtq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2duyubbyu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoavuks.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmqtdor.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwfnikl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrrhvki.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iapxgpbc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2yylmxuat.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmazyxe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpecsqz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqqvper.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnnttya.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dqamtshu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aunpkcos.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqnjruu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jnamyarj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xicbxont.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afeuwkau.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlahqfnt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlclslc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbciuwex.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anytnoup.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpdokr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzipukn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkilfmb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfitwot.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcotcazg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktsbsiw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbshzdfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxjcsxc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfukdas.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioigkvaw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspregod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdvdciy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gknfhexf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhxctio.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyguhebg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uswklgnv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcsxnjs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gptukkpx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywukammu.html


<!-- 参考信息 -->