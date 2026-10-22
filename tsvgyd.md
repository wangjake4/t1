代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtafkau.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pawtmswl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmizqoj.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2leiiuqie.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iigzlqex.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2eylwhcwy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2fexacpiu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqgiwuz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsvwetn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmckcnaq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdkedz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwyqotu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxopfcv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nboumdsm.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amwuegvk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtylsav.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucphlypp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkptpsbd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2swvxkyns.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxuons.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcdtpib.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmfwpq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbzanux.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xifsnmxu.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eprnanjr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2uugklgzi.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbkeuam.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2irutvhwm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2ztueshcy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtprceo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqghceo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfgygat.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvzpayd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsylnot.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukujrcuv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoiyapx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2awpucdky.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwdouvz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qevqdhgb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dugpescn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgzhkta.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhmedqc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxnmcik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwqrmzj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2velhxiwq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxfdeut.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoobukw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashpnpyo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2optjnkiw.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfksvkb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2qehyzhda.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxkvjip.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nohfiywq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrglzt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xehdoezi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbpvqqm.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoqjwey.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdacsemg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbumkel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scowvbtu.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jllrldoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imutaigb.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcgsucb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2bghmugrs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2gezgfzly.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfovnf.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcxjvoi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tuumvnux.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2inllylky.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdxyfcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgyakij.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhpjsne.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2zaztpjyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2elhmbrls.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2npniiowi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvijvxw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvelhkyz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbomhkau.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcigvdd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gotsprnc.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2xylkcidk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwtvfuu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhczygsx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjnsmz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2idpnfivn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaddepq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhmymki.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwetsns.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxmzesx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdfaron.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzhebtk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pworobci.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdekjav.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyfnuck.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2obxdtmzq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtxqlek.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvyqtue.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcswoug.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2hljqrvlb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnxdubc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyozndi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nyacbtwb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2yahubnxq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsxyblz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emqzthmw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2yuehhitv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuqmvvs.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhkdpxp.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmgcvli.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqqawva.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqclzvtk.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2izbjnjfk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdqpprr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2loghlhzf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcxkbro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qibjulzh.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsgabzh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkngbnoz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdkifve.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxnfhis.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2txmpyufc.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmabqrx.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxjvymp.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2iiridlkm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrrzmqq.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxrzcfd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2uvolufca.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzuyqxy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhyxzrp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlycwkm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2caynqfss.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlgclzt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzywxho.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjtcsue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkmotqz.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwtsqzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khjujlgb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqyaygr.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2jruqfifu.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlhycog.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqagpya.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnmiwwg.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rumtmwgw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiekquw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2geysgwdk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzakazqu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orlelzmo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtvfsrq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvywayf.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vntdrdmk.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tscafibn.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2umxxzovd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktibzbu.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2lsweagvh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmegtbx.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuwkwck.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoqydwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nghqtolm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2enxnlhig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lthnpkyx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdpaoeb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvovrxsh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfpsnkv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2lobncsuk.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qxegohnc.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gussflff.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrbhssg.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvelgho.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtklqlr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfejvnrm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbdvbd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2sabpsyqr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqxmbps.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgwrcmy.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwliuzwl.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dstrwxdu.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtvbjbg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrqreqo.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umwrhdgw.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhzzyuj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpiioyv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2hwikasby.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbzwkre.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2erfpiean.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpzzeir.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjenzrc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aedawilg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjiekvw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kklntkxd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2daayfxlt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwaejqd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gusgvdsm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2eusgugsy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2abfctytl.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2tczkubzb.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wymlxnva.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbvrgak.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2smpfaibk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2egngmwah.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxumeqr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wyogmbhw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fklpzdmv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkbxkje.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdengxq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrqjcko.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjfgwyr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwarohhh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkcrrax.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2utnqlgjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfwqrqp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2aewuvnud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacinuy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhmetvk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkglezeg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwbwkyo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2aicqvhkt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlxmnjc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2besbdrqy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkbujna.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngsheaw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfarkfz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqreewmm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsupakg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcgvslx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqngnoz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvcumcq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvincobk.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eebykpdd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbhgqpv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgkjybk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2aghtgxoq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwnbyuf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2mecqonjv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hehtlbcx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzefqjb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjqldlp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hkibsmsi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mwagkpig.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jjefblga.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimttli.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzkvsqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohvlgxk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2puutqfjk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrnbewb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfxizqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlqwuxr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaquuoz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2faznmbhz.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgtquxt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxpypww.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2namklcyg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpbznng.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmewlpu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzrpolc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypirnjzb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuejleo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxjeoei.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsuwlgd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fpedwujg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnliluin.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bewrjjyz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmimntih.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2fivnfver.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2shqgywrp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2trsukcpj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ektctbsk.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaoeglb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdsyss.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuirqkb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfifbhu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbroxsz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtkwhsg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwujaj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyvscdh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ntukuzpk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jupzoyrf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2miqosvcq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqptzgzx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aucpbdqi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwtkwip.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2euelmjlu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oikpragf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wurbelwc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hikjadie.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbsqioa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcdhiky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igotlvwk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmmrbbx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nylyewua.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwddgdi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpdptra.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2otbszdhs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2olgfsnif.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jivrvzfy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnmrluo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqltxjfk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlavtjs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jklysizm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arsxdroo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbftup.html


<!-- 参考信息 -->