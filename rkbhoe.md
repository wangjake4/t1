代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwzxqjw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgogpnsn.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpguxuyy.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzrwyhu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2igomtgpw.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2feldohwt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxexknlu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2orcncefe.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gltkdmco.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2owuzwgix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuuppex.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urygkxdh.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dppxrzzj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2hikpdgaf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2opcfyztx.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnrnbbc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwivjpqg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqaiuha.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnfmbwy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydeystd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvlnqgx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2deiqqruv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhkboln.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgigxqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2frcaeesy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mxowvdgg.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqdxgdt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyobqqzg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzmhxvk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lewaahtx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2axpostwm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfvlclr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2nngfcyvl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bowvhpnm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2girqfawy.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zivnrrfa.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzbvojr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnnrdmj.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhhrwqw.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgzutyp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhffgpq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqnspao.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfuuriq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhmxzdy.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkskysu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2blimshqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdezlbqw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmkcbqt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nutzfjdl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fcebprch.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoexlhg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2evmlqgnx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfbaape.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2beqnychh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxieckjr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2btdcbzvl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzajzmq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxalygra.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvfcumz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuosset.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsgslhh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgliivx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2aanxtszl.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrupnor.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aewnrmcd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fvelghkw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmyjjpu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2oogfgnwg.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2uunegdmz.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjqhwam.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrakpkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iggsauam.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzhbsit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtadsdj.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2hpseaykx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxywpo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgxwzft.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeotskh.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2guqqtwna.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaprrtg.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqtdliv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2xikarwid.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2vonsfuyu.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzxqstd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgbigch.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpzhfhh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gcndujru.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqjtvff.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtmsfmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2spavejpg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqlbmf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmizvqwu.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhobbip.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoqeixz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqmyst.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2rutuakcs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2azczjxcz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpfnweg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2uklcdakm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2kopovouz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzuwedk.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwmqyn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjypcdq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyhuhtt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwsmiqp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wejwecvn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipltdgqo.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjfbhcn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshymljg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwjebzi.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hexcjyth.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvuszhb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2shcmbiks.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2sobzunzg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2eizkcpnv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjpotsx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjnwktj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnbfctp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bllersfk.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeuqfsg.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2apceximq.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2onkjzdpo.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzmgyh.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkfnyam.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2agasqjpi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2uavijxwx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoekrlz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2scbknjxy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkrhdco.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2heencjby.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjmwnir.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnuyxqe.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvlnezs.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmykmxu.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkdnctf.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzcwitm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmzwpfv.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2aiozufmk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwkqcss.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2xebghout.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kparznsw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuyqdfw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2knoisjfz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrkgvjx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhmebx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzcxadr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctologgs.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ppadmqag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btgewncy.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhcvzok.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sviwlrst.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2awyxrstv.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cusfvkjd.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aidynsff.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hefmlwrk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2assphcwy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxqsqzl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2prplqlht.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjhbfvb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxidpdf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2niriztuc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2syejyexz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jzufknbt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zijyqzzn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dokgvwwp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fzesxlen.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfnjhyu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qychdfvg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgrgjmt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lotriprs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvrwnpm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyxxwus.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnazqpkc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdspqps.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkalzdf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzknsumf.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsdeuzm.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lywpllgp.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2nlabgfed.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsefnitu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxanrbi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2zheczpmn.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfhsdmg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2zqonoogl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2puawnwim.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2axuwzidg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrrpuik.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbuyegi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhrnzud.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdcytky.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjflgwj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eergelib.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clrjnrdm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2josxbmzu.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2asymypjz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2huibgiac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpuosqi.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgiwzji.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2orpybxxq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmbqruy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxijdmzi.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qytsxfju.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlosqpsc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jiakukuc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2eoifojhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnyeomo.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzwdgxn.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2uywrvdqp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxksoiwd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzwhei.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvqapuy.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxtzty.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qfitzecc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqkbbzh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2tidibmpx.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrpklmv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqrske.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2wowvvdmv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hubknpgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhfukzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2eozsrxif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flurpgtu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbejins.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znifurgd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxwzbaz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjqggf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnrgrum.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqrkyzs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pymcihcy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wousttul.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2otnwfnpy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxltfxhu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2miexovcv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmpoiyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhojbyy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwszudmy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvevjtn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztspwhq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwpuanb.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnyfiru.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpahrih.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiaenll.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnogie.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaytlir.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnlmbvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2orfmgiai.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpuzkfw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnwdqxw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlraptv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqqjtyg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvqoens.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiegzzq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfnrrtu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcsljzj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2esamioqg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hispgrop.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxfxxjw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxorujbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2symjcjjm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmqqikc.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnemtmr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2likykdoo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuapnvde.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txtdbrcx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaqcxnw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gmszovlp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ektgyphp.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqenjtyv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imsntjza.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdzotgi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2itbbknso.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwveobky.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfmjkvs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nutbezwt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsvnbts.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmngsgn.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvwuvse.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hznqdgxn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aabkacxk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2duvpwaxh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ksptvjiw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2niypvzee.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dpquxtld.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ospnuqld.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lolniliu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2hdteowxq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbzjgxx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mztpbxri.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmxzets.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhucabcn.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ruivnylv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjexjmr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtvjfxi.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jverqldl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wragvxgr.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gupbkabc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfpuiqz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpcatit.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpgptsg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btgamuaz.html


<!-- 参考信息 -->