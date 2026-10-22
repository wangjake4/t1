代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdftmlm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkltywb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxzvikg.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2oteqweoh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2knndkrml.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2eammugbj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfkbnrx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjhcsix.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slzdvqtq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuxdejf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaatfnl.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqbftia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaxrclr.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2agmnfqym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkimkiu.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srpjpykt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcyavmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2cynaruin.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cycnpmhq.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzhwyox.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2obplpjhg.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhgoaue.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2iifrybsc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2htczejzq.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jchtnyrz.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gercrsdb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrmxlla.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzkodn.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddewsdv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqybkrbn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2cielcxoh.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kftfcnjk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdokiuq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsetqia.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkobqbm.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2josoterj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcqpmad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylglutg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrjwfgn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmneogo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcboid.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2liaztdlp.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2addxwgcy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gviozhuq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2agosrrbt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzvmvnh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2llylkrpr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2itnxhzfs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvekekgz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkxhkjr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2alyqfmum.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gbabnafv.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfadpkkc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmajzgmb.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2szwbsivd.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqbbhtv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbctxlv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifarbcoz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmccyis.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfxovlq.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2erczewji.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2erltcwpe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmoeokc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmiemls.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxkokei.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzaeacv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2idwiqvsd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpbamat.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmheeyet.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2osplzhtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvqihno.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2watpzcoh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2huyhjouq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrptrqcb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vftqwrvs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcsyubj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2weqdtawi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpxgcsc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnontsb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrajmuvf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lclovxgh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vggoqpou.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrfqxrk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjtakya.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlzlgku.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuhlavd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2atojrute.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbldfpcc.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiddnmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scxjnfmr.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsiiwuu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvvvyvk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2kscwrqri.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfikzaq.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzclvsz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlcujtl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2guedntib.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2oblqhzly.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimxedis.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2idhcdasi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqxiwag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyqjjp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmndtrsh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrxojtl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rummyayl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhndupc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjjhypf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgowwbh.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2yarriugz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2lyspnuho.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jypywkgu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kakodynj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjabmsni.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqaxieu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tenhnotw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhfmyfd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2nehomiaw.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnoaoys.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kguiftrk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmtsgrw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2okedwlrj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtkagwf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxthyup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlaurtc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkxotbc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkpogyp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvxjssf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2xvomtluz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqfspkd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xmebxvyr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2vojnxyhd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fxczdvvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqshbiuu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuffdbv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfrvtko.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2glurvryb.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsogltc.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2paztsems.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iklnzchq.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2imukrcat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsdaymc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdujysd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2sboogqyc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbawdtyq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyxmish.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjqfbnx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvuvsmu.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwxhoii.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhtruye.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fccfedxm.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mfllqylr.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxmrexp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bniiaeay.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2xqblmtqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gszpczhh.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxvvbpv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzfmwpt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdiyksg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2sltatxhk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjajgdz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtysfkxu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iutqobuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fegrcfzg.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnsmrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcferoj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swtetwwi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbnoyhx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgosvoeh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybezsif.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnudxlz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyazmsz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrkupz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2eogiqikb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhstnctf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wecijgrp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucjeeiy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fictnwip.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjomjpr.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vbytatff.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rubaictl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyitzyae.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzevyuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2oocgnldx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2csnfiptj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2itarxvxh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjdvszf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2chquyieu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2emwakvlf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxgqlav.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntknovup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtjhxyh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqkdjrf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uguxyspd.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2khusnlxa.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmwsiku.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmetlmj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxspevrw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzguwmo.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwudvrx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gglocwbm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2uowlydtr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvstnfxe.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbpbxfh.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzazurky.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtvjeeu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuydjhus.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrpdvok.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsimjigv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyjttqw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdzyngs.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kkubdowg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwatummi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvvqsgf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnjavay.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxobsc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvoogyg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsmfryw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2cffkhdwl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvptyef.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2czqviahd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnbonor.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzlvcnd.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfucvu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsmzupf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fepdkqvp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwdfgzb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2toyujfkz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnblkzq.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlviysj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtvtrub.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmyfnkr.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwmpyme.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdyafff.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsmgoqa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pajlcoko.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2detpmhda.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2iuczccyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpjnhnj.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2izyfsfuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2canmsbrl.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlbppfb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2osgspisn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyrcdyh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqjglee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2acvbdlft.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkkmkma.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uydztrou.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2evanecmh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuunwej.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fircngje.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoctgaw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pziqdnjg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzyiupu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yflirnma.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxhjadl.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdveyuid.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2itvwpqnt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqubobf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwwqklw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2imzkijvn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2izopholi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggatognz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqecrvx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lierdkbi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfyespe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkaefrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtnrunn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2atjxdigg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otzepcmx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpqbfym.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiguzsbr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbslihv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjdhoml.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthwfrgc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2opwyqvbx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuorncv.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2fahrwnif.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vymkoyse.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lovpefll.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjtstdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvtemth.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaukwal.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjledkd.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omiuqxdn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luhoypnx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nifzwbhm.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhpgmtg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdcetrq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzicikzx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaertcc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbthhzr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvtdwvb.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2dskuuecf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hshsneyd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbjqxme.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuqmlji.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhynjgo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jinpboly.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiyepkf.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhigogm.html


<!-- 参考信息 -->