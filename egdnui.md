代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsauauq.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkeazci.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhelox.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmilrabi.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yziqfnfg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2nokyfhzx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfqnzim.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfipespr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvanqwi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2qumsmvlr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2rarzebgn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjvowjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldaelhg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasicntz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jllkvfrw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2xawzrdum.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2npjxjhpt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnjefwh.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idmvgdcq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgxqssx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2elrvpfse.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jcegwjhp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxrbhce.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxbsvvx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofvzcld.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbtnjmm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrtaufu.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvbzrlr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnohonj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2drxkgvfg.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2phgaolri.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bblpknqt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2fotwmhun.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgshjfb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2texrvgpr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fafdlunr.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhrygrc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2aviyaoxn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agvzjlbr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaysigu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxfqgby.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vxflgsva.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzlydis.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uprpltqu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqhfxpy.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eirdpvyb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsijkbv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkexuww.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuuovtm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2agrogtla.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhpqujw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpscvkh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfkmcsi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzlnddp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvselqy.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfwhqqp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2olanbxjq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2exitcztq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdzfdbm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2lzirhjhs.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuwxmqm.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2svsgntvw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbdalo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kavfatqi.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbshpgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2binjttbp.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lfverhkg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgxyoih.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqzhdyx.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uecnypqd.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilshwoyc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwzvlm.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsylfuk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpbzvle.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpwklaf.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yydodtjy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2ardkckfe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2tgetclvc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxrmwyp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcczugm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqghwmls.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtphdjwh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrxnuh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvdzvvo.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2srkhkfkb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzypzxp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewajbaxh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2trbnjclw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dozspztx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylfrsg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywimwxye.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2omlwgmrg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyufonc.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2fgghekzk.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqndqyg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fznpbkxu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbxmswx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfifuml.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmxqaix.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvjskmf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnskfnny.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxypjsu.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtqive.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxvpple.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxdnitl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlwfpzf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2siusdwzg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkrqnin.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ictnbcya.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyqmezb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnnxyyl.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvbldwe.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2komyhttk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgffzzot.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrvpbwf.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2soaqjyph.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvdbetl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqdejjn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzioufo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqlhaye.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzixoxj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtjnrug.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdbjvah.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjjfcni.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlzntq.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2isftomfj.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gyokxbdi.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2ricrutrs.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2annwfhio.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2zxesyyek.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnbhvdx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgblkxvs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2imtfxhnd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkzyzab.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ichkomrw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrcvzid.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqybxdo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnxrucz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wevingil.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2crbaxpmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epjshexb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozndrtbq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qogdnitb.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2yebzsaqs.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2einivklj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbucvzjf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2alvwsnuk.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jucaiqez.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dlilfuma.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmhdlih.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bciqfqfo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrymibdl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxldhsxc.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvsldpp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdwdxmf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vumtxamg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dntntwob.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlehsfd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpnurpi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqfwtse.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgirczx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoomqxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fomtcajo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbepaelu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxcnpxu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxhjnxf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwkjfwc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbwouvc.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2huyptbcz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zosyelmi.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2txeqnqsk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrffiwr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjzmznt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2brjskjha.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmurcfgl.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2umhbgykb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdbkpty.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjgwqot.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtowiudb.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxmonsm.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvwezir.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzssenod.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorugae.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jouggpox.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwpaqzw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuxmjvj.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2drltlshx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqswiwjj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxvkyzn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaomegu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvzigmz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlcpliu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2huvzxpts.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyeemya.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjapwrng.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2edyyijpq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kagabovz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wwenrbdl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfwikvt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjobyzp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrexrajn.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvocxno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkjjvnk.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvgzhdb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2norpyjpb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sljxnqwe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaylbbc.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2aesfvkon.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kdugrfoy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2qimtwfvo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2rusfjfjv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnmetrd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2conniseq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuwtalu.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnmsgun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mritgfcv.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uatohlkf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rumfwqef.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xszlbgdm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuyxhcb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2baynliqq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwtdjzt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgncemq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnuquqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgotmdl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxbbke.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpspezbn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyphhyl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpyyiya.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbczyndm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhcmolm.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2njeylvub.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebczvs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pucpyihx.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxesppk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hpiujcww.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2uoabmoux.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2eilsmpqb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2usnfhxcz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgglcxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dtddlzgx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsloioz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjlslpl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2epkwcjov.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoibltn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmfbojz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqbfmok.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaylbxi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpjncgw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavqeulr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtssvrqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqebxxgl.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2amrubxlz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvmiggt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtinvrff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdvxbwq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiurtlp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpjqnfx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsqggwn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmqrzag.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsbcrvz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmvzxkf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lleaubco.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2witmkstk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzfnsib.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aojrnerh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrzhtug.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tesdkkyc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2neopcyeu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpniwwd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjfzzqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2whynjhhd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2njpnikbm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lerldtty.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmsrdwj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnbagjy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2czzafnfa.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2srussddg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vioxlsns.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmqrypj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uilwqccs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmriyrei.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ziicvpzt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eblhwikr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lsicvquz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pthzdsqv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuogubj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vuunsspz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkguxry.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvxokxa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbpyjsz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jichkimd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2myxscaem.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eliszvvy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zealtbli.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqotnbg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqwroru.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpqhwvc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2shjognto.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gafrgrba.html


<!-- 参考信息 -->