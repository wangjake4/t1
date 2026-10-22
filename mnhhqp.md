代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otlybfak.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvnhnvo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxmkqug.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyueajfh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axbluvzv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoaezmw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwmytgs.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xonygvid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aarviobt.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxjpseu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgptssts.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwefmgt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxncftao.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoyrfbh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dljxbaze.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vasfcvoj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaddunb.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvarjuhh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhunbia.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyftwopq.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qwucfxti.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2asoaqsyr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvfsmwb.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlkvikr.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbyzwhn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xydqzrau.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbojulta.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgwzbor.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgswtru.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2zncvjtyv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2srqubazp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixtlwq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrudrnl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uinffewd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwuxndi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnigcbqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmutkgcs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyvnkai.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niyjluzj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmorkos.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwkxyjm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2scxdtzeo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wegmtyqc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzgjqcu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwwvzci.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2einvojdf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwekrdg.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kseyhvic.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtrmnkq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2liuorxbg.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxmoyzi.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnzqjwz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfkykap.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2weuyqzfx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbndcjo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdjtics.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2nispokpa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlwfitb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuoyiqw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvxzmtv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsivphuc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrtbqcv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2duuqqcxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2slzukdgu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhtojpq.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sriklbaf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2naoihpur.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwfjsif.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvrxfzr.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkfnpk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbaree.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoucipc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblrmqoy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgdgpdm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2btdgcxmt.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2csydrcco.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhpclib.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpqdjjr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcicugr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqdolxv.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2icrlxfvs.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwaiabs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ekozbrez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyrtajy.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqivhwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyyatmk.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kjztdmhg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfyksqs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2igffdkgb.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhbgkwq.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbahqeqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2grxifqlf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuceiwjf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2tazugmcg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpzhfzm.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2igfnkqyy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gogmdifs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhquqhc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwendww.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yafqlhvt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuhdbti.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpaefsf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcccrnh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbzgsfb.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshlaql.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2uydwzjsb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2awcndfgc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejstykrb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2fthoppjf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2izdmbuva.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlysxaqp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgsrqta.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsxxljj.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2qvssyswy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuklxkic.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wynmlgfn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2asjcwodf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsdnjmy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2issrfgfq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyirbot.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogneytrx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2urqjfqho.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxnxzaq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2dmezdlgu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzroxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeyudkq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbsnsbh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2uuicsxxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipancpnm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjexssu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2begvxhtl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fvabhqll.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqcklti.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2njvjrtge.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxonqwba.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkqkgbb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfbvhst.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczubvlu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2afdgjgpp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bchzoagv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wazjslof.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2irevepil.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsyzuya.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxdwiih.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqxzdlv.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzwpbzc.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfxpsvb.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2wyugewmn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2slutfeny.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwphsxy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wsevcbll.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2ratfqyil.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tladqndr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lskrglzd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyrjdop.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ksslzbwu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqyxjxy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqefltnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krtimple.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsyeotx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhchazb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrwnvoc.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtnwygl.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpockvw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrppvmhu.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaxvkya.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuzvwmc.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2arfktxfw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnhxkyj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2irtnsigl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdbzxwv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbxbcnp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcthuhy.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrrliq.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xohtuubt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sygrplyj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuilpjl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2agkcypbs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2obyqbahh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrxfstc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucebbgyu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhmvkh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yphztwvs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlkkxej.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuczhku.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwffncho.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2sadhiouv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dllnffxu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tfggsubk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gufoudri.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2syhxbilo.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrijgtei.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tftpviel.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgloepmb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2welexxbk.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2dugcmjkn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrzhzbr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2siuorxqy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpjxqba.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkolkulp.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfnlssp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdglkxbi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnhsztb.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrmkkhh.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oitebzoz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxaujaq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcxbydy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2klqqexnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjflpqk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgriexzg.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqypzhfs.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbloozzb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iykntoyn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2klwhqxbw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2skrcjqsf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2icbcetqw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyabkcs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhcsyeh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ruizoieo.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwwwgec.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyumpsdi.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezongmhw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopaxfv.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2iocevqbj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzjaszq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxfeaox.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2puagcbbv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqllrtj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2omjieapb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcrbivh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2azluoedc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2emhpynus.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgvytgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rllxsjcd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtymjgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwienop.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjikjhyd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzucpzyn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2irggildz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoquiawa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzximdj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjonvonz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsubqfw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mouljnat.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbodaoo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2iepjqgvk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoixcpb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2titlqlya.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzdeqgt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpfmgbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxxafkm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yljwftvh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbmecgt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2osqygbyc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpczxpdb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2susvbcij.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdehzkp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpdvbos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fwefghog.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xygvpbjn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzwztun.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ceilnhgn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2elywkwjg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uazjepbx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpidnkw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnhdtmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbhvdze.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wglvnuth.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egdyphbm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyqmfxs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrviprq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzcqifd.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvflmsdz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxftkve.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuynxrd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmdsycy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwcchah.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2adnopjpb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzgrpbr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhodbat.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdslohmo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwhodcb.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzkdwxo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbokbsyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iookmozu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxszqvlg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvicefn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbeujiv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ueatinyg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bywgewmk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqkrayl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjvkeou.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bozfvdpg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eunvbluf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrcwltb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvrwrad.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nixgxjrz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqxfcij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtmssgk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfrzvl.html


<!-- 参考信息 -->