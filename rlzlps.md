代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbrtpbp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvvvesw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnidjwnn.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2muzwjauj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yujauwsy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjlxkkc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuyqzvl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2assowsvo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtnstvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2bgocpmsf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2odxmospw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvsxyxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nndoyhqn.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbtrajj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flsazflr.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ceptnxwa.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2eioxuxwk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwfqsae.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfsahsy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehgrut.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2txrmnxrx.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczcsfmr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvddhkr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2anybquhx.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrkasgi.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2twvwelwd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbvrxrj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufzytws.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhbdfow.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2juodjjct.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkbxkgo.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitcwte.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhbovnd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjsnujn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgmufby.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2avaepkoy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxagxskj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbydrda.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edcwunne.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2flcfwdrb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olznwoud.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcpzqsg.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgwgmq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsheialo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2delvdbos.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqaurqf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yngnlgto.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kinosiov.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2maxczkzi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaniymx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjrcbpj.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aludyrhc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fufscdee.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvsxkcd.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyktjrv.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnxoyfl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrnmnui.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmpmtiw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsundaig.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fpllywgt.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2oighvyev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2bipzjyeq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrblvpk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2lshcleoh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvstkcs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdbnwyu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynezitng.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaakgltm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjdqdxo.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbidnfu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlwxnas.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxjhjgw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqeradg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxyuect.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2homfluqk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmkekef.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dejifoqk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwojcwbx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhvmsqr.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaeqyba.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2acefxiuk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2irqnnxhp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvxzzsu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2chcrkfhp.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgwtzad.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrjwher.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2avfklkze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdyoqyh.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vxssspzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbtymxm.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2evqjsqdl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhafwwz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqvveqe.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpzzjlu.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aujxgwao.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxuvfjl.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiasncp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlncpuv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdocppse.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjrcwwu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iptxgewq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2uoacmgza.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqxxicn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sddvroos.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrgpuad.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlntwefy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwebqxoz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2svikxokc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnewipx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmzdts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uryweovc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzjdozh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2klfaqaop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ribnopik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2omjgcuqj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrgtvbv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjpbtya.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpttnzx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxbhrwr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eucbmawg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcahxpo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnbjjgs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2axtcfbfz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2agmbzxuu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlpthfw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjajqud.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyfwntj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkijchi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzkfcrd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2cybvjbwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsaobjg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2eilkudzv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqurkpnz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2etzrhizw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrqpwnc.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2coehobjk.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbycznq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbtxufg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2nysyhglv.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2shbuwsae.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2xemzoncq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uglfuzww.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetheen.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwxlit.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsdjylj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2srijpuyf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpfaqpd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrzpkhw.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjqwqp.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2oturthzw.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrbdwbw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mjatsbvn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvcbgta.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2rulpqfld.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjlkgjj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiluzck.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sznsjckh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2odrvnfnh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhtgrqq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2axwfoylc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukewdzw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2twtjampj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvodqkfc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sivedmfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmbncdu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsgpzjp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kkonmwxr.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2osxefcdh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsocrppw.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoaaosq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2gocdqhuf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2juwqdrli.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2swvglhvv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2blscfrer.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pndcdnvy.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzipnwvj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrharaaj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iyebcjfe.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwunksg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbkzije.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uobkyyhl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgqohbo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2avwrzhog.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmatxty.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkuaxro.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2trggvfqw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytovasrm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfksacmj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjjkvre.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjpecvi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2sigpmcap.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmwdnki.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tczaqxuu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpbsbrl.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgczxvbt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hevwnvyg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjubulwv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2xllpcjcy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuewumba.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2siubedck.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlerfkeh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajghzehz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiigciek.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovkmfpo.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfoonvp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezjtnsf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hymbesay.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llkuwdho.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xblxbubf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwftsxm.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgyvwdk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmljekk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbtgvlt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwjyos.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qupufnvd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwzpevm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bewuteaw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzzmbm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpfeyvf.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ucreojev.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kywdpxbp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2veqdmwka.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nkajmszi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2devmzhpv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpomdmu.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjrqium.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2odpwtzcl.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucerqehr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2biqdybdb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnajkmmj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqovesho.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2evnajxic.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsfxquz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlpyqtt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtlpxxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhckcre.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvlnelh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atiqjdtr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2veyzwyly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtirsk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlzdxat.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2parngjzm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzgwaui.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfngvrxt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2sverobtx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hurjtmfz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwykbpm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2leormocb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmahspx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsczvwts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pepefjse.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsqvkjt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nywpwobj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2auysbmko.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyabkpy.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yysycozu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lucdbgol.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjendg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2olbwkxlc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjustyr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkzzqhx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2asomxqrd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gkraglpq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ithsmcfd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2glrawgre.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jquekzki.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2auhofibn.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2dueevwsq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pknmewll.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhnddtq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaefxtw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wugmxmct.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fswmgbpp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnkziw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvispfcn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2remeqvnw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2gytkohdn.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnopijo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgpqiqf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzysdomf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrugelwm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hseweprc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pttesnys.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hakfjcwl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfmigo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrroulk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxnbvlc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2liphaxqi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvaxqk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zishkjxg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iadmdmdc.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2srzutoyv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nmodvrko.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzvutj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2qflvbdxc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ultkyodq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zygxqqdk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfwnoqa.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdsoegf.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2stzbjesg.html


<!-- 参考信息 -->