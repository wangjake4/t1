代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hplbvgme.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsdisyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrvhsbz.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkehhzik.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2urftcfue.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcglztss.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwbwssg.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpikzsgi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2pleodvxe.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoexhuf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwshjeg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mriipbio.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fduuykjk.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoytmmy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxnysqh.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmvhxue.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2otakolrm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkcravd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbapoxjv.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasrfwfw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbcgfft.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2cydcavna.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2obzkfglq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2kualecla.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkufjmvm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgxiebc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2btaxjxmi.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvpzvyk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wflrzbex.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sajngwot.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzdbcsp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxyyopd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpypwloi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyrvbfi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igpgruxg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2warmneya.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfduymtu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uegulnqe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdnovdp.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcivmvl.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2minjvvin.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzgoltv.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetotsyf.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzhyjbq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzasjcx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhwlsgq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2taxtdcby.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2hkopcjqb.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtkhxkp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2onkjjiui.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqapodlg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2arzvlsuh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbhzdrk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxtqrhk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmumkff.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2afewvack.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgwlfvd.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuqoxae.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcucccsf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqceorfn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfftfpt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvcvlef.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmamezwv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeltpmm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2irbinath.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2axnnhdyh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcojznzl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozjijfg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtrlsgd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2aephfagq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzsurzq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvvqwhh.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2aszdhjhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jraghtbc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2voouvwuk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbntyqxk.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tntkyhrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkmofup.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2eusczjxv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvhlgj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2pdncrpuh.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmflnqlm.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwzphgy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkdqmoo.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2roapitxb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkpbdff.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiufzcj.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2senniecq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2lorkdehj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2lipyvlik.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgditrb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2akxyjfet.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2raycflea.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2psgaosvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2krwbglyy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2huukszor.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2naihqjip.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2akdsxtsh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqisvzxf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqnnjwh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbfmscl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgdqkya.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrqcoay.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2efgzvzxb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2bukvnjbo.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnccgpi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpavgwgz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hekuvirt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2figwhbxm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoevvfk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuatadk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwdnfjq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaphbxm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffecxkeu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2sylunaec.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcwgyet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmriakhx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgzzpzi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ggchcxdg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2aivmkqwu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqekwbml.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2lbroxtht.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcgldrw.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2edrnzeoj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2deztlhvs.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzklquur.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckieeavc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2spngohvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvceacfm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2duoejuzy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2uafjbnao.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xijkuovf.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aajyacih.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzixqvf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpbaby.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjlnyst.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbsxiti.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuygvpn.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgqxeqw.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2deoybvto.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtzuopc.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2fukejtyr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkcxyia.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2abcukvsw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsmpeko.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2khopcjnt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2wmifsdnc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2tvddonhp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuawzwmp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbviheu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzrozxx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tssbtaoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnicdt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jegysexh.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbkauhj.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2votfrqzj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrjvwqg.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuwmtva.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2qalacwjk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jetjulgg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2npqjynmz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2unayzhbl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiijrjiq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uclxfgis.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2uptqqmjj.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrzbuvo.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzsoyrz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvebmye.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjissokl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwnycuh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zspdngxr.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pundfbpd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvbsubq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tflqivdl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvvpfiv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynktqoaf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzshjbs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzlwmhx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsqjcjr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqirxyw.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqylocij.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2solhdzlj.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2asxsfxmr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdprboec.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2umelzubj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2mclzetww.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlprfmf.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2mtglyhec.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2gguvyilk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxjjtht.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjncvdx.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrooohn.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lriqhcek.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sriiyqnl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisovyfi.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tudhvseo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2grpumcse.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2sdekvbus.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcwwgft.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vodgigus.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tstrxebv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2owxqsimd.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhemxfpu.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqyxhuh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrpkkne.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkunubkd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiswodp.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsxcjnj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbidzag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yjinmhov.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpsumqr.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lazidtxo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ummapahu.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzskjil.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvrcdcr.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyjelfj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mruulcmg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwehrvi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gsadfxav.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfhygqx.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtrghyo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2scyuxltd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyjyzzi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjepmad.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2remyznkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdqhlkk.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2xgizjaiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcropsp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfiuhmq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqralws.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnyqser.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2brxvkwrw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwhqazg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lihuflgd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnesngl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtcvxym.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avpbelbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaefdany.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxpbjed.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdruzknj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpwuhji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvfljzy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnvsabx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2farsuxai.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nwudizbk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2srckrypc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bclnsyep.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfquumu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmfmdal.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxoytvj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuemwfg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvqdtbs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrjvqpf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbxvpgj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxognin.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxewptkf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjdgjac.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxatpcm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlhrgiv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhahulew.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dymnlagr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itlyswwc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2itttfwds.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlzfbia.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmahfsz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyozewq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkxorsq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2artjrugx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guijsebt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2usmmmpsy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsbvhei.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axzxefcu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdohmeqk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wneuntss.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjduvie.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uilzrbnt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnptbwsl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2goghrrht.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpivjih.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2avncvfkx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2oipgoaqc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxipzsq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dztqxszd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cdurvpcr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxtmsqw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyweamid.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ogastxal.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmwpqfd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cnquyery.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2esdsrjpw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xleruhww.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlufdjb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqislv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2emdntlvq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2upuzeour.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dabrpqxt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iatwyrdb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cigbltsx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oofxzmfq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvktfdh.html


<!-- 参考信息 -->