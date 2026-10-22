代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2queuuyul.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dryqxhqr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkewsxd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmexpbht.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikrhez.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhwmuso.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lntumxzm.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnufzsx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrndpvvf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2crhbcmax.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqptoa.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjycwim.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2unluuwxj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxjihek.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2idaclnma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2aetmoryd.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2retmsyfk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2cmoohtgg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzhrlap.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2hriyiwdv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxmtzvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubezse.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tngrfglj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwedsepd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwlehgk.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2olsplclz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mseitfjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqanuqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggbxnys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjagwyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqtnhit.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqcociy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjigkhy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvrmdmr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwcjdqe.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstyibts.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mehxfojw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrkwuhb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lggkveef.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2rwypdcyj.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyvccpb.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzppmlpz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mdapxtyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkjpbsk.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ibshjbqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emiqwlkv.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2njlfksvi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2siwgwqng.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyoucy.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwnwqyt.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdygnequ.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zajqkvyu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rebjctnl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwbtwwt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyngxsx.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaopopv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyjqhgo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvnjcbv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2auhfbeyw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtztgvm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2htijmeun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjcfokh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2afeejyte.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcbbndd.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2npweheoj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvzottf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxlcljt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdwopdz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2mskrxmix.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2inlphrft.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzpaozr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjrhzjc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaqebre.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2hljkeppb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjzzeku.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhncgnr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bwumfxki.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2frdginid.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2glraunri.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2uopsfacs.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgzafnt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmpdcve.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcobmqmk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaldjrr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzuuse.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnnkjuj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2imwebomb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhfjjlf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxtnprh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2slgsugjh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmczvhs.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmhhljf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxxkdyk.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkaozps.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xebxprhd.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqumtja.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeymwaq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2xztmddzc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskjdwdf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnihtudy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ombnvkwb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2uulxhrvx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuslstj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrecth.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2vngtutxa.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2gccpwwya.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2prulxmcm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiovfsc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgtmwgy.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfudacl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmqvxrb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2btacktlt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2irwedgpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqtihoh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmqtnxm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2biznlrtj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsclugg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2loacobli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgsrmis.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2edxjgisu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdmtwzr.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkfazgq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2edepstrn.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebimsyzc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2abddegjr.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwwzfcd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvlleji.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgtklsa.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2yedvcrmn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzwtxiw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtwdcby.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2isrsjyus.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhybhaxg.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jmibsuie.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2awmwjlkf.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2thavhvlc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtvpuwn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqhepz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qluaxzpb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2emqftqpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhdkvp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlomlsk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xymmnark.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcygioei.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2umynyhsx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuffbtuf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbiaqpk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2etpvwdow.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmgydad.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oghhgcwb.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2viohwrbq.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsuwgbf.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyywmmlc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2unlznkmm.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwrulpg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvuhziq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrlxyel.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsekffd.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odjmjlwq.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zddriqlz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2towhelrb.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlgeawv.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asxsjgmj.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyzlpgz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoucudj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ficxfeem.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhdabh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyyzwjh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uysmnxaf.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlviynfp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2epdhgohy.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzmcxej.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpyfdwg.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjjyoj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2heqtttei.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ukygxama.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcgmovq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbedeqbn.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vjonxilx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnglyff.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kalsdjyq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttxsqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2psauuyhi.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2czhocgqh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iucviolb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2poruxsvb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkycncv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhhhle.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwfojkb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggphkpmo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcgjpvv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkqeza.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2stxtjueg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qknohozz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdpfoxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxmjnsj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqedsuxy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzeewiz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2holrguji.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtciwcg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbsmoqs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyclfkbl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdymrdj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uunbvjps.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjtttje.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2moqxgdui.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mngsugcg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2emlyadxq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unahjgat.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzqnnzt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxcnjml.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbcpamx.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzfehva.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwxzbqd.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezorwxuf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgoinwf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmrcpr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cteujfli.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzafmtvz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gaahmhlj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2craclvpw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdrooel.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnabrkm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgapbce.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqorsfpi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aprikuma.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfljqmm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnslkaoo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakjqvul.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqbpjmi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaahyes.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnelcvq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoblesj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhyyjel.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldofrfan.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmvleee.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiridwd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpqbvli.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2unedrxql.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvzocmz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsoafbl.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kauihqzy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfzginp.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkkibib.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghujouzk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhoewas.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jiunswjt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yoidebdw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmjwssv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpfyagr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtrgqo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmdyhwf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2nusrihel.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bthdbvkz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpfbjgt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2czccjzna.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgryscmp.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2iivwdewa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hkngctih.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpzpzbf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqswxgps.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ormjoffb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ijthbkes.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqvjyob.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2diaycdbg.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2syrhusch.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2azvsbzab.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uphklzyq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nykestog.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwdezj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhdystr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdbsakl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jybefghn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eubmclpp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cuypwoyw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqlxsax.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwclmeww.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kgztojpj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkyeohd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqzjzds.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzhmiuy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlhfkhs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaoszdb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqpbjjg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzzenlo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avtbwlof.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhieera.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfcxsad.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkegrqss.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfasvm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yedkqbyt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvuucow.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoshneo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iejepctp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcekrqum.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkehqtl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pugqkfpm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2odcbaiws.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iucbwafj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfboouo.html


<!-- 参考信息 -->