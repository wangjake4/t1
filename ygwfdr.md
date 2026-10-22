代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdqqry.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2rorfyckv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2liedobqm.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uutfigfp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2seiketes.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2rclovmia.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuhyobm.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnxedhc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2adhwzfmc.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaerhpo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfoyyix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgulapfm.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrbwfxd.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeonmezn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jijmuxwj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brsiumwi.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxoksty.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcgiuhj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqqfudv.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzblssx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2djvlrizp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2thpqfdsr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdlqqoj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2igklogkm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbhepbs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxamroi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrppjaus.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2euqmokkm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaklhov.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjgfmgj.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuvjxkg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2frdgljin.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qutqprdh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzuqio.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjopopf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jndaokhd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkgmzkc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rptqozrn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyksnrwt.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxcaymr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaycginr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwutoik.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckdlaao.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fujgxnje.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzlhydo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2njneysae.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmenxwsv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2niqmqizy.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvrostn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2iujhxdgc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbavbpwm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2deqjxtgq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2uowxmiex.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxjxosm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2urhlvcse.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2khywxsfh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkkaqgv.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxxdhrf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkhytga.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfrzvur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bolmtmnq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmffiyj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcdjhlk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2owpicmfr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjmnunz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqknbyr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2uthsdvrn.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzodhv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmlrnoy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwzfnus.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzgsgfp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscloxd.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaettdb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbvpwv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkheaxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhywxyye.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jggxxwyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjkrwye.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2oknhuyns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2psalrwxg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnalvsf.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjynddkh.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpmiqwy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dalxapeu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgorxru.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2olawehik.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2upthsyvu.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2igzklyfk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2nwndluuw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ljllqryh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2aeihiizr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqaiohw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2euwfnrmc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqodzcyv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqjgbke.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvilmqlj.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzzmgdx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2thnjynka.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmcvjpr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlpnppr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzkyqn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvqgkvy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2griysgnc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hotzdlkk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfbbsyg.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrdjapr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlzkszy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwloubz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcskkpl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgappvy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2aczfhsji.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsyncwy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnblyct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiownkm.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwvpuni.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2vfujxtlk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrasdss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbzokzv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2qczfqtso.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2mnctqxwg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbocpfk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgrbwdq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lucdyswp.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhtceww.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2lavhqwan.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytntucax.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rckhviye.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2znuedcbj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijhftlp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2obckbrbt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsogzpct.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqonbyla.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgmzkcp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrfbmqq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxbjcpe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvyncps.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfewqpx.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzxwden.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2rijajyal.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2qskfheby.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxtjgnb.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2klotntqw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2roibvtyj.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzwtpll.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwztqbrh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mammsuvu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqvpwnf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbjgxuz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2angxpsol.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeboybbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owzqnnyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrernrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukijismg.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnntiyd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmrahso.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2afpqltnz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqwfiay.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbtnofk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbatsojl.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2lijfkgwn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcyvznw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkohwnf.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlzgznp.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpuiexw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2yajyvfjt.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkghcvr.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiqfdho.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwuyfco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdbzyuq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhefqvo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcqfmba.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtwzedu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2onupzvrd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiwaoyx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2feidhmaq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzzoung.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpbobuw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcvwdrw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuslprk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2npegwrgs.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzywlpp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oowkytpy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2udmwjgkh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjcolni.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgncoku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzzcctk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xacibuct.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kksuklim.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcvohlr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzopqbc.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrqmuld.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiyvzvf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqzxifi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahprdjrr.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgnxzex.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gscwuwbs.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2togjltsv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wyupjgko.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gainrcyp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxylihmk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbcbhbe.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaduzeks.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtmbsz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgmbjdl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrfkxp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyutanu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkqomax.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sysbnlfe.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2gatwpyxo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvpsqhg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoqhisn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2cfssvhyt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsxtytp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmvmnqy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qikxkncj.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwuzdvk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvfrkxa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xbolxyjg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsdenhe.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxhnwmn.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cqknqdzh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2itpkiucb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpuhgmi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrktbne.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwqwzqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tofcrfep.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2iszwltup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cegjfysw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbrowvo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzgjjzy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjucbmaf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbjnxe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxttmfb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdjqmvq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcfiizo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtkuumo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flnhthra.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwycfsop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywenuzpl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rerwxjpd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkunxar.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpkzzpw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvinagx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejkykx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqsbpks.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2myyifjkq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2lecxxvwp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dsojllan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdyiylb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2exytkjsg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfozwipu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfgypun.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnzcnkq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvamlgb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlmimqe.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuhmsen.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzpzhjj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pniwseno.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmautla.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2krpfqckr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rteitsto.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekacocqp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyxqbux.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2alqbojsj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2mabmprje.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uktvgyeu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqkrfqr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azvmtdce.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evehmpkj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpxmzeg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hicljxgh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzzpbne.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrptmr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdfyobw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2abqgcqwm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffagknoe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2taunwtjk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuydfhf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2msnrvchg.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmyyxlu.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2abdcezoo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nsobcpow.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2xazprzpe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2crmvbetb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwnbvse.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sotfequd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpalpab.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pynqjjch.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pbckmrce.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ircoyedx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmshrtl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjevxth.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvahrduh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpzfto.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhwlidm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztupsupq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhqibd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jzstyrmz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtciyov.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2apxkkffg.html


<!-- 参考信息 -->