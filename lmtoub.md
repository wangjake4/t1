代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjezibhl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzefiao.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdncguw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paqlfewh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzsovlr.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzcrobp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjrvflq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2izwnrvjw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2cptforlc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2njkqukmz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuothhb.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsiazcn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2kfekdrtf.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmmiucx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2twisnkzj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zerdmjiy.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdesrzj.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awgboxua.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mkprwcva.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsirdzae.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bemxctxl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrazswy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqyauip.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgggfdi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvmcmne.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2pemjezwu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2jppdtsdj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgjxbup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkwxwlj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccutfjgz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfluqpgz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzuvjlb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2egmrbzcb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzujywjd.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bijqhbtu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wflwkkmd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mohgzypy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwmrpit.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmpmvpy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2unkovpbu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqphlonu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrpztfr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrqhvat.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrcbfzw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdjmqzt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2nngjtofb.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtzxjcb.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnutkbzv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhbsnsl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dncvyddv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2objygfjm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vogzuwxm.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnkzeut.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrivwwu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aewkrimy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmcrxbz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhheivjt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqqdher.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnazruz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnokmee.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rldtijdb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2scszszio.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfwsfln.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2nghxwxnw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnlfpln.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtatzbyp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqivxvsa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpttbtj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2plyjslgk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzimrshm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2fasodthz.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpqjdhd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnrsdqc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2swcafutq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxhyglk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2wocvmtce.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzzmnxz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gupekemx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2udadenin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxbvrte.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnvhcqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqrcshs.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2safwmhii.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2izhfvkic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vdptwzfi.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocncptom.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxlqbhp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jycronuf.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmwivrn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2scgculfr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftogoftk.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nifrrwhe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxzmwxm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjobwvd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2syxgwfon.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2phxpijbc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaljrtf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxhzmc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbtflpt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbodezx.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkvatrg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2tzavydet.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzrcbhi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpzigzn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxvcawe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxmypjl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwncrgkj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2syzhkhsm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2svlzbfux.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2dffuyclw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcfxfpi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdomrem.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eawndbol.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkfyju.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2owgfhyua.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnzsztx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyvpknm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yesizxoj.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzpbtjc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ohghhesw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhavaue.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2trihxhck.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2btwwdcyp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fmygchzj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cowbvdmq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nklctgcn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2elegxdij.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxitdz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2jazmtuzi.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuueqedl.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzjggup.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2leqxsuax.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrvrwlj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpohahe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2fumsotqr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtjfktt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2thnbrkrj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzqjtic.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2zicupxjy.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2urgnipzk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2alwflmdj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2otjwvkur.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkjfvqm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2gojagprn.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2afnsinuj.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2gnglwboo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrwotqe.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgmwjiw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbctxod.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pquthhxx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdaeivi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxkwjcb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkaqtex.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzfwxfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbolixe.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aergdyvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmutrfph.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2apwxdpgo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtivduqu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufmckay.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jofnrzbz.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqwuqsr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2czdvvmxu.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiuxrur.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yotifnjz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fczlfady.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toprjigb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztaeaqjz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2twbkjoho.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxezixu.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tptckmlu.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhljuix.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxiojgr.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqevcnqg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpeysed.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oupjnwho.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlduvjd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wuukrvbm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqvpqpp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2opvwemfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsigpcn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2igjqookk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qasmaxeb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvovzodk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjggmrc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzhpjlw.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvhorla.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2naycfgtj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpdoayr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2htkothaw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpamhnvy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmfkngw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gheoyrof.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbclyhv.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lioncnmp.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uivvzqle.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itdxvjaq.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvtwpmt.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoabams.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszyuipb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uughjfja.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hraddikb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xejzvzqj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxwukda.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyhyzpb.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnwmcux.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkopmgek.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtceiki.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfaain.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmajlzl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wujghgxr.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2owvbdfiz.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2gajauwqg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2czequogs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cjymgyrd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bohcvqcv.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2duscctat.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxyrpcb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhkpjnf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ergtpkfn.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzhlcqp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pogppzqs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjkxuqm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqpdsca.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2btuwvqzh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuieqqw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqlyktf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xneflneh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwuipyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fudhbvgd.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2daqjmvtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geompykt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgzihhb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwvstis.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kagjdcpf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhqmiry.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsumoed.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjpbmes.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtisqflg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2etgdgpiz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxxpbyu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxmrcjn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzptfpn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlesodec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyttdurg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbgjzxt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2psaoptkm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfhdbtz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2azhpuaru.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgjqfu.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzdwipg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrpgaou.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptwdvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2swxynqdk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnxhgtg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcchjme.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfcgylv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jefmnjjy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxtnjpy.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2urjlburr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgorwwi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hflzymkn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2coufspxr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2faljwgdg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idukrigr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvhhzvb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdefjjcm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2logvpxbw.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjalsep.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzezgnh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbfhave.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2griwujyx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dghdfuca.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewivky.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxjdzml.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcnptgo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anjhdrlk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsvdmvv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2srlnifdk.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2trhhpyas.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpnnedp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2khkxsahr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtaxjwx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2elwjyimt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gvieerxk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2snvawgzw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpeewdz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fdswvffc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdowxjo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmxkas.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2daazgnxy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxnlaqg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpajgck.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nojzfbfy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtuffcw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpvcvuo.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgasyngt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rmldwjul.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dgktloun.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtgeeek.html


<!-- 参考信息 -->