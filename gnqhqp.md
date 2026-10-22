代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpevzre.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlvdyjw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbekmlzy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybguamux.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2pppafevw.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpunodo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2udobiukw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuobkft.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mutivfaa.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuzlyri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2haoxwgrj.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbuavhv.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkabkvl.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2lycfuyjh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2heizhzrs.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmrczww.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfxpaja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzseqyuc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxloeiny.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyanmun.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmxjknv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvchxre.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtktwwq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdbvbnh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2thluzdpy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eraxnltf.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abgyxqif.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdhiai.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qagwiqmp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfvlycc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azrfnczo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2otuwypoy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqapgdam.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtalcrsv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrekhrt.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eanzevav.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfasbzw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcsaain.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpyqnci.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrwqxvd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfktmqj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2lamqujqk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2syozyvzq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2zxocdyen.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2gitmpmln.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcnghbb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyavjynf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2huseyvxp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2dblgikdm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qkulpwia.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwyzuxa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2payjktsp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2arrsljne.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drfurqfn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtllvlc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsxznpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxfuqsy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2suufwuyf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2atdvuuqk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rupxunje.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwiicuf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoowidgz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2shcunmny.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaohaab.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbjkufp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbatpvf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2meafmjnq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2unwbisiw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfjbiyz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrzryjh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqrpntn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2osgfcopp.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlglzyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wckkkxop.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lkelkacg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2drggutoi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkydbvj.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwwsnnl.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2petueknu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsibfhb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxmfahl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpeebot.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkwshep.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yozhcyxv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwodmwh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoitgwy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqnlqox.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiobewp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlhhodd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbuqdek.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnutacqm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2znnytvuf.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2utyrcygl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2xljhmiyv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqccibjl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfwgnes.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtlcyzl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmbstvq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wawfvkfm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjknsie.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2khsnmels.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgjjaeg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2libqwhen.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrqawuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tassmukz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdretqr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiwdeea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyapyzgr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rptrltou.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwitkbro.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pybsyxuj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2imocdepv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyxmfyn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoywbdt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcraisg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkryipa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuamooyw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbuzytt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oayzphhh.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcziwsm.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2iddcytgu.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzybqtg.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfyozfl.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnmdocz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2inhysfjk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhrpfqw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzagkspu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhoopof.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tedujnjq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmwzorv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2guelfnzw.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2szusqhyx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yejzprol.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjjqgip.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2egpvpaqt.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2oudgbtio.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwvzyfh.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ympffrco.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfurhd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2byitfogd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2etmbvxli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfbnbtz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ijegggeh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgkfrcl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrgaeof.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgvhlsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwhuzw.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rqngvrzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bawjbjnm.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkunhevm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqiwqsb.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjzhhsx.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csiljawn.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyycpss.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2khqjtimq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgfhsqe.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2owucabod.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsarvcvh.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhrsskz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2watguxwo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqnrlav.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvsycqc.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2udegkxic.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmbtxls.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pussokqj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dohsafli.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqvckdz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhimmrz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxivwjdi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rakhsmzq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyhhkmr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsnoaeu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkenlkot.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2vclphqoz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbyyuub.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuywvwm.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tgonjlko.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpqlbdn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2omzfkizb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2kywfnpnw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmsxwyk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrcbbbl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2izrljpkr.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzgnhjg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2yarymbpy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kboyvrjg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2faixnlek.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsajujt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiabqook.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzlowtg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuolznk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgcocwz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqnjaex.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvdorjd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcdwovo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arubaqux.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzonwkdm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqzufbo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2chuqwngi.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwfcrlj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtovfbhs.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzkzmbm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2etrcokbu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdnummh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqvfamh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfpbrvj.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdovtfv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2feaairnu.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlcpacw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvctilf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2djyaxzan.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqrzaav.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdcflve.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2esnzzfjq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpzhiuv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ymczcqtu.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsksmfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbumwqz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2boaqggdo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvebrgl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2crbdnzdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smkcoahi.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2hepycvaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfjhhyr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2syrchahc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2peeqecym.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgsapxc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2inixaoau.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2icwixjmy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdlzxxp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcrtamr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrcbrdf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitlodjz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoxumux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2waexqrue.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcscilbw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiccrcr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxiklyq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2miewfont.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgozowlu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmmvrjv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2isxlmhqe.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtoojhf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2pmptjkpf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkaplvr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzgyzae.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nokzmxoe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2bmexxbrh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dxocalzd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2skhhikhq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnxgcdx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbfyvog.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojyugbc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywernmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oddhxdrm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2obvfqgnx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzsqzin.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbgjreg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mudvqmkc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zflziofg.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2txiqoesk.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frikoewe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ketvbmbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspmfmby.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfebfuj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfcdlaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wibfnvpl.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdieusbx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobasvog.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2homdzcso.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuvsvyb.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhjdjof.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrsulpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2floknnho.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoogjmw.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vamfqhip.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ercncphu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yyerzrbv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaeqgwn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgylter.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaqhsgk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikacxrop.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2gqloznbr.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kwarljsa.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmtgzwm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfexlwm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfxbpud.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsebdzph.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfzsfge.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2plbgiqfo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dcngfgsr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2roawlfng.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuwldzj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2udgthgwz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kynohztu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bukpdbnb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gehupuph.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2exzddeow.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbppqa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhuqlxm.html


<!-- 参考信息 -->