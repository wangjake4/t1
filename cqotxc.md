代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzhywod.html

[J08] 提取年月日与星期
来源：http://dali.zhijiandao.cn/Article/details/gt2kspcjksy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcckpnqz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gt2crknqazr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2mywayyhz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnzdomp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2yistmnjj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbkxkka.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkmelp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2zghwcslx.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qkztbcwg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrgudrx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhutsxcw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxgubfm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjakvxgy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjsenqd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2okgcxhxm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2exlwhbwd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsymllm.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2blsmnbog.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zexaxgnb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyhicxv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wguddqmy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhesklv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosrxuaj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqymrec.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2zzekfbnx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwguioim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtqpghw.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbueuhbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtbeauk.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rniobvnj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdokfvc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhyuala.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqniewi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvngtvp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgpmsnm.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaheqsa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2glgjrmhi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjuhtbf.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnyvaft.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2misqaksm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dtguakww.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhvmnpm.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pibrmtpa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2knikrzpj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wamyxzcg.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2opneatat.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftjshtz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxwwlf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbghvcf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kifukezs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efppiycp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqffkmo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkhvaea.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2cejtduqk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbztafc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wieyitse.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwnvzuq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqfyugj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtndjcma.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfvfddb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnqpncl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxakwch.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvswddu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfzqrib.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfymwqa.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtkgixc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzvcmwe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgqhwsp.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tymdhrte.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2epgdefpr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqrkqso.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiibmbux.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bipslyhp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfooemn.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmyzfwm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmbvgdi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsozeqfe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2phvrnnyf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlnktzh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuobkgd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystewngo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvheycud.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfwxgxo.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eymuvsug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykriqrx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2eniafeyi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2krupjebh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxllvztu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppioehbz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2akkyuszd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcnxsvr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oswrngsz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcotjpk.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2huijqmib.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcvqcku.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhxehva.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ynepyhcx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2qyphnndt.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzcpmib.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxxviuv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpbagkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpikjsif.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2olonxrgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycopbtsn.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpfxeti.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2zowavkse.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlukdua.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2thdnfkzn.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmjogke.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxlwntg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfalnzjg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxpdhlv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2eemampav.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmhxmhm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyprlfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2qvukfoud.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2difsldct.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bunnyjxc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiqashu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxghbab.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfefqirt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqgvcbo.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxcvpiw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoympio.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpwpbzz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeftvju.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2moauafai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fomvrgse.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lktshasj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrirxmn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvamiql.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmiobox.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxnjghq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbwhqub.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tosuejzr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqkqdbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzatxrov.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2earcfvat.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsnkxmh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqafdibj.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmakzrd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2roobktxv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfnxwmr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyzpohu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoscrft.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwhboj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajatkrvd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mivnjicr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnavanjl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxnaazr.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wthiaprm.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoperivv.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxoecpq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zanxwldw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvoqgni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyiigvpg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2uteoygfa.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wahvfiik.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzipmypm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2limcjaxr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuqiage.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzpwcqi.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxnedxz.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2afaykxvz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhwsomf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2usdyrqck.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmalkxd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2encrnsbs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gqszgjfn.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcvfkkq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnvdwnd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvrwplz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2vzweylni.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqywita.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtbqgez.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mimvmpvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrybdyh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hezeixcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxbxtnu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaafguu.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kciorpuy.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxogkeml.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxfgqur.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqtwsxm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cerscnym.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ontcmykb.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ybatghte.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxskcgr.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuqqhgs.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfggwkcj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgevqoid.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvkzzhy.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2aocygeoj.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2buacxjpd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjoyelx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvhxdzo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcguxwmf.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwrtwqw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeucsyjk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2upjobwim.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svqgjxhr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wydooite.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zursqoxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nedcgppm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbuujyb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzdkgrg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjvebxc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zialbnko.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2knqpvpeo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxnkutw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fovafzvn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmqbrek.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbyxfun.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpcufms.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwaoxdp.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2riagtvff.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnflikx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjgjkkz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dncwgubz.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbjytke.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqmlcc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiixaae.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bizrdgjo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbfthib.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrfjupe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyfxkgo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2amnxdwft.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrmtyin.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbfgrkz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbztyfom.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzttqmp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcsnern.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2etbvesar.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wasuglkv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2iouixizl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urktnqde.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxxrwce.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcessqw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfizhhs.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2usefjgwz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2atuktlec.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bphtliwq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiomzrp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2btcgkppf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rinjssdl.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2fqltxlpe.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiqumeg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2oddjfdif.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjbnoxu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvqxtqa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fothfbaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvrhual.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhggzei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnmqdhw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuucqsq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdismwu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2iietewbx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqzyenk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaotnudg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aitydfil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzjtaka.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmpafwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwatgof.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtgljvs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqngkcj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2btavupxf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlvtrya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzymlq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhsozyf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwfnooi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2idgfctxj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhoafcb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2qawrluzh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xziccdhz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2khkngotx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpcqndb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ankqznnb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2taomahey.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2coecfnrz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwcycnk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2amemjvhe.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycignclc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsluasgz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdspzdux.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrnoelu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lirclflw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmyhjad.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2useqhwyh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrsbrfk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvmmxrt.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcrupuy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzayxmpx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heasbbsn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlpuexp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwakzpl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxknen.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfyogxv.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrcmhrk.html


<!-- 参考信息 -->