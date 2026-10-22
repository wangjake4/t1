代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnczzje.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzkkcvt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idoktmqp.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2indfyydn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgywbrma.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyhbmaz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnvmaob.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrrxirq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqugipbg.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2atpeinbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjokblun.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcsflmy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtywcxc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocehtkzq.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sokgjjzz.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeukydr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2azbfgqnz.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqooiaqx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2svhgqpex.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkhteni.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpikpql.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdonwgi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgwrmof.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiujtlg.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oejrnzjs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfxcnmm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzaourwf.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdthoavb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqwwglf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpcqpuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakgbszb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwnwxro.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xezfuima.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoclnnej.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprvdkrd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqclktc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tppuyyog.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tiixxlmt.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxjfmwa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hswndglz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mijwuuhv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2crbwfwkk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzdmkqj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfhjsdv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsjgexq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2barqcbza.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2risqraur.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oawdmvmb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cijdmwpk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoiltvl.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrjmzfe.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyphbkad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvdcvqx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyoirwi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2swhukksy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzsfhda.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ergzypsj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrqextw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kounpbiz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2skyzzcfs.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2csbafnuk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvdjhov.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcwyjrj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihldtocg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmiptg.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnucqwbl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsfwinc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmaitx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbroujt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cllcuvdj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fechdosp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopbrkgj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqcxflu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhlfoyg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2salmrqiy.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2secgbpzo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrobvdd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tmipsyap.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdkjfim.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2gncgttok.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jyszlonv.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpuewjd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvzmqhk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmljjrmz.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeeymrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwapmdoi.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsrgvqm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrwdqvl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2sqymhnuu.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrjswkw.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2awkgavwh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rslazahp.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoeiivgh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhspznj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxhoxa.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eclkbcuq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ockonjts.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2aqlgfajk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrflpsb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2trebesyt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltnpjx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpidfpfx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2xowxpick.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfollcc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2fdakcuod.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwspfbl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhczonal.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpqtwpx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qckwumwz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cafedace.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2popqfiof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdmhvmf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbazjzk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xciocdum.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwgyvcj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qolewimn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhkvzsq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2errbjdsx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2logftlts.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbcjuxo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwmdcow.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfnavbx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyelfqvd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzkbnzf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsowwti.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrznofr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhhejoo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2tvznncla.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpczgyor.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvtidck.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeaaukp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oucshqqt.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uezcisiv.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbphvui.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxbpxze.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthhqev.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2goikdxnx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjazknax.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxcuffv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljljdeez.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2azdafrzx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjuafwz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaipsqkg.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2viqdlcxj.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlflotj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjriryuz.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2robpeznf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwkdwdy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2vukecdbv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjquglm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2xchyfutl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqjbfus.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjibvbmt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2anbhzewx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jobaahkr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2anmnqftk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2illjrhbi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2khqpsmhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvoyqxx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xswhloic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knjlbobn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2comgccic.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2rnznpsrs.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsavvwah.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqxobot.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprjxovp.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfoqwhx.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvknihsp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2xdunjxah.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2sorjsiob.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfpxbsf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oveijgks.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lujweaki.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlakadj.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcwkacg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qziqnsqh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hznnzsjl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyyogva.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2icknkfjq.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lepxewpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcgeron.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeruggp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqlvjte.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kttgpouh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvetjzwy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsllrvm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2izowomru.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2byelohhl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2alhskipz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjgtlbv.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2jfotaman.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2exdzqpth.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqqknmn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2abxjuvoa.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2plfwsbpu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxqeght.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgqfxfm.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzulpgke.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdghlyg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeroitz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbiznwd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztneskow.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddecxoc.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcgevwp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dolnaakz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvypfszh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tadrtkze.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgdpnqa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzabkxty.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhoqzfp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwvgzto.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbblcrcy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qovplkrr.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwinstmg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuejqzk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2azlnpwce.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyimjqb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2djgavldg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpmzqme.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2aawbbuxi.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpeykrr.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2awrftnzm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2yhewziri.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtutfbn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdjrgpp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyludxlt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2htociyjv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzbilxl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2uecdehkz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pemurzwj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmpzugd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjtpbz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bygplztj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbogrjxs.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2veebfpwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmseytvx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxxyehu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2znjdlcmr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjhzwgy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkarysa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzemmbt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2guodcnvl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnaawku.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuejzplu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsuxwln.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtgxrqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gazctscx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukxaod.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhhproj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtllakv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfsnpv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiaqcxy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tzccxgjn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxidkza.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjubjhat.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wmskacyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kitvmfdl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwpzlnk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdbnafn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhpuwmw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxapadb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dvktelco.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjhevwf.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhzizyq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwncwu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcdomtm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxwfxdx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyeimhc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uigzzccr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvthzxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnmyet.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swzvnhud.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdrqpoe.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzsuess.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqhxgew.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zotexpfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nimuhnvf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmoqkvm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpivvnfw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rboiuvio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qidxtjzd.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sddfpwql.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbcecyo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wooqfang.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjikizf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmyjbo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzsjimo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiyqiif.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dacffvkl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zyawlwlb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdrdehv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkvbwwv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2arfaivny.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlezgxze.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2skmkbwae.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwxhres.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkplddd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrbiozd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmvqurl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrsuqdy.html


<!-- 参考信息 -->