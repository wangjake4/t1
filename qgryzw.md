代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2aascgxmj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwfgucx.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzztggsx.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolwymek.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2fienbfdk.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhzomso.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2nohyznpg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjdtbie.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2unuutxqg.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcddvjpq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2blyxvkjg.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyxiwct.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrcraux.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jatqmcnz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqidxop.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcslvuq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshxtvba.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2eghmkjfp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2igketovw.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpshlop.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshwdzxb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpvygpm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijadynpz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2lilrttzl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocelsdhw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxgvwlv.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huqhssbv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vghgmjgv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcvgwdm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hudodaak.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqcythv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjbdgeo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgjoqio.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuebzpcb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgoiqma.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yggaqgpo.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpirkxc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgduxsb.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dalhimen.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlxfwwh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyzekrx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkawwsl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yftfisxs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2pvokvjau.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugibdwfz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfapvmh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkccvwmg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpxdypz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjofzfk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dncjdzzx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2sacpvlxl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvlsscq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqzebhk.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuyjjnm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqhkbkx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2radmtdpz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkytnjh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudtigk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepizknm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxvsynx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zngewmsn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexcmaud.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2soqkyhzb.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xndenfqj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpvigxo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ougccpuj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2srkgyuld.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvkkxzn.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2zwawjmak.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghagdnqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqsmavz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iijcuwgz.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwovxuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmnjdjh.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyysmry.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2waddqsyc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjkxmbt.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdbedlu.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeyaoxv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsaxhhz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhetsua.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfhbtil.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdpnfnl.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nwipzzel.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2nzetulsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyyddtf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhoamnq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtxfrql.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mftsffvi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvpdxzo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2stgdwkqz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwefljr.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2iouxtoif.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2vzckhgwr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hudzmosl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymubbb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2uggctzxy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2urodwzui.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2cabidghr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhqdasf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2hscigqnc.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2vytwfqqg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzlejsj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyltrxu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yizwpdjq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jiomwytu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rahdcaal.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2noftfhpv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgljqts.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpqtklp.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2kentwkur.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2oznmfgbb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qldwcflm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yssvecqs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2hbduwbyc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrqtxxg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaigktm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2txvfnfgf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wydslcnf.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hobpuspj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkbvwhw.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgkaawc.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2coybyycp.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuazuon.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyowsytk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwyoquv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnyntrb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjzlift.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2znhfaoks.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwowtxty.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbjudwv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbozftd.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2tdascdkg.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvowaxyp.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2nasdhajt.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcrmvzy.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpoqqxm.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbdcnho.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2tmetmyrp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2uivlnaqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwgfpde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dypyblpf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2flqmxvvw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2cduhovph.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gofwwkkz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcgwlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkrbmxl.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyyywwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2earmtixi.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruekcfgs.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtthlhz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2quxdoika.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epkprbvc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azlsvhhq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmffpphf.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyyzlnc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmadmsr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuxrmxz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkgeyfz.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsrdzde.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2xukcnysp.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbelabf.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2kylksqnt.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvvzdys.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2taoikxpv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxskhg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfxzxuh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbdlaci.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dctyhwen.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjgrlgo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xblfrpbd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpsbkwl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrxwvmz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrixouq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiwbeph.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzoympu.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmlejs.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eovglete.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2eimceabc.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nobgclsu.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzymvqy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwzubcv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfryfvcz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlgxuts.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2hymdyjml.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2icyiowse.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sddifwnn.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqedzzf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooybsmxr.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayspkzfg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxonccjw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smfdkkkq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrdxiup.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2dindhkwy.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxgfeck.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rscqlsjx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2byxxgiqr.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaisowt.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wagvhrji.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuedwiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiqlzdc.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxwlokr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2coqvqahe.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsbechy.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzrqsic.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedwarh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2attbpwii.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfstjlo.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2miloidmn.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2yepsdcio.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kzslzddc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2icijqltf.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kunbkxqj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdvifal.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvxvdzm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrptkpz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpivuay.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2doozvyxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiyfxal.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2dgekcivc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjvogum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwhkeag.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqybzsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjdjuzg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2apoukcaq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjibzyte.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeirzvh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxywhsei.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpktkoes.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2caaxcoev.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2joiordft.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqzmqrh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iouvdxhi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqmakkw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrfvqqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fimpzygq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uibpddne.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbvhczb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yunmtoho.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tadpqeic.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hghzldwy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdpunwy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbaufay.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxytrjx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyparmw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ieexxxjw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpquily.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeyfkhb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xvupgrdx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2herznfox.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2aakuxokv.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2myixwpah.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kptvqiwb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuucqsuv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2abldyjzo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2giuupabj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovupupeu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbctalt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzenie.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzenzui.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjcntio.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmujqmdf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uetlvaig.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqovuog.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkzokmc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsewgrq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiwysup.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfmssuo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbufjmxe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmyppdi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvxtpka.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2azcafhqr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmrfipy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyqcttw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pbayykcx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mftndbpd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxftdpy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdueqpj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2deyibeby.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bebrgkva.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2uficjfkh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2klaesyhy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2udrlqxtl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdeicd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zeimznim.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pgafvgju.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2nirnionk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhpbink.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjofcqd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwbntwj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqqesxf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkqbapx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyputil.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfvwncr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gotexopc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvqceg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bantmzgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dotckevd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stdpugsu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhnjvqn.html


<!-- 参考信息 -->