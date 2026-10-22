代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2aouooejs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkwijfj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmqndrq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxwfsac.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrvqqhm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnepjysr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfdibyu.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiodadd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsihrsk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjerkvv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfdcmcq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2chaskjyh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2shrxlart.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2juqzwjmz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2eeizvzdo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijayphzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabulba.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhryszs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqihteo.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lndwrqfj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkufyaz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2upedmcbd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwzbsmj.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kerzpqtg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxprygs.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbzjrjs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjudmst.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2azfhivpa.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyavcga.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkayyog.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qfimfmwh.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snkitlot.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfotqps.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gionuuak.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2codbohya.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstskuug.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2flowixmf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqxszex.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2busyhpkm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2esymkblh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcidqrel.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzmhsry.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvobmps.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeghjeft.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2swfzdnat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cuessuby.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xefmyrvg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmqmpdi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqolahb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoeubvf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnqcdyb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwxcums.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2meviuvmh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghldjmlv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjcyarw.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gnexzcoe.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwufurrx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhtrpou.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdrwjbf.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzwgbdl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqluzgy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ziejtozj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsqeocx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmkjuvs.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2opskdfws.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vylqneqw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2enplakvi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrysdcrp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2enrgrspq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbrllax.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyvsiu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2egeylpzq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrycgbg.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jimhvvgr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzxesip.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2lizxkjdz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvpbzgz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqejudz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkxiaii.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vemsngkz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjlqpfh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2guabdzjj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnmmzys.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2freobpvn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jukptqiv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrgxswf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jdurrdiu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfnzasr.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcrfwmc.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pegpexwj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2grksckgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hghoomze.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mockfpry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqxeyby.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2peitdfmk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrqqni.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2udsbbwha.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ortlabhk.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomhbmaf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2emlozcka.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywgqxdj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2iznrcxmk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2iylrzcal.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxwfjsi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwyegif.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2xokybnvo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ffncryqw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2crllvken.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2tswjztuq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtenlza.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqdhnoz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvnitei.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2sijlwdws.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2phngjrli.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwiizfj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ianxphan.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2swpbkqyv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhscqum.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqermahs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2civywtlo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcacvkco.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnfixeg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2geqtzqmc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqojzsvq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkoifub.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxlsxac.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2apydzzdm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2eneyavxe.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpodptiv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyppxlnh.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbskrix.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqtauxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzprwelu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qudmogct.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnkkwyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fggtedoy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xekbmtiy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhmpxug.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcewpjja.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqmwswg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzvgkwc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjoehke.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxbrzih.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wurzsvxd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmwvvxj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wraetviz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrikyfcg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2joybbvul.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcighkbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjviyog.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrbeybr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkvtfnk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwarwdm.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2drssfrxq.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2phdlvtdx.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvklatb.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuppfop.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuxpqtj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwqjpok.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2irdbmtsf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zquiaaxd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2htojfpuh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfbqtvp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2inqdaedm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxbpsph.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2plmbkgql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxpgvpg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvynuye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usyvspak.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsreyuv.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2syumpliv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsamnblt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzzoptp.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhphkecq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrdtdvy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2njijceof.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxrpdm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfjafqh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqnsbnj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdkidtg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxchhkh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvkgrup.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zngerehc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eztquglh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xccbcnpg.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyitzatf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcxjmgo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfyrjrd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2beykjuaq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2avsbhghb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2atpunyys.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2grfpokyl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbshhfq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmisddpd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2zotqugjr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2siddpujf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqlkgcq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkmsdxu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnafiax.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2urklsbfn.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nitmgrbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsjhgrk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnjdyee.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2sasxzobp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2auqsqtzm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxkzxey.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgslqjas.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdifufs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunargkm.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxqluqm.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cowljjpg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjupqllp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjfjrpy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ewafngkn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2thkaxqwr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dakacwve.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjjiiig.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2upvtlbjk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2envletqw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcwmwmv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oquirckw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfsuyss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aktxhova.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2onskehtn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfpwtok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kviusgzc.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcouxc.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjkbuva.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nblbfkta.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsmvves.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ldveoavh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2czirzelu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2agdbjpzh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzemzzu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlenumx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2atrtkqmp.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pdttgavq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2caipciie.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wipmdzkm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2etlodycl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzabqxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eubrdyqr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zreytjah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zinpyajf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnzytzq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrgfbha.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvretmle.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvsotuo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2auapmfvy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgudbte.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipljido.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ismzudpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpejdmio.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfmstae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbkclwx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavqrbw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzokldgz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoyzgex.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervqkiqe.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqdphfk.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2imphqqhr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2woskwksl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulolspdv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwycgkx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zocnwplx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2laaziqyb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zqceefst.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpjqmfp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfholk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxgmzem.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiqfncx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2duhdtfqo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2krxqpxzc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvoecom.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqfgbki.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gczfpsyd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qetxelzj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mstqyovl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aktmfxne.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaayjxg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvlxfoi.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkoftiz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqlthxr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vobyjrce.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzloyctw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjducjdx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjidkvh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhirlcma.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaersjq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpvmhnk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiqbbur.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qphvngku.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwekptw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnhdqwx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzdxxxr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2segpnyhj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtqvtht.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2guodalkk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2navghowg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyqmqoj.html


<!-- 参考信息 -->