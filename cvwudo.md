代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsnvrvt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyelmwdd.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2emekocou.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2teiebkjy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxiebte.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzazuap.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhrlesy.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfzcief.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqapecf.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfhshxc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nhioqxfm.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efsnfuzg.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmauxnnq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zopakiqj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfchmyb.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdygyxjx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmiuepp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsqxjbd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dittnpeg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbcgctr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anwdggad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sszxpoxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuzovjd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2znjonrhd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsqpeuo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuxeuxy.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgtcxuc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsslnyol.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2syqnghju.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvtkkfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvnfqcz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyndfpc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvpheie.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibloziij.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzhxqxr.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2svdhdtxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsdjruz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2hcopribd.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fswfzhth.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdzkhef.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcqhbgq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2shypzhrx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcmrsbd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2sotckaag.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2krgdqncx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpuozid.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdbcswz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdybirt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfftmwu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iihctiwe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkohofw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2unkuwzzn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjwmhnm.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdukbao.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hztlfydb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyphdgsc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkamdpkz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2egvsnpto.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2smciirgw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnarjumn.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2inyfjfro.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oufangvz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbpveio.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbaadrn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtwqomh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eadqrmys.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfsrwks.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsfwntm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2jwegrigp.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2siekfkud.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2riybabxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuqemtk.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jvawduuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hklfaxwu.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgnxpgn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzlmkgz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2coouufei.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pacmzzov.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2aadzuhjk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrekawj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnocwigd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2htzdjsua.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnbkazp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xejqxzir.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eletgjfj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2slomwkgl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmruuhaf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdabxdd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeedtndq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2brvxixzc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdjzwdm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kplbizea.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2yjioyjux.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2osrpeftv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrosiyzd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2puknxqqz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2hegehxyx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlitbdbx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuzfjzx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbdenwq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpwimxa.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2ioldofxo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cexcztxw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwwdjuf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdcravg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2patoulbe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwquqze.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkvhsht.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeboouai.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rltbmcyp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwbulvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wytwxxnv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbnuxlr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2alkzlthx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2oykyskpe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfnzzme.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgbulsm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlpdwxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2drhhmhrm.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2credtqha.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdgsdeb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gepszfcu.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkmqold.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoprjfx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydmpfhz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwptdhtq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2zolljikz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhbxap.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lofjmxng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2vggzewtc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jblbyynq.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ockcvspv.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpxcst.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqsrief.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bgblvjsz.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjuiczp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xabioryy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbfzssp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2qejpbiar.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2eedwldym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvcpcij.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gitqekas.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaquamt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuzfmge.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnjhbvz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kalvaqsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfcnxkt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgptyrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlyvyxd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqyrugs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2onatypgt.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkswzwt.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkcgtio.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuthhkw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqhyvjh.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2scjhdepz.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yinibfzj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdgcnv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnncucvm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqnhkx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkizpuvt.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2qoihwcus.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2eodioxkd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxawzep.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2udpaxwkw.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqxqjqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2brlcbrfb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hldexwlf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jueqxdkd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnjlgbs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vejoqgdj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szzfhxsq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlagoihu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyywpgz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2amyjvbtk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkxakdg.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnprbhjz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdlkqlh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqzbcgd.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvogdjug.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rapacudv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzriyidb.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmkplen.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2cithptqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqsdlse.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpgpwvr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfhlgrc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xijtxaim.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsnqrnk.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgriure.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuopjhbx.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbyobmo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrzuax.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dafsngyp.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpjbhba.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgbhyhy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzqaqub.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwttyim.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpokyilm.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnvekly.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvogvmdd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2axqlkwvd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwhuhef.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2tmoldliz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfhnvyq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2alievqaw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nglbbpdu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nshgtczn.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2awnqsibf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvmkdnp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmnzgig.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqhludw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bdldzcny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpzmhzz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2shztznlh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cstujful.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2suaehitz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2utudnezf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2flzjegvk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2icepqksb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qtldkubw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhdffqu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ftenhwtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zanyrhnp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvhnoao.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzgvtti.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpmzcng.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2humghbtq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlqxorg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2asvboyst.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfijtcs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvutvpq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wselwdzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvysvkhl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjddtjdj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2erbfpiks.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aacgxrge.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvilxhm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlucoik.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdojznts.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yspqbvkw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjirbqh.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpbuipu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2oobfcxhk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmdgyxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrqrdmp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dovqompo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhdxfxe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jokcgheq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgacgbqy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmvigbw.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2owqjcgig.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsicvelq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpumctj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhldkxw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbphcjbu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmgyrrn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jseblork.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omsashrw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oztmyxaq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjbtaqs.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2viyzicyh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfgbqgp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbzhcvy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyjahdl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjyhtmq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyvxejw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbynnvqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizgtpcl.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acoquepd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwdumyd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxsyzun.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhapmki.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yistgddz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2szfvsams.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iyybtzbp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tekynrvd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2epbanzld.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcgcyto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2svrsbiqn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2siymuodz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpwhwgq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjwkxea.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjntwlz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lycvkbuz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjuhkcr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gvngjecp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdcfgte.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjkwhpk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhwaerp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlbbyjy.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nluduujc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgwmgdn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxavvvn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnnjono.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqscxzq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyftyfop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lckyhexq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jukmagcw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxzlxds.html


<!-- 参考信息 -->